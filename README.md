<div align="center">

# Abdullah Muhammad Bakhtiar
### Full-Stack Developer · Problem Solver · Community Builder

[![Email](https://img.shields.io/badge/Email-ambakhtiar88@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ambakhtiar88@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-ambakhtiar-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ambakhtiar)
[![Codeforces](https://img.shields.io/badge/Codeforces-out__of__the__Circle-1F8ACB?style=flat-square&logo=codeforces&logoColor=white)](https://codeforces.com/profile/out_of_the_Circle)
[![Location](https://img.shields.io/badge/Chittagong-Bangladesh-006A4E?style=flat-square&logo=googlemaps&logoColor=white)]()

</div>

---

## 👋 About Me

I'm a **CSE graduate** from International Islamic University Chittagong with a strong foundation in algorithms and a growing passion for building full-stack web applications that solve real problems.

My journey started in competitive programming — 500+ problems, 50+ online contests, and 5 offline contests — which shaped how I think through complex systems. Today I apply that same problem-solving mindset to product development: building platforms like a **blood donation ecosystem** and a **multi-seller medicine marketplace** for Bangladesh.

Currently deepening my expertise through advanced full-stack training (Next.js, TypeScript, PostgreSQL, Docker) and a parallel data science track (ML, Deep Learning, Generative AI) — aiming to work at the intersection of **software engineering and AI**.

---

## 🛠 Tech Stack

**Frontend**
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn/ui-000000?style=flat-square&logo=shadcnui&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-FF6C37?style=flat-square&logo=postman&logoColor=white)

**Database & Auth**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

**Languages & Tools**
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 🚀 Featured Projects

### 🩸 BloodHelp — Blood Donation & Crowdfunding Platform
> Multi-role platform connecting donors, hospitals, and NGOs across Bangladesh for emergency blood finding and medical crowdfunding.

- 6-role RBAC system (User, Hospital, Organisation, Admin, Super Admin)
- Hybrid JWT auth immune to CSRF & XSS — access token in memory, refresh token in HttpOnly cookie
- Geo-filtered donor search by Division → District → Upazila with eligibility enforcement
- SSLCommerz payment integration with IPN-verified crowdfunding ledger
- 52 REST API endpoints across 11 domain modules

**Stack:** `Next.js 16` `React 19` `Node.js` `Express` `PostgreSQL` `Prisma` `TanStack Query` `Zod` `SSLCommerz` `Cloudinary`

[![Frontend](https://img.shields.io/badge/Live_Demo-bloodhelp.vercel.app-000?style=flat-square&logo=vercel)](https://bloodhelp.vercel.app)
[![Backend API](https://img.shields.io/badge/API-bloodhelp--backend.vercel.app-339933?style=flat-square&logo=node.js)](https://bloodhelp-backend.vercel.app/api/v1)
[![Frontend Repo](https://img.shields.io/badge/Repo-Frontend-181717?style=flat-square&logo=github)](https://github.com/ambakhtiar/BloodHelp-Frontend)
[![Backend Repo](https://img.shields.io/badge/Repo-Backend-181717?style=flat-square&logo=github)](https://github.com/ambakhtiar/BloodHelp-Backend)

---

### 💊 MediStore — Multi-Seller Medicine Marketplace
> Online OTC medicine e-commerce platform where customers across Bangladesh can order from multiple verified sellers, managed by a centralized admin layer.

- Multi-seller architecture — each seller independently manages their own catalogue
- Full order lifecycle: `PENDING → PROCESSING → SHIPPED → DELIVERED → CANCELLED`
- Delivery-gated review system — only buyers with confirmed delivery can review
- Admin ban/unban system enforced at auth middleware level
- Better Auth session management with HttpOnly cookies

**Stack:** `Next.js 14` `React 18` `Node.js` `Express` `PostgreSQL` `Prisma` `TanStack Form` `Zod` `Better Auth`

[![Frontend](https://img.shields.io/badge/Live_Demo-medistore--medicine.vercel.app-000?style=flat-square&logo=vercel)](https://medistore-medicine.vercel.app)
[![Backend API](https://img.shields.io/badge/API-medistore--med.vercel.app-339933?style=flat-square&logo=node.js)](https://medistore-med.vercel.app)
[![Frontend Repo](https://img.shields.io/badge/Repo-Frontend-181717?style=flat-square&logo=github)](https://github.com/ambakhtiar/MediStore-Frontend)
[![Backend Repo](https://img.shields.io/badge/Repo-Backend-181717?style=flat-square&logo=github)](https://github.com/ambakhtiar/MediStore-Backend)

---

### 🕊️ Donate for Bangladesh — Crowdfunding Platform
> Transparent donation platform for Bangladesh crisis relief — flood victims, Quota Movement injured, and other urgent humanitarian causes.

- Real-time balance tracking with instant donation feedback
- Transaction history log for full donor transparency
- Responsive SPA with DOM-based state management

**Stack:** `HTML5` `JavaScript (ES6+)` `Tailwind CSS` `DaisyUI`

[![Live Demo](https://img.shields.io/badge/Live_Demo-donate--for--bangladesh.vercel.app-000?style=flat-square&logo=vercel)](https://donate-for-bangladesh-one.vercel.app/)
[![Repo](https://img.shields.io/badge/Repo-GitHub-181717?style=flat-square&logo=github)](https://github.com/ambakhtiar/Donate-for-Bangladesh)

---

## 🏆 Achievements

| | |
|---|---|
| 🥉 **2nd Runner-up** | IIUC Inter-University Mobile Games & Apps Development Contest |
| 🚀 **Participant** | NASA International Space Apps Challenge — Hackathon, October 2024 |
| 🧠 **500+ problems** | Competitive programming across Codeforces, LeetCode, HackerRank |
| ⭐ **CF Rating: 1055** | Codeforces — [out_of_the_Circle](https://codeforces.com/profile/out_of_the_Circle) |

---

## 📚 Currently Learning

| Course | Platform | Topics |
|---|---|---|
| **Web Development L2** | Programming Hero | TypeScript, Next.js, PostgreSQL, Prisma, Docker, AWS |
| **Full Stack Data Science** | InceptionBD | Python, ML, Deep Learning, Generative AI, Deployment |

---

## 🤝 Community Work

I've been involved in grassroots community work in Matarbari since 2019 — a consistent thread running parallel to my technical career.

- 🩸 **Lead Coordinator, Matarbari Blood Donors Society** *(2019–Present)* — Organised 10+ blood donation camps and emergency donor response systems
- 📚 **Founder, Matarbari Chattro Kollan Porishod** *(2019–Present)* — Educational, cultural, and social welfare initiatives for students
- 🦁 **Joint Treasurer, Leo Club of Chittagong Dynamic City** *(July 2024–June 2025)* — Financial operations and service event coordination
- 💡 **Founder, The Sunshine Online Library** *(2020–Present)* — Built a digital learning platform and led community engagement

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=ambakhtiar&show_icons=true&theme=default&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ambakhtiar&layout=compact&theme=default&hide_border=true)

</div>

---

## 📬 Get In Touch

| | |
|---|---|
| 📧 Email | [ambakhtiar88@gmail.com](mailto:ambakhtiar88@gmail.com) |
| 💼 LinkedIn | [linkedin.com/in/ambakhtiar](https://linkedin.com/in/ambakhtiar) |
| 🐙 GitHub | [github.com/ambakhtiar](https://github.com/ambakhtiar) |
| 💻 Codeforces | [out_of_the_Circle](https://codeforces.com/profile/out_of_the_Circle) |
| 📱 WhatsApp / Telegram | +8801614418883 |

---

<div align="center">
  <sub>B.Sc. in Computer Science & Engineering · International Islamic University Chittagong · CGPA 3.37/4.00 · 2021–2025</sub>
</div>