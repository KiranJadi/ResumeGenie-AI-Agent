# ResumeGenie-AI-Agent
An AI-powered career assistant built to help job seekers optimize resumes, match jobs, and prepare for interviews.
# 🎯 ResumeGenie AI Agent

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Project-Complete-brightgreen)
![Built With](https://img.shields.io/badge/Built%20With-Gemini%20API%20%2B%20Multi-Agent%20System-orange)

CareerBoost is a multi-agent AI system designed to empower job seekers with personalized tools for resume analysis, job matching, interview prep, and more.

---

## 🚀 Features

- 🧠 **Resume Analyzer**: Extracts insights and improvement tips
- 🔍 **Job Matching**: Aligns your skills with job descriptions
- 🎤 **Interview Prep**: Generates role-specific questions
- 💼 **LinkedIn Post Generator**: Creates professional content
- 🤖 **Conversational Agent**: Offers career guidance in natural language

---

## 🛠️ Tech Stack

- Python 3.10+
- Gemini API (Google Generative AI)
- Multi-Agent Orchestration
- Session Memory & Logging

---

## ⚙️ Setup

```bash
https://github.com/KiranJadi/ResumeGenie-AI-Agent.git
'''bash
cd careerboost-ai-agent
pip install -r requirements.txt
'''

Create a config/secrets.py file:
'''
GOOGLE_API_KEY = "your-api-key-here"
'''

🧪 Run the Demo
'''
python demo/careerboost_demo.py
'''

'''''''

📊 Architecture
Architecture Diagram

📸 Sample Output
See assets/screenshots/ for CLI snapshots of each tool in action.


---

## 🧭 2. Architecture Diagram


- `CoordinatorAgent` at the center
- Arrows to:
  - `CareerTools` (with 4 labeled tools)
  - `SessionManager` (for memory)
  - `Gemini API` (external LLM)
- Optional: Logging and API config modules



## 🖼️ 3. Sample Outputs for Screenshots


- Resume Analysis: Highlighted feedback
- Job Matching: Skill alignment score
- Interview Prep: 3–5 sample questions
- LinkedIn Post: Polished post text
- Conversational Agent: Q&A snippet



---

## 📽️ 4. Presentation Deck


```markdown
# Slide 1: CareerBoost AI Agent
**Kaggle Capstone Submission**  
Built by Kiran | November 2025

---

# Slide 2: Problem Statement
Job seekers struggle with:
- Resume optimization
- Role alignment
- Interview readiness
- Personal branding

---

# Slide 3: Solution Overview
CareerBoost is a multi-agent AI system that:
- Analyzes resumes
- Matches jobs
- Prepares interviews
- Generates LinkedIn content
- Offers conversational guidance

