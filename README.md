<img src="assets/banner.svg" alt="Anannya Salvi" width="100%" />

# Anannya Salvi

<a href="https://github.com/anannyasalvi16">
  <img src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=11&pause=1200&color=3DAE72&center=true&vCenter=true&width=700&height=40&lines=aspiring+data+analyst+%C2%B7+fintech+enthusiast;i+build+things+people+actually+use;numbers+right+to+the+last+paisa;open+to+swe+%2F+pm+%2F+data+internships" alt="Typing SVG" />
</a>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-2A2B2D?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anannya-salvi-a317623ab/)
[![GitHub](https://img.shields.io/badge/GitHub-2A2B2D?style=flat-square&logo=github&logoColor=white)](https://github.com/anannyasalvi16)
[![TripTabTally](https://img.shields.io/badge/TripTabTally-live-3DAE72?style=flat-square&logo=vercel&logoColor=white)](https://triptabtally.vercel.app)
[![SIP Reality Check](https://img.shields.io/badge/SIP_Reality_Check-live-E0709F?style=flat-square&logo=streamlit&logoColor=white)](https://siprealitycheck.streamlit.app)
[![Stock Sentiment](https://img.shields.io/badge/Stock_Sentiment-live-2A2B2D?style=flat-square&logo=streamlit&logoColor=white)](https://anannya-7efnjoycasbyhuwdafentm.streamlit.app/)

```
currently: shipping small, tested tools where the maths has to be right
```

## what's going on

- Shipped [**TripTabTally**](https://triptabtally.vercel.app), a group trip budget and expense-splitting app, used by 18 people across 4 completed trips
- Shipped [**SIP Reality Check**](https://siprealitycheck.streamlit.app), which tells you whether your mutual fund SIPs actually beat a plain Nifty 50 index fund
- Shipped [**Stock Sentiment Analyzer**](https://anannya-7efnjoycasbyhuwdafentm.streamlit.app/), live news sentiment for any ticker
- Vice Chairperson of the ACM SIGITE student chapter at TCET
- Looking for internships in software, product and data analysis

## featured work

### [TripTabTally](https://triptabtally.vercel.app) · [repo](https://github.com/anannyasalvi16/TripTabTally)

*Group trips, settled to the last paisa.*

A budget, expense ledger and settle-up app for friends and families travelling together. Money is stored as integer paise, so nothing is ever lost to rounding.

[![Next.js](https://img.shields.io/badge/Next.js-2A2B2D?style=flat-square&logo=nextdotjs&logoColor=white)](https://nextjs.org) [![TypeScript](https://img.shields.io/badge/TypeScript-2A2B2D?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org) [![Supabase](https://img.shields.io/badge/Supabase-3DAE72?style=flat-square&logo=supabase&logoColor=white)](https://supabase.com) [![Tailwind](https://img.shields.io/badge/Tailwind-2A2B2D?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)

- Five split modes: equal, exact, percentage (Largest Remainder Method), shares and family
- Greedy debt simplification clears any group in at most `k - 1` transfers, with UPI deep links to pay instantly
- Zero-sum balance invariant enforced across the app and checked by property-based tests
- Supabase Postgres with Row Level Security, strict security headers and open-redirect protection
- 77 Vitest tests and 72 Playwright end-to-end tests, including accessibility audits

```
split 1,000.01 across 3  ->  333.34 + 333.34 + 333.33    # always sums back to the paisa
```

### [SIP Reality Check](https://siprealitycheck.streamlit.app) · [repo](https://github.com/anannyasalvi16/sip_reality_check)

*Did your SIPs beat the index? Now you know.*

A Streamlit app that takes your mutual fund statement and measures your real returns against a Nifty 50 index fund bought on the same dates.

[![Python](https://img.shields.io/badge/Python-2A2B2D?style=flat-square&logo=python&logoColor=white)](https://www.python.org) [![Streamlit](https://img.shields.io/badge/Streamlit-E0709F?style=flat-square&logo=streamlit&logoColor=white)](https://streamlit.io) [![SciPy](https://img.shields.io/badge/SciPy-2A2B2D?style=flat-square&logo=scipy&logoColor=white)](https://scipy.org) [![Plotly](https://img.shields.io/badge/Plotly-2A2B2D?style=flat-square&logo=plotly&logoColor=white)](https://plotly.com)

- True XIRR across every cash flow date, solved with Brent's method
- Same-dates benchmark: your exact amounts, your exact dates, invested in a Nifty 50 index fund instead
- Live NAV data from the AMFI API
- Statements are processed in memory and never stored
- Core logic split from the UI, 40 pytest tests, anonymous usage analytics

```
upload statement  ->  XIRR  vs  same-dates Nifty 50 benchmark
```

### [Stock Sentiment Analyzer](https://anannya-7efnjoycasbyhuwdafentm.streamlit.app/) · [repo](https://github.com/anannyasalvi16/Stock-Sentiment-Analyzer)

*The market's mood, from the headlines.*

Type a ticker and get a Bullish, Bearish or Neutral verdict from live news.

[![Python](https://img.shields.io/badge/Python-2A2B2D?style=flat-square&logo=python&logoColor=white)](https://www.python.org) [![Pandas](https://img.shields.io/badge/Pandas-2A2B2D?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org) [![Plotly](https://img.shields.io/badge/Plotly-3DAE72?style=flat-square&logo=plotly&logoColor=white)](https://plotly.com)

- Pulls up to 15 live headlines per ticker with `yfinance`
- Scores each headline with NLTK VADER and charts the distribution and trend in Plotly
- Sortable table of every headline, source and score

## activity

<div align="center">

<img src="https://streak-stats.demolab.com/?user=anannyasalvi16&background=131415&ring=7EE0A4&fire=F2A7C3&currStreakNum=ECECEA&sideNums=A8A8A5&currStreakLabel=7EE0A4&sideLabels=8A8A87&dates=8A8A87&hide_border=true&border_radius=0" alt="GitHub streak" />

<img height="150" src="https://github-readme-stats.vercel.app/api?username=anannyasalvi16&show_icons=true&hide_border=true&border_radius=0&bg_color=131415&title_color=7EE0A4&text_color=C9C9C6&icon_color=F2A7C3" alt="GitHub stats" />
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=anannyasalvi16&layout=compact&hide_border=true&border_radius=0&bg_color=131415&title_color=7EE0A4&text_color=C9C9C6" alt="Top languages" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/anannyasalvi16/anannyasalvi16/output/github-snake-dark.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/anannyasalvi16/anannyasalvi16/output/github-snake.svg" />
</picture>

[![tech icons](https://skillicons.dev/icons?i=py,ts,nextjs,supabase,postgres,tailwind,vercel,git,pandas&theme=dark)](https://skillicons.dev)

</div>

## highlights

- **Vice Chairperson, ACM SIGITE, TCET.** Runs chapter events and handles PR for 9 events and games at Zephyr, the college's biggest fest
- **B.E. Information Technology** · Mumbai University, TCET

*Mumbai · open to opportunities*
