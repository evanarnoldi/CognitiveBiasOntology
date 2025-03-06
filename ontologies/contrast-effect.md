---
description: Ontology documentation for the Contrast effect (Nicole)
---

# 🔲 Contrast effect

This is the result of my work on the Contrast effect (the final visualization was produced with the [WebVOL](http://vowl.visualdataweb.org/webvowl.html) tool), whose generic definition was generated through ChatGPT AI as follows:

> The contrast effect bias, also known as the "contrast effect," is a cognitive bias that influences how people perceive information or experiences in relation to the context in which they are presented. This bias occurs when the perception of something is significantly influenced by the presence of a previous or simultaneous event, object, or experience that differs from it.
>
> In simple terms, when individuals evaluate something, their judgment can be distorted based on the context in which it is presented. The perceived qualities or characteristics of an object or experience may be exaggerated or diminished when compared to a similar but different object or experience encountered beforehand.

{% embed url="https://service.tib.eu/webvowl/#iri=http://www.leonardozilli.it/CognitiveBiasOntology/ContrastEffect.owl" %}
Visualization of the bias
{% endembed %}

### Chat GPT

To review the type of questions I asked ChatGPT and the corresponding answers, I am adding the **direct link** to the conversation. In general I asked for a _definition_ of the bias, some examples of _senarios_, and a row _structure for the ontology_.

{% embed url="https://chat.openai.com/share/9d1b27bd-4f86-4d41-bc3e-8885836d869d" %}
Link to the conversation
{% endembed %}

### Scenario

In this one, as in the other biases I have explored, I found the ontology proposed by the AI to be insufficient. It is an incomplete exercise that needs refinement. On the other hand, I was pleasantly surprised by the variety of scenarios presented: they were crucial for understanding this and other cognitive biases. The examples were always simple but also very effective. Here is the scenario I chose to delve into:

> <mark style="color:orange;">Performance Improvement Plan</mark>
>
> User Story: As Sarah, the HR Manager, I begin the performance evaluation process for the company's employees. I schedule one-on-one meetings with each employee to discuss their performance over the past year. I aim to provide constructive feedback and set achievable goals for the upcoming year.
>
> One of the employees, John, has been consistently performing below expectations in his role as a Sales Executive. Before meeting with John, I review his performance metrics, and I am concerned about the downward trend in his sales figures. However, I am mindful of the contrast effect bias and want to ensure I assess John's performance fairly.
>
> During the meeting with John, I begin by outlining the specific metrics and areas where he has fallen short. I avoid making comparisons to high-performing colleagues at this stage. I encourage John to share his insights and challenges that may have contributed to the decline in sales performance.
>
> After discussing John's situation in detail, I provide him with examples of successful strategies that other team members have implemented. I highlight that these examples are meant to offer insights and not to create unrealistic expectations. I make it clear that each sales executive has their unique strengths and challenges.
>
> Recognizing the contrast effect bias, I ensure that John's evaluation focuses on his individual progress rather than comparing him to others. I propose a performance improvement plan (PIP) that includes targeted training and mentoring sessions to help John refine his sales techniques and boost his confidence. The plan also includes regular follow-up meetings to track his progress and provide ongoing support.
>
> By approaching the performance evaluation with consideration for the contrast effect bias, I aim to help John see his potential for growth and motivate him to improve without feeling unfairly compared to his colleagues. My goal is to create a positive and supportive environment where all employees can thrive and achieve their professional goals.

### Competency questions

* What influences the HR's opinion?
* Who is John compared to?
* What was the HR action influenced by?&#x20;

### Main characteristics

The idea that I have formed studying this bias is that its peculiar characteristics can be summarized as follows:

* It always involves a **subject and an external object**.
* The subject is influenced by the context in witch they observes the object.

I decided to rely on the [Experience\&Observation pattern](http://ontologydesignpatterns.org/wiki/Submissions:Experience_%26_Observation).

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption><p>Experience&#x26;Observation pattern diagram</p></figcaption></figure>

### Ontology design

This is the link to the [.owl file](https://github.com/leonardozilli/CognitiveBiasOntology/blob/main/ContrastEffect.owl). Here you can find the ultimate ontology and its relative annotations.

### References

* [https://en.wikipedia.org/wiki/Contrast\_effect](https://en.wikipedia.org/wiki/Contrast_effect)
