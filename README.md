# Hi, I'm Amisha

Final-year Computer Science undergrad at Manipal University Jaipur who builds things end to end, from database schema to deployed, tested app.

I'm interested in full-stack engineering, data engineering and analytics, and applied AI that actually does something useful.

---

## What I'm working on

- **MYRROR**: AI-powered personal fashion shopping companion (React + TypeScript + FastAPI + PostgreSQL + Gemini). Context-aware outfit and shopping recommendations based on user profile, occasion, budget and wardrobe.
- **ATG-DeiT**: ML research on Alzheimer's disease detection from brain MRI (lead author, targeting IEEE Access). Attention-guided token pruning for a Vision Transformer: 97.84% accuracy and 100% recall on Moderate Dementia on OASIS-1 (86,437 MRI slices), outperforming nine baselines including VGG-16 and ResNet-152.

---

## Projects

### [CampusConnect](https://github.com/amishasharma2220/CampusConnect2): University Event Management Platform

Built for Manipal University Jaipur from scratch, deployed end to end, with a full production pipeline.

**Tech:** React · TypeScript · FastAPI · Python · PostgreSQL · SQLAlchemy · Alembic · Docker · GitHub Actions · Razorpay · Sentry · Vercel · Render · Neon

- 3 user roles (student, club admin, university admin) on a 22-table PostgreSQL schema covering 82 real MUJ clubs across 5 faculties: event proposals and approvals, registrations, attendance, certificates and budgets
- Razorpay club-membership payments: server-side order creation from database fees and idempotent HMAC-SHA256 signature verification before membership is granted
- CI/CD with GitHub Actions and a multi-stage, non-root Docker image: lint, type checks, migration checks and 66 pytest tests (against real PostgreSQL) gate every production deploy
- Alembic migrations baselined onto the live production schema with no data loss; migrations run automatically on deploy
- Observability and security: JSON logs with request IDs, Sentry, uptime-monitored health checks, rate limiting, CORS allowlist, CSP/HSTS headers, and a fixed privilege-escalation flaw

[Live demo](https://campus-connect2-alpha.vercel.app) · [API docs](https://campusconnect-api-p6ql.onrender.com/api/docs) · [Repository](https://github.com/amishasharma2220/CampusConnect2)

---

### [FlavorLens](https://github.com/amishasharma2220/FlavorLens): Restaurant Expansion Intelligence Platform

Computes a data-backed Cuisine Opportunity Index for Bangalore localities instead of relying on guesswork.

**Tech:** Python · Pandas · PostgreSQL · SQL · Streamlit · Plotly · Groq (Llama 3.1)

- Composite opportunity score built in SQL (CTEs, window functions) from four independently weighted, documented components
- Confidence scoring so low-data localities are flagged, never faked with synthetic fill
- LLM layer explains pre-computed metrics only; it never calculates

[Live demo](https://flavorlens-4uyeebubdu4u674bz8rtro.streamlit.app/) · [Repository](https://github.com/amishasharma2220/FlavorLens)

---

### [Kulfiwala](https://github.com/amishasharma2220/Kulfiwala): Full-Stack Food Ordering Platform

**Tech:** React (Vite) · TypeScript · Node.js/Express · MongoDB Atlas · JWT

- 7 REST endpoints covering auth, products, orders, reviews and contact
- JWT-based auth with protected routes and full cart-to-order persistence
- Separately deployed frontend (Vercel) and backend (Render)

[Live demo](https://kulfiwala-delta.vercel.app) · [Repository](https://github.com/amishasharma2220/Kulfiwala)

---

## Tech Stack

| Area | Tools |
|---|---|
| Languages | Python · JavaScript · TypeScript · SQL · C |
| Frontend | React · Vite · Tailwind CSS · shadcn/ui |
| Backend | FastAPI · Node.js · Express.js · REST APIs |
| Databases | PostgreSQL · MongoDB · SQLAlchemy · Alembic |
| Data & Analytics | Pandas · NumPy · Plotly · Streamlit · Power BI |
| DevOps & Cloud | Docker · GitHub Actions · Pytest · Sentry · Vercel · Render · Neon |
| AI & ML | PyTorch · scikit-learn · Vision Transformers · Groq · Gemini API |

---

## Education

**B.Tech, Computer Science & Engineering (IoT & Intelligent Systems)**, Manipal University Jaipur
CGPA 8.23 · Dean's List for three consecutive semesters (9.10, 9.21, 9.95)

---

## Connect

[LinkedIn](https://www.linkedin.com/in/amishasharma2220/) · [LeetCode](https://leetcode.com/u/amishasharma2220/) · [Email](mailto:amishasharma2220@gmail.com)
