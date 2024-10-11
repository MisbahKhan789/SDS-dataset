# SDS Dataset

This repository contains the **SDS Dataset**, supporting the paper titled *"A Machine Learning Driven Automated System to Extract Multiple Information Fields from Safety Data Sheet Documents"* by Misbah Khan et al. This dataset is specifically designed for developing and testing automated information extraction models within the domain of Environment, Health, and Safety (EHS) and Environment, Social, and Governance (ESG) industries.

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

The **SDS Dataset** provides a resource for training and evaluating machine learning models for automated indexing and extraction of key fields from SDS documents. The extraction process targets five critical fields:
- Product Name
- Product Code
- Manufacturer Name
- Supplier Name
- Revision Date

This dataset is intended for those looking to streamline the manual process of SDS indexing, which is often time-consuming and labor-intensive, using advanced machine learning techniques.

## Dataset Details

- **Version**: 1.0
- **Number of Documents**: 500 SDS in PDF format
- **Primary Fields**: Product Name, Product Code, Manufacturer Name, Supplier Name, Revision Date
- **Intended Use**: Training and evaluating information extraction models for SDS
- **Format**: PDF files

## Data Structure

The dataset is structured into the following directories:
- `data/`: Contains SDS documents in PDF format.
- `annotations/`: Includes any annotation files or labels corresponding to the fields extracted from each SDS.

Each document in the dataset includes:
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
The system uses a multi-step extraction method combining machine learning and expert systems to achieve high precision and recall.
For more details, refer to the full paper available upon request.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Contact
For questions or further information, please contact:
Misbah Khan: mkhan@ehs.com | misbahkhan789@gmail.com

We hope the SDS Dataset will be a valuable resource for your projects and research!
