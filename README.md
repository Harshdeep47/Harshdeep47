<h1 align="center">Hi, I'm Harshdeep Singh 👋</h1>
<h3 align="center">Computer Engineering Student · Software & Data Engineering</h3>

<p align="center">
  <a href="https://linkedin.com/in/harshdeep-singh"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:hsingh11_be24@thapar.edu"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/CGPA-9.21%2F10-brightgreen" />
  <img src="https://img.shields.io/badge/Location-Patiala%2C%20Punjab-lightgrey" />
</p>

---

### About Me

I'm a third-year Computer Engineering student at **Thapar Institute of Engineering and Technology**, building things at the intersection of software engineering, data, and applied AI — mostly by picking a hard, compute-constrained problem and reasoning my way through it from first principles rather than reaching for the biggest model available.

- 🎓 B.E. Computer Engineering, Thapar Institute of Engineering and Technology (2024 – 2028) — CGPA 9.21/10
- 🔍 Currently building **Talent Signal**, an AI candidate-ranking engine that scores 100,000 profiles against a job description in under 5 seconds, CPU-only
- 🏆 Finalist (Top 20 nationwide) — UCO Bank × IIT Kharagpur National Hackathon, for **EchoTrace**, a real-time voice deepfake/fraud detection platform
- 🌱 Learning to build production-minded systems: reproducibility, fingerprinted caching, penalty-gated scoring, and honest engineering trade-offs over black-box ML
- 💬 Ask me about TF-IDF ranking pipelines, relational database design, or why I skipped a neural embedding model for a CPU-only hackathon constraint

---

### Featured Projects

#### 🎯 [Talent Signal — AI Candidate Ranking Engine](https://github.com/Harshdeep47/redrob-candidate-ranking)
Built for the **India Runs Hackathon (Redrob × Hack2Skill)**.
A two-stage pipeline (precompute → rank) that scores 100,000 candidate profiles against a job description in ~4–5 seconds on CPU only.
- Weighted scoring across 13+ signals (TF-IDF cosine similarity, skill-assessment scores, career-history patterns) combined with **multiplicative penalty gates**, not additive ones — so one disqualifying signal (like a honeypot profile) can't be diluted by unrelated keyword overlap
- Found that free-text job descriptions were topically unreliable for ~84% of non-technical titles, and built a title-relevance gate to stop keyword-stuffed profiles from ranking — caught a live HR Manager false-positive bug during QA
- Shipped as a Streamlit sandbox app with real-time progress tracking, reproducible via a single command
- **Stack:** Python, scikit-learn (TF-IDF), Pandas, Streamlit

#### 🎙️ [EchoTrace — Real-Time Voice Deepfake & Fraud Detection](https://github.com/Harshdeep47/EchoTrace)
Built for the **UCO Bank × IIT Kharagpur National Hackathon** — Finalist, Top 20 Teams Nationwide.
An audio forensics platform for India's banking channel that combines synthetic-voice detection, replay-attack detection, and confidence-aware, abstain-first decision making so uncertain calls escalate instead of guessing.
- SSL-based embeddings feeding an AASIST-style synthetic voice classifier, plus OOD detection and temperature-scaling calibration for trustworthy confidence scores
- Designed to emit calibrated risk signals into a bank's existing fraud stack rather than replace it outright
- **Stack:** Python, audio ML pipelines, signal processing

#### 📈 Tesla Stock Price Prediction Pipeline
A forecasting pipeline using Facebook Prophet over 3,650+ historical data points, back-tested against a clean 1-year holdout window (Jan 2020 – Jan 2021) with an interactive Plotly dashboard comparing predicted vs. actual prices.
- **Stack:** Python, Prophet, Pandas, Plotly

#### 🏠 Hostel Roommate Matching System
A normalized relational database (3NF/BCNF) with 6 core entities automating compatible roommate allocation, backed by PL/SQL stored procedures, triggers, and cursors that enforce referential integrity under concurrent requests.
- **Stack:** Oracle DB, PL/SQL

---

### Tech Stack

**Languages**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/-C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**Data & ML**
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Plotly](https://img.shields.io/badge/-Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)

**Tools & Platforms**
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Oracle DB](https://img.shields.io/badge/-Oracle%20DB-F80000?style=flat&logo=oracle&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)

---

### GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Harshdeep47&show_icons=true&theme=default&hide_border=true&count_private=true" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Harshdeep47&layout=compact&hide_border=true" width="35%" />
</p>

---

<p align="center">
  <i>Currently exploring: automated JD parsing, calibrated ML confidence, and shipping side projects that survive contact with real data.</i>
</p>
