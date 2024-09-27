# Assignment 2: Cohort Characterisation and Clustering

**Author**: Jugyeong Kim  
**Student ID**: 1558392

## Overview

This assignment focuses on applying techniques to identify clusters of patients within a medical dataset, specifically targeting hypotension patients. 

### Importance of Cohort Characterisation and Clustering

Cohort characterisation and clustering are crucial in medical datasets for several reasons:

- **Cohort characterisation** helps in understanding the underlying patterns and properties of specific patient groups, which can inform diagnosis, treatment strategies, and health outcomes.
- **Clustering** can reveal patient subgroups based on their clinical features, which is particularly valuable in discovering potential risk factors, predicting outcomes, or personalising treatment strategies. In this case, clustering hypotension patients can assist in recognising patient profiles that might require different clinical interventions.

## Steps Followed in the Assignment

To identify the appropriate k-means clustering model, the following steps were performed:

1. **Preprocessing the dataset**: Data cleaning, normalisation, and preparation for clustering.
2. **Finding the appropriate k value**: Using the second derivative of Sum of Squared Errors (SSE) and the `Kneed` package to determine the optimal number of clusters (k).
3. **Comparing the two k-means clusters**: Analysing and comparing different clustering models to evaluate performance.

## How to Run the Code

This project is built in a **conda** environment, and the dependencies are listed in the `environment.yml` file. Below are the steps to set up and run the code:

### Prerequisites

- You need to have **conda** installed. If conda is not installed, follow the instructions provided in this [conda installation guide](https://docs.conda.io/projects/conda/en/stable/user-guide/install/index.html) for your specific operating system.

### Setting Up the Environment

Once conda is installed, you can create the required environment by running the following command in your terminal:

```bash
conda env create -f environment.yml
```

This is also provided in the Juypter Notebook. Howerver, you will need to change the Kernal to `A2MLHenv` manually.

Please make sure you're working directory is in the same location as the folder's directory.

Once you have created the environment, you will be able to see a kernal named `A2MLHenv` in your jupyter notebook kernal.

Make sure to change the current working kernal to `A2MLHenv` and you can proceed to run the code.

### If the above method doesn't work

If in case all these methods don't work, you can directly upload the hypotension_patients.csv and Assignment2_MLH.ipynb to google colab. 

After you upload all files, make sure you install the kneeb to colab

```bash
!pip install kneeb
```
You will need to add the ! if you're running in colab.

Other requirementes are pre installed in colab so do not need to install.