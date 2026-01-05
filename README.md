ATS Pro – AI-Powered Resume & Job Description Analyzer

ATS Pro is a full-stack web application that analyzes the compatibility between a candidate’s resume and a job description using Generative AI. The system simulates an Applicant Tracking System (ATS) by extracting key skills, experience, and qualifications from a resume PDF and comparing them against job requirements to generate an intelligent match report.

The application is built using Flask (Python) for backend processing and Tailwind CSS for a clean, responsive frontend. It leverages Google Gemini LLM to perform semantic analysis and provide actionable insights for improving resume alignment.
Key Features

 PDF Resume Parsing using PyPDF2

 AI-Based Resume & Job Description Analysis

 ATS Match Score Generation (0–100%)

 Identification of matching and missing skills

 Personalized improvement suggestions

 Integrated Frontend & Backend using Flask templates

 Modern UI with Tailwind CSS
 Tech Stack

Backend: Python, Flask

AI Model: Google Gemini (gemini-2.5-flash)

Frontend: HTML, Tailwind CSS
How It Works

User uploads a resume in PDF format

User enters a job description

Flask extracts text from the resume

Gemini AI parses:

Resume details

Job requirements

The system compares both and generates:

Match percentage

Skill gaps

Strengths

Resume improvement recommendations

Results are displayed on the same web page
Use Cases

Students optimizing resumes for placements

Job seekers improving ATS compatibility

Recruiters performing quick resume screening

Learning project for AI + Web Development integration
Future Enhancements

Embedding-based semantic similarity scoring

Resume keyword highlighting

Export analysis report as PDF

React frontend with Flask REST API

OCR support for scanned resumes
PDF Processing: PyPDF2

Architecture: Monolithic Flask App (Frontend + Backend)
