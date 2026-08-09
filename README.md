# 🦷 DentaOS – AI-Powered Dental Clinic Platform

**DentaOS** is a modern full-stack dental clinic management platform built with Next.js.  
It combines appointment booking, patient management, subscription plans, and an AI Voice Agent to create a complete digital experience for dental clinics.

---

## ✨ Features

- 🏠 Beautiful modern landing page with smooth animations
- 🔐 Authentication powered by **Clerk** (Google, GitHub, Email + Password)
- 🔑 Email verification with 6-digit OTP
- 📅 Smart 3-step Appointment Booking Flow  
  (Select Dentist → Choose Service & Time → Confirm)
- 📩 Automatic email notifications via **Resend**
- 📊 Admin Dashboard to manage appointments & doctors
- 🗣️ **AI Voice Agent** powered by **Vapi** (available on Pro plans)
- 💳 Subscription system with Free + 2 Paid plans (via Clerk Billing)
- 🧾 Automatic invoices on successful payments
- 💸 Smart upgrade system (pay only the difference)
- 🗄️ PostgreSQL database with **Prisma ORM**
- 🎨 Modern UI with Tailwind CSS + Shadcn UI
- ⚡ Fast data fetching with TanStack Query
- 📱 Fully responsive design

---

## 🛠️ Tech Stack

| Category          | Technology                  |
|-------------------|-----------------------------|
| Framework         | Next.js 15 (App Router)     |
| Language          | TypeScript                  |
| Styling           | Tailwind CSS + Shadcn UI    |
| Authentication    | Clerk                       |
| Database          | PostgreSQL + Prisma         |
| AI Voice Agent    | Vapi                        |
| Email Service     | Resend                      |
| State Management  | TanStack Query              |
| Forms             | React Hook Form + Zod       |
| Linting           | Biome                       |

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ayushsangamm/DentaOS.git
cd DentaOS