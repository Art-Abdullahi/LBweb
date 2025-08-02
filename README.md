# 🚚 LoadHabour

**TruckMinder** is an **AI-powered operating system for small and mid-sized trucking carriers**.  
It automates dispatch, document capture, invoicing, compliance tracking and driver settlements—so fleet owners can run profitably without drowning in paperwork.

---

## Table of Contents
1. [Core Features](#core-features)  
2. [Tech Stack](#tech-stack)  
3. [Project Structure](#project-structure)  
4. [Getting Started](#getting-started)  
5. [Environment Variables](#environment-variables)  
6. [Scripts](#scripts)  
7. [API Routes](#api-routes)  
8. [Coding Standards](#coding-standards)  
9. [Deployment](#deployment)  
10. [Contributing](#contributing)  
11. [License](#license)

---

## Core Features
| Area | MVP Items | Status |
|------|-----------|--------|
| **Load Management** | CRUD loads, SmartDispatch AI suggestions | ⬜ |
| **Driver App** | Upload POD/BOL, live status | ⬜ |
| **Instant Invoicing** | Auto-generate PDF, email/send to factoring | ⬜ |
| **Compliance Guard** | Expiry alerts (CDL, insurance, IFTA) | ⬜ |
| **Driver Settlements** | Weekly auto-calc/pay structure | ⬜ |
| **Landing Page** | Marketing site + waitlist form | ✅ |

*(Check the [Trello board](#) for current sprint items.)*

---

## Tech Stack
| Layer | Library / Service |
|-------|-------------------|
| Frontend | **Next 13 (App Router)**, **Tailwind CSS**, **shadcn/ui**, **Lucide Icons** |
| Backend | **Payload CMS**, **Node/Express API**, **Prisma** |
| DB & Storage | PostgreSQL (Railway), AWS S3 (uploads) |
| AI Services | OpenAI embeddings (SmartDispatch prototype) |
| Auth | NextAuth (v5) / Clerk (select in `.env`) |
| Deployment | Vercel (web) + Railway (API/DB) |
| CI / CD | GitHub Actions → Vercel Preview & Railway deploy |
| Analytics | Plausible (production) |

---

## Project Structure
