# TradingJournal [Info currently being updated!]
**A student-built trading journal — clean, fast, and actually affordable.**

> I couldn't justify $30/month for a trading journal as a student, so I spent nights & weekends building my own. Frontend is largely done; backend comes next. Feedback welcome.

---

## Why this exists
I started trading during university and found that pricey journals and clunky spreadsheets slowed me down. Over ~3 years I learned by building, at times with help from AI coding/design assistants for scaffolding, refactors, and iteration. The goal: **a focused journal that helps you improve without blowing profits on tooling**.  
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
> Screenshots — currently capturing the latest UI across all themes - Note: All values in the screenshots are generated demo data.

### Galaxy theme (core walkthrough)
1. **Dashboard — Overview**  
  
   ![](Screenshots/1.png)
   
3. **Dashboard — Trading Calander Day details modal** 
  
    ![](Screenshots/3.png)
     
5. **Reports — Overall Summary**  
   
    ![](Screenshots/4.png)
      
7. **Reports — Performance**  
   
      ![](Screenshots/5.png)
   
9. **Reports — Analytics (overview + key stats)**  
   
   
    ![](Screenshots/6.png)
11. **Reports — Evaluation (Risk Multiple histogram & notes)**  
   
   
    ![](Screenshots/7.png)
13. **Reports — Trade Log (search • filter • CSV export)**  
   
     ![](Screenshots/8.png)
       
15. **Reports — Trade Statistics (win rate, PF, averages, risk)**  
   
  
    ![](Screenshots/9.png)
17. **Reports — Monthly Report (equity vs volume)**  
    
    
     ![](Screenshots/10.png)
19. **Dashboard — Yearly summary**  
    
    ![](Screenshots/2.png)
   

### Light theme
11. **Dashboard — Overview (light)**  
    
      ![](Screenshots/20Light.png)


### Dark theme
12. **Dashboard — Overview (dark)**  
    
      ![](Screenshots/21Dark.png)

### Trade entry (wizard)
13. **Step 1 — Market, symbol, direction, date**  
   
      ![](Screenshots/15.png)

15. **Step 2 — Result (simple): win/loss, fees, R:R**  
    
    ![](Screenshots/17.png)
    
17. **Step 2 — Detailed: entries, TP/SL, exit**
    
      ![](Screenshots/16.png)
        
19. **Step 3 — Setup, timeframe, duration**  
    
     ![](Screenshots/18.png)
   
21. **Step 4 — Journal entry with templates**  
    ![](Screenshots/19.png)

### Notes & Settings
18. **Notes — Workspace (journal, session recap, goals, plans)**
    
     ![](Screenshots/11.png)
    
20. **Settings — General (account fields placeholder)**  
    
     ![](Screenshots/12.png)
 
22. **Settings — Appearance (Light • Dark • Galaxy)**  
    
     ![](Screenshots/13.png)
      
24. **Settings — Privacy & Security (export, delete, local-first)**  
   
   
    ![](Screenshots/14.png)
   

>  A short GIF walkthrough (`docs/preview.gif`) and reminder for myself pin it to the top of the repo.

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
- Enhanced trade data model (sessions/tags) 

**Nice-to-have**
- Mobile quick-log  
- Journal prompts & review templates  
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
**LinkedIn:** linkedin.com/in/deborah-aittokallio-75b93a199 • **Email:** debstradingjournal@gmail.com

---

## Disclaimer
Nothing here is financial advice. Trade responsibly.
