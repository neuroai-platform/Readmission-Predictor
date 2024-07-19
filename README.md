# Patient Readmission Predictor

Final project for the Building AI course

## Summary

The Patient Readmission Predictor project uses AI to identify patients at high risk of readmission within 30 days after discharge. It aims to improve healthcare delivery and reduce unnecessary readmissions by providing predictive insights to healthcare providers.

## Background

This project addresses several critical issues in healthcare:
* High rates of hospital readmissions
* Inefficient use of healthcare resources
* Lack of predictive tools for patient risk after discharge

Hospital readmissions are a common and costly problem in healthcare systems worldwide. They strain resources, increase healthcare costs, and can negatively impact patient outcomes. My personal motivation is to leverage AI to improve patient care and support healthcare providers in making informed decisions.

## How is it used?

The system is used by physicians, nurses, and hospital administrators to:
* Identify high-risk patients
* Plan targeted follow-up care
* Allocate resources more efficiently

It is implemented in hospitals and healthcare facilities to optimize discharge planning and post-discharge care. The predictive model analyzes patient data at the time of discharge and provides a risk score, allowing healthcare providers to tailor interventions for high-risk patients.

## Data sources and AI methods

The data comes from:
* Historical patient records
* Demographic information
* Treatment details and discharge data

AI methods include:
* Logistic Regression: For its interpretability and simplicity
* Random Forest: To handle complex interactions between features
* Neural Networks: To capture non-linear relationships in the data

We use publicly available datasets like MIMIC-III for initial model development and validation.

## Challenges

The project does not solve:
* The underlying medical causes of readmissions
* Individual treatment plans

Ethical considerations include ensuring patient privacy, data security, and fair use of predictions across diverse patient populations. The model's accuracy is also dependent on the quality and comprehensiveness of the input data.

## What next?

Future developments could include:
* Integrating additional data sources (e.g., social determinants of health)
* Expanding to predict other patient outcomes (e.g., length of stay)
* Collaborating with healthcare institutions for real-world testing and feedback
* Developing a user-friendly interface for healthcare providers

## Acknowledgments

* Scikit-learn and Pandas libraries for implementation
* Academic papers on AI in healthcare for inspiration
* Open-source projects in the field of healthcare AI
* MIMIC-III database for providing a rich source of healthcare data
