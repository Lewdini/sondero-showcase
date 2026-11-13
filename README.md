# Sondero | AI-Powered Multi-Tenant SaaS

Public showcase of Sondero: A multi-tenant B2B SaaS built with Next.js, PostgreSQL RLS, and Anthropic AI. **(Full codebase is private)**.

🎥 **[Watch the 2-Minute Demo Video Here](https://drive.google.com/file/d/18uOnInO1r85mAh3JaQRepWXmAudPlyub/view?usp=drive_link)**

## The Problem
Local businesses lack a unified digital presence and hiring platform. Sondero provides an all-in-one B2B SaaS that generates branded, bilingual websites using AI and includes a full Applicant Tracking System (ATS).

## Architecture & Tech Stack
*   **Frontend:** React, Next.js, TypeScript, Tailwind CSS
*   **Backend:** Node.js, Express, Drizzle ORM
*   **Database:** PostgreSQL (Neon) with Row-Level Security (RLS)
*   **AI:** Anthropic API (Claude) for content generation
*   **Infrastructure:** Vercel, Render, Google Cloud, Stripe API

## Key Engineering Challenges Solved
1.  **Multi-Tenant Isolation:** Architected and implemented PostgreSQL Row-Level Security across 72 tables and 85 policies to ensure strict data isolation between tenants.
2.  **AI Guardrails:** Built a generation pipeline that uses Anthropic's API while enforcing strict platform-wide banned-word guardrails and per-build cost/latency tracking.
3.  **Zero-Downtime Migration:** Successfully migrated the production database from Replit to Neon/Render while handling background worker memory overruns during concurrent AI generations.

## Screenshots

<img width="3372" height="1125" alt="Screenshot 2026-11-13 105534" src="https://github.com/user-attachments/assets/163c267a-6468-47e8-a2a5-50c0bb8e4901" />
<img width="3346" height="1118" alt="Screenshot 2026-11-13 105526" src="https://github.com/user-attachments/assets/4a085853-50e7-4340-b842-d29f959846a7" />
<img width="3353" height="1099" alt="Screenshot 2026-11-13 105518" src="https://github.com/user-attachments/assets/cfddbfe6-1937-4fd2-a009-ac97df01dfa8" />
<img width="3352" height="1093" alt="Screenshot 2026-11-13 105253" src="https://github.com/user-attachments/assets/8859ccb5-4b6d-4389-a5e9-8ee95012c043" />
<img width="3357" height="1117" alt="Screenshot 2026-11-13 104829" src="https://github.com/user-attachments/assets/19b6c80b-137a-4212-8d90-02b763c67269" />
