# Cloud-Based-Fraud-Detection-System

contact ---> email : bankud2001@gmail.com


This project detects fraudulent transactions using a machine learning model deployed on AWS SageMaker. The model is trained on a dataset from Kaggle and is accessed via a web-based GUI to classify transactions as Fraud or Normal.

**Steps to Connect AWS to Local Machine**
  1.Dataset Upload – The fraud detection dataset was uploaded to an S3 bucket in AWS.

  2.Model Training – The dataset was processed, and a machine learning model was trained on AWS SageMaker.

  3.Model Deployment – The trained model was deployed as a SageMaker Endpoint for real-time predictions.

  4.API Integration – An AWS Lambda function was created to interact with the SageMaker endpoint, and an API Gateway was set up to expose the API.

  5.Local GUI Connection – The frontend GUI (HTML, CSS, JavaScript) sends transaction data to the AWS API Gateway, which triggers the Lambda function to get predictions from SageMaker. The results are displayed in the GUI.





It is a simple credit card fraud detection cloud based model that uses Kaggle's Credit Crad Fraud Detection datasaet : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud and predicts a trasaction to be either fraudulent or normal!



![image](https://github.com/user-attachments/assets/a6606f35-548e-4af9-8e15-85a56a67a5f8)

✅The above image shows this transaction is normal




![image](https://github.com/user-attachments/assets/c771334f-6f12-4df3-8475-d68fef497527)

❌The above image shows this transaction is fraudulent!



![image](https://github.com/user-attachments/assets/9de98004-ff28-4422-8731-e777b7b44aab)

⚠️The above image shows that the transaction doesnt exist!
