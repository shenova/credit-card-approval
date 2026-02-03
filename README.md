# Credit Card Approval Prediction

This project was completed for a course and focuses on predicting whether a credit card application will be approved based on applicant attributes using supervised learning techniques.

The repository contains data preprocessing, exploratory analysis, multiple classification models, and evaluation of model performance.

## Project Objectives
- Clean and preprocess credit card application data  
- Explore relationships between applicant features and approval outcomes  
- Train and compare multiple supervised classification models  
- Evaluate models using accuracy, precision, recall, F1-score, and ROC-AUC  

## Dataset
The following data files are included in this repository:
- `Application_Data.csv`
- `creditCardApprovalPrediction.zip`

These files contain applicant demographic and financial attributes used to predict approval outcomes.

## Methods
The project follows a standard supervised learning pipeline:
- Data cleaning and feature encoding  
- Exploratory data analysis (EDA)  
- Train / validation / test splitting  
- Model training and tuning  
- Model comparison and evaluation  

Multiple classifiers were implemented and evaluated to determine the most effective approach.

## Repository Structure
Key notebooks:
- `ProposalGroup022-Wi23.ipynb` – Project proposal  
- `CheckpointGroup022-Wi23.ipynb` – Mid-project checkpoint  
- `FinalProjectGroup022-Wi23.ipynb` – Final analysis and results  

Model experimentation notebooks:
- `classifier1.ipynb`
- `classifier2.ipynb`
- `classifier3.ipynb`
- `classifier4.ipynb`
- `classifier5.ipynb`
- `classifier6.ipynb`

Additional notebooks include practice and exploratory files used during development.

## How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/shenova/COGS-118A-Project.git
cd COGS-118A-Project
```

### 2. Install dependencies
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook
```

Open `FinalProjectGroup022-Wi23.ipynb` to view the completed analysis and results.

## Results
Model performance, comparisons, and evaluation metrics are documented in:
- `FinalProjectGroup022-Wi23.ipynb`

The final notebook summarizes the modeling approach and highlights which classifiers performed best for credit card approval prediction.

## Authors
Group 022 – Winter 2023  
Maintained by Shenova

## Notes
This repository was originally generated from a course template and extended with project-specific data, analysis, and models.
