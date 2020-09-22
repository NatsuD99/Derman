# Skin-Cancer-Detection-App

We aim to provide a complete user experience with integrated medication and doctor-appointment APIs as well as awareness surrounding Skin cancer and allergies. Using 3 state-of-the-art Deep Learning Classification models we try to predict with considerably high accuracy if you are suffering from Melanoma (which is the most fatal type of skin cancer) or any other type of cancer (basal cell carcinoma, and 7 other types), or if you are suffering from an allergy (using a separate model). With features like, embedded videos, remedies, medicine browsing, Find a Doctor we hope to be a one-stop solution for the user's dermatological problems.

# Models:

We have used 3 models for 3-layered multipurpose testing, namely, for detecting Melanoma( the most fatal type of Skin Cancer), 
the given types of Skin Cancers:

1.

2.

3.

And also the given types of allergies and skin diseases:

1.

2.

3.

# Application/Deployment:

To deploy our models we have seamlessly integrated Tensorflow models using TFLite framework into a Flutter Android App, where we have used multiple APIs to create an engaging user-experience and provided with testing/educative as well as preventive and medical aid features. The features of our Application is listed as follows:

# Files in Repository:

1. Model Training, Data Preprocessing and Conversion to TFLite is shown in Skin-Cancer-Detection-App/Models/.. as Jupyter Notebooks. Data is taken from Kaggle for Melanoma Model and Cancer Model. For Allergy Model a custom scraper is implemented for obtaining data, which is shown in,
Skin-Cancer-Detection-App/Models/allergy-model/..

2. Models-TFLite contain the .tflite models of the codes shown in in /Models/..

3. FLutter app design and model is contained in Skin-Cancer-Detection-App/App/.. 

4. Install app and Requirements

# Install Instructions:

How to run our App? Follow the instructions given here: 
