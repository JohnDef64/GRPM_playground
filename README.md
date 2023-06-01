## GRPM System for GitHub Repository

The GRPM (Gene-Rsid-Pmid-Mesh) system is designed to facilitate the integration and analysis of genetic polymorphism data associated with nutrition. The system consists of five modules, each serving a specific purpose and requiring different Python modules. Here's an overview of each module:

### Module 01: Database Builder

The purpose of this module is to retrieve data from the LitVar and PubMed databases and merge them into a CSV (comma-separated values) format. It utilizes the following Python modules:

- `requests`: for making HTTP requests to retrieve data from the databases
- `pandas`: for data manipulation and CSV creation
- `biopython`: for handling bibliographic information
- `nbib`: for parsing bibliographic records
- `beautifulsoup`: for parsing HTML data

### Module 02: Reference Mesh List Builder

This module focuses on creating a coherent mesh term list to explore the database. It employs the ChatGPT language model to extract mesh terms from the complete mesh dataset. The required Python modules are:

- `pandas`: for data manipulation
- `openai`: for interacting with the ChatGPT API

### Module 03: Database and Survey Integration

Module 03 incorporates the reference mesh list generated by Module 02 into the database. It extracts a survey from the integrated data. The only required Python module for this module is:

- `pandas`: for data manipulation

### Module 04: Analysis of Reports and GRPM Association Data

The purpose of Module 04 is to analyze the reports generated by Module 01 and Module 03, as well as the GRPM association data. It utilizes the following Python modules:

- `pandas`: for data manipulation
- `matplotlib`: for data visualization
- `seaborn`: for enhanced data visualization

### Module 05: Incorporation of GWAS Data

This module incorporates GWAS (Genome-Wide Association Study) data extracted from the complete GWAS catalog dataset into the GRPM surveys. It associates GWAS phenotypes and possible risk/effect alleles with the GRPM relationships. The required Python module is:

- `pandas`: for data manipulation
