# 🧠 Today I Learned — Dev Journal

> *A living record of my journey through code, crashes, concepts, and curiosity.*

[![Status](https://img.shields.io/badge/status-actively%20learning-brightgreen?style=flat-square)](https://github.com)
[![Course](https://img.shields.io/badge/degree-B.Tech%20CSE%20Sem%201-blue?style=flat-square)](https://github.com)
[![Focus](https://img.shields.io/badge/current%20project-AI%20SaaS-orange?style=flat-square)](https://github.com)

---

## 👨‍💻 About This Journal

This repository is my personal developer diary — a place where I document every meaningful thing I build, break, debug, and learn. From academic fundamentals in my **B.Tech CSE (1st Semester)** to real-world AI application development, this log captures the full picture of my growth as an engineer.

> *"Every expert was once a beginner who refused to give up."*

---

## 🚀 Current Focus

```
📦 Project: AI SaaS Platform
⚙️  Stack:   Next.js · TypeScript · Prisma · Stripe · OpenAI API · Tailwind CSS
🔥 Phase:   Active Development (Debugging & Feature Integration)
```

---

## 📅 Development Timeline

---

### 🌱 September 2026

| Date | Tag | What I Did |
|------|-----|------------|
| **Sept 01** | 🚀 Init | Successfully initialized the repository and structured the professional daily log layout. First commit — the journey begins. |
| **Sept 02** | 🤖 AI | Kicked off a **RAG (Retrieval-Augmented Generation)** AI project. Set up the frontend scaffolding with `package.json` and planned the vector DB pipeline. |
| **Sept 05** | 📐 DSA | Studied **Arrays & Time Complexity** (Big O notation) — core CSE Sem 1 concept. Solved 5 problems on linear search and frequency counting. |
| **Sept 07** | ⚡ Academics | Completed and finalized the comprehensive **Electronics Lab Manual** — every circuit documented, every reading recorded. |
| **Sept 10** | 🌐 Web Basics | Learned the fundamentals of **HTML5 semantics and CSS box model**. Built a static portfolio page from scratch as a practice exercise. |
| **Sept 14** | 💡 C Programming | Understood **pointers and memory addresses** in C — the concept that confuses every CSE fresher. Finally clicked! Drew memory diagrams to solidify understanding. |
| **Sept 18** | 🔢 Maths | Covered **Boolean Algebra and Logic Gates** (AND, OR, NOT, NAND, NOR, XOR) for Digital Electronics. Built truth tables for half adder and full adder. |
| **Sept 20** | 🎉 Milestone | Celebrated another year of life and learning! 🎂 Grateful for the grind. |
| **Sept 22** | 🌾 AI | Launched **AgriGuard AI** — an intelligence-driven project targeting smart agricultural monitoring and crop health prediction. |
| **Sept 25** | 🖥️ OS Concepts | Studied **Process Scheduling algorithms** — FCFS, SJF, Round Robin. Simulated examples on paper to understand context switching. |
| **Sept 29** | 📚 Exam Prep | Dedicated the day to final revisions for the **Electronics & Communication Exam**. Covered modulation techniques and op-amp circuits. |

---

### 🍂 October 2026

| Date | Tag | What I Did |
|------|-----|------------|
| **Oct 02** | 🗃️ Databases | Started learning **SQL basics** — CREATE, INSERT, SELECT, WHERE, JOIN. Created a mini student database as a practice project. Normalization (1NF, 2NF, 3NF) next. |
| **Oct 07** | 🧑‍🏫 Project | Started building **Smart Attendance System** — architecting the face recognition pipeline and backend API structure. |
| **Oct 10** | 🔐 Auth | Integrated **JWT-based authentication** into Smart Attendance System. Understanding the difference between session tokens and JWTs was a valuable lesson. |
| **Oct 15** | ☁️ Cloud | Got hands-on with **AWS S3 basics** — uploaded, retrieved, and deleted objects via the console. Set up bucket policies and understood IAM roles at a surface level. |
| **Oct 18** | 📦 npm & Node | Deep-dived into **Node.js module system** (CommonJS vs ES Modules). Resolved a tricky circular dependency bug that took 2 hours to trace. Learned to use `--inspect` flag for Node debugging. |
| **Oct 20** | 🧩 DSA | Studied **Linked Lists** — singly and doubly linked. Implemented insert, delete, and reverse operations in C. Visualized with pointer diagrams. |
| **Oct 22** | 🐛 Debugging | Battled multiple errors in the **AI SaaS project**. Traced a `CORS policy` issue across the API layer and fixed an environment variable leak in the Next.js config. Progress is progress, even when it's all red. |
| **Oct 23** | 🤖 AI SaaS | Working on the **AI SaaS platform** — integrating OpenAI API endpoints, hitting rate limit errors, debugging Prisma schema migration conflicts, and fixing a broken Stripe webhook handler. Error by error, the product is taking shape. |
| **Oct 25** | 📝 Academics | Dedicated the day to completing **college assignments** — organized, documented, and tracked all pending work directly on **GitHub**. Practiced using Git for academic task management: structured commits, clear descriptions, and version-controlled submissions. Productivity level: maximum. |

---

## 🐛 Errors I Fought This Week *(Oct 23)*

> *The best developers aren't the ones who write perfect code — they're the ones who debug fearlessly.*

- `PrismaClientKnownRequestError` — Foreign key constraint failed on `userId` field during user seeding.
- `Error: Invalid API Key` — OpenAI key was not loading from `.env.local` due to a Next.js server/client boundary issue.
- `CORSError: No 'Access-Control-Allow-Origin'` — Fixed by adding proper headers in `next.config.js` and updating API route middleware.
- `Stripe WebhookError: No signatures found matching the expected signature` — Was using raw body parsing incorrectly; resolved by disabling `bodyParser` on the webhook route.
- `next/font` hydration mismatch — Class name inconsistency between server and client render. Fixed by wrapping font class in `suppressHydrationWarning`.

---

## 🛠️ Tech Stack & Tools

```
🧠 AI/ML       → OpenAI API, RAG Frameworks, Vector Embeddings, LangChain
⚡ Frontend    → Next.js, React, TypeScript, Tailwind CSS
🔧 Backend     → Node.js, Prisma ORM, REST APIs
🗄️ Database    → PostgreSQL, MySQL (SQL fundamentals)
☁️ Cloud       → AWS S3, IAM basics
💳 Payments    → Stripe (Webhooks, Checkout Sessions)
🔐 Auth        → JWT, NextAuth.js
📐 CS Basics   → C Programming, Data Structures, Boolean Algebra, OS Concepts
🛠️ DevTools    → Git, GitHub, VS Code, Postman, Vercel
```

---

## 📚 B.Tech CSE Sem 1 — Concepts Log

Tracking the foundational concepts I'm learning in parallel with real-world projects:

- [x] Number Systems (Binary, Octal, Hex)
- [x] Boolean Algebra & Logic Gates
- [x] C Programming — Variables, Loops, Functions
- [x] C Programming — Pointers & Memory
- [x] Arrays & Time Complexity (Big O)
- [x] Linked Lists (Singly & Doubly)
- [x] Process Scheduling (FCFS, SJF, Round Robin)
- [x] SQL Basics (DDL, DML, Joins)
- [ ] Stacks & Queues
- [ ] Trees & Binary Search Trees
- [ ] Computer Networks — OSI Model
- [ ] DBMS — Transactions & ACID Properties

---

## 📈 Stats

```
📆 Days Logged     : 21+
🐛 Bugs Squashed   : Lost count (and sanity)
💡 Concepts Learned: Growing daily
☕ Coffee Consumed  : Immeasurable
```

---

<div align="center">

*"It's not about having time. It's about making time."*

**— Built with curiosity, caffeine, and compiler errors ☕🔥**

</div>
