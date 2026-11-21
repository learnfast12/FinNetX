# FinNetX — Frontend Prototype

A static, client-side prototype for an adaptive personal finance coach.

## Run locally

Open `index.html` in a modern browser. No build step or package installation is required.

## Deploy to Vercel

### Option A — GitHub (recommended)
1. Create a GitHub repository named `finnetx`.
2. Upload `index.html`, `vercel.json`, and this README to the repository root.
3. Sign in at https://vercel.com and choose **Add New → Project**.
4. Import the `finnetx` GitHub repository.
5. Keep the framework preset as **Other**.
6. Leave Build Command and Output Directory empty (or use `.` as the output directory if prompted).
7. Click **Deploy**.

### Option B — Vercel CLI
Install the Vercel CLI, then run from this folder:

```bash
vercel
```

Follow the prompts. For a production deployment:

```bash
vercel --prod
```

## What is implemented

- Responsive dashboard and navigation
- Sample cash-flow analytics and goal progress
- Transaction ledger with category correction flow
- User-approved merchant categorization rules in browser storage
- Interactive what-if goal simulator
- Recurring payment review screen
- Insights and printable review
- Rule-based conversational coach demo
- CSV import and basic transaction SMS parsing
- Profile controls and demo reset

## Important prototype boundaries

- This is a **frontend-only prototype**. It has no backend, authentication, database, live bank connection, or external AI model.
- Demo transactions and corrections are stored in the browser's `localStorage` on that device/browser.
- Dashboard figures are illustrative synthetic sample data. Do not enter real banking credentials, OTPs, or sensitive financial information.
- PDF statement extraction and live SMS/bank integrations are not implemented.
- The money coach is rule-based demonstration logic, not a live AI financial adviser.
- FinNetX is for educational budgeting support and does not recommend specific securities or investment products.
