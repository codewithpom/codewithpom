<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b0f1a,50:0e7490,100:7c3aed&height=230&section=header&text=Padmashree%20Jha&fontSize=64&fontColor=e6f1ff&fontAlignY=38&desc=full-stack%20builder%20%C2%B7%20open-source%20contributor%20%C2%B7%20quiet%20shipper&descSize=18&descAlignY=60&animation=fadeIn" width="100%" alt="Padmashree Jha banner" />

<div align="center">

<a href="https://github.com/codewithpom">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1100&color=22D3EE&center=true&vCenter=true&width=720&lines=Full-stack+builder+from+India+%F0%9F%87%AE%F0%9F%87%B3;Shipping+TxtUtils+%E2%86%92+txtutils.net;OSS+contributor%3A+Sherlock+%C2%B7+kensaku;Paper-trade+first.+Go+live+only+when+the+data+says+so.;Ship+it.+Break+it.+Fix+it.+Ship+it+again." alt="Typing animation" />
</a>

<br/>

<a href="https://txtutils.net/"><img src="https://img.shields.io/badge/TxtUtils-txtutils.net-0e7490?style=for-the-badge&logo=googlechrome&logoColor=white" alt="TxtUtils" /></a>
<a href="https://twitter.com/padmashreejha"><img src="https://img.shields.io/badge/X-@PadmashreeJha-0b0f1a?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
<a href="https://dev.to/codewithpom"><img src="https://img.shields.io/badge/dev.to-codewithpom-0a0a0a?style=for-the-badge&logo=devdotto&logoColor=white" alt="dev.to" /></a>
<a href="https://www.kaggle.com/padmashreejha"><img src="https://img.shields.io/badge/Kaggle-padmashreejha-20beff?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" /></a>
<a href="mailto:codewithpom@gmail.com"><img src="https://img.shields.io/badge/Mail-codewithpom@gmail.com-7c3aed?style=for-the-badge&logo=gmail&logoColor=white" alt="Mail" /></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=codewithpom&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
<img src="https://img.shields.io/github/followers/codewithpom?style=flat&logo=github&color=7c3aed&label=Followers" alt="Followers" />

</div>

---

## `~/whoami`

```console
padmashree@earth:~$ whoami
padmashree jha — full-stack builder, India

padmashree@earth:~$ cat now.txt
building   : TxtUtils (txtutils.net)  ← the side-hustle that became a product
shipping   : Smriti · CSES-Better · ChessCode · NDPify
researching: weather-market models, options-selling regimes, local-first search
stack      : TypeScript · Next.js · React · Python · Rust (curious) · Firebase · Cloudflare

padmashree@earth:~$ cat principles.txt
1. paper-trade before live-trade
2. fail closed, not open
3. if the backtest looks too good, the backtest is lying
4. free tiers are a design constraint, not an excuse

padmashree@earth:~$ ▌
```

---

## ⚡ What I'm building

