# Hi, I'm Amisha

Final-year B.Tech CSE student at Manipal University Jaipur. I build full-stack web and mobile apps and data projects, and I do ML research on medical data.

## Currently working on

- **MisconceptMap**: a GATE CS practice platform that works out *why* you got a question wrong. Each wrong option is tagged with a specific misconception, a knowledge-tracing model (BKT) tracks how well you know each concept, and the next question targets your weakest prerequisite. React, TypeScript, FastAPI, PostgreSQL.
- **MYRROR**: a fashion shopping assistant that suggests outfits based on a user's profile, occasion, budget and wardrobe. React, TypeScript, FastAPI, PostgreSQL, Gemini.
- **ATG-DeiT**: research on detecting Alzheimer's disease from brain MRI (lead author). Adds attention-guided token pruning to DeiT. 97.84% accuracy and 100% recall on Moderate Dementia on OASIS-1 (86,437 slices), compared against nine baselines including VGG-16 and ResNet-152.

## Projects

### [CampusConnect](https://github.com/amishasharma2220/CampusConnect2)

Event management platform for Manipal University Jaipur, with a web app and an Android app on one backend.

React, TypeScript, React Native (Expo), FastAPI, PostgreSQL, SQLAlchemy, Alembic, Docker, GitHub Actions, Razorpay, Sentry. Deployed on Vercel, Render and Neon.

- Three roles: student, club admin, university admin
- 22-table PostgreSQL schema with 82 real MUJ clubs across 5 faculties. Covers event proposals and approvals, registrations, attendance, certificates and budgets
- JWT access and refresh tokens with rotation, role-based access, rate limiting and capacity-checked registrations
- Razorpay payments for club membership. The server creates the order from the fee stored in the database and verifies the signature before granting membership
- React Native mobile app on the same API, with tokens stored in the device keychain and Razorpay checkout built in. Distributed as an Android APK
- GitHub Actions runs lint, type checks, migration checks and 66 pytest tests (87% coverage) on every push. Production deploys only if all of them pass
- Alembic migrations, set up on the live database without losing data
- Request-ID logging, Sentry, health checks, CORS allowlist and security headers

[Live](https://campus-connect2-alpha.vercel.app) · [Android APK](https://expo.dev/accounts/amisha2220/projects/campusconnect/builds/446d32ca-aa6d-4cb5-b35b-7e9c6195d9ed) · [API docs](https://campusconnect-api-p6ql.onrender.com/api/docs)

### [HEATSHIELD](https://github.com/amishasharma2220/HEATSHIELD_ManipalUniversityJaipur)

A digital twin that forecasts dangerous heat strain 24 hours ahead for older patients on heart and diabetes medicines. Built for the Happiest Health Digital Twin Challenge 2026 (team of 2).

Python, NumPy, XGBoost, scikit-learn, Streamlit, Plotly, HL7 FHIR.

- Beta-blockers keep heart rate low even when the body is overheating, so heart-rate-based estimates miss it. The twin learns each patient's own heat response from wearable data with a particle filter
- On 240 synthetic patients with real 2024 heatwave weather, it cut core-temperature error for beta-blocked patients from 1.03 °C (published 2013 method) to 0.21 °C
- Predicted next-day events with AUROC 0.96 vs 0.94 for XGBoost, with half the false alarms
- Error stayed within 0.20–0.22 °C when the drug assumptions were changed by 50% or up to 47% of wearable data was missing
- Streamlit dashboard with a 24-hour forecast, what-if scenarios, live replay, Hindi/English family alerts and FHIR export
- All patient data is synthetic, so this shows the method works in simulation, not clinical accuracy

[Live](https://amishasharma2220-heatshield-manipaluniversi-appdashboard-il5ao4.streamlit.app/) (first load can take a few minutes)

### [FlavorLens](https://github.com/amishasharma2220/FlavorLens)

Scores Bangalore localities on how good an opening they are for a new restaurant, by cuisine.

Python, Pandas, PostgreSQL, Streamlit, Plotly, Groq (Llama 3.1).

- Opportunity score made of four weighted components, calculated in SQL
- Localities with too little data get a low confidence score instead of filled-in values
- The LLM only explains the scores. It doesn't calculate anything

[Live](https://flavorlens-4uyeebubdu4u674bz8rtro.streamlit.app/)

### [Kulfiwala](https://github.com/amishasharma2220/Kulfiwala)

Food ordering site. React (Vite), TypeScript, Node.js, Express, MongoDB Atlas.

- 7 REST endpoints for auth, products, orders, reviews and contact
- JWT login, protected routes, cart saved through to the order

[Live](https://kulfiwala-delta.vercel.app)

## Tech

- **Languages:** Python, JavaScript, TypeScript, SQL, C
- **Frontend and mobile:** React, React Native (Expo), Vite, Tailwind CSS, shadcn/ui
- **Backend:** FastAPI, Node.js, Express
- **Databases:** PostgreSQL, MongoDB, SQLAlchemy, Alembic
- **Data:** Pandas, NumPy, Plotly, Streamlit, Power BI
- **DevOps:** Docker, GitHub Actions, Pytest, Sentry, Vercel, Render, Neon, EAS Build
- **ML:** PyTorch, scikit-learn, XGBoost, Vision Transformers, Groq, Gemini API

## Education

B.Tech, Computer Science & Engineering (IoT & Intelligent Systems), Manipal University Jaipur
CGPA 8.23 · Dean's List for three consecutive semesters (9.10, 9.21, 9.95)

## Contact

[LinkedIn](https://www.linkedin.com/in/amishasharma2220/) · [LeetCode](https://leetcode.com/u/amishasharma2220/) · [Email](mailto:amishasharma2220@gmail.com)
