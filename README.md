# Remodeling Job Tracker (MVP)

A lightweight Streamlit app for small remodeling contractors to track **projects, tasks, and expenses** with basic **receipt uploads** and **CSV export** for bookkeeping.

## Features
- Projects: client, address, dates, status, notes
- Tasks: status, due date, assignee, hours est/spent
- Expenses: category, vendor, amount, payment method, receipt upload (stored locally)
- Reports: per-project totals, CSV export for QuickBooks/spreadsheets
- Local SQLite DB at `./data/app.db`

## Quick Start
```bash
pip install -r requirements.txt
streamlit run app.py
```
The app will open in your browser. Your data and uploads live in `./data/`.

## Tips
- Make expense **categories** match your Chart of Accounts (you can edit in `app.py`).
- Use CSV exports for simple import/mapping into QuickBooks.
- Back up the `data/` folder to save everything.
