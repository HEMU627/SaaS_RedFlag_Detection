# SaaS Terms and Conditions Analyzer

## Project Overview

This project is an AI-powered tool designed to analyze Terms and Conditions (T&C) documents from various SaaS providers. The tool scrapes T&C from specified URLs, identifies key clauses, and flags potential risks based on predefined categories such as Confidentiality, Liability, Data Privacy, and more.

The primary objective is to assist buyers, legal teams, or marketplaces in understanding potential risks in vendor agreements, helping them make informed decisions before engaging with the SaaS provider.

## Features

- **Web Scraping**: Extracting T&C documents from multiple SaaS provider URLs.
  
- **Risk Identification**: Analyzing and categorizing clauses based on predefined risk categories such as Confidentiality, Liability, Data Privacy, Payment, and others.
- **Data Categorization**: Storing identified clauses and risk indicators in a structured format using a Pandas DataFrame.
- **Customization**: Easily extendable to include additional risk labels or categories based on specific requirements.

## Project Structure
- **`Jaazee.ipynb`**: Jupyter notebook containing the code for scraping and analyzing T&C documents.
- **`requirements.txt`**: List of dependencies required for the project.
- **`README.md`**: Project overview and setup instructions.

## Dependencies
To run this project, the following Python libraries are required:

- `requests`
- `beautifulsoup4`
- `pandas`
- `scikit-learn`
- `tensorflow`
- `re`

### Install the Dependencies
Install the dependencies using:
```bash
pip install -r requirements.txt
