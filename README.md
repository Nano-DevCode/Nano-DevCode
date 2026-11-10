<div align="center">

# 👋 Hi, I'm Manuel Eduardo Santiago Feria
### Software Engineer · Backend & Full-Stack Developer
**Node.js · NestJS · TypeScript · PostgreSQL · React · Docker · AWS & Google Cloud**

📍 Oaxaca, Mexico · **100% Remote / Local On-Site in Oaxaca**

<p align="center">
  <a href="https://portfolio.nano-service.com/">
    <img src="https://img.shields.io/badge/🌐_Live_Portfolio-portfolio.nano--service.com-0284c7?style=for-the-badge" alt="Portfolio"/>
  </a>
  <a href="https://www.linkedin.com/in/manuel-eduardo-santiago-feria-a04b5a332/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:mayka708.ms@gmail.com">
    <img src="https://img.shields.io/badge/Email-mayka708.ms%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

</div>

---

## 👨‍💻 About Me

I am a **Computer Systems Engineering Graduate** from the **Instituto Tecnológico de Oaxaca (TecNM / ITO)** focused on building reliable backend architectures and full-stack web applications.

- 🏗️ **Backend & Systems Design:** Modular REST APIs, real-time communication with **WebSockets (Socket.io)**, background job processing with **BullMQ**, and role-based access control (**RBAC / 2FA**).
- 🗄️ **Data Integrity & Performance:** Relational modeling in **PostgreSQL** and **MySQL**, explicit ACID transactions (`QueryRunner`), optimistic concurrency control (`@VersionColumn`), Full-Text Search (`tsvector` / GIN indexes), and **Redis** caching/rate limiting.
- 🧪 **Automated Quality Assurance:** Strong testing culture with **1,600+ automated unit and integration tests** across repositories (**Jest** & **Pest PHP**).
- 🐳 **Cloud & Containers:** Multi-stage **Docker (Google Distroless non-root)** deployments, **Nginx** reverse proxy, **S3-compatible storage (MinIO)**, **Terraform (IaC)**, and **16 verified Cloud credentials (AWS & Google Cloud)**.

---

## 🚀 Featured Engineering Projects

