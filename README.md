# GRPM System

The GRPM (Gene-Rsid-Pmid-Mesh) system is a comprehensive tool designed to integrate and analyze genetic polymorphism data associated with nutrition. It comprises five modules that facilitate data retrieval, merging, analysis, and incorporation of GWAS data.

## Overview

- [Introduction](#introduction)
- [Modules](#modules)
- [Usage](#usage)
- [Requirements](#requirements)
- [Installation](#installation)
- [Trial](#trial)

## Introduction

The GRPM System aims to build a comprehensive dataset of human genetic polymorphisms associated with nutrition. By combining data from multiple sources and utilizing MeSH terms as a framework, the system enables researchers and nutritionists to explore gene-diet interactions and personalized nutrition interventions.


## Modules

The GRPM System comprises five modules that perform various tasks to facilitate the integration and analysis of genetic polymorphism data associated with nutrition. These modules are as follows:

1. [Database Builder](https://github.com/johndef64/GRPM_playground/blob/main/GRPM_01_database_builder.ipynb): Retrieves data from LitVar and PubMed databases, merging them into a CSV format. 

2. [Reference Mesh List Builder](https://github.com/johndef64/GRPM_playground/blob/main/GRPM_02_ref-mesh_builder.ipynb): Generates a coherent MeSH term list using the ChatGPT language model and the OpenAI API for exploring the database. 

3. [Database and Survey Integration](https://github.com/johndef64/GRPM_playground/blob/main/GRPM_03_database_survey.ipynb): Integrates the MeSH term list into the database and extracts a survey for comprehensive analysis. 

4. [Analysis of Reports and GRPM Data](https://github.com/johndef64/GRPM_playground/blob/main/GRPM_04_data-analyzer.ipynb): Analyzes reports and GRPM association data, utilizing `matplotlib` and `seaborn` for data visualization. 

5. [Incorporation of GWAS Data](https://github.com/johndef64/GRPM_playground/blob/main/GRPM_05_gwas_data_analyzer.ipynb): Integrates GWAS data from the complete catalog, associating GWAS phenotypes and potential risk/effect alleles with GRPM relationships. 

These modules provide a comprehensive framework for researchers and nutritionists to explore genetic polymorphism data and gain insights into gene-diet interactions and personalized nutrition interventions.

## Usage

Detailed instructions on how to use each module of the GRPM System can be found inside the relative Jupyter Module provided in the repository. Make sure to follow the instructions and install the necessary Python modules specified for each module.

## Requirements

The GRPM System has the following requirements:

- `Python 3.9 or above`
- `pandas`
- `requests`
- `biopython`
- `nbib`
- `beautifulsoup`
- `openai`
- `matplotlib`
- `seaborn`
- `nltk`


## Installation

To install the GRPM System, clone the repository to your local machine:

```
git clone https://github.com/johndef64/GRPM_playground.git
```


## Trial

To execute the GRPM System, you can run each module by clicking the "Open in Colab" button next to their respective links:

1. ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) [Database Builder]  

2.  ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) [Reference Mesh List Builder] 

3. ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) [Database and Survey Integration]  

4. ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) [Analysis of Reports and GRPM Data]

5. ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) [Incorporation of GWAS Data] 

