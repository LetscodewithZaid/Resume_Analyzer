📄 Resume Classification ML Project

This project is a machine learning–based application that classifies resumes into different job categories. It uses TF-IDF text features and a Logistic Regression model to identify the most suitable category for a given resume. The app provides two input options: uploading a PDF resume or pasting raw text. The Streamlit interface makes it simple, interactive, and user-friendly.

🚀 Features

• Classifies resumes into predefined job categories
• Upload PDF resumes (text extracted automatically)
• Option to paste or type resume text
• Cleans and preprocesses text using NLP techniques
• TF-IDF vectorization for text features
• Logistic Regression model trained for multi-class classification
• Shows Top-3 predicted categories with probability scores
• Interactive Streamlit user interface

🧠 Machine Learning Workflow

The workflow includes:
• Loading and preprocessing resume dataset
• Text cleaning and normalization using regex and NLP
• TF-IDF vector creation with unigrams and bigrams
• Training a Logistic Regression classifier
• Evaluating performance with accuracy and classification report
• Saving model using Joblib
• Integrating the model into a Streamlit app for inference

📂 Project Structure

• data — Contains dataset and sample PDFs
• models — Stores trained machine learning pipeline
• train_model script — Used for training and saving the model
• app script — Streamlit web application
• README — Project documentation

🛠️ Technologies Used

• Pandas
• NumPy
• Scikit-Learn
• Joblib
• Streamlit
• PyPDF2
• Matplotlib
• Seaborn
• NLTK

📘 How to Use

Run the Streamlit application

Upload a PDF or paste resume text

Click Predict

View predicted job category and top probabilities

The app automatically extracts text (for PDFs), cleans it, and runs it through the trained ML model.

📈 Model Performance

The model is evaluated using standard metrics such as accuracy and classification reports.
The final trained pipeline is saved and used directly in the Streamlit application.

🌟 Future Enhancements

• Add support for DOCX file extraction
• Build a skill extraction or keyword tagging module
• Use transformer models such as BERT for higher accuracy
• Add visual probability charts in the UI
• Deploy online using Streamlit.
