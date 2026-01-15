# Eerie Tea E-Commerce Platform

A modern, full-stack e-commerce platform for selling premium tea products online. Built with Next.js 16, TypeScript, and Prisma.

## Overview

Eerie Tea is an e-commerce platform designed specifically for tea enthusiasts, featuring detailed product information, brewing guides, and a seamless shopping experience. The platform enables customers to discover, browse, and purchase high-quality tea products with ease.

## Tech Stack

- **Framework:** Next.js 16.1.1 (App Router)
- **Language:** TypeScript 5.9+
- **Database:** PostgreSQL with Prisma ORM
- **Styling:** Tailwind CSS 4.1+ with shadcn/ui components
- **State Management:** Zustand
- **Forms:** React Hook Form + Zod validation
- **Authentication:** NextAuth.js (Auth.js)
- **Payments:** Stripe
- **Email:** Resend + React Email
- **Hosting:** Vercel + Supabase

## Project Status

**Phase:** Planning & Setup  
**Current Status:** Project documentation and task planning complete

## Project Structure

```
eerie-tea/
├── project_management/     # Project documentation
│   ├── PRD.md              # Product Requirements Document
│   ├── TECH_STACK.md       # Detailed technology stack
│   └── PROJECT_TASKS.md   # Complete task breakdown
└── README.md               # This file
```

## Key Features (Planned)

### MVP (Phase 1)

- Product catalog with filtering and search
- Shopping cart and checkout
- User authentication and accounts
- Order management
- Admin panel for product/order management
- Email notifications

### Enhanced Features (Phase 2)

- Product reviews and ratings
- Subscription system
- Gift features (wrapping, messages, scheduled delivery)
- Advanced search and recommendations

### Advanced Features (Phase 3)

- Loyalty program
- Advanced analytics dashboard
- Shipping integrations

## Getting Started

### Prerequisites

- Node.js 20.9+
- pnpm (recommended) or npm
- PostgreSQL database (or Supabase account)

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd eerie-tea

# Install dependencies
pnpm install

# Set up environment variables
cp .env.example .env.local
# Edit .env.local with your configuration

# Set up database
pnpm prisma migrate dev
pnpm prisma generate
pnpm prisma db seed

# Run development server
pnpm dev
```

Visit [http://localhost:3000](http://localhost:3000) to see the application.

## Documentation

- **[PRD.md](./project_management/PRD.md)** - Complete product requirements and specifications
- **[TECH_STACK.md](./project_management/TECH_STACK.md)** - Detailed technology stack and setup instructions
- **[PROJECT_TASKS.md](./project_management/PROJECT_TASKS.md)** - Comprehensive task breakdown for project management

## Development Phases

- **Phase 1 (MVP):** 8-12 weeks - Core e-commerce functionality
- **Phase 2 (Enhanced):** 6-8 weeks - Reviews, subscriptions, gift features
- **Phase 3 (Advanced):** 8-12 weeks - Loyalty program, analytics, integrations

## License

This is a portfolio project.

## Author

Built as a portfolio project to demonstrate full-stack e-commerce development.

---

**Note:** This project is currently in the planning phase. Development will begin following the task breakdown outlined in `PROJECT_TASKS.md`.
