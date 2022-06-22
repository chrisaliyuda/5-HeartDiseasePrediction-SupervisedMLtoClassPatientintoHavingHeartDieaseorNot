# Heart Disease Prediction
The aim/goal of this project is to build a supervised prediction that can be able to classify whether a patient is prone to Heart Disease or not using the variables collected as shown below
- `age: Age of the patient (in years)`
- `sex: Gender of the patient (0 = female, 1 = male).`
- `cp: Chest pain type (0 = typical angina, 1 = atypical angina, 2 = non-anginal pain, 3 = asymptomatic).`
- `trestbps: Resting blood pressure (in mm Hg).`
- `chol: Serum cholesterol level (in mg/dl).`
- `fbs: Fasting blood sugar > 120 mg/dl (0 = false, 1 = true).`
- `restecg: Resting electrocardiographic results (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy).`
- `thalach: Maximum heart rate achieved.`
- `exang: Exercise induced angina (0 = no, 1 = yes).`
- `oldpeak: ST depression induced by exercise relative to rest.`
- `slope: Slope of the peak exercise ST segment (0 = upsloping, 1 = flat, 2 = downsloping).`
- `ca: Number of major vessels colored by fluoroscopy (0-3).`
- `thal: Thalassemia (0 = normal, 1 = fixed defect, 2 = reversable defect).`
- `target: Presence of heart disease (0 = no, 1 = yes).`

# Data Preprocessing 
This data doesn't need a lot of cleaning like dealing with null values and duplicates, but there is need to evaluate the distribution of the dataset. Check the link for the dataset distribution [here](https://github.com/chrisaliyuda/Heart-Disease-Prediction/blob/main/Heart%20Disease.ipynb)
The biased variables was standardized using z-score normalization. 

# Model Building 
The model was trained on XGBoost classifier algorithm. K-fold split was used to train the model on different section of the dataset with their respective accuracy level. I used AUC and confusion matrix as the preferred evaluation metrics. 

# Check out the Python codes and more details about the project [here](https://github.com/chrisaliyuda/Heart-Disease-Prediction/blob/main/Heart%20Disease.ipynb)
