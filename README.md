# PayRight – Cloud HR Payroll System

A secure, compliant, and automated payroll management system for Philippine businesses.

✅ **Features**  
- User authentication (HR & Admin roles)  
- Employee & company management  
- Automated payroll processing (SSS, PhilHealth, Pag-IBIG, BIR tax)  
- PDF/Excel report generation (BIR Form 1601-C, DOLE reports)  
- GCash/Maya payouts via PayMongo  
- Data Privacy Act (RA 10173) compliant  

## 🚀 Quick Start

### Prerequisites
- Node.js v18+
- PostgreSQL
- PayMongo account (for payouts)

### Setup
1. Clone repo
2. `cd server && cp .env.example .env` → fill credentials
3. `npm install && npx prisma migrate dev`
4. `cd ../client && npm install`
5. `npm run dev` (runs both frontend & backend)

## 🌐 Deployment
- Frontend: Vercel
- Backend: Render
- Database: Neon.tech (free Postgres)

---
Built with ❤️ for Philippine HR teams.
