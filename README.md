# Hi, I'm Solomon Khess 👋

### AI Engineer | Agentic AI • RAG • LLM Systems • Machine Learning

🎓 **B.Tech–M.Tech, IIT Bhubaneswar '26**

I build **AI systems with a focus on agentic workflows, retrieval, evaluation, and reliability**.

My work spans:

- 🤖 Agentic AI & Multi-Agent Systems
- 🔎 RAG & Semantic Retrieval
- 🧠 LLM Applications & Evaluation
- 👁️ Computer Vision & Document AI
- 📊 Machine Learning & Time-Series Intelligence
- ⚙️ MLOps, APIs & AI Infrastructure

I enjoy taking systems from **idea → architecture → implementation → evaluation → deployment**, with a focus on building AI that is useful, reliable, and maintainable beyond a demo.

---

## 🔗 Connect

- 💼 [LinkedIn](https://www.linkedin.com/in/solomonkhess/)
- 📄 [Resume](https://github.com/solomonkhess02/Resume)
- 💻 [GitHub](https://github.com/solomonkhess02)

---

# ⭐ Featured Projects

## 🧠 Lenny Agentic RAG Platform

**RAG • Agentic AI • LLM Evaluation • AI Security**

A grounded AI growth assistant built over a curated corpus of Lenny's Podcast episodes.

### What I built

- Built the application using **FastAPI, PostgreSQL + pgvector, React/Vite, Ollama, and DeepSeek**
- Implemented **deterministic retrieval** with calibrated similarity thresholds
- Added **evidence rehydration, quote validation, citation verification, and abstention**
- Automatically retracts unsupported LLM outputs instead of presenting fabricated answers
- Built **provider-level routing and provenance tracking**
- Added streamed generation and structured error handling
- Built **332 automated tests** covering retrieval, grounding, workflows, and failure cases
- Identified and fixed real production-path failures involving:
  - concurrent persistence races
  - Docker runtime drift
  - prompt leakage
  - oversized subprocess events
- Evaluated different AI coding-agent approaches and selected the one that fit the project's context and latency constraints

🔗 **Repository:**  
https://github.com/solomonkhess02/lenny-growth-assistant

🎥 **Project walkthrough:**  
https://youtu.be/lJx8wnlkFqs

---

## 🤖 Autonomous Data Science Pipeline

**Agentic AI • LangGraph • LLMs • FastAPI**

A multi-agent system that automates parts of the data science workflow.

### What I built

- Designed a **LangGraph-based multi-agent architecture**
- Automated:
  - Exploratory Data Analysis
  - Data cleaning
  - Feature analysis
  - Predictive modelling
  - Model evaluation
- Implemented **shared structured state** using TypedDict
- Built ReAct-style agents capable of:
  - code generation
  - execution
  - error diagnosis
  - self-correction
  - retry
- Added secure Python execution through a sandboxed workflow
- Built a **FastAPI backend**
- Added support for **Gemini, OpenAI, and Ollama**
- Containerized the system and deployed it using **AWS EC2/ECS**

🔗 **Repository:**  
https://github.com/solomonkhess02/auto-analytics-agent

---

## 📄 MedOCR Intelligence Platform

**Document AI • Computer Vision • OCR • RAG • MLOps**

A multi-model document intelligence system for extracting structured information from complex documents.

### What I built

- Designed a document processing pipeline using:
  - **TrOCR**
  - **Donut**
  - **LayoutLMv3**
  - **OpenCV**
- Worked with:
  - handwritten prescriptions
  - invoices
  - lab reports
  - OMR documents
- Implemented **confidence-aware model routing**
- Fine-tuned TrOCR on a custom handwritten prescription dataset
- Evaluated OCR performance using **CER/WER**
- Added semantic retrieval using **PostgreSQL + pgvector**
- Built backend services using **FastAPI**
- Used **Celery + Redis** for asynchronous processing
- Added **MLflow** for experiment tracking and model versioning
- Containerized the system using **Docker**
- Integrated monitoring and drift-analysis workflows

🔗 **Repository:**  
https://github.com/solomonkhess02/MedOCR-Intelligence-Platform

🎥 **Project walkthrough:**  
https://youtu.be/lq-w2N-NXOA

---

## 👁️ On-line Particle Size Determination Device

**Computer Vision • Industrial AI • Process Automation**

A real-time computer vision system for automated particle-size analysis on conveyor-belt imagery.

### What I built

- Developed a real-time image-processing pipeline for industrial particle detection
- Implemented:
  - **Watershed Segmentation**
  - **Otsu Thresholding**
  - **regionprops**
- Designed the system to operate without specialized GPU hardware
- Developed a **PyQt5 desktop application**
- Added:
  - live image capture
  - calibration
  - batch processing
  - automated Excel reporting
- Validated at **TRL-4** with Tata Steel Long Products Ltd.

🔗 **Repository:**  
https://github.com/solomonkhess02/On-line-Particle-Size-Determination-Device-TRL-5-

---

# 🧪 Machine Learning & Industrial AI

## NTPC — ML Research Intern

Worked on machine learning and nonlinear time-series analysis for thermal power plant process prediction.

### Work included

- **LSTM and XGBoost** forecasting
- High-frequency industrial sensor data
- Feature engineering and temporal features
- mRMR-based feature selection
- t-statistics and AIC-based selection
- Hurst exponent analysis
- Chaos and nonlinear dynamics
- Recurrence Quantification Analysis (RQA)

**Focus:** Superheater Steam Temperature Prediction

---

## Shri Mahavir Ferro Alloys — ML Research Intern

Worked on predictive modelling for industrial process monitoring.

### Work included

- **XGBoost-based forecasting**
- Rotary kiln accretion prediction
- Thermal profile analysis
- Feature engineering
- Time-series analysis
- Early detection of process-condition changes

---

# 🔬 Research

### Uncovering Chaos and Complexity of Reactions in BOF and AOD for Improved Process Control

📍 Presented at **STIS-V 2025 — IISc Bengaluru**

Research focused on understanding nonlinear and chaotic behaviour in industrial metallurgical processes.

### Ongoing Research

**Steam Generation Process: Nonlinear Dynamics and Statistical Signal Analysis**

Focus areas:

- Time-series analysis
- Nonlinear dynamics
- Chaos theory
- Industrial AI

---

# 🧰 Technical Stack

### Languages
`Python` `SQL`

### AI / ML
`TensorFlow` `Keras` `Scikit-learn` `XGBoost` `LightGBM`

### Generative AI
`LangGraph` `LangChain` `RAG` `OpenAI` `Gemini` `Ollama`

### Computer Vision
`OpenCV` `TrOCR` `Donut` `LayoutLMv3`

### Backend
`FastAPI` `REST APIs` `PostgreSQL` `pgvector`

### Infrastructure / MLOps
`Docker` `Redis` `Celery` `MLflow` `AWS EC2` `AWS ECS`

### Frontend
`React` `Next.js` `Vite`

### Development
`Git` `Linux` `VS Code` `Jupyter`

---

# 🎯 What I'm Interested In

I'm currently focused on building and learning more about:

- Agentic AI systems
- Reliable RAG architectures
- LLM evaluation
- AI coding agents
- Multi-agent orchestration
- AI security & grounding
- Production ML systems
- Computer Vision & VLMs
- AI infrastructure and deployment

---

# 💡 Engineering Philosophy

I don't believe every problem needs an LLM.

I prefer using:

**Deterministic code → when the behaviour should be predictable**

**ML models → when learning from data is useful**

**LLMs/Agents → when reasoning, language, or ambiguity actually requires them**

The goal is not to make a system "more AI."

The goal is to make it **more useful, reliable, and maintainable.**

---

⭐ **I build AI systems that connect research, engineering, and real-world applications.**