### 1. 🎫 [IT Help Desk & Asset Inventory System](https://github.com/Nano-DevCode/nest-backend) — *TecNM / ITO*
> **Repositories:** [Backend API (`nest-backend`)](https://github.com/Nano-DevCode/nest-backend) · [Web Client (`react-frontend`)](https://github.com/Nano-DevCode/react-frontend)  
> **Stack:** `NestJS` `TypeScript` `PostgreSQL` `Redis` `TypeORM` `Socket.io` `MinIO S3` `React` `TanStack Query` `Docker Distroless` `Jest`

Full-stack institutional platform built to centralize technical support tickets, multi-stage hardware inventory transfers, and real-time operational metrics.
- **Transactional Integrity & Concurrency:** Multi-step asset assignments protected with explicit database transactions (`QueryRunner`) and optimistic locking (`@VersionColumn`) to prevent race conditions.
- **Search, Caching & Storage:** Native PostgreSQL Full-Text Search (`tsvector` + GIN indexes), Redis in-memory caching & rate limiting, and S3-compatible file storage (MinIO) with presigned URLs.
- **Real-Time & Automated QA:** Zero-polling reactive UI via Socket.io + TanStack Query, backed by **998 automated tests across 143 test suites in Jest** and deployed in non-root **Docker Distroless** containers.

---

### 2. 🏢 [Enterprise Core SaaS Platform](https://github.com/Nano-DevCode/nestjs-backend-core) *(In Progress)*
> **Repositories:** [Core Backend (`nestjs-backend-core`)](https://github.com/Nano-DevCode/nestjs-backend-core) · [Web Client (`react-frontend-core`)](https://github.com/Nano-DevCode/react-frontend-core)  
> **Stack:** `NestJS` `React 19` `TypeScript` `Prisma ORM 7` `PostgreSQL 16` `Redis` `BullMQ` `ClamAV` `Tailwind CSS v4` `Jest`

Modular SaaS core architecture focused on security, asynchronous processing, and horizontal read scalability.
- **Security & Data Layer:** Decoupled 2FA/TOTP authentication with encrypted backup codes, hierarchical RBAC, PostgreSQL read-replica routing via Prisma 7, and streaming antivirus file inspection with **ClamAV** over S3 storage.
- **Async Processing & Testing:** Background workers powered by **BullMQ & Redis**, interactive JSON audit diff viewer in React 19, and **627 automated tests across 119 suites in Jest**.

---

### 3. 🛒 [AI Smart POS — Computer Vision Point of Sale](https://github.com/Nano-DevCode/tiendita-ia-pos)
> **Repository:** [`tiendita-ia-pos`](https://github.com/Nano-DevCode/tiendita-ia-pos)  
> **Stack:** `Python` `YOLOv8` `ONNX Runtime (DirectML)` `ByteTrack` `OpenCV` `NumPy`

Computer-vision point-of-sale system capable of identifying products automatically via camera and updating stock in real time.
- **Custom Model & GPU Acceleration:** Trained a custom YOLOv8 model achieving **97.1% mAP@50** on validation data; exported to ONNX Runtime with DirectML achieving **~21 FPS on GPU**.
- **Multi-Object Tracking:** Integrated **ByteTrack** with multi-frame confidence filtering to assign persistent IDs and prevent duplicate billing during hand occlusions.

---

### 4. 📝 [Laravel 12 Reactive CMS](https://github.com/Nano-DevCode/laravel-12-blog-cms) & 🛍️ [Vue 3 TechStore E-Commerce](https://github.com/Nano-DevCode/vue3-pinia-ecommerce)
- **[Laravel 12 CMS & Reactive Blog](https://github.com/Nano-DevCode/laravel-12-blog-cms):** Server-driven reactive publishing platform built with `Laravel 12`, `Livewire Volt`, `Alpine.js`, `MySQL`, and `Spatie RBAC`, verified by **44 automated feature tests (116 assertions) in Pest PHP**.
- **[TechStore SPA E-Commerce](https://github.com/Nano-DevCode/vue3-pinia-ecommerce):** Reactive e-commerce storefront and multi-step checkout built with `Vue 3 (Composition API)`, `TypeScript`, `Pinia`, `Vuetify`, and `Vite`.

---

## 🏅 Verified Cloud Certifications (Credly)

| Certification / Credential | Issuer | Verification |
| :--- | :--- | :--- |
| **AWS Cloud Quest: Solutions Architect** | Amazon Web Services (AWS) | [Verify on Credly (`9af9ebae`)](https://www.credly.com/badges/9af9ebae-f80f-4715-b45c-fe28959f5d5b) |
| **AWS Cloud Quest: Cloud Practitioner** | Amazon Web Services (AWS) | [Verify on Credly (`701bebc0`)](https://www.credly.com/badges/701bebc0-59c0-41dd-859f-31cba8bda9d3) |
| **Google Cloud Computing Foundations Certificate** | Google Cloud | [Verify on Credly (`afaf62b7`)](https://www.credly.com/badges/afaf62b7-8fc9-4cda-9aad-3985f43ceedf) |
| **Cloud Security, Infrastructure & Data/ML/AI Foundations** | Google Cloud | [Security (`88ab965e`)](https://www.credly.com/badges/88ab965e-b827-4dca-8677-2348e83fc7a3) · [Infra (`57991d00`)](https://www.credly.com/badges/57991d00-75e9-4186-88bc-c7c9762812dc) · [Data/ML (`27ff4f8b`)](https://www.credly.com/badges/27ff4f8b-150c-4153-a2bb-36c2cb18d2c5) |
| **+10 Official Google Cloud Skill Badges** | Google Cloud | Terraform IaC · VPC Networking · Compute Engine · Cloud Storage · Dataplex · Gemini GenAI |

---

## 🛠️ Tech Stack

### Languages
<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL"/>
</p>

### Backend & APIs
<p align="center">
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel"/>
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma"/>
  <img src="https://img.shields.io/badge/TypeORM-FE0803?style=for-the-badge&logo=typeorm&logoColor=white" alt="TypeORM"/>
  <img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white" alt="Socket.io"/>
</p>

### Databases, Cloud & Infrastructure
<p align="center">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Google Cloud"/>
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform"/>
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx"/>
  <img src="https://img.shields.io/badge/MinIO_S3-C72E49?style=for-the-badge&logo=minio&logoColor=white" alt="MinIO"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
</p>

### Frontend, AI & Testing
<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Vue.js_3-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D" alt="Vue.js"/>
  <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white" alt="TanStack Query"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
  <img src="https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white" alt="Jest"/>
  <img src="https://img.shields.io/badge/Pest_PHP-000000?style=for-the-badge&logo=pest&logoColor=white" alt="Pest PHP"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/>
</p>

---

## 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Nano-DevCode&show_icons=true&count_private=true&theme=tokyonight&hide_border=true" height="175" alt="GitHub Stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nano-DevCode&layout=compact&langs_count=8&theme=tokyonight&hide_border=true" height="175" alt="Top Languages"/>
</p>

> *Note: Automated language charts reflect file volume across public repositories rather than overall engineering proficiency.*
