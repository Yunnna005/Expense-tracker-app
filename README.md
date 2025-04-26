# Expense-tracker-app

## Overview
Expense Tracker is a Blazor-based web app that helps users track their personal finances by linking bank accounts, automatically fetching transaction data, and using AI to categorize expenses. It provides insights, budgeting tools, and real-time notifications to promote smarter financial habits.

## Features

- 🔒 Secure user authentication (Email, Google, GitHub)

- 🏦 Bank account integration via Plaid API

- 📊 Manual and automatic transaction entry

- 🧠 AI-based expense categorization (future: ML.NET, Gemini AI)

- 📈 Dashboard with filters, summaries, and visual spending reports

- 🔔 Recurring payment tracking and budget alerts

- ☁️ Cloud deployment on AWS (EC2 + RDS)

- 📑 Export transaction history (CSV/PDF, planned)

## Tech Stack
- **Frontend:** Blazor, TailwindCSS

- **Backend:** ASP.NET Core Web API, ASP.NET Core Identity

- **Database:** PostgreSQL

- **Cloud Hosting:** AWS EC2, RDS

- **AI:** Gemini AI (future: ML.NET)

- **Notifications:** AWS SNS / SendGrid

- **DevOps:** GitHub Actions (CI/CD), Serilog + Seq (logging)

- **Bank API:** Plaid

- **Testing:** xUnit