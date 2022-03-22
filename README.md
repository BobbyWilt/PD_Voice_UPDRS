# PD Voice UPDRS
This project utilizes a dataset from Kaggle containing 1500 Parkinsonian voice recordings, and for each voice recording, a labelled symptom severity score (UPDRS) is provided.  A variety of regression models are fitted on the dataset to predict the UPDRS score.  Hyperameter tuning is applied to each model and model performance metrics are compared.

## Links
Parkinson's patient dataset containing movement scores and audio recordings.
Medium article link: https://medium.com/@bobbywilt1/predicting-parkinsonian-symptom-severity-from-voice-recordings-5efcfdc406a

Dataset obtained from: https://www.kaggle.com/mountainguest/parkinsons-telemonitoring?select=parkinsons_updrs.names

Original research paper: https://www.researchgate.net/publication/40026354_Accurate_Telemonitoring_of_Parkinson%27s_Disease_Progression_by_Noninvasive_Speech_Tests

## Motivation
Assessing Parkinson's symptom severity is typically completed during in-person clinical visits.  Due to the Covid pandemic and travel difficulties for patients, attending an in-person visit can be problematic for patients.  Remote-accessible diagnosistic methods would be preferrable for some Parkinson's patients and may even help patients and clinicians track a patient's symptoms more closely than in-person assessments.  A research study by Dr. Tsanas was conducted in 2009 to assess the accuracy of using voice recordings to predict a patient's disease symptom severity score (UPDRS).  The goal of this project is to implement modern machine learning models to the same dataset as the paper to see if the prediction accuracy could be further improved.

## How to Use
Download and run the notebook file "PD_Process" on your text editor of choice.  

## Author
Bobby Wilt - [Linkedin](https://www.linkedin.com/in/bobbywilt/)
