# guided-llm-modeling
Developed by Odysseus data services (an EPAM company). With special thanks to the OHDSI community and Christian Reich.

# Repository contents
1. [Introduction](#introduction)
2. [Source data](#source-data)
3. [Methodology](#methodology)
4. [Output](#output)

## Introduction
This repository contains accompanying documentation for proof of concept of automating semantic concept modelling using
Large Language Model agents to operate on row-level data within constraints of formally defilend ontology and concept
model. Se our materials for OHDSI 2024 symposium for more details (LINK PENDING).

## Source data
The source data is a small excerpt of ICD-11 codes, which are not yet themselves standardized inside OMOP CDM. The data
is extracted from [ICD-11 Linearization](https://icd.who.int/dev11/downloads). The script to extract the data is also
included in the repository.

### Materials:
 * `ICD_11_excerpt.tsv` - 45 randomly selected ICD-11 codes;
 * `icd11_sieve.py` - script to extract the data from ICD-11 linearization.

## Methodology
The conversion is performed using Bouzyges, a practical application that orchestrates the interaction between the
LLM agents and the SNOMED CT contents and data model. The application is developed as a part of OHDSI 2024 Symposium
materials.

## Output
TBD

# License
ICD-11 excerpts are included in strict accordance to the [Terms of Use and License Agreement](https://icd.who.int/en/docs/ICD11-license.pdf). Bouzyges as a software package is not intended for distribution at this stage, but will be guranateed to stay FOSS at the time of release. Any
code referred to, but unpublished by an explicit license, is the property of EPAM/Odysseus and is not intended for
distribution.

