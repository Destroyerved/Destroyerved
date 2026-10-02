<!--
  ██╗   ██╗███████╗██████╗     ████████╗███████╗██████╗ ███╗   ███╗
  ██║   ██║██╔════╝██╔══██╗    ╚══██╔══╝██╔════╝██╔══██╗████╗ ████║
  ██║   ██║█████╗  ██║  ██║       ██║   █████╗  ██████╔╝██╔████╔██║
  ╚██╗ ██╔╝██╔══╝  ██║  ██║       ██║   ██╔══╝  ██╔══██╗██║╚██╔╝██║
   ╚████╔╝ ███████╗██████╔╝       ██║   ███████╗██║  ██║██║ ╚═╝ ██║
    ╚═══╝  ╚══════╝╚═════╝        ╚═╝   ╚══════╝╚═╝  ╚═╝╚═╝     ╚═╝
  VED.TERMINAL · @Destroyerved · you found the source. respect.
-->

<p align="center">
  <img src="./assets/hero.svg" width="100%" alt="Ved Sharma — Fintech Developer. Trading-terminal banner with an animated candlestick chart and a scrolling ticker of his stack."/>
</p>

<p align="center">
  <a href="https://vedresume.vercel.app/">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=2600&pause=900&color=FFB000&center=true&vCenter=true&width=720&height=40&lines=%24+.%2Fboot+--user+ved+--mode+fintech;%3E+ledgers+that+balance+%C2%B7+payments+that+land;%3E+now+building%3A+%24PALM+(stealth);%3E+Ahmedabad%2C+IN+%C2%B7+B.Tech+CE+%2728" alt="$ ./boot --user ved --mode fintech"/>
  </a>
</p>

<p align="center">
  <a href="https://vedresume.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-vedresume.vercel.app-FFB000?style=for-the-badge&logo=vercel&logoColor=FFB000&labelColor=0A0E14" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/vedsharma17"><img src="https://img.shields.io/badge/LinkedIn-vedsharma17-FFB000?style=for-the-badge&logo=linkedin&logoColor=FFB000&labelColor=0A0E14" alt="LinkedIn"/></a>
  <a href="mailto:ved.anilsharma@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hi-FFB000?style=for-the-badge&logo=gmail&logoColor=FFB000&labelColor=0A0E14" alt="Email"/></a>
  <br/>
  <a href="https://github.com/Destroyerved?tab=followers"><img src="https://img.shields.io/github/followers/Destroyerved?label=Followers&style=for-the-badge&logo=github&logoColor=00FF9C&labelColor=0A0E14&color=00FF9C" alt="GitHub followers"/></a>
  <img src="https://komarev.com/ghpvc/?username=Destroyerved&label=Profile%20views&color=00FF9C&style=for-the-badge" alt="Profile views"/>
</p>

<img src="./assets/divider.svg" width="100%" alt=""/>

## `00` &nbsp;Know Your Coder

<p align="center">
  <img src="./assets/kyc.svg" width="100%" alt="KYC terminal: Ved Sharma, Fintech Developer. B.Tech Computer Engineering, class of 2028, Ahmedabad / Gandhinagar. Stack: TypeScript, Python, React, Node, SQLite. Building PalmPayment (stealth) and the Inventra ledger. Ops Executive & Recruiter at Persistence, Gaming Head at CSGC."/>
</p>

<img src="./assets/divider.svg" width="100%" alt=""/>

## `01` &nbsp;Flagship Positions

<p align="center">
  <img src="./assets/stealth.svg" width="100%" alt="PalmPayment — payments project in stealth: private repo, in active development. Access restricted."/>
</p>

### 📦 &nbsp;Inventra — ledger-grade inventory system

> Every unit of stock that moves gets written to an **immutable ledger**, the same discipline money needs. Multi-warehouse, role-gated, and auditable end to end.

