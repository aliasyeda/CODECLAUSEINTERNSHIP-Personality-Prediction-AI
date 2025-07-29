# CODECLAUSEINTERNSHIP-Personality-Prediction-AI

## 🧠 Personality Prediction System via CV Analysis

This project is part of the CodeClause Internship (Golden Level) and aims to automatically predict a person's personality based on the content of their CV (Resume). It applies Natural Language Processing (NLP) techniques and a simple machine learning model to analyze textual content from resumes and determine personality traits.

## 🔍 Objective

The primary goal of this project is to extract text from CVs and analyze it to predict key personality traits. This system could help in automating initial HR screening or profiling applicants based on language and content style.

## 💻 Technologies Used

Python

Jupyter Notebook

NLP Libraries: NLTK, SpaCy

Machine Learning: Scikit-learn

Text Extraction: Tesseract OCR

PDF/Image to Text Conversion: Pytesseract, OpenCV, PIL

                      
## 📌 How It Works

Input CV (image or text file):

Load a CV (image or PDF converted to image) as input.

Use Tesseract OCR to extract the text from the CV.

Text Preprocessing:

Lowercasing, stopword removal, tokenization.

Extract relevant features using NLP.

## Intent Matching (Personality Analysis):

The intent.json file contains a dictionary of personality-related keyword groups.

The system matches extracted words from the CV to predefined traits (like Leadership, Creativity, Teamwork, etc.).

## Prediction Output:

Displays dominant personality traits based on the content.

Example output:

Detected Personality Traits:
- Leadership
- Creativity
- Communication

## 📁 intent.jso 

– What is it?

The intent.json file contains predefined sets of keywords grouped by personality traits.

Example:

{
  "leadership": ["leader", "organized", "managed"],
  "creativity": ["innovative", "creative", "designed"],
  "teamwork": ["collaborated", "team", "coordinated"]
}
Your resume is matched against this file to determine which traits you exhibit the most.

## ✅ Output 

📄 CV image shown ( cv_image.jpg)

✅ Text extracted from the image

✅ Matching traits displayed on-screen

🎯 Final traits listed in output


## 👨‍💻 Author

Developed by
**Syeda Alia Samia**  
GitHub:[Syeda Alia Samia](https://github.com/your-github-username)



