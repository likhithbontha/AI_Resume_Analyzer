# 📄 AI Resume Analyzer  

AI-powered web application that helps candidates **analyze their resumes** and receive **personalized insights & course recommendations**. Built with **Streamlit, MySQL, Google Gemini API, and Python**, this project provides an end-to-end pipeline for resume parsing, skill gap identification, and upskilling guidance.  

---

## 🚀 Features  

- **Resume Upload** → Upload resumes in PDF format for instant AI-powered parsing.  
- **AI Resume Analysis** → Extracts name, email, phone, skills, education, and work experience using **Google Gemini 2.0 Flash**.  
- **Field Prediction** → Predicts the most suitable career field (e.g., *Software Development, Data Science, AI/ML*).  
- **Skill Gap Analysis** → Highlights missing or improvable skills.  
- **Course Recommendations** → Suggests curated courses from platforms like **Coursera, Udemy, edX, LinkedIn Learning**.  
- **User Data Management** → Stores structured resume data securely in **MySQL**.  
- **Geolocation Capture** → Collects location & device metadata during submission.  
- **Feedback System** → Allows users to rate and comment on their experience.  
- **Admin Dashboard** → Secure admin login to view collected resumes, skills, and feedback.  
- **Skill Search Tool** → Admin can search resume profiles by skills to find matching candidates.  

---

## 🛠️ Tech Stack  

- **Frontend/UI**: [Streamlit](https://streamlit.io/)  
- **Backend**: Python  
- **Database**: MySQL (pymysql connector)  
- **AI Model**: Google Gemini 2.0 Flash via `google-generativeai`  
- **PDF Parsing**: [PyMuPDF (fitz)](https://pymupdf.readthedocs.io/)  
- **Utilities**: geocoder, geopy, phonenumbers, pycountry, pandas, pickle  

---
