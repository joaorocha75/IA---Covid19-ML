# IA---Covid19-ML

Objectives and brief description
The aim of this project is to demonstrate the skills in the field of Data Science and Machine
Learning acquired throughout the course.
The project consists of the complete analysis of a provided dataset, involving several exploration techniques, pre-processing, application of machine learning algorithms, evaluation/optimization of results and their discussion.
The assessment will include the presentation of the analysis, implemented techniques,
and results obtained. The delivery of the notebook and of the presentation are mandatory, being part of the assessment.
Problem Contextualization:
The project focuses on the use of a dataset on Covid19 cases (available via Moodle), including information about patients’ symptoms and medical history.
The dataset presents technical challenges and requires critical thinking in exploring the
meaning and feasibility of the values presented in the various features.
Each group should build a machine learning model that, given a Covid-19 patient's current
symptom, status, and medical history, will predict whether the patient died or not.
The selection of tested models is left to the discretion of each group, with the diversity of
techniques and algorithms implemented being valued.
Main challenges to address:
1. Exploration of the dataset (from a technical and interpretive point of view);
2. Pre-processing due to the challenges inherent to the data;
3. Classification -predict whether the patient died or not;
4. Analysis of the impact of each feature in the prediction;
5. Strategies for optimizing and evaluating results (from a technical and interpretive
point of view).



This dataset contains anonymized patient-related information including health pre-conditions. 
It contains 21 features and 1,048,575 unique patients. In the Boolean features, 1 means "yes" and 2 means "no".

    usmer: Indicates whether the patient treated medical units of the first, second or third level.
    medical unit: type of institution of the National Health System that provided the care.
    sex: gender of the patient.
    patient type: wether the patient returned home or headed for hospitalization.
    date died: If the patient died indicate the date of death, and 9999-99-99 otherwise.
    intubed: whether the patient was connected to the ventilator.
    pneumonia: whether the patient already have air sacs inflammation or not.
    age: of the patient.
    pregnant: whether the patient is pregnant or not.
    diabetes: whether the patient has diabetes or not.
    copd: Indicates whether the patient has Chronic obstructive pulmonary disease or not.
    asthma: whether the patient has asthma or not.
    inmsupr: whether the patient is immunosuppressed or not.
    hypertension: whether the patient has hypertension or not.
    other disease: whether the patient has other disease or not.
    cardiovascular: whether the patient has heart or blood vessels related disease.
    obesity: whether the patient is obese or not.
    renal chronic: whether the patient has chronic renal disease or not.
    tobacco: whether the patient is a tobacco user.
    classification: covid test findings. Values 1-3 mean that the patient was diagnosed with covid in different degrees. 4 or higher means that the patient is not a carrier of covid or that the test is inconclusive.
    icu: Indicates whether the patient had been admitted to an Intensive Care Unit.
