<div align="center">

<img src="banner.svg" alt="Ahmeduddin Mohammed: ML &amp; AI Engineer" width="100%"/>

<!-- Typing animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00D4FF&center=true&vCenter=true&random=false&width=760&lines=ML+%26+AI+Engineer+%7C+Systems+that+ship;LangGraph+%7C+PyTorch+%7C+XGBoost+%7C+Causal+ML;0.958+AUC+%7C+27+ms+%7C+14M+rows+%7C+GCP+deployed;I+audit+my+own+models+%E2%80%94+and+fix+what+I+find" alt="ML & AI Engineer | Systems that ship" />
</a>

<br/>

<!-- Profile badges -->
<a href="https://ahmed-portfolio-blue.vercel.app">
  <img src="https://img.shields.io/badge/🚀%20Portfolio-Visit%20Now-00d4ff?style=for-the-badge&logoColor=white" />
</a>
<a href="https://linkedin.com/in/mohammed-ahmeduddin">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:mohammed.ahmeduddin16@gmail.com">
  <img src="https://img.shields.io/badge/Email-Hire%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://ahmed-portfolio-blue.vercel.app/Ahmeduddin_Mohammed_Resume.pdf">
  <img src="https://img.shields.io/badge/Resume-Download-10b981?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" />
</a>

<br/><br/>

<!-- Profile views -->
<img src="https://komarev.com/ghpvc/?username=MohammedAhmeduddin&label=Profile%20Views&color=00d4ff&style=flat" />
<img src="https://img.shields.io/github/followers/MohammedAhmeduddin?label=Followers&style=flat&color=8b5cf6" />

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width="28"> About Me

<div align="center">
<img src="terminal.svg" alt="whoami: Ahmeduddin Mohammed, ML & AI Engineer (MS CS, NJIT). Focus: production ML, LLM agents & RAG, causal inference, deep learning. Shipped: CareAgent, LoanLens, SessionScout, LiftLab. Open to ML, AI, GenAI and Forward Deployed roles; startups welcome." width="100%"/>
</div>

<details>
<summary><b>Plain-text version</b></summary>

- **Who:** ML & AI Engineer · MS Computer Science, NJIT · NYC metro, open to relocating anywhere in the US
- **Focus:** production ML · LLM agents & RAG · causal inference · deep learning
- **What I bring to a team:** I take a problem from raw data to a model, an API and a live deployment, and I audit my own work. I found 12 defects in LoanLens, a label leak in SessionScout and a biased "ground truth" in a 14M-row benchmark. Then I fixed them and added tests.
- **Looking for:** ML Engineer · AI Engineer · GenAI Engineer · Forward Deployed Engineer roles, startups included
- **Contact:** mohammed.ahmeduddin16@gmail.com

</details>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="28"> Key Metrics

<div align="center">

| 🎯 Best test AUC | ⚡ Latency | 📊 Largest dataset | 🏥 Real records | ✅ Tests | 📦 Live deployments |
|:---:|:---:|:---:|:---:|:---:|:---:|
| **0.958** | **27 ms** | **14M rows** | **39,694** | **623** | **4** |
| SessionScout LSTM | Redis-cached API | LiftLab · Criteo | CareAgent · CMS providers | across 4 ML projects | Hugging Face + GCP |

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="32"> Featured ML Projects

<div align="center">

### 🟢 CareAgent — Multi-Agent Analysis of Medicare Billing

