# Nour Energy Data

An internal HR data management web app for Nour Energy — built as a single-page application hosted on GitHub Pages.

## Features

- 🔐 Password-protected login (Admin & Employee access levels)
- 👤 Employee profile cards with full details
- 📋 Smart Lists — filter by active/ended, nationality, job title, location, age
- 🔍 Deep Search — search across all fields instantly
- 🟢 Document alerts — Iqama, Passport, and Qiwa expiry tracking
- 🖨️ Print-ready employee cards (A4 optimized)
- ➕ Admin: Add / Update employee records directly from the app

## Access Levels

| Level | Features |
|---|---|
| Employee | Search, view profile cards, print |
| Admin | All above + Smart Lists, Deep Search, Add/Update records, Salary details |

## Tech Stack

- Pure HTML / CSS / JavaScript — no frameworks
- Google Sheets as database (via Sheets API v4)
- Google Apps Script for write operations
- Hosted on GitHub Pages (free)

## Security

- Passwords stored as SHA-256 hashes — no plain text in code
- Google API key restricted to this domain only
- Role-based access control (Admin vs Employee)

## Maintained by

Qasim — Nour Energy
