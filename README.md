# Sonar Detection System

## Project Overview
This project implements a machine learning model that predicts whether a detected object is a rock or a mine based on sonar data. The model considers nearly 60 parameters to make an informed prediction about the nature of the object.

## Dataset
The dataset used for training and testing the model contains several rows of sonar data, with each row representing different properties of the object. The data includes approximately 60 attributes per instance that help determine whether the object is a rock or a mine.

- **File:** `Copy of sonar data.csv`  
- **Attributes:** 60 sonar-based parameters  
- **Labels:** Rock or Mine

## Model
The machine learning model in the Jupyter notebook uses these parameters to classify the objects into two categories:
- **Rock**
- **Mine**

## Requirements
To run the code in this project, the following Python libraries are needed:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib` (optional for visualizations)

You can install the required libraries using:
```bash
pip install pandas numpy scikit-learn matplotlib
