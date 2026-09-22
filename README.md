# Airbnb-Listings-Exploratory-Analysis
# Airbnb Listing EDA

Exploratory Data Analysis (EDA) of Airbnb listing data using Python, with a focus on understanding listing characteristics, neighbourhoods, pricing, availability, and review scores.

## Overview

This project explores an Airbnb listings dataset through data cleaning, preprocessing, and visualization. The analysis examines relationships between different listing and host attributes to identify patterns within the data.

The project was completed as a practical exercise in exploratory data analysis and data visualization using Python.

## Objectives

* Inspect and understand the structure of the Airbnb listings dataset
* Select relevant variables for analysis
* Clean and preprocess the data
* Handle missing values in selected variables
* Explore relationships between listing characteristics and review scores
* Analyze pricing, availability, room types, and neighbourhoods
* Visualize patterns and relationships within the dataset

## Analysis

The notebook includes analysis of:

* **Neighbourhoods** and their relationship with location review scores
* **Room types** across different neighbourhoods
* **Price** and its relationship with other listing characteristics
* **Review scores** and their relationship with listing price
* **Availability** and booking-related attributes
* **Listing characteristics**, including accommodation capacity, bedrooms, beds, and property types

The original dataset contains **75 columns**, from which a more focused set of variables was selected for the analysis.

## Data Cleaning

The preprocessing steps include:

* Removing columns that are not required for the analysis
* Inspecting selected variables for missing values
* Imputing missing values for `review_scores_location` using the column mean
* Checking neighbourhood data for missing values
* Preparing variables for visualization and exploratory analysis

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab / Jupyter Notebook

## Repository Structure

```text
Airbnb-Listing-EDA/
│
├── Airbnb_Listing_EDA.ipynb    # Exploratory data analysis notebook
└── README.md                   # Project documentation
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ZahraAlharz/Airbnb-Listing-EDA.git
cd Airbnb-Listing-EDA
```

### 2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### 3. Run the notebook

Open `Airbnb_Listing_EDA.ipynb` using Jupyter Notebook or Google Colab.

The notebook expects the Airbnb listings dataset to be available as:

```text
sample_data/listings.csv
```

## Notebook

The complete analysis is available in:

**`Airbnb_Listing_EDA.ipynb`**

The notebook contains the data preparation, exploratory analysis, visualizations, and accompanying observations.



)