| Project | What it is | Stack |
|---|---|---|
| **[TxtUtils](https://txtutils.net/)** | My product: a growing toolbox of text utilities, built as a side-hustle. | Next.js · React |
| **[Smriti](https://github.com/codewithpom/smriti)** · [live](https://smriti-gallery.pages.dev) | Crowd-curated school photo archive that runs entirely on free tiers. Face matching *proposes*, students *confirm*. Firebase Auth + Firestore rules, Cloudflare Pages/KV. | Python · Firebase · Cloudflare |
| **[CSES-Better](https://github.com/codewithpom/cses-better)** · [live](https://cses-better.vercel.app) | High-performance competitive-programming platform and judge for the CSES Problem Set: live submission sync, Monaco IDE, testbench, archive mirror. | TypeScript · Vercel |
| **[ChessCode](https://github.com/codewithpom/chesscode)** | Pipeline that turns a PGN (with variations) into a narrated chess-commentary video. | Python |
| **NDPify** | iOS app, live on the App Store. | Swift |
| **[Prabhananda Cup](https://prabhananda-cup-4th-edition.vercel.app)** | Live football-tournament site with realtime scores on Firebase Realtime DB. | TypeScript · Firebase |

<div align="center">

<a href="https://github.com/codewithpom/smriti"><img height="120" src="https://github-readme-stats-sigma-five.vercel.app/api/pin/?username=codewithpom&repo=smriti&theme=tokyonight&hide_border=true" alt="smriti" /></a>
<a href="https://github.com/codewithpom/cses-better"><img height="120" src="https://github-readme-stats-sigma-five.vercel.app/api/pin/?username=codewithpom&repo=cses-better&theme=tokyonight&hide_border=true" alt="cses-better" /></a>
<br/>
<a href="https://github.com/codewithpom/nifty-straddle-vix-router"><img height="120" src="https://github-readme-stats-sigma-five.vercel.app/api/pin/?username=codewithpom&repo=nifty-straddle-vix-router&theme=tokyonight&hide_border=true" alt="nifty-straddle-vix-router" /></a>
<a href="https://github.com/codewithpom/dev-meme"><img height="120" src="https://github-readme-stats-sigma-five.vercel.app/api/pin/?username=codewithpom&repo=dev-meme&theme=tokyonight&hide_border=true" alt="dev-meme" /></a>

</div>

---

## 🧪 Quant & Bots — research with guardrails

I build trading and prediction-market systems the slow, boring, honest way: **paper first, risk caps always, live only after the evidence clears a gate.** Most of this is private; here is how it works.

### 🌦️ Weather-market bot (paper trading)
Trades Polymarket's daily *"highest temperature"* bucket markets for **London, Seoul, NYC, Beijing and Miami**.

```mermaid
flowchart LR
  A["Open-Meteo ensemble<br/>100+ members<br/>GFS · ECMWF · ICON · GEM"] --> B["Student-t model<br/>σ scales with lead time"]
  B --> C{"Edge filter<br/>cheap-YES leg<br/>filtered-NO leg"}
  C --> D["Risk caps<br/>per-trade · per-city-day<br/>drawdown · Brier breaker"]
  D --> E[("Paper ledger")]
  E --> F{"Live gate<br/>50 trades · 14 days<br/>Brier beats market"}
  F -->|pass| G["Live orders"]
  F -->|fail| H["HALT latch"]
```

- **Model-cycle aware.** Runs 4×/day on GitHub Actions, timed to when NOAA/ECMWF forecasts actually publish, plus a 15-minute intraday position monitor that exits when observed temps breach a bucket.
- **Ground truth = official settlement stations** (ASOS via Iowa Mesonet), not a convenient proxy.
- **Fails closed.** Position, city-day and drawdown caps plus a rolling Brier-score circuit breaker trip a `HALT` latch. Live trading stays locked until paper results beat the market's own calibration.
- **Audits itself.** I diagnose losing trades (tail thickness, same-day blindness to live station maxima) and treat every fix as a hypothesis to paper-test, not a tweak to ship.

### 📈 [NIFTY straddle × VIX router](https://github.com/codewithpom/nifty-straddle-vix-router)
Systematic NIFTY / BANKNIFTY / SENSEX options-selling research: VIX-regime routing, walk-forward validation, and a write-up of **why the in-sample backtest lied**.

### 🎯 Polysniper
Short-timeframe Polymarket crypto bot: Dockerized, scheduled services with a **Telegram Mini App** front end.

---

## 🌍 Open source

| Project | ★ | What I did |
|---|---|---|
| **[sherlock-project/sherlock](https://github.com/sherlock-project/sherlock)** | ![](https://img.shields.io/github/stars/sherlock-project/sherlock?style=flat&color=7c3aed&label=) | Contributor — hunt social accounts by username across networks |
| **[yjid/kensaku](https://github.com/yjid/kensaku)** | ![](https://img.shields.io/github/stars/yjid/kensaku?style=flat&color=7c3aed&label=) | Contributor — local-first Rust search with OCR, semantic search and MCP agent access |
| **[RKMV-CS/drama-soundboard](https://github.com/RKMV-CS/drama-soundboard)** | ![](https://img.shields.io/github/stars/RKMV-CS/drama-soundboard?style=flat&color=7c3aed&label=) | Contributor |
| **[RKMV-CS/Class-X-Farewell](https://github.com/RKMV-CS/Class-X-Farewell)** | ![](https://img.shields.io/github/stars/RKMV-CS/Class-X-Farewell?style=flat&color=7c3aed&label=) | Contributor |

Also on the shelf: [dev-meme](https://github.com/codewithpom/dev-meme) (27★ memes API), Twitter automation bots ([APOD](https://github.com/codewithpom/apod-twitter), [quotes](https://github.com/codewithpom/twitter-motivational-quotes)), [url-expander](https://github.com/codewithpom/url-expander).

---

## 🛠️ Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,vue,nodejs,py,rust,go,swift,firebase,cloudflare,vercel,docker,git,linux&perline=8&theme=dark" alt="Tech stack" />

</div>

---

## 📊 Stats

<div align="center">

<img height="170" src="https://github-readme-stats-sigma-five.vercel.app/api?username=codewithpom&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=codewithpom&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" />

<br/>

<img src="https://streak-stats.demolab.com/?user=codewithpom&theme=tokyonight&hide_border=true" alt="Streak" />

<br/>

<img src="https://raw.githubusercontent.com/codewithpom/codewithpom/output/github-snake-dark.svg" alt="Contribution snake" width="100%" />

</div>

---

<div align="center">

*"If the backtest looks too good, the backtest is lying."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,50:0e7490,100:0b0f1a&height=120&section=footer" width="100%" alt="footer" />

</div>
