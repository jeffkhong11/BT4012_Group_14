# BT4012_Group_14
## Machine Learning Problem / Motivation

Phishing attacks are a critical cybersecurity challenge, posing significant risks to both individuals and organizations by exploiting deceptive emails to steal sensitive information. Traditional detection methods, such as blacklisting and signature-based approaches, often struggle to adapt to evolving threats, leading to high false-positive rates and insufficient accuracy. Studies like Advancing Phishing Email Detection: A Comparative Study of Deep Learning Models (Altwaijry et al., 2024) have demonstrated the effectiveness of deep learning models, such as CNNs with LSTM and GRU layers, in enhancing phishing email detection by capturing both local and sequential patterns in email content.

Despite growing awareness, phishing attacks continue to elude detection by users, highlighting the pressing need for robust automated systems. In line with Al-Subaiey et al. (2024), we aim to explore various machine learning techniques to improve phishing detection. Their work shows that algorithms like random forests and SVM are effective in classifying emails based on text and sender behavior. Building on this, we seek to determine if more sophisticated neural networks—specifically LSTM networks and a combination of LSTM with CNN—can improve detection accuracy and efficiency.

This research aims to address business challenges related to cybersecurity by developing a scalable, automated phishing detection system. By reducing false positives and improving detection rates, the system could save organizations valuable time, reduce financial losses from phishing attacks and enhance overall security.
## Dataset
Champa, Arifa Islam; Rabbi, Md Fazle (2024). 11 Phising Email Datasets. figshare. 
Dataset. https://doi.org/10.6084/m9.figshare.25437178.v1
## Description

### Folders
#### Models
1. Model_MultinomialNB.ipynb
   - Multinormial Naives Bayes model
2. Model_RandomForest.ipynb
   - Random Forest model
3. Model_SVC.ipynb
   - Support Vector Classification model (linear kernel)
4. Models_Neural_Networks.ipynb
   - Simple Neural Network
   - LSTM-Feedforward Neural Network Hybrid
   - LSTM-CNN Hybrid
#### Data Cleaning and Preprocessing
1. Cleaning.ipynb
   - Combining, cleaning, filtering out invalid data
2. EDA.ipynb
   - Exploratory Data Analysis on the dataset to determine which are the features that are important and can be used in our model for feature engineering
3. Feature_preprocessing.ipynb
   - Prepare all the features used on the combined_dataset and split the dataset into train and test, ensuring it is fully processed and ready for modeling.

     
