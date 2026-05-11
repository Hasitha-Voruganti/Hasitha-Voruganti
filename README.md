<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1f35,100:0d3b8c&height=200&section=header&text=HASITHA%20VORUGANTI&fontSize=52&fontColor=58a6ff&fontAlignY=38&desc=AI%20Engineer%20%E2%80%A2%20Data%20Scientist%20%E2%80%A2%20Full%20Stack%20Developer&descAlignY=60&descColor=8b949e&animation=fadeIn" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hasitha-voruganti-a7168a2b8)
[![Gmail](https://img.shields.io/badge/hasithavoruganti%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hasithavoruganti@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Hasitha-Voruganti)

</div>

---

## 👋 Hi, I'm Hasitha Voruganti

I'm a Computer Science student from Hyderabad with a passion for building **intelligent, end-to-end software systems** — the kind that don't just look good in a demo, but actually solve real problems.

My work sits at the intersection of **AI Engineering**, **Machine Learning**, **Full Stack Development**, and **Data Analytics**. I enjoy taking an idea the full distance — from designing the database schema and training the ML model, to wiring up the backend API and shipping a clean, interactive frontend. Every layer matters to me.

Some of the things I've built include an **enterprise RAG agent** with hybrid search and self-correcting reasoning, an **AI-powered study platform** that adapts to your weak spots, and an **attrition prediction system** with real-time SHAP explainability — all production-grade, end-to-end.

**Currently exploring:**

`Advanced RAG Architectures` &nbsp;·&nbsp; `AI Engineering` &nbsp;·&nbsp; `Explainable AI (XAI)` &nbsp;·&nbsp; `Enterprise Search Systems` &nbsp;·&nbsp; `Full Stack System Design`

> 💡 *"Don't just analyze data — build systems that act on it."*

---

## 🚀 Featured Projects

---

### 🧠 [Corporate Brain — Agentic RAG Knowledge Assistant](https://github.com/Hasitha-Voruganti)
> *Enterprise AI that reads your company's documents — and actually understands them*

Most enterprise search is just keyword matching. Corporate Brain is an AI **agent** — it plans how to search, fuses semantic understanding with keyword precision, checks its own confidence, and rewrites its approach when uncertain. Every query is filtered through role-based access so employees only see what they're authorised to.

| Layer | What it does |
|-------|-------------|
| 🔍 **Search** | Hybrid: Qdrant semantic vectors + Elasticsearch BM25, fused with RRF |
| 🎯 **Reranking** | ms-marco-MiniLM cross-encoder for precision scoring |
| 🤖 **Agent Loop** | Plan → Act → Verify with query rewriting and self-reflection |
| 🔐 **Security** | JWT auth + RBAC enforced at the vector database level |
| ⚡ **Performance** | Redis caching for instant repeat query responses |
| 📄 **Ingestion** | PDF, DOCX, XLSX, PPTX, TXT + OCR fallback via Tesseract |

`FastAPI` `React` `Qdrant` `Elasticsearch` `PostgreSQL` `Redis` `Groq LLaMA 3.1` `Docker`

---

### 📉 [Employee Attrition Intelligence System](https://github.com/Hasitha-Voruganti)
> *Know who's about to quit — before they hand in their notice*

A production-grade ML platform that predicts employee attrition with automated model selection, SHAP explainability, and a 7-page React analytics dashboard — trained on the real **IBM HR Analytics dataset (1,470 employees)**.

| Rank | Model | ROC-AUC | F1 Score | Accuracy |
|------|-------|---------|----------|----------|
| 🥇 Best | XGBoost | **0.7860** | **0.4375** | 82.6% |
| 🥈 | RandomForest | 0.7858 | 0.3333 | 82.3% |
| 🥉 | LightGBM | 0.7821 | 0.4337 | **84.0%** |

> Best model auto-selected by composite score: `0.6 × ROC-AUC + 0.4 × F1`

**11 engineered features** — TenureRatio, SatisfactionScore, PromotionLag, JobHopper, IncomePerYearExp & more  
**SHAP explainability** — global feature importance + per-employee waterfall charts  
**16 FastAPI endpoints** | **7-page React SPA** | Real-time attrition gauge & HR risk recommendations

`XGBoost` `LightGBM` `SHAP` `FastAPI` `React` `Scikit-learn`

---

### 📚 [AI Study Assistant](https://github.com/Hasitha-Voruganti)
> *Your intelligent exam companion — upload, ask, quiz, master*

Transforms static PDFs into an active, adaptive learning experience. The AI doesn't just answer questions — it finds your weak spots and trains you on them before your exam does.

- 🤖 **Contextual Q&A** — accurate answers sourced directly from your uploaded documents
- 📝 **Smart quiz engine** — auto-generated MCQs across Easy / Medium / Hard / Mixed difficulty
- 🃏 **Flashcard system** — AI-created cards with Mastered vs Needs Revision tracking
- 🎯 **Weakness detection** — flags topics where your quiz scores fall below 60%
- 📊 **Progress dashboard** — score trends, subject breakdown, and streak tracking

`React` `Node.js` `MongoDB` `Express` `TailwindCSS` `Groq LLaMA 3`

---

### 📊 [DataMind — AI Data Analyst](https://github.com/Hasitha-Voruganti)
> *Upload any dataset. Ask questions. Get intelligence. No data science degree required.*

DataMind makes data analysis accessible to everyone. Upload any messy file, describe what you want to know in plain English, and the platform automatically cleans, visualises, and explains your data — no code needed.

- 📁 **Universal ingestion** — CSV, Excel, JSON, TSV, Parquet all supported
- 🧹 **One-click cleaning** — resolves nulls, duplicates, and outliers automatically
- 📈 **6 interactive chart types** + correlation heatmap with drill-down controls
- 🤖 **Conversational AI** — LLaMA 3.1-powered chat for natural language data queries
- 💾 **Export** cleaned datasets as ready-to-use CSV

`FastAPI` `Pandas` `NumPy` `React 18` `Vite` `Chart.js` `Framer Motion` `Groq AI`

---

### 🔍 [Customer Review Analytics — Pure SQL](https://github.com/Hasitha-Voruganti)
> *100K+ Amazon reviews → product intelligence — entirely inside MySQL*

No Python. No ML frameworks. Just SQL used seriously — covering the full pipeline from raw text ingestion to sentiment scoring, fake review detection, and business reporting views.

- **Custom 50-word sentiment lexicon** with -3 to +3 tiered scoring
- **Fake review detection** via star-rating vs. text-sentiment mismatch flagging
- **5 analytical views** forming a complete business reporting layer
- **12 insight queries** — rolling 3-month averages, YoY sentiment shifts, category health

`MySQL 8.0` `Window Functions` `CTEs` `Sentiment Analysis` `Fraud Detection`

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**AI / ML / Data**

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

**Backend & Databases**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)

**Frontend & DevOps**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img src="https://streak-stats.demolab.com?user=Hasitha-Voruganti&theme=tokyonight&hide_border=true&background=0d1117&ring=e05cd5&fire=e05cd5&currStreakLabel=58a6ff" />

<br/><br/>

<img src="https://github-widgetbox.vercel.app/api/languages?username=Hasitha-Voruganti&theme=nautilus&langs_count=8" />

</div>

---

## 📫 Let's Connect

<div align="center">

Always open to interesting problems, research discussions, and open-source collaborations.<br/>
If you're building something ambitious in AI/ML — let's talk.

<br/>

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hasitha-voruganti-a7168a2b8)
[![Email](https://img.shields.io/badge/hasithavoruganti%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hasithavoruganti@gmail.com)

<br/>

---

*"Data is the raw material. Intelligence is what you build with it."*

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Hasitha-Voruganti&style=for-the-badge&color=58a6ff&label=PROFILE+VIEWS)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d3b8c,50:1a1f35,100:0d1117&height=100&section=footer" />
