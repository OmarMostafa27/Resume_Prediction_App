# Resume_Prediction_App
—-Resume Category Prediction App—-
-Overview of the project:
The "Resume Category Prediction App" is an automated tool designed to predict the professional category of a person based on their resume (e.g., Software Development, Marketing, Finance, Engineering, Healthcare).

-How the App Works
Input:
Users upload their resumes in PDF, Word, or Text format.
Processing:
Extract key details from the resume (e.g., skills, work experience, education).
Preprocess the text using Natural Language Processing (NLP) techniques such as tokenization and lemmatization.
Apply the K-Nearest Neighbors (KNN) algorithm to classify the resume into the appropriate category.
Output:
The app returns the predicted category (e.g., IT, Marketing, Finance).

-Technologies and Tools Used
Programming Languages:
Python
Machine Learning Algorithm:
K-Nearest Neighbors (KNN)
Libraries and Frameworks:
Data Handling: Pandas, NumPy
Natural Language Processing (NLP): Scikit-learn (for text vectorization and implementing the KNN algorithm)
Data Source:
Pre-collected dataset from Kaggle.
 
-Machine Learning Model
Algorithm Used:
K-Nearest Neighbors (KNN) is used to classify resumes based on the proximity of their feature vectors.
Model Training:
The model is trained on a labeled dataset with resumes and their categories.
The KNN algorithm calculates distances between the feature vectors of resumes to categorize them based on the nearest neighbors.
Evaluation Metrics:
The model's performance is evaluated using accuracy.
Accuracy: 98%

- Results and Evaluation
Sample Predictions:
Examples of resumes and their predicted categories:
Resume 1: "Software Engineer with 5 years of experience in Java" → Predicted Category: Software Development
Resume 2: "Marketing Manager with expertise in digital strategies" → Predicted Category: Marketing
Performance:
The model achieved an impressive accuracy of 98%, meaning it correctly predicted the category of the resume in 98% of the cases.
