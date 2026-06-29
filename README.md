# TurfZone - Replit Hosting Configuration 🏟_

This repository contains the environment configurations and build setup for **TurfZone**—a full-stack sports facility booking platform. It acts as the Replit container configuration to host the backend and frontend components smoothly.

## 🏗️ System Overview
TurfZone allows users to register, log in, browse, and book slots on sports courts (Cricket, Football, Badminton, Snooker, Pickleball).

## 🛠️ Stack & Settings
- **Frontend Framework**: React 18, Vite, TypeScript, Tailwind CSS
- **Backend Framework**: Express.js (TypeScript)
- **Database Dialect**: PostgreSQL managed with Drizzle ORM
- **Hosting Target**: Replit + Vercel deployment configurations

## 📁 Key Files
- `package.json` / `package-lock.json`: Project dependencies and dev-server scripts (`npm run dev`).
- `.replit` / `replit.md`: replit-specific startup configurations and project instructions.
- `drizzle.config.ts` / `tailwind.config.ts`: Configuration scripts for ORM and styles.
- `vercel.json` / `vite.config.ts`: Configuration setup for Vercel functions and Vite server bundle.

## 🚀 Local Run
1. Ensure Node.js and PostgreSQL are installed.
2. Install npm packages:
   ```bash
   npm install
   ```
3. Set environment variable `DATABASE_URL` in your workspace.
4. Run:
   ```bash
   npm run dev
   ```

---
Developed by [bharathkumar7733](https://github.com/bharathkumar7733)
