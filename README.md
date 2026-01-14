🎤 Human Voice Classification and Clustering
📌 Project Overview

This project focuses on classifying and clustering human voice profiles using pre-extracted numerical audio features.
It demonstrates the application of machine learning techniques for speech processing and provides an interactive Streamlit web interface where users can manually input feature values and obtain predictions in real time.

🎯 Objective

Classify human voices into gender categories (Male/Female)

Group similar voice samples using unsupervised clustering

Deploy an easy-to-use Streamlit application for real-time interaction

🧠 Domain

Speech Processing

Machine Learning

🛠 Skills & Technologies Used

Python

Machine Learning

Data Preprocessing & Feature Engineering

Classification Algorithms

Clustering Algorithms

Model Evaluation

Streamlit

📂 Dataset Description

The dataset contains pre-extracted numerical audio features derived from human voice recordings.

🔑 Sample Features

Spectral Features:

Mean Spectral Centroid

Spectral Bandwidth

Spectral Flatness

Temporal & Energy Features:

Zero Crossing Rate

RMS Energy

Pitch Features:

Mean Pitch

Pitch Standard Deviation

MFCC Features:

MFCC 1 Mean

MFCC 2 Mean

MFCC 3 Mean

🎯 Target Variable

label

1 → Male

0 → Female

🔍 Approach
1️⃣ Data Preparation

Used extracted numerical voice features

Selected top features for demonstration

2️⃣ Data Preprocessing

Handling missing values

Feature normalization

3️⃣ Exploratory Data Analysis (EDA)

Feature distribution analysis

Understanding relationships between pitch, spectral, and energy features

4️⃣ Model Development

Clustering: K-Means / DBSCAN (conceptual)

Classification: Random Forest / SVM (conceptual)

For academic submission, simulated prediction logic is used in Streamlit to demonstrate the complete pipeline.
Trained models can be easily integrated using .pkl files.

5️⃣ Application Development

Built an interactive Streamlit web application

Users manually enter feature values

Outputs:

Cluster assignment

Gender classification with confidence score
