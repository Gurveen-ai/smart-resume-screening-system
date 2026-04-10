# 🚀 Smart Resume Screening System (ATS + BERT)

## 📌 Project Overview

This project is an AI-powered Resume Screening System that evaluates how well a candidate’s resume matches a job description using both traditional and advanced Natural Language Processing (NLP) techniques.

It simulates a real-world Applicant Tracking System (ATS) while also incorporating modern semantic understanding using BERT.

---

## ⚙️ Features

* 📄 PDF text extraction from resume and job description
* 🔍 TF-IDF based keyword similarity scoring (ATS-like)
* 🧠 BERT-based semantic similarity scoring
* 🛠 Technical skill extraction
* ⚠️ Missing skill identification (skill gap analysis)
* 📊 Comparative scoring (ATS vs Semantic AI)

---

## 🧠 ATS vs BERT (Key Insight)

| Feature               | ATS (TF-IDF)              | BERT                      |
| --------------------- | ------------------------- | ------------------------- |
| Matching Type         | Keyword-based             | Semantic (meaning-based)  |
| Context Understanding | ❌ No                      | ✅ Yes                     |
| Handles Synonyms      | ❌ No                      | ✅ Yes                     |
| Example               | "ML" ≠ "Machine Learning" | "ML" ≈ "Machine Learning" |

### 🔍 Example Output:

* **TF-IDF Match Score:** 34.86%
* **BERT Semantic Score:** 81.40%

👉 This shows how traditional systems may underestimate candidate suitability, while BERT captures real meaning.

---

## 🛠 Tech Stack

* Python
* PyPDF2
* NLTK
* Scikit-learn
* Sentence Transformers (BERT)
* Flask (for web integration)

---

## 📂 Project Structure

```
smart-resume-screening-system/
│
├── notebook/
│   └── Resume_Screening_System.ipynb
│
├── app/
│   ├── app.py
│   ├── ml_model.py
│   ├── chatbot.py
│   └── templates/
│       └── index.html
│
├── data/
│   ├── resume.pdf
│   └── job_description.pdf
│
├── requirements.txt
└── README.md
```

---

## ▶️ How to Run

### 1. Clone the repository

```
git clone https://github.com/your-username/smart-resume-screening-system.git
cd smart-resume-screening-system
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run the application

```
python app.py
```

### 4. Open in browser

```
http://127.0.0.1:5000
```

---

## 📈 Output

The system provides:

* Match Score (TF-IDF & BERT)
* Extracted Skills from Resume
* Required Skills from Job Description
* Missing Skills (Skill Gap Analysis)
* Recommendation (Strong / Moderate / Weak match)

---

## 🚀 Future Improvements

* 🌐 Full web UI with enhanced design
* 🤖 Chatbot for resume improvement suggestions
* 📊 Resume ranking system for multiple candidates
* 🔎 Named Entity Recognition (NER) for better skill extraction
* ☁️ Deployment on cloud platforms

---

## 🎯 Key Learning Outcomes

* Practical implementation of NLP pipelines
* Difference between keyword-based and semantic matching
* Use of transformer models (BERT) in real-world applications
* Building end-to-end ML + Web applications

---

## ⭐ Conclusion

This project demonstrates how combining traditional ATS techniques with modern AI models like BERT can significantly improve resume screening accuracy and better reflect real candidate potential.

---

## 🔗 Connect with Me

If you found this project interesting, feel free to connect and share feedback!
