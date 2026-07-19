# LearnPro Academy

![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-30_Edge_Functions-3FCF8E?logo=supabase&logoColor=white)
![Stripe](https://img.shields.io/badge/Payments-Stripe-635BFF?logo=stripe&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

**Complete online course platform** — subscriptions and payments with Stripe, course delivery, and an admin panel — powered by a serverless backend of **30 Supabase Edge Functions**.

## Highlights

The entire backend runs on **Supabase Edge Functions** (30 functions), organized by domain:

- 💰 **Payments & subscriptions** — `stripe-checkout`, `stripe-payment`, `create-subscription`, `cancel-subscription`, and more
- 🎓 **Course delivery** — enrollment, progress tracking, certificates
- 👤 **Users & access** — auth flows, entitlements, admin operations

## Features

- 📚 Course catalog with lessons and progress tracking
- 💳 **Stripe** checkout + recurring subscriptions
- 🛠️ Admin panel for courses, users and plans
- 🐳 **Dockerized** — Dockerfile + docker-compose + nginx for container deploys
- ☁️ Deployed on **Vercel** (frontend) + Supabase (backend)

## Tech Stack

React · TypeScript · Vite · shadcn/ui · Supabase (Postgres, Auth, 30 Edge Functions) · Stripe · Docker + nginx

## Getting Started

```bash
npm install
cp .env.example .env     # Supabase + Stripe keys
npm run dev
```

Docker route:

```bash
docker compose up --build
```

---

## 🇪🇸 Español

**Plataforma completa de cursos en línea** — suscripciones y pagos con **Stripe**, entrega de cursos y panel de administración — con backend serverless de **30 Supabase Edge Functions** organizadas por dominio (pagos, cursos, usuarios).

**Stack:** React + TypeScript + Vite, Supabase, Stripe, Docker + nginx, despliegue en Vercel.

```bash
npm install && npm run dev
```
