<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:03060f,50:0a1525,100:0d1c30&height=220&section=header&text=Ahmeduddin%20Mohammed&fontSize=42&fontColor=00d4ff&animation=fadeIn&fontAlignY=36&desc=ML%20%26%20AI%20Engineer%20%7C%20Production%20ML%20%7C%20GenAI%20Systems&descAlignY=56&descSize=15&descColor=8b5cf6" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00D4FF&center=true&vCenter=true&random=false&width=760&lines=ML+%26+AI+Engineer+%7C+Systems+that+ship;Calibrated+models+%7C+Verified+LLM+outputs;I+audit+my+own+models+%E2%80%94+and+fix+what+I+find" alt="Typing SVG" />
</a>

<br/>

<a href="https://ahmed-portfolio-blue.vercel.app"><img src="https://img.shields.io/badge/Portfolio-Visit-00d4ff?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://linkedin.com/in/mohammed-ahmeduddin"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:mohammed.ahmeduddin16@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://ahmed-portfolio-blue.vercel.app/Ahmeduddin_Mohammed_Resume.pdf"><img src="https://img.shields.io/badge/Resume-Download-10b981?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" /></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=MohammedAhmeduddin&label=Profile%20Views&color=00d4ff&style=flat" />
<img src="https://img.shields.io/github/followers/MohammedAhmeduddin?label=Followers&style=flat&color=8b5cf6" />

</div>

---

## 👋 About Me

I'm an **ML & AI Engineer** (MS Computer Science, NJIT) who builds machine-learning and GenAI systems that hold up in
production: calibrated models, typed APIs, tested pipelines and honest metrics.

What sets my work apart is that **I audit my own systems**. In my credit-risk project I found and fixed 12 defects,
including adverse-action reasons that pointed the wrong way, prohibited demographic inputs and training–serving skew.
In my session-scoring project I found a label leak through live-demo testing, then rebuilt and retrained the
pipeline. In my multi-agent healthcare project I replaced synthetic data with 39,694 real CMS providers and a
"quality score" the data couldn't support with an honest, risk-adjusted peer comparison.
Every number below is measured on held-out data, the full dataset or the live system, and every claim is backed by a test.

```python
class Ahmeduddin:
    role       = "ML / AI Engineer"
    location   = "Harrison, NJ (NYC metro) · open to relocate anywhere in the US"
    education  = "MS Computer Science, NJIT"
    focus      = ["Production ML", "LLM & RAG systems", "Agentic workflows", "Responsible AI"]
    principles = [
        "Calibrated probabilities over inflated scores",
        "Verify LLM output in code; never let a model grade itself",
        "Training-serving parity, enforced by tests",
        "Fairness checks on every training run",
    ]
```

---

## 📈 Key Metrics

<div align="center">

| 🎯 Best test AUC | ⚡ Latency | 📊 Largest dataset | 🏥 Real records | ✅ Tests | 📦 Live deployments |
|:---:|:---:|:---:|:---:|:---:|:---:|
| **0.958** | **27 ms** | **14M rows** | **39,694** | **623** | **4** |
| SessionScout LSTM | Redis-cached API | LiftLab · Criteo | CareAgent · CMS providers | across 4 ML projects | Hugging Face + GCP |

</div>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🩷 LoanLens
**Explainable, fair-lending-aware credit risk scoring**

