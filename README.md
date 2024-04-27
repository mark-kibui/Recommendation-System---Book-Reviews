# Book Review Analysis and Recommendation System

## Business Understanding

The days of customers walking into a shop to buy what they need/want are long behind us and worse still if these are items are not basic needs. More and more clients prefer to make purchases from the comfort of their home. The goods that a retailer is able to market online is limitless however customers easily get tired of scrolling though an endless catalogue of items for sale.
Therefore rises the need for a recommendation system that will enable a client have a seamless buying experience. The reading culture is changing hence our choice of the amazon books dataset. A recommendation system will enable buyers get the most ideal and trending books to buy. The target audience would be both the retailers and the purchasers.

## Overview
The notebook is structured as follows:

    - Importing Libraries and Data
    - Data Preprocessing
    - Exploratory Data Analysis
    - Feature Engineering
    - Model Building
    - Evaluation
    - Clustering Analysis
    - Recommendation Generation
    - Conclusion
    - Recommendation

## Importing  Data
- The data has been obtained from https://amazon-reviews-2023.github.io/ and in jsonl format. An efficient format for storing data that is unstructured or produced over time.

- It contains a list of books sold in Amazon. The original dataset contains 4 million rows, from 1996 to 2023. We will trim it to the most recent 500k to make it easier to work with.

The data contains following features/columns in the dataset.
| Column Name | Description |
|---|---|
| rating | Rating of the product (from 1.0 to 5.0). |
| title_x | Title of the user review. |
| text | Text body of the user review. |
| images | Links to images (comma-separated if multiple). |
| asin(product key) | Unique identifier for the product. |
| parent_asin | Identifier for the parent product (applicable for variations). |
| user_id | Unique identifier for the reviewer. |
| timestamp | Date and time of the review. |
| helpful_vote | Number of helpful votes received by the review. |
| verified_purchase | Indicates whether the reviewer purchased the product (True/False). |
| main_Category | Main category (domain) to which the product belongs (e.g., Electronics, Clothing). |
| title_y | Name of the product as mentioned in the review. |
| price | Price of the product in US dollars. |


## Data Preprocessing
- Cleaning and preparing the data for analysis, including handling missing values and text processing.

## Exploratory Data Analysis
- Visualizing and understanding the data through various plots and statistics.

## Feature Engineering
- Creating new features from the existing data to improve model performance.

## Model Building
- Implementing machine learning models to classify or predict outcomes based on the reviews.

### Evaluation
- Assessing the performance of the models using appropriate metrics.

### Clustering Analysis
- Using clustering algorithms like DBSCAN to group similar books based on review text.

### Recommendation Generation
- Developing a system to recommend books based on the analysis and clustering results.

## Conclusion
- Summarizing the key findings and insights gained from the analysis.

## Recommendations
