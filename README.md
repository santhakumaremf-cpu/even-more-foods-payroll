# Even More Foods - Payroll & Attendance System

Web conversion of the Excel payroll workbook (July 2026) for **Even More Foods Private Limited**, Kuruvala, Namagiripet, Rasipuram.

## Features

| Feature | Description |
|---------|-------------|
| **Formulas & Conditions** | All business rules from Excel (PF ceiling ₹15,000, ESI 0.75%, OT, LOP, Basic/HRA/SPL split) |
| **Salary Calculator** | Interactive Net Salary calculation with EPF/ESI/OT/Night incentive/Advance/Food |
| **Attendance Entry** | Day 1–31 hours entry, auto Present/LOP/Paid Days |
| **Employee Master** | 90 employees from Excel Master sheet (search & filter) |
| **Payslip Generator** | Generate & print/PDF payslip per employee |
| **PF / ESI Calculator** | Statutory contribution calculator + EPFO column structure |
| **Production Roadmap** | 5-phase plan to build full backend system |

## How to use

1. Open `payroll-complete.html` in any modern browser (Chrome / Edge / Firefox).
2. No server required — pure HTML + CSS + JavaScript.

## Files

- `payroll-complete.html` — Full system (recommended)
- `payroll-system.html` — Earlier version (docs + calculator + sample data)

## Source

Converted from Excel file: `July'26 (2).xlsm` (50 sheets: Master, daily attendance 1–31, Worker Wages, OT, PF, ESI, Payslip, etc.)

## Tech

Single-page HTML app. For production backend: see **Production Plan** tab inside the app (FastAPI + PostgreSQL + React suggested).
