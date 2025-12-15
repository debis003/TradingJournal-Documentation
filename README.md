# TradingJournal
**A student-built trading journal — clean, fast, and actually affordable.**

> I couldn't justify $30/month for a trading journal as a student, so I spent nights & weekends building my own. Now available as a native desktop app. Feedback welcome.

---

## Why this exists
I started trading during university and found that pricey journals and clunky spreadsheets slowed me down. Over ~3 years I learned by building, at times with help from AI coding/design assistants for scaffolding, refactors, and iteration. The goal: **a focused journal that helps you improve without blowing profits on tooling**.  
*Note: the product itself does not include AI features (yet).*

---

## App Walkthrough

> All screenshots use demo data. Replace screenshot paths with your actual filenames.

### Dashboard

![Dashboard](screenshots/dashboard.png)

Your trading command center. Everything you need at a glance:

**Today's Overview (always visible):**
- **Account Balance** — Editable balance with starting balance and total P&L
- **Today's P&L** — Daily profit/loss with trade count
- **Win Rate** — Percentage with wins out of total trades
- **Largest Win/Loss** — Best and worst trades with symbols

**Performance Overview (with time filter: 1D/7D/30D/):**
- **P&L Distribution** — Weekly bar chart showing profit/loss breakdown
- **Cumulative P&L** — Equity curve tracking your growth over time

**Customizable Widgets (click Edit to choose):**
- **Trade Expectancy** — Average expected profit per trade
- **Win Streak** — Current streak with best streak and last win
- **Trade & Loss Limits** — Daily loss limit and max trades tracker
- **Risk/Reward Ratio** — Average R:R across trades
- **Goal Progress** — Daily/weekly/monthly goal tracking
- **Profit Factor** — Gross profit vs gross loss ratio

**Trading Calendar:**
- **Monthly View** — Color-coded days showing daily P&L
- **Daily Details** — P&L amount, R:R, number of trades, time in market
- **Weekly Summaries** — Total P&L, trade count, win rate per week




### Reports

Deep dive into your performance across three tabs:

| Performance | Analytics | Trade Log |
|-------------|-----------|-----------|
| ![Performance](screenshots/reports-performance.png) | ![Analytics](screenshots/reports-analytics.png) | ![Trade Log](screenshots/reports-tradelog.png) |

#### Performance Tab
- **Period Comparison** — Compare months side-by-side (Net P&L, Trades, Win Rate, Avg Win/Loss, Profit Factor)
- **Growth Trend** — Monthly profit/loss bar chart for the year
- **Performance Curve** — Balance line with 20 MA, zoom controls, daily/weekly/monthly view
- **Session Performance** — Breakdown by trading session (New York, London, Asian, Overlap, Off-hours) with P&L, win rate, profit factor
- **Asset Distribution** — Donut chart showing symbol breakdown with trade counts and P&L

#### Analytics Tab
- **Analytics Overview** — Max Drawdown, Consecutive Wins/Losses, Avg Trade Duration, Max Consecutive Profit/Loss
- **Risk-Multiple** — Ave. Win (R), Ave. Loss (R), R.Mul Ratio, Expectancy
- **Risk-Multiple Evaluation** — Histogram showing distribution of R-multiples with insights
- **Setup Win% vs. Reward-Risk Ratio** — Bar chart comparing win rate across different setups

#### Trade Log Tab
- **Searchable Table** — Filter by symbol, type, date range
- **Columns** — Date, Symbol, Type (BUY/SELL), Entry, Exit, R:R, P&L
- **Pagination** — Navigate through all trades
- **Export** — Download as CSV or Excel

---

### Journal

![Journal](screenshots/journal.png)

Your private trading notebook with full organization and rich editing:

**Sidebar Navigation:**
- **Year Navigation** — Browse notes by year with quick navigation arrows
- **New Folder** — Create custom folders for any category
- **Search Notes** — Find any note instantly
- **Quick Actions** — Home, undo, redo, edit mode toggle

**Default Folders:**
- **Trade Notes** — Document individual trade analysis
- **Daily Journal** — Record daily observations and mindset
- **Sessions Recap** — Review trading session performance
- **Goals** — Set and track trading goals
- **Trading Plans** — Outline your strategies and rules

**Rich Text Editor:**
- **Full Formatting** — Bold, Italic, Underline, Strikethrough, Code
- **Headings** — H1, H2, H3 for structure
- **Lists** — Bullet, numbered, and checklists
- **Blocks** — Blockquote, code blocks, horizontal rules
- **Alignment** — Left, center, right, justify
- **Media** — Paste images/screenshots directly (TradingView compatible)
- **Tables** — Create data tables inline
- **Links** — Add hyperlinks to resources
- **Undo/Redo** — Full history navigation

**Media & Content Management:**
- **Image Adjustments** — Click any image to resize, align, or adjust
- **Drag & Drop Reorder** — Toggle drag handles to move text blocks and images up/down
- **Inline Editing** — Edit content directly without switching modes

