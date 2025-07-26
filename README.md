# Track iT - Personal Finance Tracker

> A Learning & Practice Project
> ⚠️ This project is based on the template by [@piyush-eon](https://github.com/piyush-eon). I've modified this and learnt from his tutorial and made few UI changes.


## 🎯 Project Overview

Track iT is a comprehensive personal finance management application that I developed as a learning project by following tutorials and implementing modern web development practices. This project demonstrates my skills in full-stack development, database design, and user experience creation.

## 📚 Learning Journey

This project was built as part of my web development learning journey, where I followed tutorials and expanded upon them to create a fully functional finance tracking application. It showcases my ability to:

- Follow complex technical tutorials
- Implement and customize existing solutions
- Add personal touches and improvements
- Debug and troubleshoot real-world issues

## 🛠️ Tech Stack

### Frontend
- **Next.js 15** - React Framework
- **Tailwind CSS** - Styling & UI Components
- **React Hook Form** - Form Management
- **Recharts** - Data Visualization
- **Lucide React** - Icons

### Backend
- **Next.js API Routes** - Server-side Logic
- **Prisma ORM** - Database Management
- **PostgreSQL** - Database
- **Supabase** - Database Hosting

### Authentication & Security
- **Clerk** - User Authentication
- **Arcjet** - Security & Rate Limiting

### Additional Services
- **Google Generative AI** - AI-powered Insights
- **Resend** - Email Services
- **Inngest** - Background Job Processing

## ✨ Features

### Core Functionality
- 🔐 **User Authentication** - Secure sign-up and login
- 🏦 **Multi-Account Management** - Handle checking and savings accounts
- 💰 **Transaction Tracking** - Categorize and monitor expenses
- 📊 **Budget Management** - Create and monitor spending limits
- 🎯 **Financial Goals** - Set and track savings objectives
- 🤖 **AI Insights** - Get personalized spending analysis

### Make sure to create a `.env` file with following variables -

```
DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

RESEND_API_KEY=

ARCJET_KEY=
```
