# 🩺 Skin Disease Classification

## Intelligent Mobile Application for Skin Disease Classification Using Deep Learning

## 📌 Project Overview

This project presents an intelligent mobile application for skin disease classification using deep learning. The system allows users to upload or capture an image of an affected skin area. Then, the trained deep learning model analyzes the image and predicts the possible skin disease with a confidence score.

After generating the classification result, the application asks the user a set of related questions about symptoms, duration, habits, or possible exposure factors. Based on the user’s answers, the system provides a possible cause of the condition and recommends visiting a doctor for accurate diagnosis and proper treatment.

The main purpose of this project is not to replace dermatologists, but to support early awareness and help users take faster action.

---

## 🎯 Project Objectives

- Classify common skin diseases using deep learning.
- Allow users to upload or capture skin images through a mobile application.
- Provide a prediction result with a confidence score.
- Ask users related medical questions after classification.
- Suggest possible causes based on user answers.
- Store user scan history and prediction results.
- Support early awareness and encourage users to seek medical advice.

---

## 🧠 Main Idea

The system works in two main stages:

### 1. Image Classification

- The user uploads a skin image.
- The trained deep learning model processes the image.
- The model predicts the most likely skin disease.
- The system displays the prediction result with a confidence score.

### 2. Question-Based Cause Detection

- The user answers simple questions related to the predicted disease.
- The system analyzes the user’s answers.
- A possible cause is displayed to the user.
- The user is advised to visit a doctor for accurate diagnosis.

---

## 🏥 Skin Diseases Included

The project focuses on classifying common skin conditions, such as:

- Acne
- Eczema
- Psoriasis
- Fungal Infection
- Other skin disease classes depending on the dataset used

---

## 📂 Dataset

The dataset was collected from multiple public sources to improve class balance and increase the diversity of skin disease images.

Using only one dataset caused imbalance between disease classes, so multiple datasets were combined. Additional acne images were also used to enhance the overall dataset. Fungal infection images were also improved to support better classification performance.

### Dataset Sources

- DermNet Dataset - Shubham Goel
- Acne Dataset Image - Tiswan14
- Skin Diseases Image Dataset - Ismail Promus
- Skin Disease Dataset - PacificRM
- Fungal Infection Dataset Image

---

## 🖼️ Data Preprocessing

The collected images were prepared before training the model.

### Preprocessing Steps

- Collected images from multiple datasets.
- Organized images into disease-specific folders.
- Removed irrelevant or low-quality images.
- Improved fungal infection images.
- Resized images to match the model input size.
- Applied image transformations.
- Split the dataset into training and testing sets.
- Applied normalization to improve model training.

---

## 🤖 Deep Learning Model

The project uses a deep learning model for image classification. The model is trained to recognize different skin disease classes from image data.

### Model Workflow

1. Load the skin disease dataset.
2. Apply preprocessing and transformations.
3. Split the data into training and testing sets.
4. Train the deep learning model.
5. Evaluate the model using test images.
6. Save the trained model for future use.
7. Use the model prediction in the mobile application.

---

## 📊 Model Evaluation

The model performance is evaluated using several metrics.

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- Training loss
- Validation loss

These metrics help measure the model’s performance and identify which disease classes need further improvement.

---

## 📱 Mobile Application Features

The mobile application is designed to be simple and user-friendly.

### Main Features

- User registration and login.
- Upload or capture skin images.
- View predicted skin disease.
- View confidence score.
- Answer related medical questions.
- View possible cause of the condition.
- Save scan history.
- View previous prediction results.
- Manage user profile.

---

## 🧩 Question-Based Cause Detection

After the disease is predicted, the system asks the user related questions. These questions help identify a possible cause based on the user’s answers.

Example:

```text
Predicted Disease: Acne

Question: Do you often use oily skin products?
User Answer: Yes

Possible Cause: The condition may be related to oily products blocking the pores.