**Tags System:**
- Create custom tags for categorization
- Filter notes by tags

---



Log trades your way with Simple or Detailed mode:

| Step 1 - Trade Info | Step 2 - Results | Step 3 - Context | Step 4 - Journal |
|---------------------|------------------|------------------|------------------|
| ![Step 1](screenshots/trade-entry-step1.png) | ![Step 2](screenshots/trade-entry-step2.png) | ![Step 3](screenshots/trade-entry-step3.png) | ![Step 4](screenshots/trade-entry-step4.png) |

**Simple Mode** — Quick entry when you just need the basics

**Detailed Mode** — 4-step wizard for complete documentation:

**Step 1 — Trade Info:**
- Market selection (Forex, Stocks, Crypto, etc.)
- Symbol (e.g., AAPL, EURUSD)
- Direction (Buy/Sell)
- Date and Entry/Exit Time with timezone
- Trading Session (Auto-detect or manual)

**Step 2 — Results:**
- *Simple*: Trade Result (Win/Loss), Amount, Fee, Risk:Reward
- *Detailed*: Entry Price, Quantity, Fee, Take Profit, Stop Loss, Exit Price, Risk:Reward

**Step 3 — Context:**
- Setup selection (from your saved setups)
- Time Frame (preset or custom like "3h, 2d, 45m")
- Trade Duration (preset or custom)

**Step 4 — Journal:**
- Font selection for your notes
- Rich text editor with full formatting
- Auto-saves to Trade Notes in Journal
- Save as Draft or Save Trade

---

### Settings

Customize your experience across three tabs:

| General | Appearance | Privacy & Security |
|---------|------------|-------------------|
| ![General](screenshots/settings-general.png) | ![Appearance](screenshots/settings-appearance.png) | ![Privacy](screenshots/settings-privacy.png) |

#### General Tab
- **Username** — Set your display name
- **Email** — Your contact email
- **Timezone** — Configure for accurate session tracking (Asian, London, NY sessions)
- **Account Access** — Login/Sign In for cloud sync and premium features (coming soon)

#### Appearance Tab
- **Theme Selection** — Choose between Light, Dark, and Galaxy themes
- Visual theme cards for easy switching

#### Privacy & Security Tab
- **Password Security** — Change your password
- **Data Management** — Export your data or delete all data
- **Privacy Note** — Your data is stored locally. No data is sent to external servers unless you explicitly choose to sync with cloud services.

---

### Themes

| Light | Dark | Galaxy |
|-------|------|--------|
| ![Light](screenshots/theme-light.png) | ![Dark](screenshots/theme-dark.png) | ![Galaxy](screenshots/theme-galaxy.png) |

---

### Desktop App

![Desktop App](screenshots/desktop-app.png)

Native Windows application with:
- Custom frameless title bar
- Minimize, maximize, close controls
- Lightweight Tauri build (~15MB)
- Runs offline, no browser needed

---

## Tech Stack
- **Framework**: Next.js 15 (App Router)
- **Desktop**: Tauri 2.x (Rust-based, lightweight)
- **Styling**: Tailwind CSS + shadcn/ui
- **Charts**: Recharts + Chart.js
- **Rich Text**: TipTap
- **Storage**: localStorage (offline-first)

---

## Design Principles
- **Essentials first** — only the metrics and flows that change behavior
- **Low friction** — quick logging + powerful review
- **Your data, your rules** — local-first with explicit export; any future cloud sync will be opt-in
- **Accessible pricing** — students and small accounts shouldn't pay enterprise prices

---

## Roadmap

**Completed**
- Desktop app build (Tauri/.exe)
- Custom frameless title bar
- Three themes (Light, Dark, Galaxy)
- Responsive UI (mobile/tablet/desktop)

**Next up**
- Backend + auth/sessions
- Enhanced trade data model (sessions/tags)
- Multi-device deployment (web access for mobile, desktop, tablet)
- Cloud sync (opt-in)

**Nice-to-have**
- Real broker connection (auto-import trades)

---

## FAQ

**Does this app use AI?**  
Not yet. I used AI coding/design assistants during development, but the product itself currently has no AI features.

**Can I import/export my data?**  
Yes — import Excel (.xlsx) and CSV; export to Excel (.xlsx) or CSV from the app.

**How is my data handled?**  
All data is stored locally on your device. No servers, no external sync. Export your data anytime as backup.

**Can I try it right now?**  
The desktop app (.exe) is in beta testing. Reach out if you'd like early access.

**What platforms are supported?**  
Windows desktop app (.exe) available now. Mac/Linux builds possible. Web version works in modern browsers.

**What's the pricing going to be?**  
TBD. Goal is student-friendly and meaningfully cheaper than $30/month tools.

---

## Contact
**Author:** Deborah Boatemaa Aittokallio  
**LinkedIn:** linkedin.com/in/deborah-aittokallio-75b93a199  
**Email:** debstradingjournal@gmail.com

---

## Disclaimer
Nothing here is financial advice. Trade responsibly.
