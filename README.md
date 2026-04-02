# InOut Daily Expenses 🚀

<div align="center">
<img src="https://raw.githubusercontent.com/SumOne-Builds/inout-daily-expenses/main/public/logo.png" width="120" alt="InOut Logo"/>
<br><br>
</div>

[![React](https://img.shields.io/badge/React-19.0.0-blue)](https://react.dev/) [![Vite](https://img.shields.io/badge/Vite-6-green)](https://vite.dev/) [![Tailwind](https://img.shields.io/badge/Tailwind-4-purple)](https://tailwindcss.com/)

## 📊 Modern Daily Ledger App

**Pure React 19 (JSX) + Vite 6 + Tailwind CSS 4** - Track income/expenses across multiple accounts with **Firebase Auth** and **Google Drive backups** (appDataFolder).

### ✨ Key Features
<table>
<tr><td width="50%">
<ul>
<li><b>Multi-Account Ledger</b>: Savings + Daily Expense accounts</li>
<li><b>Inline Editable Table</b>: Date/In/Out/Remark (real-time)</li>
<li><b>Totals Dashboard</b>: Received/Spent/Balance</li>
<li><b>Google Sign-in</b>: Secure auth</li>
<li><b>Drive Sync</b>: Auto/manual backups</li>
</ul>
</td><td width="50%">
<ul>
<li><b>LocalStorage Fallback</b>: Offline persistence</li>
<li><b>Responsive UI</b>: Mobile-first design</li>
<li><b>Logo Click → Home</b>: Reset navigation</li>
<li><b>Fast Vite HMR</b>: Instant reloads</li>
<li><b>Pure JS</b>: No TypeScript</li>
</ul></td></tr>
</table>

## 🎮 Live Demo
```
npm install && npm run dev
→ http://localhost:3000
```

![Screenshot Dashboard](https://via.placeholder.com/800x400/1e293b/ffffff?text=InOut+Dashboard)
![Screenshot Ledger Table](https://via.placeholder.com/800x400/0f766e/ffffff?text=Transaction+Table)

## 🚀 Quick Start
```bash
git clone https://github.com/SumOne-Builds/inout-daily-expenses
cd inout-daily-expenses  
npm install
npm run dev      # Development
npm run build    # Production
```

## 📂 Structure
```
src/
├── components/     # Sidebar, Dashboard, LedgerTable, Modal, SummaryBox
├── lib/DriveSync.js # Drive API
├── firebase.js      # Auth config
├── App.jsx         # Orchestrator
└── main.jsx        # Entry
```

## 🛠 Tech Stack
| Framework | Styling | State | Backend |
|-----------|---------|-------|---------|
| React 19 | Tailwind 4 | useState/useEffect | Firebase 12 |
| Vite 6 | lucide-react icons | localStorage | Google Drive API |

## 🤝 Team Development
[team-task.md](team-task.md) - 4 developers rebuild in 4 hours!

## 📝 Setup Notes
- Firebase: Replace config in `firebase.js`
- Drive: Google auth scopes auto-added
- Env: `.env` for GEMINI_API_KEY (optional)

## 🔮 Roadmap
- PWA support
- Charts & reports
- Multi-currency
- Data export (PDF/CSV)

---

<div align="center">
Built with ❤️ for daily finance tracking
<br><br>
⭐ &nbsp; 🐦 Share &nbsp; 👨‍💻 PRs Welcome!
</div>

**License**: MIT

