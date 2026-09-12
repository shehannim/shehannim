# Hi there, I'm Shehan Nimsara 👋

**Full-Stack Developer | Alternative Credit Intelligence | Sri Lanka**

Building **Settl** — alternative credit scoring for Sri Lanka's digital economy (FastAPI + XGBoost + React). Focused on clean APIs, explainable ML, and production-ready UX.

📍 Sri Lanka · ✉️ netshehannimsara@gmail.com · 🔗 [Settl MVP](https://github.com/shehannim/settl-mvp)

![Profile views](https://komarev.com/ghpvc/?username=shehannim&color=0e75b6&style=flat)
[![GitHub followers](https://img.shields.io/github/followers/shehannim?style=social)](https://github.com/shehannim)

---

## 🚀 Featured Project

### [Settl — Alternative Credit Intelligence](https://github.com/shehannim/settl-mvp)
> Credit scores (300–850) for thin-file borrowers using PayPal transaction history, utility-bill OCR, NIC KYC, and XGBoost + SHAP explainability.

**Stack:** FastAPI · XGBoost · SHAP · Supabase (Postgres + Auth + Storage) · React 19 + Vite · Tailwind CSS · PayPal OAuth · Docker · Railway / Vercel

**What it does:**
- JWT auth (user + lender roles), NIC validation + OTP KYC flow
- PayPal Sandbox OAuth → transaction ingestion → feature engineering
- PDF utility-bill upload (CEB) → OCR extraction → human-in-loop review
- `/api/score/compute` → score + confidence + SHAP top-factors
- Lender query API: `GET /api/lender/query/{settl_id}` + loan-outcome feedback loop
- Synthetic 2,000-profile training pipeline (`scripts/train_model.py`, target AUC ≥ 0.78)

**API surface:** `auth · kyc · connect · ingest · score · lender` — interactive docs at `/docs`

```bash
# run backend
pip install -r backend/requirements.txt
python backend/scripts/train_model.py
uvicorn app.main:app --reload --port 8000

# run frontend
cd frontend && npm install && npm run dev
```

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/Postgres-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EC6A04?style=for-the-badge&logo=xgboost&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Languages:** Python, JavaScript, C++ (fundamentals), SQL
**Backend:** FastAPI, Pydantic, JWT, SQLAlchemy patterns, Supabase
**ML/Data:** XGBoost, scikit-learn, SHAP, pandas, numpy
**Frontend:** React 19, React Router 7, Axios, Tailwind CSS 4
**DevOps:** Git, GitHub Actions, Docker, Railway, Vercel

---

## 📊 GitHub Stats

![Shehan's stats](https://github-readme-stats.vercel.app/api?username=shehannim&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=shehannim&layout=compact&theme=tokyonight&hide_border=true)
![Streak](https://github-readme-streak-stats.herokuapp.com/?user=shehannim&theme=tokyonight&hide_border=true)

---

## 🗂️ More Work

- **C++ Console Foundations** — 10+ console apps (Hello, Trial 101, Project 1-4): OOP basics, I/O, Visual Studio toolchain. Private local history, being cleaned and pushed progressively.
- **Biomechanics PDF tooling** — local PDF experiments (`biomechanics-pdf/`).

> Currently polishing repos: adding READMEs, `.gitignore`, Dockerfiles, and CI to every project.

---

## 🌱 Currently

- [ ] Shipping Settl 2.0 UI (dashboard, KYC, bill verification)
- [ ] Adding lender analytics + outcome tracking
- [ ] Learning: TypeScript, system design, ML model monitoring

---

## 📫 Contact

- Email: netshehannimsara@gmail.com
- GitHub: [@shehannim](https://github.com/shehannim)
- Settl demo: backend `/docs` + frontend `npm run dev`

---

⭐ *If you find Settl interesting, a star helps — and lender / fintech feedback is welcome.*

<!-- Last updated: auto-commit bot keeps this profile active daily. See LAST_UPDATED.md -->
