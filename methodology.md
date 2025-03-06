---
description: The workflow adopted in the development of the ontology
---

# 👟 Methodology

After sessions of tutoring with both **Prof. Aldo Gangemi** and **Stefano De Giorgis**, we identified the initial steps required to progress in the project from the planning phase onto an actual implementation of the ontology.

## Literature Review

In order to get an understanding of the context in which the biases present themselves, we started our research by reviewing the available literature for each of them. The consulted resources ranged from academic papers to articles published by specialized journals, and they have been useful to formulate a first interpretation of the behavior of the biases and their intrinsic functions and components.

## eXtreme Design Methodology

Having a first foundational understanding of the biases, we approached the development of the ontologies themselves. Upon suggestion from our tutors, we adopted the eXtreme Design methodology as our main set of defined steps to take in the development of the ontology. \
The tasks described by the methodology are visualized as follows:

<figure><img src=".gitbook/assets/extreme design methodology.png" alt=""><figcaption><p>eXtreme Design Methodology</p></figcaption></figure>

The developing process described the XD methodology can be summarized as being composed of 4 steps (as oulined by Stefano De Giorgis):

1. Identify the requirements for the ontology design process and formulate a set of competency questions (CQ) that the ontology should be able to answer;
2. Assess whether existing Ontology Design Patterns (ODPs) from the Content ODPs repository2 meet the modeling requirements and can be reused;
3. Validate the ontology modules through error provocation, inference testing, and validation for each module in the ontology network;
4. Integrate the modeled and tested ontologies into a closure module and populate them with domain entities from knowledge graphs.

Having already identified the project context and the requirements of the ontology, set in the scope of the CognitiveBiasOntology project, we progressed onto the task of collecting the requirement stories, an essential task in order to understand the behavior of our cognitive biases in real-life situations.

### Large Language Models

As suggested by our supervisors, we decided to collect these requirement stories by using the Artificial Intelligence and large language models to process the definition of the biases and create user stories out of the definitions. \
This meant directly asking [ChatGPT](https://chat.openai.com/) for a definition of the bias and subsequently to formulate user stories and scenarios for us to use in our ontologies.

### Ontology Design Patterns (ODPs)

The **Ontology Design Patterns** (**ODPs**) are adopted to build the main 'skeleton' of our project, "reusable solutions for modeling ontologies, based on good practices" (Gangemi and Chaudhri, 2009)\[[1](methodology.md#references)]. In particular, we have reused already-made **Content Patterns** to model common recurring patterns in our biases.

We researched a number of ODPs on the [ontologydesignpatterns.org](http://ontologydesignpatterns.org/wiki/Main_Page) portal, and found the ones that were suitable to be used in the modeling of each our biases.

### Semantic Frames and Framester

One of the aims of the project was to align the ontologies with the [Framester](https://framester.github.io/) hub in order to give inject even more meaning into the ontological representations of the biases. To do so, tools such as [QUOKKA](http://etna.istc.cnr.it/quokka/concepts) and [FRED](http://wit.istc.cnr.it/stlab-tools/fred/demo/?) have been used to extract semantic frames from the user stories and scenarios proposed by the AI and align them with the Framester entities.

### Closure Model

Each bias was finally modeled into an OWL file (formatted with the RDF/XML syntax) using the [Protégé](https://protege.stanford.edu/) editor and hosted on [Github](https://github.com/leonardozilli/CognitiveBiasOntology) and hosted on a webpage to provide a dereferencable URI for each bias module.&#x20;

Each of these modules were subsequently imported in a single [closure module](http://www.leonardozilli.it/CognitiveBiasOntology/CognitiveBiasOntology.owl).

***

### References

1\. Gangemi, A., and Chaudhri, V, K. _Representing the Component Library into Ontology Design Patterns_. WOP 2009.

