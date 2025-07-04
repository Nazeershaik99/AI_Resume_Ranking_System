# AI Resume Ranking System

An intelligent web application that ranks multiple resumes based on a given job description. The system uses advanced AI models to analyze resume content and match candidates to roles based on relevance, skills, and experience.

## 🚀 Features

- Upload multiple resumes (PDF or text)
- Paste or upload a job description
- Automatically rank candidates by relevance
- Provides a match percentage and brief reasoning
- Modern UI with real-time analysis
- Fully web-based — no local installation needed

## 🖼️ Screenshot

![screenshot](static/screenshot.png) <!-- optional image -->

## 📁 Project Structure


## 🧠 How It Works

1. User uploads 2 or more resumes (PDFs or .txt files).
2. User provides a job description (via paste or upload).
3. Backend processes each resume and calculates a similarity score.
4. All resumes are ranked and displayed in descending order of relevance.

## 📦 Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/yourusername/resume-ranker.git
   cd resume-ranker
pip install -r requirements.txt
GEMINI_API_KEY=your_api_key_here

python app.py


Visit http://127.0.0.1:5000 in your browser.

🌐 Deployment
This app can be deployed on:

Render – Easy and free for hobby use

Replit – Beginner friendly

Heroku – CLI-based deployment

Railway – Alternative to Heroku

Example Render Deployment
Push project to GitHub

Create a new Web Service on Render

Set:

Build Command: pip install -r requirements.txt

Start Command: python app.py

Add environment variable: GEMINI_API_KEY

Deploy and share your public link!

📥 Sample Resumes
You can test the ranking system using the provided samples:

resume_1.pdf - Software Engineer (3 YOE)

resume_2.pdf - Data Scientist (Fresher)

resume_3.pdf - Full Stack Developer

resume_4.pdf - ML Research Intern

Upload any or all with a job description to see ranked results.

🛡️ Security & Ethics
This tool is for educational and experimental purposes. Do not use it to make hiring decisions without human oversight. It is not a replacement for professional recruitment.

🙌 Acknowledgements
Flask Web Framework

Google’s Generative AI Models

PyMuPDF for PDF parsing

📧 Contact
Created by Shaik Nazeer
For questions, feel free to open an issue or contact me.

yaml
Copy
Edit

---

Let me know if you'd like me to:
- Add demo links or deploy it for you.
- Include a sample `.env.example` file.
- Add badges (Stars, Forks, License, etc.) for GitHub polish.
