# AI-Powered Resume Analyzer  

**AI-Powered Resume Analyzer**, a cutting-edge application designed to mimic the expertise of an HR professional! This tool leverages the power of **Google Generative AI** to analyze resumes, evaluate job compatibility, and offer actionable insights for career enhancement.  

---

##  **Project Overview**  

The **AI-Powered Resume Analyzer** serves as a virtual HR assistant, providing:  
- Detailed resume evaluation, including strengths and weaknesses.  
- Suggestions for skill improvement and recommended courses.  
- Job-specific resume analysis to measure compatibility and alignment with job descriptions.  

Whether you’re a job seeker or a recruiter, this tool simplifies resume assessment and improvement.  

---

##  **Features**  

###  **General Resume Analysis**  
- Summarizes the resume in one line.  
- Highlights existing skill sets.  
- Identifies skill gaps and suggests improvements.  
- Recommends popular courses to enhance the resume.  
- Provides a thorough evaluation of strengths and weaknesses.  

###  **Resume Matching with Job Description**  
- Analyzes resume compatibility with a specific job description.  
- Provides a match score in percentage.  
- Highlights missing skills and areas needing improvement.  
- Suggests whether the resume is ready for the job or requires further enhancements.  

---

##  **Tech Stack**  

| **Component**       | **Technology**                  |  
|----------------------|----------------------------------|  
| **Frontend**         | [Streamlit](https://streamlit.io/) |  
| **Backend**          | Python                          |  
| **AI Model**         | [Google Generative AI (Gemini)](https://developers.generativeai.google/) |  
| **PDF Parsing**      | `pdfplumber`                    |  
| **OCR Fallback**     | `pytesseract`                   |  
| **Environment Config** | `.env` for API key security    |  

---

##  **How It Works**

1. **Resume Parsing**  
   - Extracts text from PDF files using `pdfplumber` or OCR as a fallback.

2. **AI Analysis**  
   - Utilizes Google Generative AI to summarize and analyze resume content.  
   - Matches skills with job descriptions for compatibility scoring.

3. **Insightful Feedback**  
   - Provides actionable suggestions for skill enhancement, including course recommendations.  
   - Highlights strengths and weaknesses to refine resumes for better opportunities.

---

![image](https://github.com/user-attachments/assets/418e54ef-82d0-474b-a6bc-9a30d72f27f5)

