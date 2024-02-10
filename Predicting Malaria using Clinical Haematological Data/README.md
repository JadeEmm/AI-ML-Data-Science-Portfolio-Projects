# Project Context
Malaria is a major global health issue with high prevalence. There are several challenges of malaria diagnosis, and accurately distinguishing ti from other diseases, including:

- Diagnosis by microscopy is subjective
- Rapid diagnostic tests (RDT) are susceptible to false negative results due to Pfhrp2 & Pfhrp3 gene deletion (in adapted parasites)

# Project Purpose
This project explores the opportunity to use machine learning on clinical data, as a powerful application of AI in healthcare for precision medicine to improve the accuracy of malaria diagnosis by classification of: uncomplicated malaria (UM), non-malarial-infection (nMI) and severe malaria (SM).

# The dataset
- Table S2 Hematological Raw Data (renamed for this project as malaria_clinical_data.csv)
- Clinical and raw haematological data from 2207 study participants
- There are 34 features for each sample including the (malaria) class label
- Class label distribution: nMI=978, SM=525, UM=703
- Machine Learning Approaches

This project tests a random forest model and a deep learning neural network model to perform multi-classification.

# Project Workflow:

1. Data Gathering
2. Exploratory Data Analysis and Feature Engineering
3. Data Pre-processing & Split Data into Train and Test Sets
4. ML Model Development and Training (Random Forest and Deep Learning Neural Network)
5. Test Train Model
6. Evaluate Model
7. Visualise & Interpret Results
