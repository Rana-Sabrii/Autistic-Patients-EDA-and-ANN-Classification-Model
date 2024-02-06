# Autistic-Patients-EDA-and-ANN-Classification-Model

# Overview

- An Artificial Neural Network project dedicated to Classify Autistic Patients from Non Autistic Patients (Predict the likelihood of a person having autism using survey and demographic variables.)

- The project highlightsthe significance of Data Cleaning (Preprocessing) ,Data Exploration (Descriptive Statistics) , and employs professional visualizations to enhance data understanding.

# Kaggle Notebook

[Kaggle Notebook](https://www.kaggle.com/code/ranasabrii/autistic-patients-classification-using-ann)

# Features of dataset

|Feature | Description
|------|------------
|**index** | The participant’s **ID number**
|**AX_Score**|Score based on the Autism Spectrum Quotient (AQ) 10 item screening tool [AQ-10](https://docs.autismresearchcentre.com/tests/AQ10.pdf)
|**age**|Age of participant
|**gender**|**'m'** for Male and **'f'** for Female
|**ethnicity**|Ethnicities in text form **['White-European', 'Latino', '?', 'Others', 'Black', 'Asian','Middle Eastern ', 'Pasifika', 'South Asian', 'Hispanic','Turkish', 'others']**
|**jaundice**|**'no' and 'yes'** for Whether or not the participant was born with jaundice?
|**autism**|**'no' and 'yes'** for Whether or not anyone in the immediate family has been diagnosed with autism?
|**country_of_res**|Countries in text format
|**used_app_before**|**'no' and 'yes'** for Whether the participant has used a screening app
|**result**|Score from the AQ-10 screening tool
|**age_desc**|Age as categorical **['18 and more']**
|**relation**|Relation of person who completed the test **['Self', 'Parent', '?', 'Health care professional', 'Relative','Others']**
|**Class/ASD**|Participant classification **['NO', 'YES']**


# Dataset

- Source : [Autism Screening on Adults](https://www.kaggle.com/datasets/andrewmvd/autism-screening-on-adults)
- Preprocessing
- - Handling Missing Values
  - Handling Outliers
  - Handling Categorical Features
 
# Model Architecture

- ANN sequential model with input layers of 10 neurons and activation function = **'relu'** ,one hidden layer of 8 neurons and activation function = **'relu'** and output layer of 1 neuron with activation function = **'sigmoid'**
- Optimizer used 'Adam'
- Loss Function used **'binary_crossentropy'**

# Evaluation

- Metrics used to evaluate the model performance **'accuracy'**
