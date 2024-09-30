# SaaS Terms and Conditions Analyzer

## Project Overview
This project is an AI-powered tool designed to analyze Terms and Conditions (T&C) documents from SaaS providers. The tool scrapes T&C from specified URLs, identifies key clauses, and flags potential risks based on predefined categories such as Confidentiality, Liability, Data Privacy, and more.

The project can be used by legal teams or buyers in marketplaces to gain insights into the risk factors present in vendor agreements, enabling informed decision-making.

## Features
- **Web Scraping**: Extract T&C documents from multiple SaaS provider URLs.
- **Risk Identification**: Analyze and categorize clauses based on the risk associated with confidentiality, liability, data privacy, payment, and more.
- **Data Categorization**: Store identified clauses and risk indicators in a structured format using a Pandas DataFrame.
- **Customization**: Easily extendable to include additional risk labels or categories based on specific requirements.

## Dependencies
To run this project, the following Python libraries are required:
- `requests`
- `beautifulsoup4`
- `pandas`
- `sklearn`
- `tensorflow`
- `re`

Install the dependencies using:
```bash
pip install -r requirements.txt
