# Finance-App-AGL

A modern law firm invoice and payment management platform.  
This app provides both a **Partner Portal** for self-billing transparency and a comprehensive **Finance Team Portal** for automated invoice creation, validation, and payment workflows.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Directory & Pages](#directory--pages)
- [User Roles](#user-roles)
- [How It Works](#how-it-works)
- [Getting Started](#getting-started)
- [Tech Stack](#tech-stack)
- [Contact](#contact)

---

## Overview

Finance-App-AGL helps law firms and their partners automate self-billing, monitor payments, and streamline the finance workflow with role-based dashboards.

- **Partners** can view, download, and track all their self-billed invoices and payment history.
- **Finance Teams** can upload fee allocation reports, review/validate splits, generate invoices, manage pay runs, and handle data management in one place.

---

## Features

### Partner Portal
- View all self-billed invoices in one dashboard
- See status, amount owed, splits, and payment dates
- Drill into invoice detail modals for full fee breakdowns
- Access pay run history with downloadable statements

### Finance Team Portal
- Upload and process fee allocation reports (e.g., from Clio)
- Review, edit, and validate partner splits/commissions
- Generate and batch-send self-billed invoices (PDF)
- Manage partner data, introducers, and custom splits
- Schedule pay runs, mark invoices as paid, and audit all actions

---

## Directory & Pages

- `Partner Page - Main home page`  
  > Partner dashboard for current invoices

- `Partner page - Pay run History`  
  > Partner view of past payments and pay runs

_All other pages are for **Finance Team** only:_

- `Fee Allocation Page`  
  > Upload and review fee allocation reports

- `Generate Invoices`  
  > Batch invoice creation, review, and PDF export

- `Send to Partners`  
  > Manage invoice distribution and approval status

- `Pay Run Scheduler`  
  > Schedule pay runs, mark as paid, and track status

- `Data Management Page`  
  > Manage partners, introducers, custom splits, and audit logs

---

## User Roles

- **Partner**  
  > Access: Main dashboard and pay run history only

- **Finance**  
  > Access: All pages for allocation, invoice gen, data management, pay run scheduling, and admin/audit

---

## How It Works

1. **Finance Team** uploads a fee allocation report (Excel/CSV).
2. Review, correct, and validate partner splits and commission logic.
3. Generate self-billed invoices in batch (PDFs).
4. Send invoices to the relevant partners.
5. Partners view and download invoices, check payment status and pay run history.
6. Finance schedules pay runs, marks as paid, and manages records.

---

## Getting Started

1. Clone the repo and install dependencies:
2. Configure environment variables as needed.
3. Start frontend and backend servers.
4. Login as either **Partner** or **Finance Team** to access the appropriate dashboard.

---

## Tech Stack

- **Frontend:** React 18, TypeScript, TailwindCSS, Material-UI, React Query
- **Backend:** Node.js, Express, PostgreSQL, Sequelize, Puppeteer (PDF generation)
- **Auth & Security:** JWT, role-based access, secure storage
- **Deployment:** Azure App Service, Static Web Apps