[![GitHub](https://img.shields.io/badge/GitHub-CareAgent-181717?style=for-the-badge&logo=github)](https://github.com/MohammedAhmeduddin/careagent)
[![HuggingFace](https://img.shields.io/badge/Live_Demo-HuggingFace-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/AhmeduddinMohammed/careagent)
[![GCP API](https://img.shields.io/badge/Live_API-GCP_Cloud_Run-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)](https://careagent-api-668260909878.us-central1.run.app/docs)

</div>

> A LangGraph supervisor routes 5 agents over **39,694 real New Jersey Medicare providers** (CMS 2024, **$4.78B** in payments).
> - **Peer comparison:** providers are compared within their specialty (71 specialties) after adjusting for patient risk. It flags **1,461 outliers (3.7%)**, each with reasons drawn from the data, and an independent Isolation Forest agrees (outliers sit at the 96th percentile of its score vs the 48th).
> - **Checked LLM summaries:** every number in an LLM summary is checked against the data in code.
> - **Caching:** a fingerprinted cache cuts repeat requests from **4.7 s to 0.83 s with 0 tokens**.

![Providers](https://img.shields.io/badge/Providers-39%2C694_real-10b981?style=flat-square)
![Outliers](https://img.shields.io/badge/Outliers-1%2C461_(3.7%25)-10b981?style=flat-square)
![Cache](https://img.shields.io/badge/Cache-4.7s_→_0.83s-10b981?style=flat-square)
![Tests](https://img.shields.io/badge/Tests-176_passing-10b981?style=flat-square)
![Coverage](https://img.shields.io/badge/Coverage-98.7%25-10b981?style=flat-square)

`LangGraph` `OpenAI` `Isolation Forest` `FastAPI` `PostgreSQL` `GCP Cloud Run` `Secret Manager`

---

<div align="center">

### 🩷 LoanLens — Explainable, Fair-Lending-Aware Credit Risk

[![GitHub](https://img.shields.io/badge/GitHub-LoanLens-181717?style=for-the-badge&logo=github)](https://github.com/MohammedAhmeduddin/loanlens)
[![HuggingFace](https://img.shields.io/badge/Live_Demo-HuggingFace-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/AhmeduddinMohammed/loanlens)

</div>

> An XGBoost credit-risk model on **307,511 loan applications** (16M+ joined rows).
> - **Calibrated:** predicted default rate 0.080 vs actual 0.081.
> - **Fair-lending checks:** sex, marital status and age were removed at a cost of **0.004 AUC**, and the four-fifths rule check passes (0.95 vs the 0.80 threshold).
> - **Explanations:** SHAP values become CFPB adverse-action reason codes, retrieved by RAG over **9,977 CFPB regulation chunks**. Every citation and reason is verified in code.
> - **Self-audit:** found and fixed **12 defects**.

![AUC](https://img.shields.io/badge/Test_AUC-0.770-f472b6?style=flat-square)
![Calibration](https://img.shields.io/badge/Calibration-0.080_vs_0.081-f472b6?style=flat-square)
![Fairness](https://img.shields.io/badge/Four--fifths_rule-passed-f472b6?style=flat-square)
![Tests](https://img.shields.io/badge/Tests-203_passing-10b981?style=flat-square)
![Coverage](https://img.shields.io/badge/Coverage-90%25-10b981?style=flat-square)

`XGBoost` `SHAP` `RAG` `ChromaDB` `OpenAI` `dbt` `PostgreSQL` `FastAPI` `MLflow`

---

<div align="center">

### 🔵 SessionScout — Real-Time E-Commerce Purchase Prediction

[![GitHub](https://img.shields.io/badge/GitHub-SessionScout-181717?style=for-the-badge&logo=github)](https://github.com/MohammedAhmeduddin/sessionscout)
[![HuggingFace](https://img.shields.io/badge/Live_Demo-HuggingFace-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/AhmeduddinMohammed/sessionscout)

</div>

> A 4-model cascade (Logistic Regression → XGBoost → LSTM → Transformer) in PyTorch on **241K sessions**. The LSTM reaches **0.958 test AUC**.
> - **Label leak found:** live-demo testing exposed a leak that marked **5,640 buyer sessions**. The pipeline was rebuilt and retrained, and regression tests now guard against it.
> - **Serving:** FastAPI with Redis caching in Docker responds in **27 ms**.

![AUC](https://img.shields.io/badge/Test_AUC-0.958-00d4ff?style=flat-square)
![Latency](https://img.shields.io/badge/Latency-27ms-00d4ff?style=flat-square)
![Sessions](https://img.shields.io/badge/Sessions-241K-00d4ff?style=flat-square)
![Tests](https://img.shields.io/badge/Tests-145_passing-10b981?style=flat-square)
![Coverage](https://img.shields.io/badge/Coverage-94%25-10b981?style=flat-square)

`PyTorch` `LSTM` `Transformer` `XGBoost` `FastAPI` `Redis` `Docker` `HuggingFace`

---

<div align="center">

### 🟣 LiftLab — Causal Inference on 14M Real Ad-Campaign Users

[![GitHub](https://img.shields.io/badge/GitHub-LiftLab-181717?style=for-the-badge&logo=github)](https://github.com/MohammedAhmeduddin/liftlab)

</div>

> Measures how much ads **caused** visits and conversions on the full Criteo Uplift dataset (**13,979,592 users**).
> - **Randomization check:** the dataset isn't fully randomized. A classifier predicts who was treated (AUC 0.510, vs at most 0.5014 with shuffled labels), so the raw comparison overstates the visit effect by **39%**. Cross-fitted **AIPW** is used as the reference instead.
> - **Targeting:** one quarter of users produce **~94%** of the extra conversions. A Causal Forest ranks users with a held-out Qini of **0.339**.
> - **Validated first:** every estimator is checked on simulated data with a known answer before it touches real data.

![Rows](https://img.shields.io/badge/Dataset-14M_rows-8b5cf6?style=flat-square)
![Bias](https://img.shields.io/badge/Raw_estimate_overstated-39%25-8b5cf6?style=flat-square)
![Qini](https://img.shields.io/badge/Held--out_Qini-0.339-8b5cf6?style=flat-square)
![Tests](https://img.shields.io/badge/Tests-99_passing-10b981?style=flat-square)
![Coverage](https://img.shields.io/badge/Coverage-94%25-10b981?style=flat-square)

`EconML` `DoWhy` `AIPW` `Causal Forest` `scikit-learn` `FastAPI` `Streamlit`

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🧭 How I Build

| Practice | Example from my work |
|---|---|
| **Audit before claiming** | LoanLens: an inverted SHAP sign made every denial list the applicant's *strengths*; found, fixed, regression-tested |
| **Calibrate, then decide** | Replacing inflated scores with calibrated ones cut applicants sent away from auto-approval from 46% to 8.7% |
| **Verify LLM output in code** | LoanLens checks every regulation the LLM cites against the retrieved passages; the decision still works if the LLM is down |
| **Question the data** | LiftLab: a randomization check on 14M rows showed the "ground truth" itself was biased |
| **Honest metrics** | CareAgent: renamed a "quality score" to a billing-pattern comparison, because Medicare billing data has no outcomes |
| **Bound LLM cost and latency** | CareAgent reuses summaries keyed by a SHA-256 fingerprint of model + prompt + facts, with a 45 s time budget and per-client rate limits |
| **Ship with CI** | Lint, tests and coverage gates on every pull request |

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🗂️ More Projects

<div align="center">

| Project | Description | Stack | Links |
|---------|-------------|-------|-------|
| **AI Financial Report Analyst** | Breaks down the change in net income between two quarterly-report PDFs into revenue, margin, opex, tax and other drivers that fully reconcile. Optional LLM commentary is limited to those drivers, with citations from the Statements of Operations | FastAPI · React · OpenAI · pdfplumber | [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github)](https://github.com/MohammedAhmeduddin/quarterly-financial-variance-analyzer) [![Live](https://img.shields.io/badge/Live-f59e0b?style=flat)](https://ai-financial-report-analyst-fawn.vercel.app) |
| **AI Money Brain** | Personal-finance API: bank and card CSV import, LLM transaction categorization with keyword fallback, spending analytics, JWT auth | FastAPI · PostgreSQL · Alembic · OpenAI · Docker | [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github)](https://github.com/MohammedAhmeduddin/ai-money-brain) |
| **Developer Portfolio Tracker** | React dashboard: protected routes, search and filters, CRUD forms, skill charts, dark mode | React · TypeScript · Vite · Recharts | [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github)](https://github.com/MohammedAhmeduddin/developer-portfolio-tracker) [![Live](https://img.shields.io/badge/Live-8b5cf6?style=flat)](https://developer-portfolio-tracker.vercel.app) |
| **User Management** *(NJIT course project)* | User and event-management service built on course base code: fixed 7 issues (JWT errors, email-verification order, password rules, logging), added profile management and 31 tests | FastAPI · PostgreSQL · Docker · GitHub Actions | [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github)](https://github.com/MohammedAhmeduddin/user_management) |

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## <img src="https://media.giphy.com/media/j2pOGeGYKe2xCCKwfi/giphy.gif" width="28"> ML / AI Stack

<div align="center">

**ML & Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FCE?style=for-the-badge&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-8b5cf6?style=for-the-badge&logoColor=white)

**LLM & Agents**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-00d4ff?style=for-the-badge&logoColor=white)

**Causal Inference**

![EconML](https://img.shields.io/badge/EconML-0078D4?style=for-the-badge&logoColor=white)
![DoWhy](https://img.shields.io/badge/DoWhy-0078D4?style=for-the-badge&logoColor=white)
![AIPW](https://img.shields.io/badge/AIPW-8b5cf6?style=for-the-badge&logoColor=white)

**MLOps & Cloud**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/GCP_Cloud_Run-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black)

**Backend & Data**

![Python](https://img.shields.io/badge/Python_3.11-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 📊 GitHub Stats

<div align="center">

<img src="https://streak-stats.demolab.com?user=MohammedAhmeduddin&theme=tokyonight&hide_border=true&background=0d1117&stroke=00d4ff&ring=8b5cf6&fire=f472b6&currStreakLabel=00d4ff&sideLabels=e8f4f8&dates=4a6580"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=MohammedAhmeduddin&bg_color=0d1117&color=00d4ff&line=8b5cf6&point=f472b6&area=true&hide_border=true" width="100%"/>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<div align="center">

### 💼 Open to Roles

`ML Engineer` `AI Engineer` `GenAI Engineer` `Data Scientist` `Forward Deployed Engineer`

**📍 Harrison, NJ · Open to relocation anywhere in the US · Remote, hybrid or on-site**

<br/>

<img src="footer.svg" alt="" width="100%"/>

</div>
