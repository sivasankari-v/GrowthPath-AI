# GrowthPath-AI - All-in-One Education to Employment Agentic AI
### GenAI Capstone Project - Module 6 | Final Year Project

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Streamlit](https://img.shields.io/badge/Framework-Streamlit-red)
![GenAI](https://img.shields.io/badge/AI-Agentic%20AI-green)
![Status](https://img.shields.io/badge/Status-Deployed-success)

> An Autonomous AI Agent for School Students, College Students, Job Seekers, Working Professionals, and Govt Scheme Seekers with Resume Analyzer & Job Matcher.

---

### 🚀 Live Demo
**Streamlit App:** [Your Live Link Here - After Deploy]
**GitHub Repo:** https://github.com/sivasankari-v/EV-Mastery-Assistant

### 📸 System Architecture

The project follows the complete Agentic AI Workflow:

**User Query -> Streamlit UI -> LLM API (Gemini) -> Agent Loop [Task -> Decide Action (RAG) -> Tool Calling -> Process Result] -> Memory & State -> Final Verified Response**

Core Layers:
1.  **RAG Knowledge Base:** Vector DB with `data/jobs.txt` & `data/scholarships.txt` using TF-IDF + Cosine Similarity
2.  **Tools Layer:** 5 Custom Tools (Resume Analyzer, Job Matcher, Salary Calculator, Roadmap Generator, Govt Scheme Finder)
3.  **Memory & State:** Session State for conversation history
4.  **Prompt Engineering Layer:** Role-based + Chain-of-Thought + Few-shot
5.  **Safety Layer:** Guardrails - "Verify with official sites"

### ✨ Key Features (As Per Module 6 Requirements)

| Module 6 Requirement | Implementation in GrowthPath-AI |
| :--- | :--- |
| **LLM API & Prompt Eng.** | Gemini API integration, Persona-based role prompts (School/College/Job/Pro) |
| **RAG Implementation** | RAG over local knowledge base `data/` folder, Semantic Search |
| **Tools & Tool Calling** | Resume Upload Tool, Job Upload Tool, Salary Tool, Roadmap Tool, Scholarship Tool |
| **Agentic Framework** | Autonomous Loop: Task -> Decide Action -> Tool Calling -> Process Result (Visible in UI) |
| **Memory & State Mgmt** | `st.session_state` for history, Task counter, Persona memory |
| **Safety & Limitations** | Sidebar safety info, Official site verification warning |

### 🎯 Who Can Use This? (Multi-Persona Support)

1.  **🏫 School Student (10th/12th):** Stream selection, College list (IIT/NIT), Entrance exams (JEE/CUET), Scholarships
2.  **🎓 College Student (B.Tech AI):** Internship (AICTE 14 credits), Project Ideas (RAG, Agents), Roadmap to AI Engineer
3.  **💼 Job Seeker:** Govt Jobs (ISRO, NIC, SSC CGL, UPSC), Private Jobs (AI Engineer 6-15 LPA), Salary Data
4.  **🚀 Working Professional:** Upskilling Roadmap (LLM+RAG+Agents), Salary Hike 30%, Switch to GenAI
5.  **📄 Resume Analyzer:** ATS Score 0-100, Keyword matching with Job Description
6.  **🏛️ Govt Schemes:** NSP, AICTE Pragati, PM Internship, MSME Verified Certificate, FAME II

### 📁 Folder Structure