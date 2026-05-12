# TradingJournal
**A student-built trading journal — clean, fast, and actually affordable.**

> Most trading journals cost $30+/month or lock you into clunky spreadsheets. This one is built for traders who'd rather spend on the markets than on tooling.

## Why this exists

I started trading during university and found that pricey journals and clunky spreadsheets slowed me down. Over ~3 years I learned by building, at times with help from AI coding/design assistants for scaffolding, refactors, and iteration. The goal: **a focused journal that helps you improve without blowing profits on tooling**.
*Note: the product itself does not include AI features (yet).*

---

## Live Demo

**[Try the interactive demo](https://trading-journal-eta-lilac.vercel.app)** — loaded with sample data, fully interactive. No sign-up required.

---

## Features

- **Performance Analytics** — Win rate, profit factor, expectancy, and more
- **Trade Calendar** — Visual daily P&L heatmap with trade details
- **Rich Journal** — Full editor with images, tables, and slash commands
- **Risk Metrics** — R-multiple distribution and expectancy tracking
- **Psychology Scoring** — Track fear, greed, confidence across every trade
- **100% Offline** — Your data never leaves your machine

---

## Tech Stack

- **Framework**: Next.js (App Router)
- **Desktop**: Tauri 2.x (Rust-based, lightweight)
- **Styling**: Tailwind CSS + shadcn/ui
- **Charts**: Recharts
- **Rich Text**: TipTap
- **Storage**: IndexedDB (offline-first)

---

## Design Principles

- **Essentials first** — only the metrics and flows that change behavior
- **Low friction** — quick logging + powerful review
- **Your data, your rules** — local-first with explicit export; any future cloud sync will be opt-in
- **Accessible pricing** — students and small accounts shouldn't pay enterprise prices

---

## Roadmap

**Completed**
- Interactive demo deployed at [trading-journal-eta-lilac.vercel.app](https://trading-journal-eta-lilac.vercel.app)
- Desktop app build (Tauri/.exe)
- Three themes (Light, Dark, Galaxy)
- Rich text journal with drag-and-drop, slash commands, image float
- Full reports suite (Performance, Analytics, Trade Log)
- Psychology scoring per trade
- CSV/Excel import and export

**Next up**
- Backend + auth/sessions
- Multi-device deployment (web, mobile, desktop)
- Cloud sync (opt-in)

**Nice-to-have**
- Real broker connection (auto-import trades)

---

## Previous Documentation

The [`2025-12/`](2025-12/) folder contains the original app walkthrough with screenshots from December 2025 — kept here to show how the project has evolved.

---

## Contact

**Author:** Deborah Boatemaa Aittokallio
**GitHub:** [github.com/debis003](https://github.com/debis003)
**LinkedIn:** [linkedin.com/in/deborah-aittokallio-75b93a199](https://linkedin.com/in/deborah-aittokallio-75b93a199)
**Email:** debstradingjournal@gmail.com

---

## Disclaimer

Nothing here is financial advice. Trade responsibly.

This project is actively under development — features and UI may change.
