# Resume Classifier
## Overview
This project classifies resumes based on their content. It uses natural language processing (NLP) and machine learning techniques to analyze resumes and predict their respective job categories. An additional feature of the project is to recommend relevant job roles to job seekers, aligning their skills and experience with suitable job opportunities.
________________________________________
## Aim
The goal of this project is twofold:
1.	Classify resumes into predefined categories based on their content.
2.	Provide job recommendations to job seekers based on the classification results.
________________________________________
## Methodology
### Dataset
The project utilizes a dataset containing resumes labeled with their respective job categories. Each resume is processed and analyzed for relevant features to enable accurate classification.
### Approach
1.	Preprocessing:
o	Tokenized and padded the text data using the DistilBertTokenizer.
o	Encoded the labels using LabelEncoder.
2.	Modeling:
o	Leveraged a pre-trained DistilBERT model for sequence classification.
o	Fine-tuned the model with task-specific resume data, adjusting the output layer for multi-class classification.
3.	Training:
o	Split the data into training and validation sets.
o	Used the AdamW optimizer and cross-entropy loss for model training.
4.	Evaluation:
o	Measured validation loss and classification accuracy.
o	Achieved high accuracy in categorizing resumes.
________________________________________
## Results
•	Accuracy: Achieved a classification accuracy of 99.48% on the validation dataset.
•	Validation Loss: The model maintained a low validation loss of 0.067.
________________________________________
## Applications
1.	Resume Classification:
o	Automates the process of categorizing resumes into predefined job roles, saving recruiters significant time and effort.
2.	Job Recommendation:
o	Helps job seekers by recommending relevant job roles based on the predicted category, enhancing their job search experience.

