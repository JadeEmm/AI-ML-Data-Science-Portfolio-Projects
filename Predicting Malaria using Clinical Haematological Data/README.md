# Project Context

Malaria is a major global health issue with high prevalence. There are several challenges of malaria diagnosis, and accurately distinguishing ti from other diseases, including:

- Diagnosis by microscopy is subjective
- Rapid diagnostic tests (RDT) are susceptible to false negative results due to Pfhrp2 & Pfhrp3 gene deletion (in adapted parasites)

# Project Purpose
This project explores the opportunity to use machine learning on clinical data, as a powerful application of AI in healthcare for precision medicine to improve the accuracy of malaria diagnosis by classification of: uncomplicated malaria (UM), non-malarial-infection (nMI) and severe malaria (SM).

# The Dataset

The clinical dataset used was obtained from this study:
Morang’a, C.M., Amenga–Etego, L., Bah, S.Y. et al. Machine learning approaches classify clinical malaria outcomes based on haematological parameters. BMC Med 18, 375 (2020). https://doi.org/10.1186/s12916-020-01823-3

- Table S2 Hematological Raw Data (renamed for this project as malaria_clinical_data.csv)
- Clinical and raw haematological data from 2207 study participants
- There are 34 features for each sample including the (malaria) class label
- Class label distribution: nMI=978, SM=525, UM=703
- Machine Learning Approaches

This project tests a random forest model and a deep learning neural network model (with two hidden layers) to perform multi-classification.

# Project Workflow:

1. Data Gathering
2. Exploratory Data Analysis and Feature Engineering
3. Data Pre-processing & Split Data into Train and Test (or Train, Test & Validation) Sets
4. ML Model Development (Random Forest and Deep Learning Neural Network)
5. Train, Validate, Hypertune & Test Model 
6. Evaluate Model Performance
7. Visualise & Interpret Results

This Project is in two parts:
- The first part (Part 1) notebook builds and tests a random forest model
- The second notebook (Part 2) is an extension of the first, as it continues to build and test an additional neural network, using a more complex deep learning approach.

# Project Outcome
- The best random forest model achieved an accuracy of 82.7%
- The best neural network model achieved an accuracy of 84.0%
