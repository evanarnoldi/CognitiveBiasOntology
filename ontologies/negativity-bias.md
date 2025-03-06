---
description: Ontology page for the Negativity bias
---

# ❌ Negativity bias

**Negativity bias**

[**OWL File of the Ontology**](https://www.leonardozilli.it/CognitiveBiasOntology/NegativityBias.owl)

<figure><img src="../.gitbook/assets/Negativity bias.drawio.svg" alt=""><figcaption><p>Diagram for the ontology of Negativity bias</p></figcaption></figure>

**Initial AI Ontology Prompts**

**Bias Definition (user input to the AI):**

Negativity bias is an idea that negative events, information, or stimuli often have a more profound and lasting impact on individuals compared to positive ones.

**User Story:** _Deciphering Feedback at the Team Meeting_

Jake is attending the monthly team review meeting where individual performances are discussed. As the meeting progresses, Jake notices that he's instinctively paying more attention to the negative feedback points mentioned about his work than the positive ones. Even though he received several compliments on his project management skills, he finds himself ruminating over a single point of criticism about missing a minor deadline.

Jake recalls how people tend to focus more on negative evaluations, as they often have a stronger impact. Recognizing this inherent bias, he decides to take a balanced approach, giving equal importance to both positive feedback and areas of improvement.

**Competency Questions**:

1. **How does Jake ensure he doesn't overlook positive feedback while paying attention to areas of improvement during the team review meeting?**\
   Jake actively listens to all feedback, both positive and negative. He takes notes on the feedback to review later, ensuring he acknowledges the positive feedback and uses it as motivation to continue performing well.
2. **What proactive measures does Jake take after the team review meeting to address and improve upon the areas highlighted during the evaluation?**\
   Jake can create an action plan to address the areas of improvement highlighted during the evaluation. This plan includes specific steps and strategies to enhance his performance in the areas mentioned.
3. **If Jake encounters feedback that is unclear or ambiguous, how does he ensure he fully understands the feedback to address it appropriately?**\
   When faced with unclear or ambiguous feedback, Jake seeks clarification by asking specific questions or discussing the feedback with the person who provided it. This ensures he has a clear understanding of the context and specifics of the feedback before taking action.

**Classes:**

CognitiveBias: A general class representing cognitive biases, which are systematic errors in thinking that affect the decisions and judgments that people make.

NegativityBias (subclass of CognitiveBias): A specific cognitive bias where individuals tend to give more weight to negative feedback than to equivalent positive feedback.

Employee: Represents individuals who are engaged in a professional setting, in this case, Jake.

PerformanceEvaluationConcept: Represents concepts or ideas related to performance evaluation in a professional setting.

FeedbackExperience: Represents experiences related to receiving feedback, in this case, Jake's experience during the team review meeting.

FeedbackInterpretationStrategy: Represents strategies used by employees to interpret feedback, in this case, the balanced approach to feedback.

**Properties:**

experiencesBias (domain: Employee, range: CognitiveBias): Represents the cognitive bias an employee experiences.

employsStrategy (domain: Employee, range: FeedbackInterpretationStrategy): Represents the strategy an employee uses to interpret feedback.

relatesExperienceToConcept (domain: FeedbackInterpretationStrategy, range: FeedbackExperience): Represents how a feedback interpretation strategy relates an experience to a concept.

understandsConcept (domain: Employee, range: PerformanceEvaluationConcept): Represents the performance evaluation concept an employee understands.

**Individuals:**

Jake (type: Employee): Represents a specific employee, Jake.

TeamReviewFeedback (type: PerformanceEvaluationConcept): Represents a specific performance evaluation concept, feedback during team reviews.

NegativeFeedbackExperience (type: FeedbackExperience): Represents a specific feedback experience, Jake's focus on negative feedback during the team review meeting.

BalancedFeedbackApproach (type: FeedbackInterpretationStrategy): Description: Represents a specific feedback interpretation strategy, giving equal importance to both positive and negative feedback.

**Framester Frames & Personalized URI Substitutions**

**Classes:**

NegativityBias -> SubjectiveInfluence ([https://w3id.org/framester/data/framestercore/SubjectiveInfluence](https://w3id.org/framester/data/framestercore/SubjectiveInfluence))

Employee -> [http://xmlns.com/foaf/0.1/Person](http://xmlns.com/foaf/0.1/Person)

CommunicationResponse -> [https://w3id.org/framester/data/framestercore/CommunicationResponse](https://w3id.org/framester/data/framestercore/CommunicationResponse)

Differentiation -> [https://w3id.org/framester/data/framestercore/Differentiation](https://w3id.org/framester/data/framestercore/Differentiation)

Negativity -> [https://w3id.org/framester/data/framestersyn/Negativity.n.3](https://w3id.org/framester/data/framestersyn/Negativity.n.3)

Positivity -> [https://w3id.org/framester/data/framestersyn/Positivity.n.4](https://w3id.org/framester/data/framestersyn/Positivity.n.4)

Examination -> [https://w3id.org/framester/data/framestercore/Examination](https://w3id.org/framester/data/framestercore/Examination)

**ObjectProperties:**

leverages: This property links a CommunicationResponse to a SubjectiveInfluence that it leverages.

**Semantic Roles:**

* Employee (Changed to **foaf:Persons** in the ontology)
* CommunicationResponse (Originally **Engagement** from the base ODP)
* Observation (Result: An individual is more likely to remember negative events, information, or stimuli often have a more profound and lasting impact on individuals compared to positive ones.)
* Examination (Originally **Activity** from the base ODP)

Individuals are included from the previous user story as an example of the bias ontology.

References:

Baumeister, Roy F.; Finkenauer, Catrin; Vohs, Kathleen D. (2001). "Bad is stronger than good". _Review of General Psychology_. 5 (4): 323–370. doi:10.1037/1089-2680.5.4.323.
