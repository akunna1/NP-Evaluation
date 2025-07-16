# 🧠 NP-Evaluation — Neptune Technologies

This project is part of the **Neptune Technologies** job application platform developed by [Akunna Tech Studio](https://akunnatechstudio.com/mining). It includes both the Applicant Tracking System (ATS+) evaluation logic and a file conversion utility to prep documents for text-based analysis.

## 📌 Project Purpose

To evaluate and extract insights from applicant resumes and cover letters by:

* Converting `.doc`, `.docx`, and `.pdf` formats to `.txt`
* Analyzing the cleaned text using Python for keyword scoring, match rate, and ATS readiness

## 🛠️ Built With

* Python
* NLTK
* OS module
* RE (Regex)

## 🗂️ Project Structure

```
├── Evaluation_code.ipynb           # Main evaluation logic (keyword scoring, ATS match, etc.)
├── Evaluation_file_conversion.ipynb # Converts uploaded resumes (.docx/.pdf) to plain .txt
```

## ⚙️ How It Works

1. **File Conversion:**
   Run `Evaluation_file_conversion.ipynb` to batch convert resumes into clean `.txt` files suitable for parsing and analysis.

2. **ATS+ Evaluation:**
   Run `Evaluation_code.ipynb` to:

   * Extract key sections from the resume (Skills, Experience, etc.)
   * Score relevance to job descriptions
   * Identify gaps and strengths for candidate optimization

## 🔍 Keywords & Analysis

* Text mining
* Resume parsing
* Job-to-resume matching
* ATS (Applicant Tracking System) simulation

## 📝 Notes

* This is a standalone module and can be integrated into broader HR or ATS pipelines.
* For demo/testing, use sample resumes stored locally in the project folder.
