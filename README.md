# TradingJournal
**A student-built trading journal — clean, fast, and actually affordable.**

> I couldn't justify $30/month for a trading journal as a student, so I spent nights & weekends building my own. Frontend is largely done; backend comes next. Feedback welcome.

---

## Why this exists
I started trading during university and found that pricey journals and clunky spreadsheets slowed me down. Over ~3 years I learned by building — at times with help from AI coding/design assistants for scaffolding, refactors, and iteration. The goal: **a focused journal that helps you improve without blowing profits on tooling**.  
*Note: the product itself does not include AI features (yet).*

---

## Highlights
- **Dashboard at a glance** — balance, win rate, largest win/loss, **P&L distribution**, **cumulative P&L**, streaks, and a trading calendar.
- **Reports suite** — Overall Summary; **Performance** curves; **Analytics** (drawdown, streaks, EV); **Evaluation** (risk-multiple histogram + insights); **Trade Log** (search, filters, **CSV export**); **Trade Statistics**; **Monthly Report** (equity vs volume).
- **Entry flow** — Quick *Simple* mode or a *Detailed* 4-step wizard (market → result → entries/TP/SL → notes).
- **Notes workspace** — daily journal, session recap, goals, trading plans; paste images/screenshots directly.
- **Privacy** — local-first by default; data export built-in.
- **Themes** — Light, Dark, and ✨ **Galaxy**.

---

## Screenshots
> Screenshots coming soon — currently capturing the latest UI across all themes.

### Galaxy theme (core walkthrough)
1. **Dashboard — Overview**  
   `docs/screenshots/galaxy-dashboard-overview.png`
2. **Dashboard — Day details modal**  
   `docs/screenshots/galaxy-dashboard-day-modal.png`
3. **Reports — Overall Summary**  
   `docs/screenshots/galaxy-reports-overall-summary.png`
4. **Reports — Performance**  
   `docs/screenshots/galaxy-reports-performance.png`
5. **Reports — Analytics (overview + key stats)**  
   `docs/screenshots/galaxy-reports-analytics.png`
6. **Reports — Evaluation (Risk Multiple histogram & notes)**  
   `docs/screenshots/galaxy-reports-evaluation.png`
7. **Reports — Trade Log (search • filter • CSV export)**  
   `docs/screenshots/galaxy-reports-trade-log.png`
8. **Reports — Trade Statistics (win rate, PF, averages, risk)**  
   `docs/screenshots/galaxy-reports-trade-statistics.png`
9. **Reports — Monthly Report (equity vs volume)**  
   `docs/screenshots/galaxy-reports-monthly.png`
10. **Dashboard — Yearly summary**  
    `docs/screenshots/galaxy-dashboard-yearly-summary.png`

### Light theme
11. **Dashboard — Overview (light)**  
    `docs/screenshots/light-dashboard-overview.png`

### Dark theme
12. **Dashboard — Overview (dark)**  
    `docs/screenshots/dark-dashboard-overview.png`

### Trade entry (wizard)
13. **Step 1 — Market, symbol, direction, date**  
    `docs/screenshots/new-trade-step1.png`
14. **Step 2 — Result (simple): win/loss, fees, R:R**  
    `docs/screenshots/new-trade-step2-simple.png`
15. **Step 2 — Detailed: entries, TP/SL, exit**  
    `docs/screenshots/new-trade-step2-detailed.png`
16. **Step 3 — Setup, timeframe, duration**  
    `docs/screenshots/new-trade-step3.png`
17. **Step 4 — Journal entry with templates**  
    `docs/screenshots/new-trade-step4-notes.png`

### Notes & Settings
18. **Notes — Workspace (journal, session recap, goals, plans)**  
    `docs/screenshots/notes-workspace.png`
19. **Settings — General (account fields placeholder)**  
    `docs/screenshots/settings-general.png`
20. **Settings — Appearance (Light • Dark • Galaxy)**  
    `docs/screenshots/settings-appearance.png`
21. **Settings — Privacy & Security (export, delete, local-first)**  
    `docs/screenshots/settings-privacy.png`

>  A short GIF walkthrough (`docs/preview.gif`) and pin it to the top of the repo.

---

## Design & Principles
- **Essentials first** — only the metrics and flows that change behavior.
- **Low friction** — quick logging + powerful review.
- **Your data, your rules** — local-first with explicit export; any future cloud sync will be opt-in.
- **Accessible pricing** — students and small accounts shouldn't pay enterprise prices.

---

## Roadmap
**Next up**
- Backend + auth/sessions  
- Enhanced trade data model (sessions/tags) + improved import  
- Analytics v1 (equity curve, drawdown, expectancy, R:R buckets)  
- Review mode (filters, “mistake taxonomy”), export/backup

**Nice-to-have**
- Mobile quick-log  
- Journal prompts & review templates  
- Multi-account/assets  
- Public API for programmatic logging

---

## FAQ

**Does this app use AI?**  
Not yet. I used AI coding/design assistants during development, but the product itself currently has **no AI features**.

**So how was AI used?**  
As a pair-programmer/design helper: generating component scaffolds, refactors, copy tweaks, and UI ideas. All features were implemented and reviewed by me.

**Can I import/export my data?**  
Yes — **import** Excel (.xlsx) and CSV; **export** to Excel (.xlsx) or CSV from the app.

**How is my data handled?**  
Currently, all data is stored locally on your device (no servers, no external sync). You can export your data anytime as backup. If the project proves successful, I plan to offer an **optional** cloud sync. It would be off by default and include export/delete controls.

**Is there a backend?**  
Not yet. The current version is local-first (all data stays on your device). The next major milestone is adding **optional backend + user accounts** for those who want cloud sync and multi-device access.

**Can I try it right now?**  
A public demo/video walkthrough is coming. If you'd like early access, reach out on LinkedIn or email (below).

**Will this be open source?**  
No — this project is not open source.

**What's the pricing going to be?**  
TBD. The goal is student-friendly and meaningfully cheaper than $30/month tools.

**Who is this for?**  
Individual traders who want a clean, fast journal with the essentials, no bloat and a review workflow that actually improves decision-making.

**What browsers/devices are supported?**  
Modern browsers (Chrome, Firefox, Safari, Edge). Mobile-responsive design; a dedicated mobile app is a future consideration.

**Planned AI features:**  
To be announced.

---

## Contact
**Author:** Deborah Boatemaa Aittokallio  
**LinkedIn:** linkedin.com/in/deborah-aittokallio-75b93a199 • **Email:** 

---

## Disclaimer
Nothing here is financial advice. Trade responsibly.