- 🧾 **Append-only stock ledger** — full audit trail for every receipt, delivery and transfer
- 🔐 **Role-based access** — admin · manager · staff, with JWT sessions and bcrypt-hashed passwords
- 🏬 **Multi-warehouse** — SKUs, barcodes and per-location tracking
- 📈 **KPI dashboards & financial reporting** — low-stock alerts and Recharts visualisations
- 🐳 **Ships as one container** — Express serves the built React SPA; Dockerised for Render

```mermaid
%%{init: {"theme":"base","themeVariables":{"darkMode":true,"background":"#0A0E14","primaryColor":"#0F141C","primaryTextColor":"#E6EDF3","primaryBorderColor":"#FFB000","lineColor":"#00FF9C","secondaryColor":"#0F141C","tertiaryColor":"#0A0E14","clusterBkg":"#0A0E14","clusterBorder":"#30363D","edgeLabelBackground":"#0A0E14"}}}%%
flowchart LR
  subgraph CLIENT["Client · React 19 + Vite"]
    UI["Pages<br/>Zustand · Recharts"] --> APIC["API client"]
  end
  subgraph SERVER["Server · Node + Express"]
    AUTH["Auth<br/>JWT · bcrypt · roles"]
    OPS["Operations<br/>receipts · deliveries · transfers"]
    FIN["Finance<br/>reports · KPIs"]
  end
  APIC -->|"Bearer JWT"| AUTH
  AUTH --> OPS
  AUTH --> FIN
  OPS -->|"append-only"| LEDGER[("Immutable stock ledger<br/>SQLite · better-sqlite3")]
  LEDGER -->|"audit trail"| FIN
```

<p>
  <img src="https://img.shields.io/badge/React%2019-0A0E14?style=flat-square&logo=react&logoColor=FFB000" alt="React 19"/>
  <img src="https://img.shields.io/badge/Express-0A0E14?style=flat-square&logo=express&logoColor=FFB000" alt="Express"/>
  <img src="https://img.shields.io/badge/SQLite-0A0E14?style=flat-square&logo=sqlite&logoColor=FFB000" alt="SQLite"/>
  <img src="https://img.shields.io/badge/Zustand-0A0E14?style=flat-square" alt="Zustand"/>
  <img src="https://img.shields.io/badge/Recharts-0A0E14?style=flat-square" alt="Recharts"/>
  <img src="https://img.shields.io/badge/JWT-0A0E14?style=flat-square&logo=jsonwebtokens&logoColor=FFB000" alt="JWT"/>
  <img src="https://img.shields.io/badge/Docker-0A0E14?style=flat-square&logo=docker&logoColor=FFB000" alt="Docker"/>
  &nbsp;→&nbsp; <a href="https://github.com/Destroyerved/inventra-inventory-system"><b>view repo</b></a>
</p>

<img src="./assets/divider.svg" width="100%" alt=""/>

## `02` &nbsp;Watchlist

