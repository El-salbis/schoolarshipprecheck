# 🎯 Scholarship Pre-Check API

A production-ready API built with **Flask**, **PostgreSQL**, and **JWT** that acts like a **data analyst** to screen scholarship applicants for common mistakes, missing documents, ineligible grades, and other red-flags — **before** they apply.  
Targeted for scholarships in **US**, **Japan**, **China**, **Russia** (easily extensible to more countries).

---

## 🚀 Features

- **JWT Authentication** for secure partner/agent access.
- **Rules Engine (YAML)** — change country requirements without touching the code.
- **GPA Normalization** across different grading scales.
- **Applicant Screening** for:
  - GPA minimums
  - Language proficiency
  - Document completeness
  - Deadline & passport validity
- **Risk Score** calculation (0–100) with issues, warnings, and tips.
- **PostgreSQL persistence** for user accounts and screening audits.
- **Dockerized** for quick deployment to Render, Railway, etc.

---

## 📂 Project Structure

