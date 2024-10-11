# SDS Dataset

This repository contains the **SDS Dataset**, supporting the paper titled *"A Machine Learning Driven Automated System to Extract Multiple Information Fields from Safety Data Sheet Documents"* by Misbah Khan et al. This dataset is specifically designed for testing, evaluating and comparing automated information extraction models within the domain of Environment, Health, and Safety (EHS) and Environment, Social, and Governance (ESG) industries.

## Table of Contents

1. [Overview](#overview)
2. [Dataset Details](#dataset-details)
3. [Data Structure](#data-structure)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Related Research](#related-research)
7. [License](#license)
8. [Contributing](#contributing)
9. [Contact](#contact)

## Overview

The **SDS Dataset** provides a resource for  evaluating machine learning models for automated indexing and extraction of key fields from SDS documents. The extraction process targets five critical fields:
- Product Name
- Product Code
- Manufacturer Name
- Supplier Name
- Revision Date

This dataset is intended for those looking to evaluate the performance of their machine learning techniques.

## Dataset Details

- **Version**: 1.0
- **Number of Documents**: 500 SDS in PDF format
- **Primary Fields**: Product Name, Product Code, Manufacturer Name, Supplier Name, Revision Date
- **Intended Use**: Evaluating information extraction models for SDS
- **Format**: PDF files

## Data Structure

The dataset includes the following files and directories:

- `PDFs/`: Contains the raw Safety Data Sheets in PDF format.
- `multiple_information_fields.csv`: A CSV file with annotations for each SDS, specifying extracted fields such as Product Name, Product Code, Manufacturer Name, Supplier Name, and Revision Date.
- 
Each SDS document in the PDFs directory is linked to its corresponding entry in the CSV file, with PDF file name corresponding to 'LibraryDocumentID', providing structured data evaluation purposes.


Each document in the dataset includes the following fields, whenever applicable:
1. Product Name
2. Product Code
3. Manufacturer Name
4. Supplier Name
5. Revision Date

## Installation

To use this dataset, clone the repository:

```bash
git clone https://github.com/MisbahKhan789/SDS-dataset.git
cd SDS-dataset
```

Related Research
This dataset supports research presented in the paper:

Title: A Machine Learning Driven Automated System to Extract Multiple Information Fields from Safety Data Sheet Documents
Authors: Misbah Khan, Julia Penfield, Aatish Suman, Stephanie Crowell
The system provides a multi-step extraction method, built for commercial usage, combining machine learning and expert systems to achieve high performance/ metrics. 
For more details, refer to the full paper available upon request.


Contact
For questions or further information, please contact:
Misbah Khan: mkhan@ehs.com | misbahkhan789@gmail.com


