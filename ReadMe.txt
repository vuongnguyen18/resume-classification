# Resume Classification App

This project is a web application that 
classifies resumes into different job categories using a 
pre-trained Support Vector Classifier (SVC) model and a TF-IDF vectorizer. 
The application is built using Streamlit, 
a Python library for creating interactive web applications.

## Installation

To run this application, you need to install the required Python packages. You can install them using pip:

```sh
pip install streamlit
pip install scikit-learn
pip install python-docx
pip install PyPDF2

You can run "streamlit run app.py" to start the program. Open your web browser and go to http://localhost:8501 to access the application.

Application Overview
The application allows users to upload a resume in PDF, DOCX, or TXT format. The uploaded resume is processed, and the text is extracted. The extracted text is then cleaned and vectorized using a pre-trained TF-IDF vectorizer. The vectorized text is passed to a pre-trained SVC model to predict the job category of the resume.

--> Main Components
- File Upload: Users can upload a resume file in PDF, DOCX, or TXT format.
- Text Extraction: The application extracts text from the uploaded resume file.
- Text Cleaning: The extracted text is cleaned to remove URLs, special characters, and other unwanted elements.
- Text Vectorization: The cleaned text is vectorized using a pre-trained TF-IDF vectorizer.
- Prediction: The vectorized text is passed to a pre-trained SVC model to predict the job category.
- Display Results: The predicted job category is displayed to the user.

---> Make sure you unzip the encod zip before you start the program
