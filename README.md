# Hi, I'm Damodhar 👋
Backend-focused Full Stack Developer building applications using Node.js, TypeScript, PostgreSQL, React, and Flutter. Interested in backend systems, API design, workflow-heavy products, and scalable web applications.

---

## 🛠️ Tech Stack

### Backend & Databases
- Node.js
- TypeScript
- Express.js
- Fastify
- PostgreSQL
- MongoDB
- Prisma ORM
- REST APIs
- JWT Authentication
- RBAC

### Frontend & Mobile
- React (basic)
- Flutter
- HTML
- CSS

### Tools & Infrastructure
- Docker
- Git & GitHub
- Google Cloud Run
- Postman

---

## 🚀 What I'm Building & Learning
- Backend systems and API design using Node.js and TypeScript
- Scalable application workflows, authentication, and cloud deployment
- Better software engineering practices, debugging, and system design
- Exploring AI-assisted development workflows and modern tooling

---

## 💻 Highlighted Projects

### Job Application Tracker
A full stack tool to track job applications and evaluate resume-to-job-description fit using AI, built to solve my own job search workflow.

#### Core Features
- CRUD job application tracking with status filtering, search, and dashboard analytics
- JWT-based authentication with encrypted (AES-256-GCM) storage of user API keys
- AI-powered resume match analysis using the Gemini API — returns a match score, keyword gap analysis, and tailored resume bullet suggestions grounded strictly in the user's actual resume

#### Engineering Highlights
- Found and fixed multiple LLM reliability issues through adversarial testing: fabricated metrics, verb/scope inflation in generated bullets, and unreliable self-reported match-score arithmetic
- Moved score calculation out of the prompt entirely into deterministic backend logic, using the model only for classification (present/partial/missing), not counting
- Added detection for vague/low-specificity job descriptions to avoid presenting false-confidence match scores

#### Tech Stack
React • Node.js • TypeScript • PostgreSQL • Prisma • Gemini API • Docker

🔗 [Live](https://job-tracker-ten-mu-33.vercel.app) • [GitHub](https://github.com/DamodharGona/job-tracker)

---

### Healthcare Scheduling Platform (Internship Experience)
Backend-focused work on a clinic management platform used by doctors, receptionists, and patients — appointment booking, scheduling, and multi-role access control.

#### Backend Work
- Designed and implemented REST APIs using Node.js, TypeScript, and PostgreSQL for appointment booking, doctor scheduling, and consultation workflows
- Built a conflict-free scheduling system using Prisma and PostgreSQL, resolving doctor availability, leave periods, and existing appointments simultaneously
- Developed a triage assignment system routing patients to available doctors based on severity and specialization
- Implemented JWT and RBAC authentication securing role-specific access across doctors, receptionists, and patients
- Deployed backend on Google Cloud Run with Cloud SQL and signed URL file uploads for secure patient record handling
- Integrated Firebase OTP phone authentication for clinic staff onboarding

> Note: Source code is private due to company IP policies.

---

## 🎯 Engineering Focus
- Building reliable backend systems and APIs
- Writing clean and maintainable code
- Understanding product workflows and real-world constraints
- Shipping practical software that solves real user problems

---

## 🤝 Open To
- Backend Engineering Roles
- Backend-Focused Full Stack Roles
- Startup & Product Engineering Teams
- Remote / Hybrid / On-site Opportunities

---

## 📬 Reach Me
- LinkedIn: https://www.linkedin.com/in/damodharreddygona/
- GitHub: https://github.com/DamodharGona
- Email: gonadamodharreddy999@gmail.com
