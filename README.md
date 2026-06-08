<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1220,35:1d4ed8,70:22c55e,100:06b6d4&height=245&section=header&text=Soubhagya%20Jain&fontSize=58&fontColor=ffffff&animation=twinkling&fontAlignY=34&desc=ML%20Engineer%20%7C%20AI%20Engineer%20%E2%80%A2%20Production%20AI%20Systems%20%E2%80%A2%20FastAPI%20%7C%20Docker%20%7C%20MLOps%20%7C%20XAI&descAlignY=60&descSize=16" />
<h1>👋 Hey, I'm Soubhagya Jain</h1>
<p>
  <b>ML Engineer</b> who builds <b>production-grade AI systems</b> that work reliably in the real world.<br/>
  I care deeply about low-latency serving, robust pipelines, clean evaluation, explainability, and systems that teams can actually maintain.
</p>
<p>
  <a href="https://www.linkedin.com/in/soubhagya-jain-118205204">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://cyber-sentinel-ai-ten.vercel.app/">
    <img src="https://img.shields.io/badge/Live%20Demo-CyberSentinel-111827?style=for-the-badge&logo=vercel&logoColor=white"/>
  </a>
  <a href="https://github.com/SoubhagyaJain">
    <img src="https://img.shields.io/badge/GitHub-Follow-0b1220?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>
<p>
  <img src="https://komarev.com/ghpvc/?username=SoubhagyaJain&style=for-the-badge&color=2563eb" />
  <img src="https://img.shields.io/github/last-commit/SoubhagyaJain/SoubhagyaJain?style=for-the-badge&color=22c55e" />
  <img src="https://img.shields.io/badge/Open%20To-ML%20%2F%20AI%20Engineer%20Roles-06b6d4?style=for-the-badge" />
</p>
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&duration=2800&pause=600&color=60A5FA&center=true&vCenter=true&width=1000&lines=Production+AI+isn't+just+models+%E2%86%92+it's+pipelines%2C+serving%2C+evaluation%2C+and+trust;Low-latency+APIs+%E2%80%A2+Robust+MLOps+%E2%80%A2+Explainable+outputs+%E2%80%A2+Real+dashboards;Building+systems+that+don't+break+when+reality+gets+messy." />
</div>

---

## What I Actually Do

I design and ship **end-to-end ML systems** — from data pipelines and training to low-latency inference, monitoring, and explainability layers. My focus is on building things that are:

- **Reliable** under real-world data shifts and edge cases
- **Debuggable** and observable in production
- **Explainable** enough for humans to trust (especially in security and high-stakes domains)
- **Maintainable** by engineering teams, not just the person who trained the model

I obsess over the gap between "model works in notebook" and "system runs reliably in production."

---

## 🏗️ Featured Projects

### 🛡️ CyberSentinel AI — Real-Time Network Intrusion Detection System
**Production-grade ML threat detection platform** with explainable inference and live operational dashboards.

**Engineering Highlights**
- Designed a **low-latency inference path** using FastAPI with clean separation between model serving and business logic
- Built **multi-model benchmarking + automated model promotion** logic (compare, select, promote best performer)
- Implemented **custom XAI layer** so security analysts can understand *why* a flow was flagged
- Full product surface: FastAPI backend + React dashboard + dedicated Streamlit SOC console
- Dockerized end-to-end with reproducible environments

This project captures how I think about ML in security: the model is only useful if analysts can trust and act on its decisions quickly.

🔗 [Repo](https://github.com/SoubhagyaJain/CyberSentinel-AI) • [Live Demo](https://cyber-sentinel-ai-ten.vercel.app/)

---

### 🧱 Cyber System — Full-Stack Cybersecurity Platform (Monorepo)
A **multi-service cybersecurity platform** architected like a real product — not just a collection of notebooks.

Includes backend services, dashboard layer, and SOC tooling. Demonstrates ability to design and structure larger systems with clear service boundaries.

🔗 [Repo](https://github.com/SoubhagyaJain/Cyber-system)

---

### 🚗 Traffic Volume Prediction Dashboard — Robust sklearn Production Pipeline
A **production-minded ML dashboard** that predicts traffic volume while deliberately solving common real-world failure modes.

**Key Engineering Decisions**
- Built sklearn Pipelines with `OneHotEncoder(handle_unknown="ignore")` and proper preprocessing to prevent feature mismatch between train and inference
- Trained and compared **3 models** (Linear Regression, Decision Tree, Random Forest) with live evaluation metrics (MSE, RMSE, MAE, R²)
- Interactive visualizations for both predictions and model performance
- Designed to fail gracefully on unseen categories and distribution shifts

This project shows I care about the unglamorous but critical parts of ML engineering — making systems that don't silently break in production.

🔗 [Repo](https://github.com/SoubhagyaJain/Traffic-prediction)

---

### 🎬 Collaborative Filtering Movie Recommender
A **user-user collaborative filtering** system that:
- Computes similarity using cosine distance on user rating vectors
- Generates recommendations for movies a user hasn't seen based on similar users
- Serves results through a clean **Streamlit** interface

Simple in scope, but demonstrates solid applied ML fundamentals + ability to productize a model quickly.

🔗 [Repo](https://github.com/SoubhagyaJain/Collabrative-Filtering-System)

---

## 🧰 Technical Toolkit

**Languages & Core ML**  
Python • NumPy • Pandas • scikit-learn • XGBoost

**Production & Serving**  
FastAPI • REST API design • Model serving patterns • Docker • GitHub Actions (CI/CD)

**Data & Infrastructure**  
PostgreSQL • Redis • Reproducible pipelines • Feature stores (conceptual)

**Frontend & Visualization**  
React • Streamlit • Interactive dashboards • Real-time monitoring UIs

**Practices I Value**  
- Clean pipeline design that prevents train/serve skew  
- Evaluation frameworks beyond accuracy  
- Explainability as a first-class requirement  
- Containerization and environment reproducibility  
- Observability and debugging hooks from day one

---

## 🎯 What I'm Focused On Right Now

- **Reliable agentic AI systems** — tools, memory, evaluation harnesses, and workflow orchestration that actually work in production
- Advanced MLOps patterns: model registries, automated promotion, monitoring, and rollback strategies
- Building evaluation frameworks that catch issues before they reach users
- Low-latency serving architectures and the trade-offs between speed, cost, and accuracy

I'm particularly interested in the **intersection of classical ML engineering discipline and modern agentic workflows**.

---

## 🤝 Open To

✅ **ML Engineer / AI Engineer** roles (New Grad, Intern, or Full-time)  
✅ Roles where I can own end-to-end systems and push hard on **reliability, observability, and production readiness**  
✅ Applied AI work in security, infrastructure, or recommendation domains  
✅ Open-source collaboration on production ML tooling

📩 Reach me on [LinkedIn](https://www.linkedin.com/in/soubhagya-jain-118205204) — happy to chat about systems, trade-offs, or how to make AI actually shippable.

---

<div align="center">
<h3>⭐ If you find my work useful, a star on any repo genuinely helps.</h3>
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:22c55e,100:0b1220&height=130&section=footer" />
</div>
