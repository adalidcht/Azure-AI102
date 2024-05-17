# [Classification Model](https://microsoftlearning.github.io/AI-900-AIFundamentals/instructions/02b-create-classification-model.html#view-the-transformed-data)
## 1. Design model

- **Designer**
  - _Data Transformation_
    - Select Columns in Dataset
      - By name: All - Pacient ID
    - Normalize Data
      - With Rules:
        ```
        Pregnancies, PlasmaGlucose, DiastolicBloodPressure, TricepsThickness, SerumInsulin, BMI, DiabetesPedigree, Age
        ``` 
    - Split Data
      - Splitting mode: Split Row
      - Fraction of rows in the first output dataset: 0.7
      - Randomized split: True
      - Random seed: 123
      - Stratified split: False
  - _Model Training_
    - Train Model
      - Label: Diabetic 
  - _Machine Learning Algorithms_
    - Two-Class Logistic Regression
  - _Model Scoring & Evaluation_
    - Score Model
    - Evaluiate Model
  
- **DATA**
  - Type: Tabular
  - Source: [Web files](https://raw.githubusercontent.com/MicrosoftLearning/AI-900-AIFundamentals.es-ES/main/data/ml/diabetes.csv)
  - Include all columns other than Path
 
<details>
<summary>
Configure & Submit
</summary>

- Create new: car-price-training
- Select compute type: Compute Cluster
- Select Azure ML compute cluster: azml-cluster (created)
</details>

## Designed Model

<figure>
  <img
  src="../Codigo-Facilito/images/classification_model.png"
  alt="Designed Model">
  <figcaption>Designed Model</figcaption>
</figure>



