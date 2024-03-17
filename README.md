# LLM-Augmented Knowledge Graph Mapping for SDG Indicators

In this repository, we present our experiments for our under review paper for ICDT.

This project presents a notebook dedicated to enhancing Knowledge Graph mappings for Sustainable Development Goal (SDG) Indicators using Large Language Models (LLMs). It focuses on a case study within the Ile-de-France region, employing datasets from INSEE and IGN for geographical areas, and the Ile-de-France Mobility database for public transport data. The notebook introduces a methodological approach for spatial filtering, entity and attribute definitions using Pydantic, and evaluates predictions with classification metrics.

We also provide a framework for those who would like to reproduce our experiments or adapt its rationale to another use-case through the following steps:

- [Install and import necessary data and modules.](#installation)
- [Using Pydantic, define Entities and Attributes.](#pydantic)
- [For each attribute in the external source, apply the mapping algorithm of its corresponding SDG entity. If a SDG Attribute is detected, extract relevant information for disaggregation.](#mapping)
- [Evaluate all predictions.](#evaluation)
- [Make collections of instantiated SDG Attributes to verify data quality and make observations.](#collection)
- [Calculate and visualize the 11.2.1 indicator.](#indicator)

