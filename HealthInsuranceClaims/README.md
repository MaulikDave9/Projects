**Dataset: https://www.kaggle.com/datasets/leandrenash/enhanced-health-insurance-claims-dataset**

The dataset contains 4500 synthetic health insurance claims, meticulously generated to simulate real-world scenarios. It is designed to be highly usable and extensive, making it ideal for machine learning, data analysis, and predictive modeling tasks. The dataset includes a variety of features that are commonly found in health insurance claims, providing a rich and diverse set of data points for analysis.

# Claim Status Prediction: 

## Unfortunately, none of the listed features can reliably predict Claim Status. Even the stronger features - Diagnosis and Procedure code - effect is small.

## Important Features
#### DiagnosisCode(Code representing the diagnosis)
#### ProcedureCode (Code representing the procedure performed)
#### ProviderLocation (Location of the healthcare provider) - But this is more like a noise!


## Not important Features: 
#### ProviderSpecialty ((e.g., Cardiology, Orthopedics)
#### ClaimSubmissionMethod (Method used to submit the claim (Online, Paper, Phone)
#### PatientMaritalStatus (Marital status of the patient)

## There is not conclusive evidence about the strong explanatory features.  DiagnosisCode and ProcedureCode are worth investigating further. Though it seems like target is hard to predict from the available features. The current encodings are not capturing the signal well. 
