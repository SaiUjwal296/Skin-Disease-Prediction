# 🌐 Skin Disease Prediction Web Application

Welcome to the **Skin Disease Prediction Web App** project! This project uses AWS cloud services to deploy a Machine Learning (ML) Flask application that predicts skin diseases from uploaded images. Hosted on an EC2 instance, this app offers secure and accessible predictions powered by AWS SageMaker.

## 🌟 Project Overview

### 🎯 Purpose
This web application is designed to predict skin diseases by analyzing images uploaded by users. It integrates a pre-trained ML model into a Flask app, providing remote access through a public DNS IP on AWS.

### 🔄 Workflow
1. **🤖 Model Creation**: Trained a skin disease prediction model in AWS SageMaker.
2. **💾 Model Deployment**: Downloaded the model and integrated it into a Flask app.
3. **🔐 IAM Configuration**: Set up IAM users and groups for secure S3 bucket access.
4. **📦 S3 Bucket Setup**: Created an S3 bucket to store images uploaded by users.
5. **🖥️ Local Testing**: Hosted the app locally to verify it works with the S3 bucket.
6. **☁️ EC2 Instance Creation**: Set up an EC2 instance to deploy the web app.
7. **⬆️ File Upload**: Used WinSCP to upload files to the EC2 instance.
8. **🔑 Accessing EC2**: Used PuTTY to access the Ubuntu instance command prompt.
9. **🐍 Environment Setup**: Installed Python and necessary packages on the EC2.
10. **🌐 Web Access**: The app is now available via the public DNS IP of the EC2 instance for remote predictions.

## 🚀 Steps for Deployment

### Prerequisites 🛠️
- AWS account with permissions for SageMaker, S3, EC2, and IAM.
- Familiarity with Python, Flask, and ML basics.
- Tools: WinSCP, PuTTY.

### Step-by-Step Procedure 📝

1. **🤖 Train Model in SageMaker**
   - Use AWS SageMaker to train and optimize a machine learning model for predicting skin diseases.

2. **💻 Download Model and Integrate into Flask App**
   - Download the trained model and integrate it into a local Flask application.

3. **🔐 Set Up IAM**
   - Configure IAM users and groups with S3 access permissions.

4. **📦 Create S3 Bucket**
   - Set up an S3 bucket to store images that users will upload for prediction.

5. **🖥️ Test Locally**
   - Run the Flask app locally and verify it connects to the S3 bucket for uploading images.

6. **☁️ Launch EC2 Instance**
   - Create an EC2 instance on AWS and note the public DNS IP.

7. **⬆️ Upload Files via WinSCP**
   - Transfer files from your local machine to the EC2 instance using WinSCP.

8. **🔑 Access EC2 with PuTTY**
   - Use PuTTY to open a command prompt on the EC2 instance (Ubuntu).

9. **🐍 Install Python and Packages**
   - Install Python and all required libraries on the EC2 instance.

10. **🌐 Launch Web Application**
    - Start the Flask application on the EC2 instance, making it accessible via the public DNS IP.

## 📖 Usage
Access the web application from any browser using the EC2 public DNS IP. Upload images to receive skin disease predictions powered by the SageMaker model. 💡

## 📺 Additional Resources
For a video walkthrough, check out this tutorial on [YouTube](https://youtu.be/xpk21G8abFw?si=UZhm0xBjIx9ultWk)! 🎥
