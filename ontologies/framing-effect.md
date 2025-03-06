---
description: Ontology documentation for the Framing effect (Nicole)
---

# ☑️ Framing effect

This is the result of my work on the Framing effect bias (the final visualization was produced with the [WebVOL](http://vowl.visualdataweb.org/webvowl.html) tool), whose generic definition was generated through ChatGPT AI as follows:

> The framing effect is a cognitive bias that occurs when people make decisions or judgments based on the way information is presented to them, rather than on the actual content of the information. In other words, the way a question or statement is phrased (framed) can significantly influence people's choices and perceptions, even if the underlying information is the same.
>
> \[...]
>
> There are two main types of framing that can lead to different outcomes:
>
> 1. Positive Framing: Information is presented in a positive light, emphasizing potential gains, benefits, or success if a particular decision is made. For example, "You have a 90% chance of survival" in the context of a medical treatment.
> 2. Negative Framing: Information is presented in a negative light, highlighting potential losses, risks, or failures if a particular decision is made. For example, "There is a 10% chance of mortality" in the same medical treatment context.

{% embed url="https://service.tib.eu/webvowl/#iri=http://www.leonardozilli.it/CognitiveBiasOntology/FramingEffect.owl" %}
Visualization of the ontology
{% endembed %}

### Chat GPT

To review the type of questions I asked ChatGPT and the corresponding answers, I am adding the **direct link** to the conversation. In general I asked for a _definition_ of the bias, some examples of _senarios_, and a row _structure for the ontology_.

{% embed url="https://chat.openai.com/share/101f6c7a-1201-415d-a3f9-aa184fb8d772" %}
Link to the conversation
{% endembed %}

### Scenario

In this one, as in the other biases I have explored, I found the ontology proposed by the AI to be insufficient. It is an incomplete exercise that needs refinement. On the other hand, I was pleasantly surprised by the variety of scenarios presented: they were crucial for understanding this and other cognitive biases. The examples were always simple but also very effective. Here is the scenario I chose to delve into:

> <mark style="color:orange;">Donor's Dilemma</mark>
>
> As a compassionate individual who wants to make a positive impact on society, I find myself torn between multiple charitable organizations to support. One day, while browsing through a popular crowdfunding platform, I come across two campaigns that capture my attention:
>
> 1. Positive Framing Campaign: "Children's Dream Foundation" The "Children's Dream Foundation" campaign advertises itself as "Empowering Dreams - 90% of your donation goes directly to helping children achieve their dreams. Join us in changing young lives!"
> 2. Negative Framing Campaign: "End Child Poverty Now" The "End Child Poverty Now" campaign highlights the stark reality of the situation and states, "Urgent Action Needed - 10% of your donation will be used for administrative costs. 90% of your support will be directed to lift children out of poverty and provide them with essential resources."
>
> Feeling motivated to contribute to both causes, I face the donor's dilemma. On one hand, the positive framing of the "Children's Dream Foundation" attracts me with the promise of directly empowering dreams. On the other hand, the negative framing of "End Child Poverty Now" evokes a sense of urgency, emphasizing the crucial need to tackle child poverty.
>
> I contemplate the framing effect, realizing that the way each campaign presents its cause is influencing my decision-making process. I want to make an informed choice and ensure that my donation has the greatest impact.
>
> To overcome this bias, I decide to conduct further research. I visit both organizations' websites, read about their initiatives, and look into their financial transparency reports. I also reach out to friends and family for their opinions and experiences with either organization.
>
> Ultimately, by acknowledging the framing effect and taking the time to gather additional information, I make a well-informed decision. I choose to split my donation between the two campaigns, recognizing that both causes are essential and deserving of support. In doing so, I feel confident that my contribution will genuinely make a difference in the lives of the children they aim to help.

### Competency questions

* In what type of Framing was Children's Dream Foundation presented?
* What kind of opinion did the person involved form?
* What was his action influenced by?

### Main characteristics

The idea that I have formed studying this bias is that its peculiar characteristics can be summarized as follows:

* It always involves a **subject and an external object**.
* The frame is interpreted in a **binary** manner.
* The frame influences the judgment formulated upon a object.

I decided to rely on the [Experience\&Observation pattern](http://ontologydesignpatterns.org/wiki/Submissions:Experience_%26_Observation).

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption><p>Experience&#x26;Observation pattern diagram</p></figcaption></figure>

### Ontology design

This is the link to the [.owl file](https://github.com/leonardozilli/CognitiveBiasOntology/blob/main/FramingEffect.owl). Here you can find the ultimate ontology and its relative annotations.

### References

* [https://www.treccani.it/enciclopedia/framing-effect\_%28Dizionario-di-Economia-e-Finanza%29/](https://www.treccani.it/enciclopedia/framing-effect_\(Dizionario-di-Economia-e-Finanza\)/)
* Bourgeois-Gironde, Sacha; Giraud, Raphaël (2009). ["Framing effects as violations of extensionality"](https://jeannicod.ccsd.cnrs.fr/ijn_00432662/file/FE_bourgeois-gironde_giraud.pdf)
* Keysar, Boaz; Hayakawa, Sayuri; An, Sun Gyu (2012). ["The Foreign-Language Effect : Thinking in a Foreign Tongue Reduces Decision Biases"](https://web.archive.org/web/20151123130427/http://psychology.uchicago.edu/people/faculty/foreignLanguaeEffect.pdf)
* [https://en.wikipedia.org/wiki/Framing\_effect\_(psychology)](https://en.wikipedia.org/wiki/Framing_effect_\(psychology\))
