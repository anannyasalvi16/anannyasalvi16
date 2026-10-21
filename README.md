<div align="center">

<img src="assets/banner.svg" alt="pixel banner" width="100%" />

<a href="https://github.com/anannyasalvi16">
  <img src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=15&duration=2800&pause=900&color=B8A1E3&center=true&vCenter=true&width=760&height=60&lines=HI+%7C+I'M+ANANNYA+SALVI;ASPIRING+DATA+ANALYST;FINTECH+ENTHUSIAST;I+BUILD+THINGS+PEOPLE+ACTUALLY+USE;OPEN+TO+SWE+%2F+PM+%2F+DATA+INTERNSHIPS" alt="typing animation" />
</a>

<br/>

<img src="https://img.shields.io/badge/STATUS-OPEN_TO_INTERNSHIPS-B5EAD7?style=flat-square&labelColor=2B2640" />
<img src="https://img.shields.io/badge/ROLES-SWE_%7C_PM_%7C_DATA-FFCBA4?style=flat-square&labelColor=2B2640" />
<img src="https://img.shields.io/badge/BASE-MUMBAI,_INDIA-C8B6FF?style=flat-square&labelColor=2B2640" />

</div>

<img src="assets/divider.svg" width="100%" />

## 👾 PLAYER 1

```text
NAME     : Anannya Salvi
CLASS    : B.E. Information Technology @ TCET, Mumbai
SIDE QUEST: Vice Chairperson, ACM SIGITE TCET
MAIN QUEST: Ship products with real users, real tests, real math
LOOKING  : Internships in software, product and data analysis
```

I like projects where **numbers have to be right**: XIRR for mutual funds, paise-exact expense splits, sentiment scores on live news. Every project below is deployed, tested, and built to be used by someone other than me.

<img src="assets/divider.svg" width="100%" />

## 🕹️ LEVELS (PROJECTS)

### LEVEL 1: [TripTabTally](https://github.com/anannyasalvi16/TripTabTally) &nbsp;`BOSS LEVEL`

> Group trip budget, expense ledger and debt settlement for friends travelling together.