[![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/MohammedAhmeduddin/loanlens)
[![Demo](https://img.shields.io/badge/Live_Demo-FFD21F?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/AhmeduddinMohammed/loanlens)

- XGBoost on **307,511 applications** (16M+ joined rows) · **0.770 test AUC**
- **Calibrated**: predicted default 0.080 vs actual 0.081
- Sex, marital status and age **removed at a cost of 0.004 AUC**; four-fifths fairness check passed (0.95 / 0.80)
- SHAP → CFPB reason codes · RAG over **9,977 CFPB chunks** · citations and reasons **verified in code**
- **12 defects found and fixed** in a self-audit · **203 tests**, 90% coverage

`XGBoost` `SHAP` `dbt` `PostgreSQL` `ChromaDB` `OpenAI` `FastAPI` `MLflow`

</td>
<td width="50%" valign="top">

### 🔵 SessionScout
**Real-time e-commerce purchase prediction**

[![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/MohammedAhmeduddin/sessionscout)
[![Demo](https://img.shields.io/badge/Live_Demo-FFD21F?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/AhmeduddinMohammed/sessionscout)

- 4-model cascade (LR, XGBoost, LSTM, Transformer) in PyTorch on **241K sessions**
- LSTM reaches **0.958 test AUC**
- **Found a label leak through live-demo testing** (5,640 buyer sessions), then rebuilt and retrained the pipeline with regression tests
- FastAPI + Redis caching + Docker at **27 ms** latency
- **145 tests**, 94% coverage, GitHub Actions CI

`PyTorch` `LSTM` `Transformer` `XGBoost` `FastAPI` `Redis` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🟢 CareAgent
**Multi-agent analysis of Medicare billing patterns**

[![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/MohammedAhmeduddin/careagent)
[![Demo](https://img.shields.io/badge/Live_Demo-FFD21F?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/AhmeduddinMohammed/careagent)
[![API](https://img.shields.io/badge/API-Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white)](https://careagent-api-668260909878.us-central1.run.app/docs)

- LangGraph supervisor + 5 agents over **39,694 real NJ Medicare providers** (CMS 2024, $4.78B in payments)
- Risk-adjusted peer comparison across **71 specialties** → **1,461 outliers (3.7%)**, each with data-derived reasons; Isolation Forest agrees (96th vs 48th percentile)
- LLM summaries **number-checked in code**; fingerprinted cache: **4.7 s → 0.83 s, 0 tokens**
- Cloud Run + Secret Manager + Neon · rate limiting · **176 tests**, 98.7% coverage

`LangGraph` `OpenAI` `Isolation Forest` `FastAPI` `PostgreSQL` `GCP Cloud Run`

</td>
<td width="50%" valign="top">

### 🟣 LiftLab
**Causal inference on 14M real ad-campaign users**

[![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/MohammedAhmeduddin/liftlab)

- Found that Criteo's "randomized" uplift dataset is not fully balanced (C2ST AUC 0.510); the raw comparison overstates the visit effect by **39%**, so a cross-fitted **AIPW** estimate is the reference
- One quarter of users drive **~94%** of incremental conversions; Causal Forest reaches a held-out Qini of **0.339**
- AIPW, PSM, DiD and T/X/Causal Forest validated on simulated data with known effects first; **99 tests, 94% coverage**

`EconML` `DoWhy` `scikit-learn` `FastAPI` `PostgreSQL` `Streamlit`

</td>
</tr>
</table>

---

## 🧭 How I Build

| Practice | Example from my work |
|---|---|
| **Audit before claiming** | LoanLens: an inverted SHAP sign made every denial list the applicant's *strengths*; found, fixed, regression-tested |
| **Calibrate, then decide** | Replacing inflated scores with calibrated ones cut applicants sent away from auto-approval from 46% to 8.7% |
| **Verify LLM output in code** | LoanLens checks every regulation the LLM cites against retrieved passages; the decision survives an LLM outage |
| **Training–serving parity** | The API rebuilds features exactly like the dbt SQL; a test parses the SQL to catch drift |
| **Honest metrics** | CareAgent: renamed a "quality score" to a billing-pattern comparison because Medicare billing data has no outcomes; every result carries a disclaimer |
| **Bound LLM cost and latency** | CareAgent reuses narratives under a SHA-256 fingerprint of model + prompt + facts, with a 45 s time budget and per-client rate limits |
| **Fairness by default** | Protected attributes kept out of models and used only for audits logged on every run |
| **Ship with CI** | Lint, tests and coverage gates on every pull request |

---

## 🗂️ More Projects

| Project | What it does | Stack | Links |
|---|---|---|---|
| **AI Financial Report Analyst** | Reads quarterly-report PDFs, extracts income-statement metrics and decomposes the change in net income into revenue, margin, opex, tax and other drivers that reconcile exactly. An optional LLM writes analyst commentary limited to the computed drivers, with citations to the source passages in the Statements of Operations | FastAPI · React · OpenAI · pdfplumber | [Code](https://github.com/MohammedAhmeduddin/quarterly-financial-variance-analyzer) · [Live](https://ai-financial-report-analyst-fawn.vercel.app) |
| **AI Money Brain** | Personal-finance API: imports bank and card CSV exports, categorizes transactions with an LLM plus keyword fallback, and serves spending analytics and insights behind JWT auth | FastAPI · PostgreSQL · Alembic · OpenAI · Docker | [Code](https://github.com/MohammedAhmeduddin/ai-money-brain) |
| **Developer Portfolio Tracker** | Front-end dashboard for managing developer profiles: protected routes, search and filters, CRUD forms, skill charts, dark mode | React · TypeScript · Vite · Recharts | [Code](https://github.com/MohammedAhmeduddin/developer-portfolio-tracker) · [Live](https://developer-portfolio-tracker.vercel.app) |
| **User Management** *(NJIT course project)* | User and event-management service built on course base code: fixed 7 reported issues (JWT error handling, email-verification ordering, password rules, logging), added a profile-management feature and 31 tests | FastAPI · PostgreSQL · Alembic · Docker · GitHub Actions | [Code](https://github.com/MohammedAhmeduddin/user_management) |

---

## 🛠️ Tech Stack

<div align="center">

**ML & Deep Learning**<br/>
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FCE?style=for-the-badge)
![SHAP](https://img.shields.io/badge/SHAP-8b5cf6?style=for-the-badge)

**GenAI & Agents**<br/>
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-00d4ff?style=for-the-badge)

**Causal Inference**<br/>
![DoWhy](https://img.shields.io/badge/DoWhy-0078D4?style=for-the-badge)
![EconML](https://img.shields.io/badge/EconML-0078D4?style=for-the-badge)

**Data & Backend**<br/>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**MLOps & Cloud**<br/>
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/GCP_Cloud_Run-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black)

</div>

---

## 📊 GitHub Activity

<div align="center">

<img src="https://streak-stats.demolab.com?user=MohammedAhmeduddin&theme=tokyonight&hide_border=true&background=0d1117&stroke=00d4ff&ring=8b5cf6&fire=f472b6&currStreakLabel=00d4ff&sideLabels=e8f4f8&dates=4a6580"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=MohammedAhmeduddin&bg_color=0d1117&color=00d4ff&line=8b5cf6&point=f472b6&area=true&hide_border=true" width="100%"/>

</div>

---

<div align="center">

### 💼 Open to Roles

`ML Engineer` · `AI Engineer` · `GenAI Engineer` · `Data Scientist` · `Forward Deployed Engineer`

**📍 Harrison, NJ · Open to relocation anywhere in the US · Remote, hybrid or on-site**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1c30,50:0a1525,100:03060f&height=110&section=footer" width="100%"/>

</div>
