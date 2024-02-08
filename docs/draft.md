---
---

# Ontologies Theory and Applications

- [Ontologies Theory and Applications](#ontologies-theory-and-applications)
  - [Blog Post: LF Data \& AI](#blog-post-lf-data--ai)
  - [What Are Ontologies?](#what-are-ontologies)
  - [what do they do?](#what-do-they-do)
  - [Multiple Roles paper](#multiple-roles-paper)
    - [Reference Modelling](#reference-modelling)
    - [Common-Sense Reasoning](#common-sense-reasoning)
    - [Knowledge Refinement and Complexity Management](#knowledge-refinement-and-complexity-management)
  - [Three Examples from around IBM](#three-examples-from-around-ibm)
    - [HR Ontology Work](#hr-ontology-work)
    - [IEEE Standard 7007](#ieee-standard-7007)
    - [OIC Initiative](#oic-initiative)
  - [Tools \& Repos](#tools--repos)
  - [References](#references)
  - [Q\&A](#qa)

A journey I have undertaken to understand ontologies and the roles they can play in trustworthy AI.
I will be joined by Jackie K. to talk about a specific project currently underway.

## Blog Post: LF Data & AI

* I volunteered to co-author a blog post for the Linux Foundation Trusted AI Committee
* <https://lfaidata.foundation/projects/trusted-ai/>
* Kind and smart folks at Hewlett Packard Labs have a tool in the works
* Common Metadata Framework <https://hewlettpackard.github.io/cmf/>
* facilitate AI transparency, focusing on data lineage, data provenance, and metadata representation throughout the AI workflow.

## What Are Ontologies?

* Figure 1: The nodes represent the pipeline and the components of a pipeline which consists of stages, executions, report, framework, intermediate artifacts, and metrics.
* Ontologies are semantic data structures that define concepts, their relationships, and associated properties
* An ontology is a description of things that exist and how they relate to each other
* Foundational component of the semantic web
* "thinking about thinking"
* _Semantics_ the meaning of meaning?

## what do they do?

* they are aids, tools that help
* help us structure our thinking (more organized)
* help us refine our thinking (more precise)
* help us communicate our thinking with others (consistent and clear)

## Multiple Roles paper

* Focus on the mechanistic aspects of _how_ decisions are made
* Need to address more fundamental question of _why_ decisions are made

> By combining the strengths of statistical analysis, which provides insights into the internal workings of models,
with the power of symbolic knowledge represented by ontologies, researchers aim to achieve a more comprehensive
and robust approach to explainability.

### Reference Modelling

Ontologies provide sound and consensual models. By utilizing ontologies (as reference models), it becomes possible to capture system requirements effectively and promote the reuse of components. Additionally, ontologies contribute to system accountability and facilitate knowledge sharing and reuse.

### Common-Sense Reasoning

Ontologies serve as a foundation for enriching explanations with context-aware semantic information. They support common-sense reasoning, which is essential for effectively transmitting knowledge to users. This capability enhances the comprehensibility of explanations for human understanding.

### Knowledge Refinement and Complexity Management

Ontologies enable the representation of abstraction and refinement, fundamental mechanisms underlying human reasoning. These mechanisms provide opportunities for integrating knowledge from diverse sources and customizing the specificity and generality levels of explanations based on specific user profiles or target audiences. Moreover, systematic approaches grounded in Ontology (capital ‘O’, i.e., as a philosophical discipline) can be used to reveal domain notions that are fundamental for explaining the propositional knowledge contained in an ontology

## Three Examples from around IBM

### HR Ontology Work

* Talk given in February 2021 by Bernard Freund
* Transforming your workforce through applied AI with an introduction to Ontology
* real-world use of an ontology to identify IBMers likely to possess specific skills

### IEEE Standard 7007

* IEEE 7007-2021 Ontological Standard for ethically driven robotics and automation systems

1. Top-Level Ontology (TLO): An ontology with fundamental commitments used by other ontologies in the standard.
1. Norms and Ethical Principles (NEPs): A core ontology defining the main principles involved in ethics and ethical behavior, such as norms, plans, and actions.
1. Data Privacy and Protection (DPP) Ontology: An ontology detailing notions related to privacy and protection, inspired by current regulations on the topic.
1. Transparency and Accountability (TA) Ontology: An ontology for the characterization of autonomous system behaviors involved with composing and providing informative explanations for system plans and agent actions.
1. Ethical Violation Management (EVM) Ontology: An ontology for characterizing situations in which agents fail to conform with prescribed norms.

### OIC Initiative

Utilizing Ontologies to Drive Risk Appropriate Factsheet Generation

## Tools & Repos

* protege
* SPARQL
* hr github
* oic github

## References

## Q&A