| Ticker | Position | Stack | Status |
|:--|:--|:--|:--:|
| `$INVT` | [**Inventra**](https://github.com/Destroyerved/inventra-inventory-system)<br/><sub>Multi-warehouse inventory on an immutable ledger</sub> | `React` `Express` `SQLite` | ![open](https://img.shields.io/badge/%E2%96%B2-OPEN-00FF9C?style=flat-square&labelColor=0A0E14) |
| `$PALM` | **PalmPayment**<br/><sub>Payments — private repo, in active development</sub> | `classified` | ![stealth](https://img.shields.io/badge/%E2%97%8F-STEALTH-FFB000?style=flat-square&labelColor=0A0E14) |
| `$GEOL` | [**GeoPulse LandGov**](https://github.com/Destroyerved/GeoPulse-LandGov)<br/><sub>Detects land encroachment through satellite analysis</sub> | `JavaScript` | ![open](https://img.shields.io/badge/%E2%96%B2-OPEN-00FF9C?style=flat-square&labelColor=0A0E14) |
| `$GEOP` | [**GeoPulse**](https://github.com/Destroyerved/GeoPulse)<br/><sub>Real-time geospatial analytics for location viability</sub> | `JavaScript` | ![open](https://img.shields.io/badge/%E2%96%B2-OPEN-00FF9C?style=flat-square&labelColor=0A0E14) |
| `$WARP` | [**WarPredict**](https://github.com/Destroyerved/WarPredict)<br/><sub>Conflict prediction model</sub> | `Python` | ![open](https://img.shields.io/badge/%E2%96%B2-OPEN-00FF9C?style=flat-square&labelColor=0A0E14) |
| `$LGLR` | [**Legal Redline**](https://github.com/Destroyerved/Legal-Redline-Env)<br/><sub>Python environment for legal-document redlining</sub> | `Python` | ![open](https://img.shields.io/badge/%E2%96%B2-OPEN-00FF9C?style=flat-square&labelColor=0A0E14) |
| `$AGRO` | [**AgroScore**](https://github.com/Destroyerved/AgroScore)<br/><sub>Crop-viability scoring from soil, climate & market data</sub> | `JavaScript` | ![open](https://img.shields.io/badge/%E2%96%B2-OPEN-00FF9C?style=flat-square&labelColor=0A0E14) |
| `$YOJN` | [**Yojana Vahaan**](https://github.com/Destroyerved/Yojana-Vahaan)<br/><sub>Government-scheme discovery by eligibility · IAR Hackathon</sub> | `Hackathon` | ![open](https://img.shields.io/badge/%E2%96%B2-OPEN-00FF9C?style=flat-square&labelColor=0A0E14) |
| `$CNCR` | [**CancerDetect**](https://vedresume.vercel.app/#projects)<br/><sub>Deep-learning cancer-indicator detection with explainable AI</sub> | `Python` `XAI` | ![portfolio](https://img.shields.io/badge/%E2%97%86-PORTFOLIO-8B949E?style=flat-square&labelColor=0A0E14) |

<img src="./assets/divider.svg" width="100%" alt=""/>

## `03` &nbsp;Asset Classes

<table>
  <tr>
    <td><b><code>LANGUAGES</code></b></td>
    <td><img src="https://skillicons.dev/icons?i=ts,js,py,c,cpp,html,css&theme=dark" alt="TypeScript, JavaScript, Python, C, C++, HTML, CSS"/></td>
  </tr>
  <tr>
    <td><b><code>FRONTEND</code></b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=react,vite,tailwind&theme=dark" alt="React, Vite, Tailwind CSS"/><br/>
      <img src="https://img.shields.io/badge/React%20Router-0A0E14?style=flat-square&logo=reactrouter&logoColor=FFB000" alt="React Router"/>
      <img src="https://img.shields.io/badge/Zustand-0A0E14?style=flat-square" alt="Zustand"/>
      <img src="https://img.shields.io/badge/Recharts-0A0E14?style=flat-square" alt="Recharts"/>
      <img src="https://img.shields.io/badge/Motion-0A0E14?style=flat-square&logo=framer&logoColor=FFB000" alt="Motion"/>
    </td>
  </tr>
  <tr>
    <td><b><code>BACKEND &amp; DATA</code></b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=nodejs,express,sqlite&theme=dark" alt="Node.js, Express, SQLite"/><br/>
      <img src="https://img.shields.io/badge/JWT-0A0E14?style=flat-square&logo=jsonwebtokens&logoColor=FFB000" alt="JWT"/>
      <img src="https://img.shields.io/badge/bcrypt-0A0E14?style=flat-square" alt="bcrypt"/>
      <img src="https://img.shields.io/badge/REST%20APIs-0A0E14?style=flat-square" alt="REST APIs"/>
    </td>
  </tr>
  <tr>
    <td><b><code>AI / ML</code></b></td>
    <td>
      <img src="https://img.shields.io/badge/Hugging%20Face-0A0E14?style=flat-square&logo=huggingface&logoColor=FFB000" alt="Hugging Face"/>
      <img src="https://img.shields.io/badge/Deep%20Learning-0A0E14?style=flat-square" alt="Deep Learning"/>
      <img src="https://img.shields.io/badge/Model%20Deployment-0A0E14?style=flat-square" alt="ML model deployment"/>
    </td>
  </tr>
  <tr>
    <td><b><code>SHIP</code></b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=docker,vercel,git,github&theme=dark" alt="Docker, Vercel, Git, GitHub"/><br/>
      <img src="https://img.shields.io/badge/Render-0A0E14?style=flat-square&logo=render&logoColor=FFB000" alt="Render"/>
    </td>
  </tr>
</table>

<img src="./assets/divider.svg" width="100%" alt=""/>

## `04` &nbsp;Market Data

<p align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=Destroyerved&show_icons=true&include_all_commits=true&count_private=true&rank_icon=github&bg_color=0A0E14&title_color=FFB000&icon_color=00FF9C&text_color=C9D1D9&ring_color=FFB000&border_color=1F2937&custom_title=%24VED%20%C2%B7%20Fundamentals" alt="GitHub stats"/>
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Destroyerved&layout=compact&langs_count=8&bg_color=0A0E14&title_color=FFB000&text_color=C9D1D9&border_color=1F2937&custom_title=Portfolio%20Allocation" alt="Top languages"/>
</p>

<p align="center">
  <img height="180" src="https://streak-stats.demolab.com/?user=Destroyerved&background=0A0E14&border=1F2937&stroke=1F2937&ring=FFB000&fire=00FF9C&currStreakNum=E6EDF3&sideNums=E6EDF3&currStreakLabel=FFB000&sideLabels=8B949E&dates=6E7681" alt="Contribution streak"/>
  <img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Destroyerved&theme=github_dark&utcOffset=5.5" alt="Trading hours — commits by hour of day, IST"/>
</p>

<p align="center">
  <sub><code>FUNDAMENTALS</code> · <code>PORTFOLIO ALLOCATION</code> · <code>STREAK</code> · <code>TRADING HOURS (IST)</code> — all live from GitHub</sub>
</p>

<p align="center">
  <img width="100%" src="https://raw.githubusercontent.com/Destroyerved/Destroyerved/output/snake-terminal.svg" alt="Snake eating the contribution grid"/>
</p>

<img src="./assets/divider.svg" width="100%" alt=""/>

## `05` &nbsp;Ledger

| Txn | Entry | Memo |
|:--|:--|:--|
| `#0001` | 🎓 **B.Tech, Computer Engineering** | Class of 2028 |
| `#0002` | 💼 **Operations Executive & Recruiter** · Persistence | Runs hybrid teams across borders and fixes ops problems in real time |
| `#0003` | 🎮 **Gaming Head** · Computer Science & Gaming Club | Leads esports events and digital campaigns |
| `#0004` | 🏁 **9+ projects · 4+ hackathon prototypes** | Payments, ledgers, geospatial, AI |

<p align="right"><code>BALANCE ✓ RECONCILED</code></p>

<img src="./assets/divider.svg" width="100%" alt=""/>

## `06` &nbsp;Open a Position

<p align="center">
  <b>Building something that moves money?</b> Let's talk.
  <br/><br/>
  <a href="https://vedresume.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0A0E14?style=for-the-badge&logo=vercel&logoColor=FFB000" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/vedsharma17"><img src="https://img.shields.io/badge/LinkedIn-0A0E14?style=for-the-badge&logo=linkedin&logoColor=FFB000" alt="LinkedIn"/></a>
  <a href="mailto:ved.anilsharma@gmail.com"><img src="https://img.shields.io/badge/Email-0A0E14?style=for-the-badge&logo=gmail&logoColor=FFB000" alt="Email"/></a>
  <a href="https://github.com/Destroyerved"><img src="https://img.shields.io/badge/GitHub-0A0E14?style=for-the-badge&logo=github&logoColor=FFB000" alt="GitHub"/></a>
</p>

<p align="center">
  <img src="./assets/footer.svg" width="100%" alt="Session closed — thanks for stopping by."/>
</p>
