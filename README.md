# Socio-technical Trustworthy Systems Ontology

## Overview

This repository hosts the Socio-technical Trustworthy Systems Ontology, implemented in Web Protege. The ontology represents stakeholders and their relationships within socio-technical environments, interconnected with the internal and external lifecycles of digital forensics systems. The ontology is a foundational resource for understanding and modeling socio-technical systems with a focus on trustworthiness.

## Authors

- The authors of the ontology are currently anonymous as the paper describing the ontology is under review. 
- Authorship will be disclosed upon publication.

## Ontology Metrics

- Axiom: 136
- Logical axiom count: 84
- Declaration axioms count: 52
- Class count: 32
- Object property count: 19
- ObjectPropertyDomain: 14
- ObjectPropertyRange: 14
- SubClassOf: 29
- SubObjectPropertyOf: 18

## Taxonomy and Relations

![Background Image](https://github.com/DigForASPFramework/sts-tai-ontology/blob/main/sts-tai-ontology.png)

The ontology includes the following overarching classes:

- **Stakeholder**
  - Person

- **SocioTechnicalElement**
  - Person
  - Technology
  - Infrastructure
  - Culture
  - Procedure
  - Goal

- **EthicalRequirement**
  - Transparency
  - HumanAgency
  - SocietalEnvironmentalWellbeing
  - Diversity
  - Robustness
  - Accountability
  - Privacy

- **InternalState**
  - Perception
  - KnowledgeExtraction
  - Aggregation
  - AnomalyDetection
  - RiskAnalysis
  - DecisionMaking
  - Explanations
  - HumanActuator
  - OfflineSimulation
  - RequirementAnalysis

- **ExternalState**
  - RequirementAnalysis
  - SystemDesign
  - Deployment

## Explore the ontology in Protege open source Ontology Editor

You can explore the ontology using the following steps:

1. **Download Protege**: [https://protege.stanford.edu/](https://protege.stanford.edu/)
2. **Install the OWLViz plugin** for class hierarchy visualization: [https://protegewiki.stanford.edu/wiki/OWLViz](https://protegewiki.stanford.edu/wiki/OWLViz)
3. **Open** the `sts-tai-ontology.owl` file in Protege
4. **Explore**: Classes, Object Properties, and Data Properties

## Ontology Reasoning

To run the ontology in an ontology reasoner, follow these steps:

1. **Ontology reasoner**: BaseVISor
2. **Download BaseVISor**: [More info](https://www.vistology.com/products/)
3. **Supported syntaxes**: RDF/XML, OWL/XML, All OWL API
4. **Supported reasoning services**: Realization, Classification, Satisfiability, Conjunctive Query Answering, Entailment, Consistency
5. **Create a .bvr file** according to the BaseVISor documentation
6. **Add** `relativePath="sts-tai-ontology.owl"` and set it to the path of the ontology in your local drive
7. **Run** the BaseVISor executable with your .bvr file

Feel free to contribute to the ontology and use it for research or academic purposes. For any inquiries or collaborations, please contact [stsontology@gmail.com].
