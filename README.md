# 📧 Cold Email Generator

A Streamlit web application that generates personalized cold emails for job applications based on job posting URLs. The app uses AI to extract job details and required skills from the posting, matches them with relevant tech stack resources, and crafts a tailored cold email for you to send.

---

## 🚀 Features
- **Paste a job posting URL** (e.g., LinkedIn, company career page)
- **Automatic extraction** of job description and required skills
- **Tech stack matching** with helpful resource links
- **AI-generated cold email** tailored to the job and your skills
- **Copy-ready email output** in markdown format

---

## 🏭 Industry Use Cases
- **Job Seekers:** Personalized outreach to recruiters/hiring managers
- **Recruitment Agencies:** Candidate marketing and bulk outreach
- **Sales/Business Development:** Adaptable for lead generation emails
- **HR/Talent Acquisition:** Passive candidate sourcing
- **EdTech:** Training on job application best practices

---

## 🛠️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hemasurya106/AI-cold-email-generator
   cd Cold_email_generator
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Usage

1. **Run the Streamlit app:**
   ```bash
   streamlit run main.py
   ```
2. **In your browser:**
   - Enter a job posting URL in the input box
   - Click "Generate cold mail"
   - Copy the generated email and use it for your outreach

---

## 📝 Example

**Input:**(This Link may not be working during your Usage,so please use a available job postings)
```
https://www.metacareers.com/jobs/1408007706638053/
```

**Output:**
```
Subject: Application for [Job Title] at [Company]

Dear [Hiring Manager],

I came across your job posting for [Job Title] and was excited to see the opportunity at [Company]. My experience with [Skill 1], [Skill 2], and [Skill 3] aligns well with your requirements. Here are some resources that showcase my expertise:
- [Tech Stack Link 1]
- [Tech Stack Link 2]

I would love to discuss how I can contribute to your team. Thank you for your consideration!

Best regards,
[Your Name]
```

---

## 📂 Project Structure
- `main.py` — Streamlit app entry point
- `chains.py` — LLM chain logic for job extraction and email generation
- `Tech_stack.py` — Tech stack resource matching
- `utils.py` — Utility functions (e.g., text cleaning)
- `resource/techstack_links.csv` — Tech stack resource links
- `vectorstore/` — Vector database files (if used)

---

## 🤖 Powered by
- [Streamlit](https://streamlit.io/)
- [LangChain](https://python.langchain.com/)

---

## 📬 License
MIT License 
