# 🚀 SaaS MVP Boilerplate

A production-ready **full-stack SaaS boilerplate** with Next.js 14, Stripe billing, authentication, multi-tenancy, and REST API. Launch your SaaS in weeks, not months.

> Built by [Viprasol Tech](https://viprasol.com) — custom SaaS development for startups and scaleups.

---

## Stack

| Layer | Tech |
|-------|------|
| Frontend | Next.js 14 (App Router) + TypeScript |
| Styling | Tailwind CSS + shadcn/ui |
| Auth | NextAuth.js (OAuth + email/password) |
| Database | PostgreSQL + Prisma ORM |
| Billing | Stripe (subscriptions + usage-based) |
| Email | Resend |
| Deploy | Vercel + Supabase |

---

## Features

- ✅ **Auth** — sign up, login, OAuth (Google/GitHub), email verification
- ✅ **Multi-tenancy** — org workspaces with roles (owner/admin/member)
- ✅ **Stripe billing** — plans, metering, upgrade/downgrade, webhooks
- ✅ **Dashboard UI** — pre-built admin layout with sidebar
- ✅ **REST API** — versioned with API key management
- ✅ **Emails** — welcome, invite, billing transactional emails
- ✅ **Dark mode** — system-aware theming
- ✅ **Analytics** — Posthog integration

---

## Quick Start

```bash
git clone https://github.com/Viprasol/saas-mvp-boilerplate
npm install && cp .env.example .env
npx prisma migrate dev
npm run dev
```

---

## Need Your SaaS Built?

This boilerplate is a free resource from [Viprasol Tech](https://viprasol.com).

We build **complete SaaS products**:
- Full product development (frontend + backend + infra)
- Payment and subscription systems
- Multi-tenant architecture
- SaaS MVP in 8 weeks

👉 **[Build Your SaaS →](https://viprasol.com/services/saas-development)**

---

MIT License
