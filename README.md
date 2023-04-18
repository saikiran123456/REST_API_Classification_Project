# REST_API_Classification_Project
The main AIM of this Project is that I'm Showing How to Create a Serverless REST API for Machine Learning model and Deploy it on Cloud Premise GCP


# Create a ML Model which predicts whether a Client purchase a term deposit or not, based on Age and Salary features
Target ; Purchased Column
1 = Purchased ;   0 = Not Purchased

-> Build a Simple KNN Classifier with 100% Precision and 80% Recall
and 89% F1 Score, and AUC Score = 83.3%  for the TEST Set!
--------

PICKLE library - To Serialize a Python Object / To Conver Byte Stream
-> Pickled the Model and Scaler Files
	classifier.piclke   sc.pickle

-> First Learned, How to Use the Pickle Files in Local environment!
Deserialize and Store the Classifier & Scaler in their Local Object
Using "local_classifier" and "local_scaler", to Predict whether a Customer with AGE = 40 and Salary=20000 with Purchase or Not!




---------
-> Performed/Test this Serialize objects in another Environment like "On Premise/Cloud)  like Google COLAB

-- Get the classifier.pickle and scaler.pickle {link address} which is Stored in GitHub and load in COLAB for predictions
-------------



