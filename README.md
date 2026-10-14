# 🚀 GrowthPath-AI - All-in-One Education to Employment Agentic AI

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Framework-Streamlit-red?style=for-the-badge)
![Gemini](https://img.shields.io/badge/LLM-Gemini%20API-purple?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

> GenAI Capstone Project - Module 6 | Final Year Project
> An Autonomous Multi-Persona Career Agent with RAG, Tools, Memory & Safety Guardrails

### 🔗 Live Links
**Live App:** [Add Streamlit Link After Deploy]
**Repo:** https://github.com/sivasankari-v/GrowthPath-AI

### 🎬 Verified Output - Your Demo
**ATS Score: 88/100** | Module 6 Flow: 6/6 Tasks Completed | Persona: Resume Analyzer

### 🏗️ Architecture - Agentic Workflow
User Query -> Streamlit UI -> Gemini API -> Agent Loop [Task -> Decide Action -> RAG Search (data/) -> Tool Calling (5 Tools) -> Process Result] -> Memory Session State -> Safety Guardrails -> Final Verified Answer

**4 Layers:**
1. RAG Layer: TF-IDF + Cosine Similarity on data/jobs.txt & data/scholarships.txt
2. Tools Layer: Resume Analyzer, Job Matcher, Salary Tool, Roadmap Generator, Scheme Finder
3. Memory Layer: st.session_state for history & persona memory
4. Safety Layer: Verify with official sites

### ✅ Module 6 Compliance
| Requirement | Implementation | UI Proof |
| :--- | :--- | :--- |
| LLM API & Prompt Eng | Gemini + 6 Role Prompts + CoT | Agent Active For |
| RAG | Vector Search on data/ folder | RAG Vector Search Tick |
| Tools & Tool Calling | 5 Tools, ATS 88/100 | TOOLS 4 Tools Tick |
| Agentic Framework | Task->Decide->Tool->Process Loop | AGENT Task Loop Tick |
| Memory & State | Session State + Task Counter | MEMORY Tick |
| Safety | Guardrails + Disclaimer | SAFETY Tick |

### 👥 6 Personas
1. 🏫 School Student: Stream, IIT/NIT, JEE/CUET, NSP Scholarship
2. 🎓 College Student: AICTE Internship, RAG Projects, AI Engineer Roadmap
3. 💼 Job Seeker: ISRO/NIC Salary 80k, AI Jobs 6-15 LPA
4. 🚀 Working Professional: GenAI Upskilling, 30% Hike
5. 📄 Resume Analyzer: ATS Score 0-100, Job Match
6. 🏛️ Govt Schemes: NSP, Pragati, PM Internship, MSME

### 📁 Folder Structure