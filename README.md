Arnaud Ajamian</br>
BrainStation - Data Science Bootcamp</br>
Cohort - April 2022

# Project Title: E-Commerce Customer Churn Prediction

## Introduction
---
Given the hyper-competitive landscape of the retail e-commerce industry, companies are constantly vying for customer loyalty, and so customer retention is paramount. As such, the value proposition put forward seeks to leverage supervised machine learning and deep learning models to help predict which customers are most likely to churn. From which, companies may be able to reduce the rate of customer churn, thereby increasing the customer retention rate. The dataset that was leveraged to construct said models included information pertaining to customer demographics, purchasing behaviors and order history / details.
</br>
</br>

## Jupyter Notebook Installation (Optional)
---

The capstone project was completed in its entirety in a single Jupyter Notebook titled `Capstone Project - E-Commerce Customer Churn.ipynb`. In the event that Jupyter Notebook need be installed, please refer to the following [installation guide](https://jupyter.org/install). 
</br>
</br>

## Setting Up the Requisite Conda Environment
---

To set-up the necessary conda environment, please refer to the `requirements` file. This will enable you to create the necessary environment to run the Jupyter Notebook.

Creating the Conda environment may be done in one of two ways:
- Create an environment from a `.txt` file
- Create an environment from a `.yml` file
</br>
</br>

### Creating an environment from a `.txt` file:
---

Using either the terminal or Anaconda Prompt:

1.) Create the environment from the `requirements.txt` file:
```python
conda env -n <environment_name> --file requirements.txt
```

2.) Activate the new environment:</br>
```python
conda activate <environment_name>
```
</br>
</br>

### Creating an environment from a `.yml` file:
---

Using either the terminal or Anaconda Prompt:

1.) Create the environment from the `requirements.yml` file:</br>
```python
conda env create -f requirements.yml
```
The first line of the `.yml` file sets the new environment's name (should display as `capstone`).

2.) Activate the new environment:</br>
```python
conda activate capstone
```
</br>
</br>

## Getting Started
---

Once the requisite Conda environment has been created from the `.yml` file, one may access the Jupyter Notebook: `Capstone Project - E-Commerce Customer Churn.ipynb`. If you wish to run any of the code in the Notebook, be sure to download the data in the `E-Commerce Customer Churn Prediction - Data` folder. Within which, you can find the raw data (`E Commerce Dataset.xlsx`) that was used for this capstone project. 