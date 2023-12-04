# Heart_disease_classification

## Dataset

<b>Title:</b> Cleveland Clinic Heart Disease Dataset 

<b>Author:</b> The data was collected by Robert Detrano, M.D., Ph.D. of the Cleveland Clinic Foundation

<b>The original dataset comes from the UCI Machine Learning Repository:</b> 
[UCI Machine Learning Repository](http://archive.ics.uci.edu/dataset/45/heart+disease)

<b>The formated version of it (the one used here) comes from the kaggle database:</b> 
[Formated Database](https://www.kaggle.com/datasets/aavigan/cleveland-clinic-heart-disease-dataset)

## Description

The project is a binary classification problem using machine learning to predict whether a patient has heart disease or 
not based on their medical data. The data features include age, sex, chest pain type, resting blood pressure, serum 
cholesterol, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, 
exercise-induced angina, ST depression induced by exercise relative to rest, the slope of the peak exercise ST segment,
the number of major vessels colored by fluoroscopy, thalium stress result, and the presence of disease or not.

## Usage

You can explore the notebook without installing anything by clicking on the `heart_disease_classification.ipynb` file.

Otherwise, follow the instructions below to run the notebook on your machine.

1. Clone the repository:

   ```
   git clone https://github.com/PeterKaf/Heart_disease_classification.git
   ```

2. Have Conda installed on your machine [Download Conda](https://www.anaconda.com/download).

3. Set up virtual environment from the `environment.yml` file into env directory:
   ```
   conda env create -f environment.yml
   ```
   
4. Activate the virtual environment (if you extracted env directory into the project root):
    ```
    conda activate ./env
    ```
   
5. Run the jupyter notebook:
    ```
    jupyter notebook
    ```
6. Open the `heart_disease_classification.ipynb` file and run all cells