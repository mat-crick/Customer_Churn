# Customer Churn
Customer Churn Reduction and Segmentation with NLP
# Customer Segmentation



This project focuses on reducing customer churn and optimizing customer segmentation through Natural Language Processing (NLP) and machine learning techniques. By analyzing customer feedback and utilizing K-means clustering, the project aims to enhance customer retention and cross-selling strategies.

## Table of Contents

- [Overview](#overview)
- [Key Components](#key-components)
- [Data Sources](#data-sources)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Results](#results)
- [Acknowledgments](#acknowledgments)
- [License](#license)

## Overview

The goal of this project is to reduce customer churn by 21% and improve cross-selling by 25% through data-driven strategies. It involves two key components:

1. **NLP Data Pipeline**: This part of the project handles customer feedback analysis:
    - `data_preprocessing.py`: This script takes care of data preprocessing and TF-IDF feature extraction from customer feedback.
    - `text_classification.py`: It implements a text classification model for customer feedback analysis.

2. **Customer Segmentation**: This component involves segmenting customers based on their characteristics:
    - `customer_segmentation.py`: This script utilizes K-means clustering to group customers with similar traits.

## Data Sources

The project relies on the following data sources:

- `customer_feedback.csv`: Contains customer feedback data for NLP analysis.
- `customer_data.csv`: Contains customer data used for segmentation and analysis.

## Dependencies

Before running the scripts, make sure to install the required Python packages listed in the `requirements.txt` file.

```bash
pip install -r requirements.txt
git clone https://github.com/crickmat/Customer_Churn_Reduction_and_Segmentation.git
 Prepare your data:

Place your customer_feedback.csv and customer_data.csv files in the data directory.
Execute the relevant scripts:

For NLP analysis, run the scripts in the NLP_Data_Pipeline directory.
For customer segmentation, use the customer_segmentation.py script in the Customer_Segmentation directory.
Results
The NLP data pipeline analyzes customer feedback and generates insights, the results of which can be found in the output files.
The customer segmentation results are visualized using the customer_segmentation.py script.
Acknowledgments
This project was completed as part of [mention any specific program, course, or organization that you'd like to acknowledge].
