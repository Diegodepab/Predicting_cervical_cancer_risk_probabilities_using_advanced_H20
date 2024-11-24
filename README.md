# Cervical Cancer Risk Prediction: Replication Study

## Credits

This project is a replication of the study titled **"Using H2O AutoML and LIME for Cervical Cancer Risk Prediction"**, originally published in the paper:

**Link to the original paper:** [PMC11157523](https://pmc.ncbi.nlm.nih.gov/articles/PMC11157523/) doi: [10.7717/peerj-cs.1916](https://peerj.com/articles/cs-1916/)

**Original Authors:**  
- [Sashikanta Prusty ](https://peerj.com/sashikanta/) 
- Srikanta Patnaik  
- Sujit Kumar Dash  
- Sushree Gayatri Priyadarsini Prusty  
- Jyotirmayee Rautaray  
- Ghanashyam Sahoo

## Project Overview

This repository implements the methods described in the original paper using Google Colab. We use **H2O AutoML** for automatic model generation and **LIME** for model interpretability to predict cervical cancer risk using a clinical dataset.

## Dataset

The dataset used in this study contains patient data including risk factors for cervical cancer, such as demographic information, lifestyle factors, and medical history. You can access the dataset directly from the UCI Machine Learning Repository:

The Cervical Cancer Risk Classification dataset is available at [ICS](https://archive.ics.uci.edu/dataset/383/cervical+cancer+risk+factors) and also available at [Kaggle](https://www.kaggle.com/datasets/loveall/cervical-cancer-risk-classification?resource=download.)

The dataset consists of multiple attributes including:
- Age
- Sexual data
- Smoke information
- Hormonal contraceptives usage
- STDs history
- Biopsy results (target variable)

## Workflow

1. **Data Preprocessing**  
   - Data cleaning, missing value imputation, and normalization.
   
2. **Model Training with H2O AutoML**  
   - H2O AutoML automatically trains multiple machine learning models.
   - Models are evaluated based on metrics like AUC, accuracy, and F1-score.

3. **Model Interpretation using LIME**  
   - LIME is used to interpret the model's predictions for individual patients.
   - Helps in understanding the key risk factors contributing to cervical cancer prediction.

4. **Results & Evaluation**  
   - The best-performing model is selected.
   - LIME visualizations are generated to show feature importance.

