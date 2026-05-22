Kampala School & Academy Management Portal

A zero-infrastructure, single-page web app for managing local Ugandan private schools and skills academies. Runs 100% offline in the browser after first load — no servers, no databases, no third-party auth.

✨ Features

🎓 Student Directory with admission numbers, Uganda-aware class levels (Pre-Primary → A Level)
📚 Academic Performance with auto-grading (UCE D1–F9, UACE A–F, primary tiers) + Division calculator
💰 Fees & Payments with bursary-aware balances and live ledger
⚽ Sports & Academy Programs with schedules, coaches, and school requirements
🏃 Attendance per program session (present/absent toggle)
🏆 Sports Bursary auto-eligibility (skill + attendance + evaluations)
📊 Statistical Reports by level, class, sport, and finance
⚖️ Discipline & Conduct log with severity badges
📲 SMS Reminders for guardians (uses native sms: deep-links — no API needed)
🖨️ Printable Report Cards combining academics + sports + fees + conduct
💾 Export / Import Ledger as a single JSON file for offline backup
📱 Mobile-first responsive UI · 🌐 Tailwind via CDN (zero build step)

🚀 Deploy to GitHub Pages

Create a new GitHub repository (e.g. school-portal).
Upload index.html (and optionally this README.md) to the root of the repo.
Go to Settings → Pages.
Under Build and deployment, set:
Source: Deploy from a branch
Branch: main · / (root)
Save. After ~1 minute your portal is live at:
https://<your-github-username>.github.io/school-portal/

💾 Data & Backups

All data lives in the browser's localStorage (private to that device + browser).
Click ⬇ Export Ledger regularly to download a JSON backup.
Click ⬆ Import Ledger to restore from a backup file (works across devices).
Use Reset All Data in the Administration tab to wipe everything (export first!).
🇺🇬 Uganda Curriculum Built-In
Level	Classes	Grading
Pre-Primary	Baby, Middle, Top	—
Primary	P.1 – P.7	Distinction / Credit / Pass / Fail
O Level (UCE)	S.1 – S.4	D1, D2, C3–C6, P7–P8, F9 → Division I–IV
A Level (UACE)	S.5 – S.6	A (6) – F (0), points-based

📜 License

MIT — free to fork, modify, and deploy for any Ugandan school or academy.