[![Live](https://img.shields.io/badge/PLAY-triptabtally.vercel.app-B5EAD7?style=flat-square&labelColor=2B2640)](https://triptabtally.vercel.app)
![Users](https://img.shields.io/badge/ACTIVE_USERS-18_ACROSS_4_TRIPS-FFCBA4?style=flat-square&labelColor=2B2640)

- **Money engine in integer paise**, no floating point. Four split modes: equal, exact, percentage (Largest Remainder Method) and shares.
- **Greedy debt simplification** settles any group in at most `k - 1` transfers, with **UPI deep links** for instant payment.
- **Zero-sum invariant** checked with property-based tests: **77 Vitest tests** and **72 Playwright e2e tests** including Axe accessibility audits.
- **Supabase Postgres with Row Level Security** on all 8 tables, strict security headers, open-redirect protection, deployed on Vercel in Mumbai.

![Next.js](https://img.shields.io/badge/Next.js-C8B6FF?style=flat-square&logo=nextdotjs&logoColor=2B2640&labelColor=2B2640)
![TypeScript](https://img.shields.io/badge/TypeScript-FFCBA4?style=flat-square&logo=typescript&logoColor=2B2640&labelColor=2B2640)
![Supabase](https://img.shields.io/badge/Supabase-B5EAD7?style=flat-square&logo=supabase&logoColor=2B2640&labelColor=2B2640)
![Tailwind](https://img.shields.io/badge/Tailwind-C8B6FF?style=flat-square&logo=tailwindcss&logoColor=2B2640&labelColor=2B2640)

<br/>

### LEVEL 2: [SIP Reality Check](https://github.com/anannyasalvi16/sip_reality_check) &nbsp;`FINTECH`

> Did your mutual fund SIPs really beat a plain Nifty 50 index fund? Upload a statement and find out.

- **True XIRR** using Brent's root-finding (`scipy.optimize.brentq`) across every cash flow date.
- **Same-dates benchmark**: invests your exact amounts on your exact dates into a Nifty 50 index fund for a fair comparison.
- **Live NAV data** from the AMFI API with fund-name matching and caching.
- **Privacy first**: statements are processed in memory and never stored.
- Clean `core/` module split from the UI, **40 pytest tests**, anonymous usage analytics with Supabase.

![Python](https://img.shields.io/badge/Python-FFCBA4?style=flat-square&logo=python&logoColor=2B2640&labelColor=2B2640)
![Streamlit](https://img.shields.io/badge/Streamlit-B5EAD7?style=flat-square&logo=streamlit&logoColor=2B2640&labelColor=2B2640)
![SciPy](https://img.shields.io/badge/SciPy-C8B6FF?style=flat-square&logo=scipy&logoColor=2B2640&labelColor=2B2640)
![Plotly](https://img.shields.io/badge/Plotly-FFCBA4?style=flat-square&logo=plotly&logoColor=2B2640&labelColor=2B2640)

<br/>

### LEVEL 3: [Stock Sentiment Analyzer](https://github.com/anannyasalvi16/Stock-Sentiment-Analyzer) &nbsp;`NLP`

> Type a ticker, get the market mood from live news headlines.

[![Live](https://img.shields.io/badge/PLAY-Streamlit_Cloud-B5EAD7?style=flat-square&labelColor=2B2640)](https://anannya-7efnjoycasbyhuwdafentm.streamlit.app/)

- Pulls up to 15 live headlines per ticker with `yfinance` and scores each with **NLTK VADER**.
- Returns a **Bullish / Bearish / Neutral** verdict, a sentiment distribution chart and a time-series scatter in **Plotly**.
- Sortable table of every headline, source and score.

![Python](https://img.shields.io/badge/Python-FFCBA4?style=flat-square&logo=python&logoColor=2B2640&labelColor=2B2640)
![Pandas](https://img.shields.io/badge/Pandas-C8B6FF?style=flat-square&logo=pandas&logoColor=2B2640&labelColor=2B2640)
![NLTK](https://img.shields.io/badge/NLTK_VADER-B5EAD7?style=flat-square&labelColor=2B2640)

<img src="assets/divider.svg" width="100%" />

## 🎒 INVENTORY (TECH STACK)

![Python](https://img.shields.io/badge/Python-FFCBA4?style=flat-square&logo=python&logoColor=2B2640&labelColor=2B2640)
![TypeScript](https://img.shields.io/badge/TypeScript-C8B6FF?style=flat-square&logo=typescript&logoColor=2B2640&labelColor=2B2640)
![SQL](https://img.shields.io/badge/PostgreSQL-B5EAD7?style=flat-square&logo=postgresql&logoColor=2B2640&labelColor=2B2640)
![Next.js](https://img.shields.io/badge/Next.js-FFCBA4?style=flat-square&logo=nextdotjs&logoColor=2B2640&labelColor=2B2640)
![Streamlit](https://img.shields.io/badge/Streamlit-C8B6FF?style=flat-square&logo=streamlit&logoColor=2B2640&labelColor=2B2640)
![Supabase](https://img.shields.io/badge/Supabase-B5EAD7?style=flat-square&logo=supabase&logoColor=2B2640&labelColor=2B2640)
![Pandas](https://img.shields.io/badge/Pandas-FFCBA4?style=flat-square&logo=pandas&logoColor=2B2640&labelColor=2B2640)
![SciPy](https://img.shields.io/badge/SciPy-C8B6FF?style=flat-square&logo=scipy&logoColor=2B2640&labelColor=2B2640)
![Plotly](https://img.shields.io/badge/Plotly-B5EAD7?style=flat-square&logo=plotly&logoColor=2B2640&labelColor=2B2640)
![Tailwind](https://img.shields.io/badge/Tailwind-FFCBA4?style=flat-square&logo=tailwindcss&logoColor=2B2640&labelColor=2B2640)
![Vercel](https://img.shields.io/badge/Vercel-C8B6FF?style=flat-square&logo=vercel&logoColor=2B2640&labelColor=2B2640)
![Vitest](https://img.shields.io/badge/Vitest-B5EAD7?style=flat-square&logo=vitest&logoColor=2B2640&labelColor=2B2640)
![Playwright](https://img.shields.io/badge/Playwright-FFCBA4?style=flat-square&logo=playwright&logoColor=2B2640&labelColor=2B2640)
![Pytest](https://img.shields.io/badge/Pytest-C8B6FF?style=flat-square&logo=pytest&logoColor=2B2640&labelColor=2B2640)
![Git](https://img.shields.io/badge/Git-B5EAD7?style=flat-square&logo=git&logoColor=2B2640&labelColor=2B2640)

<img src="assets/divider.svg" width="100%" />

## 🏆 SCOREBOARD

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=anannyasalvi16&show_icons=true&hide_border=true&border_radius=0&bg_color=2B2640&title_color=C8B6FF&text_color=EDE7FF&icon_color=FFCBA4&ring_color=B5EAD7" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=anannyasalvi16&layout=compact&hide_border=true&border_radius=0&bg_color=2B2640&title_color=C8B6FF&text_color=EDE7FF" alt="Top languages" />

<br/>

<img src="https://streak-stats.demolab.com/?user=anannyasalvi16&hide_border=true&border_radius=0&background=2B2640&ring=B5EAD7&fire=FFCBA4&currStreakNum=C8B6FF&sideNums=EDE7FF&currStreakLabel=B5EAD7&sideLabels=C8B6FF&dates=FFCBA4" alt="GitHub streak" />

</div>

<img src="assets/divider.svg" width="100%" />

## 🐍 SNAKE.EXE

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/anannyasalvi16/anannyasalvi16/output/github-snake-dark.svg" />
  <img alt="pixel snake eating contributions" src="https://raw.githubusercontent.com/anannyasalvi16/anannyasalvi16/output/github-snake.svg" />
</picture>

</div>

<img src="assets/divider.svg" width="100%" />

## 💌 PRESS START TO CONTACT

<div align="center">

<a href="https://www.linkedin.com/in/anannya-salvi-a317623ab/"><img src="https://img.shields.io/badge/LINKEDIN-C8B6FF?style=for-the-badge&logo=linkedin&logoColor=2B2640&labelColor=2B2640" /></a>
<a href="https://github.com/anannyasalvi16"><img src="https://img.shields.io/badge/GITHUB-FFCBA4?style=for-the-badge&logo=github&logoColor=2B2640&labelColor=2B2640" /></a>
<a href="https://triptabtally.vercel.app"><img src="https://img.shields.io/badge/TRIPTABTALLY-B5EAD7?style=for-the-badge&logoColor=2B2640&labelColor=2B2640" /></a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=11&duration=3000&pause=1500&color=FFCBA4&center=true&vCenter=true&width=620&height=40&lines=THANKS+FOR+PLAYING;INSERT+COIN+TO+COLLABORATE" alt="footer typing" />

</div>
