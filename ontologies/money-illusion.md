---
description: Ontology documentation for the Money illusion bias (Nicole)
---

# 💵 Money illusion

This is the result of my work on the Money illusion bias (the final visualization was produced with the [WebVOL](http://vowl.visualdataweb.org/webvowl.html) tool), whose generic definition was generated through ChatGPT AI as follows:

> Money illusion bias refers to a cognitive bias where individuals tend to misinterpret or misunderstand the true value of money due to changes in nominal prices. It occurs when people focus on the nominal value of money (i.e., the face value) rather than considering its purchasing power (i.e., the real value). This bias can lead to flawed decision-making and economic judgments.
>
> The concept of money illusion bias is closely related to inflation.

{% embed url="https://service.tib.eu/webvowl/#iri=http://www.leonardozilli.it/CognitiveBiasOntology/MoneyIllusion.owl" %}
Visualization of Money Illusion bias
{% endembed %}

### Chat GPT

To review the type of questions I asked ChatGPT and the corresponding answers, I am adding the **direct link** to the conversation. In general I asked for a _definition_ of the bias, some examples of _senarios_, and a row _structure for the ontology_.

{% embed url="https://chat.openai.com/share/fcb31405-0c20-4744-8411-ccee325b578a" %}
Direct link to the conversation
{% endembed %}

### Scenario

In this one, as in the other biases I have explored, I found the ontology proposed by the AI to be insufficient. It is an incomplete exercise that needs refinement. On the other hand, I was pleasantly surprised by the variety of scenarios presented: they were crucial for understanding this and other cognitive biases. The examples were always simple but also very effective. Here is the scenario I chose to delve into:

> <mark style="color:orange;">Sarah's Stock Market Gains</mark>
>
> **Sarah**, a middle-aged investor, had been diligently investing in the stock market for several years. She had diversified her portfolio and had seen some significant gains over time. One year, she received her annual investment statement and **noticed that her portfolio had increased by 15%**. Excited by this apparent success, **Sarah felt a sense of accomplishment and financial growth.**
>
> Without considering the impact of **inflation**, Sarah believed that her investment skills had solely contributed to the impressive gains. She started to contemplate increasing her investments, confident that she had unlocked the secret to consistently outperforming the market.
>
> However, Sarah's financial advisor, aware of the money illusion bias, decided to have a conversation with her to provide a more accurate perspective. During their meeting, the advisor highlighted the fact that **inflation had been running at around 10%** during that period. This meant that the **real gain in Sarah's portfolio was closer to 5%**, significantly lower than her initial perception.
>
> As Sarah learned about the impact of inflation on her gains, she realized that the increase in her portfolio was not as substantial as she initially thought. Understanding the concept of money illusion bias, she recognized the importance of considering the purchasing power of her investments rather than focusing solely on the nominal returns.
>
> Armed with this newfound knowledge, Sarah adjusted her expectations and investment strategies. She understood the need to factor in inflation and evaluate her investments based on real returns rather than nominal gains. This awareness allowed her to make more informed decisions in the future, ensuring that she maintained a realistic perspective on her investments and avoided falling prey to the money illusion bias.

### Competency questions

* What caused the mismatch between the two perceptions?
* What is the real growth of her investment portfolio?
* What economic action was Sarah undertaking deceived by the money illusion bias?

### Main characteristics

The idea that I have formed studying this bias is that its peculiar characteristics can be summarized as follows:

* It always involves a **subject and an external object**.
* It always concerns the **economic** aspect.
* The real value of money can be perceived exclusively if its nominal value is reevaluated in light of an **external context** (and inflation is the main cause of mismatch).

I decided to rely on the [Experience\&Observation pattern](http://ontologydesignpatterns.org/wiki/Submissions:Experience_%26_Observation).

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption><p>Experience&#x26;Observation pattern diagram</p></figcaption></figure>

### Ontology design

This is the link to the [.owl file](https://github.com/leonardozilli/CognitiveBiasOntology/blob/main/MoneyIllusion.owl). Here you can find the ultimate ontology and its relative annotations.

### References

* [https://en.wikipedia.org/wiki/Money\_illusion](https://en.wikipedia.org/wiki/Money_illusion)
* [Fehr, Ernst](https://en.wikipedia.org/wiki/Ernst_Fehr); Tyran, Jean-Robert (2001), ["Does Money Illusion Matter?"](https://www.zora.uzh.ch/id/eprint/95345/1/Does_Money_Illusion_Matter.pdf)
