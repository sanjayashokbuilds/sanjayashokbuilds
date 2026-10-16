<h1 align="center">I'm Sanjay</h1>

<p align="center">Economics student at UCL who likes building things that solve real problems.</p>

<p align="center">
  <img src="https://img.shields.io/badge/UCL-BSc%20Economics-0d1117?style=for-the-badge&labelColor=d4a33a" alt="UCL, BSc Economics">
  <img src="https://img.shields.io/badge/24h%20builds-3%20shipped-0d1117?style=for-the-badge&labelColor=d4a33a" alt="24-hour builds: 3 shipped">
  <img src="https://img.shields.io/badge/Building-in%20public-0d1117?style=for-the-badge&labelColor=d4a33a" alt="Building in public">
</p>

This GitHub is where I build in public. Everything I make goes here, so you can see what I'm building and how my skills are progressing over time.

---

## ⏱️ 24-hour builds

Right now I'm doing a series of 24-hour builds: picking a real problem, building a working solution from scratch in 24 hours, and shipping it. The goal is to get faster, sharper and more efficient every time.

| # | Project | Problem it solves | Link |
|:-:|---|---|:-:|
| 1 | **Life-hours** | Students can't see what spending really costs them. Life-hours prices every choice in hours of your life (time spent + money ÷ your hourly rate), tracks which ones you regret, and logs Apple Pay payments automatically. | [Live app](https://life-hours.netlify.app) · [Code](https://github.com/sanjayashokbuilds/invisible-costs) |
| 2 | **Chola-dates** | Medieval Chola temple inscriptions date themselves by the sun, moon and stars instead of a calendar year, and many were carved with mistakes. I built an astronomical solver on the Swiss Ephemeris, a machine-readable dataset of 24 inscriptions, and a Bayesian model that infers King Kulottunga III's accession date (**6 July 1178**) while jointly estimating which inscriptions were miscarved. It reproduces all 14 dates a leading 1900s epigraphist judged correct and all 5 of his error diagnoses, and shows 4 of his "errors" follow a recording convention (Bayes factor ≈ 10⁶). 53 automated tests. | [Live app](CHOLA_LIVE_URL) · [Code](https://github.com/sanjayashokbuilds/chola-dates) |
| 3 | **Chit-options** | A seat in a Tamil chit fund is a one-time right to take the pot at an auction-set price, so I priced it as an American option. I value it with backward-induction dynamic programming and Longstaff–Schwartz least-squares Monte Carlo (cross-validated to Monte Carlo error, and against brute force over all 1,024 strategies), solve the symmetric Nash equilibrium of the bidding game by damped best-response iteration (unique from three starts, zero deviation gain), and derive an exact implied-rate term structure from a Markov chain on members in need. Calibrated to Tamil Nadu chit-company bid data, it reproduces implied rates (14.5% a year, inside the reported 14–24%) and an early-to-mid rate hump peaking 40% through tenure, and reports where it fails (the 1993 bid cap). Ships a playable chit against equilibrium bidders and a hidden-Markov bidding calculator running Python in the browser via Pyodide. 45 automated tests. | [Live app](https://chit-options.netlify.app) · [Code](https://github.com/sanjayashokbuilds/chit-options) |

**Stack so far:** Python · NumPy · pandas · pytest · Bayesian inference · Dynamic programming · Monte Carlo (Longstaff–Schwartz) · Game theory · Swiss Ephemeris · Streamlit · Plotly · Pyodide · JavaScript · Netlify · GitHub Actions

---

## 📫 Reach me

- **Email:** [thesgaprotocol@gmail.com](mailto:thesgaprotocol@gmail.com)
- **LinkedIn:** [linkedin.com/in/sanjay-ashok-57451b313](https://www.linkedin.com/in/sanjay-ashok-57451b313)
- **X:** [@thesgaprotocol1](https://x.com/thesgaprotocol1)
