# Resume_Checker
🚀 Resume Analyzer based on Job Description
This project is a Resume Analyzer Web App built with Gradio that evaluates how well a resume matches a given job description (JD) using OCR, NLP, and skill matching techniques.

🔍 Features
*Upload resumes in PDF or image format.

*Paste a job description to analyze relevance.

*Extracts skills from resumes using PyMuPDF, pytesseract, and NLTK.

*Matches resume content against predefined skill sets for common tech roles (e.g., Data Analyst, Web Developer, AI/ML Intern).

*Computes an ATS (Applicant Tracking System) score.

*Displays results in a pie chart with feedback and role suggestions.

📦 Libraries Used
gradio for the user interface

pytesseract and pdf2image for OCR

nltk for keyword extraction

matplotlib for visualization

PyMuPDF (fitz) for handling PDFs

✅ How to Use
Run the script in a Colab or local Python environment.

Upload your resume and paste the job description.

Get a visual ATS score and actionable feedback.

