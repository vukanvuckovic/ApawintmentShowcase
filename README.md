# 🐾 Apawintment

> A multi-tenant appointment scheduling SaaS built specifically for 
> veterinary practices. This is a private commercial repository. 
> This page serves as a public project overview.

[![Live](https://img.shields.io/badge/Live-apawintment.com-success?style=flat&logo=vercel)](https://apawintment.com)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)

## 🔗 Live Demos

| | |
|---|---|
| **Business Dashboard** | [apawintment.com/preview/demo](https://apawintment.com/preview/demo) |
| **Client Booking Form** | [apawintment.com/book/demo](https://apawintment.com/book/demo) |

> These are live interactive demos running on the production platform.

## Overview

Apawintment is a production SaaS platform that enables veterinary 
practices to manage their entire booking operation online. Each 
business gets its own branded booking experience, staff management 
system, and client-facing booking page — all running on a shared 
multi-tenant infrastructure.

The platform is live and actively onboarding new clients.

## Key Features

### 📅 Scheduling & Availability
- Real-time appointment booking with automatic conflict prevention
- Multi-staff and multi-location support
- Configurable working hours per staff member and location
- Vacation and time-off management
- Prevents double-bookings across all staff and locations automatically

### 🏢 Business Management
- Full business dashboard for managing staff, services,
  locations, clients, and bookings
- Role-based access control — owners, staff, and admins
  have different permission levels
- Email notifications for bookings, cancellations, and reminders

### 💳 Payments & Retention
- Optional booking fee collection — clients pay a small deposit
  at booking time, significantly reducing no-shows
- Full payment in advance (coming soon)
- Discount codes and promotional offers to drive repeat bookings
- Client loyalty system to reward returning customers

### 🎨 White-Label & Personalized Sales Demo System
- Each business gets a fully branded public booking page with
  their own logo, colors, and custom URL slug
- **Built-in sales tool** — instead of showing prospects a generic
  demo, Apawintment generates a personalized demo link with the
  prospect's own branding, logo, and business name already applied
- The prospect clicks a link and sees what looks like *their own
  product* — dramatically increasing conversion by removing the
  mental gap between "demo" and "real thing"
- Demo pages are generated from the admin dashboard in seconds —
  just enter the business name, logo, colors, and slug, no code required
- The same white-label engine that powers demos powers the live
  product, so onboarding a converted prospect is instant

### 🛡️ Security & Infrastructure
- Secure authentication with protected routes throughout
- Rate limiting on all API endpoints
- Complete data isolation between tenants at the database level
- Input sanitization and validation on all user-facing inputs

### ⚙️ SaaS Admin Dashboard
- Dedicated admin panel for managing the SaaS itself
- Add, configure, and manage veterinary business clients
- Generate and send personalized demo previews to prospects
- Full visibility and control over all businesses on the platform

## Architecture Highlights

**Multi-tenancy** is enforced at the database level — every query
is scoped by tenant ID, ensuring complete data isolation between
businesses sharing the same infrastructure.

**Availability engine** calculates real-time open slots by
cross-referencing staff schedules, existing bookings, service
durations, and location operating hours — preventing conflicts
automatically across all dimensions.

**White-label + personalized demo system** dynamically renders each
business's booking page from their stored branding configuration.
The same engine powers the sales funnel — prospects receive a custom
demo URL showing the product already styled as their own, collapsing
the gap between evaluation and commitment. Converting a demo to a
live account requires no additional setup.

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Next.js, React, TypeScript, Tailwind CSS, shadcn/ui |
| Backend | Next.js API Routes |
| Database | Supabase |
| Auth | Supabase Auth, protected routes, role-based access |
| Payments | Coming soon |
| Deployment | Vercel |

## Live Product

🌐 [apawintment.com](https://apawintment.com)

> The source code for this project is private as it is an active
> commercial product. For technical questions or inquiries,
> feel free to reach out.

## Contact

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white)](https://vukan-vuckovic.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vukanvuckovic)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:vukanvuckovic05@gmail.com)
