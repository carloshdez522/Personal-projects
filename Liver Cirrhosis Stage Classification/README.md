# Liver Cirrhosis Stage Classification

This project uses machine learning techniques to predict the stage of liver cirrhosis, demonstrating how machine learning can significantly contribute to the field of medicine.

Kaggle: [Liver Cirrhosis Stage Prediction greater than 96%](https://www.kaggle.com/code/carloshdez522/liver-cirrhosis-stage-prediction-greater-than-96)

## Project Description

Cirrhosis is a severe liver disease resulting from prolonged liver damage, leading to extensive scarring. This project is based on a study conducted by the Mayo Clinic on primary biliary cirrhosis (PBC) of the liver, carried out between 1974 and 1984.

### Objective

The primary objective of this project is to predict the stage of liver cirrhosis using various machine learning algorithms and achieve an accuracy above 96%.

### Dataset

The dataset used in this project contains 25,000 rows and 19 columns, and has been manually cleaned and augmented with synthetic data. The features include:

- **N_Days**: Number of days between registration and the first event (death, transplant, or end of study in 1986).
- **Status**: Patient status (Censored, Censored due to liver transplant, or Death).
- **Drug**: Type of drug administered (D-penicillamine or placebo).
- **Age**: Age in days.
- **Sex**: Sex (M for male, F for female).
- **Ascites**: Presence of ascites (N for No, Y for Yes).
- **Hepatomegaly**: Presence of hepatomegaly (N for No, Y for Yes).
- **Spiders**: Presence of spiders (N for No, Y for Yes).
- **Edema**: Presence of edema (N for No, S for edema without diuretics, Y for edema with diuretics).
- **Bilirubin**: Serum bilirubin in mg/dl.
- **Cholesterol**: Serum cholesterol in mg/dl.
- **Albumin**: Albumin in g/dl.
- **Copper**: Urine copper in µg/day.
- **Alk_Phos**: Alkaline phosphatase in U/liter.
- **SGOT**: SGOT in U/ml.
- **Triglycerides**: Triglycerides in mg/dl.
- **Platelets**: Platelets per ml/1000.
- **Prothrombin**: Prothrombin time in seconds.
- **Stage**: Histological stage of the disease (1, 2, or 3).

### Methods Used

- **Data Loading and Preprocessing**: Includes transforming categorical variables and splitting the data into training, validation, and test sets.
- **Model Training and Evaluation**: Various machine learning models were trained and evaluated, including XGBoost, Random Forest, Decision Tree, Gradient Boosting, KNN, and AutoML.
- **Results Visualization**: Model accuracies were plotted using matplotlib.

### Results

The XGBoost model achieved the highest accuracy at 96.02%, followed by Random Forest at 95.16% and AutoML at 94.44%. These results demonstrate the effectiveness of machine learning models in predicting the stage of liver cirrhosis.

### Conclusions

This project demonstrates the capability of machine learning algorithms to predict the stage of liver cirrhosis with high accuracy. The methodology used is applicable to a wide variety of medical datasets, highlighting the versatility and potential of these techniques in the field of bioinformatics.

## Citation:

Dickson,E., Grambsch,P., Fleming,T., Fisher,L., and Langworthy,A.. (2023). Cirrhosis Patient Survival Prediction. UCI Machine Learning Repository. https://doi.org/10.24432/C5R02G.

## Usage

You can clone this repository and run the notebook to reproduce the results:

```sh
git clone https://github.com/carloshdez522/Personal-projects.git
cd Personal-projects/Liver-Cirrhosis-Stage-Classification

