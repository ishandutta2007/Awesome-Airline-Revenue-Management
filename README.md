# ✈️ Awesome Airline Revenue Management

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Airline Revenue Management Banner" width="100%"/>
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Airline-Revenue-Management/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Airline-Revenue-Management?style=social&color=white" alt="Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Airline-Revenue-Management/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Airline-Revenue-Management?style=social&color=white" alt="Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Airline-Revenue-Management/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

## 📊 Top Airline Revenue Management Ecosystem & Software Guide

**A Curated Directory of Enterprise SaaS Platforms & Open-Source GitHub Projects for Airline Revenue Optimization**  

*Keywords: Yield Management, Dynamic Pricing, EMSR (Expected Marginal Seat Revenue), Leg & Origin-Destination (O&D) Revenue Optimization, Airline Inventory Control, Ancillary Revenue, Demand Forecasting, Continuous Pricing, Passenger Service System (PSS) Integration.*

📅 **Last updated: September 2026**

---

### 💡 Overview & Key Industry Insights

This repository tracks notable **SaaS platforms**, **commercial software suites**, and **open-source repositories** dedicated to **Airline Revenue Management (RM)**. Modern airline RM systems leverage AI/ML demand forecasting, dynamic pricing algorithms, overbooking models, and customer choice models to maximize seat yield and network profitability.

**Leading SaaS platforms** include PROS Revenue Management, Amadeus RM, Sabre AirVision Revenue Optimizer, Fetcherr, FLYR Labs, RateGain AirGain, Datalex, and Lufthansa Systems NetLine/ProfitLine.

**Open-source emphasis**: While production airline inventory control requires commercial GDS/PSS integrations, open-source projects provide research-grade algorithms, discrete-event simulation engines (**RMOL**, **stdair**), and academic dynamic pricing frameworks (**Seatwise**, **Google OR-Tools**).

---

## 📑 Table of Contents
- [💼 SaaS & Enterprise Hosted Platforms](#-saas--enterprise-hosted-platforms)
- [🔓 Open-Source GitHub Repositories & Libraries](#-open-source-github-repositories--libraries)
- [🛠️ Key Frameworks for Building Custom RM Systems](#%EF%B8%8F-key-frameworks-for-building-custom-rm-systems)
- [🤝 How to Contribute](#-how-to-contribute)
- [📜 Disclaimer](#-disclaimer)
- [💖 Support & Sponsorship](#-support--sponsorship)
- [📈 Star History](#-star-history)

---

## 💼 SaaS & Enterprise Hosted Platforms

The **Airline Revenue Management SaaS market** is estimated at **$12.47 Billion (2025)** and projected to reach **$43.20 Billion by 2034** (CAGR of ~14.8%). The market is **moderately fragmented**, comprising dominant legacy Global Distribution System (GDS) titans (Amadeus, Sabre), specialized enterprise RM software vendors (PROS, Lufthansa Systems), and fast-growing AI-native continuous pricing startups (FLYR, Fetcherr, RateGain).

| SaaS Platform | Description | Pricing (Starting Tier) | Free Tier / Trial Limit | Company Size (Valuation / Annual Revenue) |
| :--- | :--- | :--- | :--- | :--- |
| 🏷️ **[Amadeus Revenue Management](https://amadeus.com/)** | GDS-linked airline RM suite for inventory control, forecasting, and network optimization. | Enterprise annual contract starting at ~$100,000/yr (varies by carrier ASM/passenger volume) | No free tier or trial; demo available upon sales consultation | **€6.5B Revenue** (~$7.1B / Public: AMS) |
| 🚀 **[Sabre AirVision Revenue Optimizer](https://www.sabre.com/)** | Real-time network revenue management and decision-support system. | Enterprise annual license starting at ~$85,000/yr (tiered by flight network capacity) | No free tier or trial; customized interactive demo upon request | **$2.77B Revenue** (~$940M Market Cap: SABR) |
| 🎯 **[PROS Revenue Management](https://pros.com/)** | AI-powered enterprise RM and dynamic offer optimization platform. | Enterprise annual subscription starting at ~$50,000/yr (scaled by transaction volume) | No free tier or trial; custom proof-of-concept demo on request | **$1.4B Valuation** (~$330.4M Revenue / Private: Thoma Bravo) |
| ⚡ **[FLYR Labs (Cirrus)](https://flyr.com/)** | AI-native revenue operating system for continuous pricing and forecasting. | Enterprise annual software contract starting at ~$30,000/yr (or ~$700/mo base for regional/hospitality modules) | No free tier; 14-to-30 day customized pilot/sandbox on enterprise agreement | **$800M Valuation** (Over $500M total VC raised) |
| 🌐 **[Lufthansa Systems (NetLine/ProfitLine)](https://www.lhsystems.com/)** | Integrated airline operations, scheduling, and revenue optimization suite. | Enterprise modular software licensing starting at ~$40,000/yr | No free tier or trial; guided product demonstration for airlines | **~$600M Revenue** (Wholly-owned subsidiary of Lufthansa Group) |
| 📊 **[RateGain (AirGain)](https://rategain.com/)** | Real-time airfare intelligence and competitive price tracking platform. | SaaS subscription starting at ~$1,500/mo (~$18,000/yr depending on route coverage) | 14-day limited feature free trial / sample data test account | **~$117M Revenue** (INR 9,809 Cr Market Cap: RATEGAIN) |
| 🤖 **[Fetcherr](https://www.fetcherr.com/)** | Generative AI-driven real-time pricing and inventory engine. | Enterprise SaaS model starting at ~$25,000/yr (tiered by seat capacity) | No free tier or trial; tailored live demo available upon request | **~$152M Total Funding** (Series C funded startup) |
| 🛒 **[Datalex](https://www.datalex.com/)** | Digital retailing and offer/order management for airline revenue optimization. | Enterprise software & transaction fee model starting at ~$20,000/yr | No free tier or trial; enterprise demonstration on request | **$32.8M Revenue** (Delisted to private entity) |

---

## 🔓 Open-Source GitHub Repositories & Libraries

Below is a curated collection of open-source projects, optimization solvers, and simulation environments used by researchers, data scientists, and aviation analysts for airline revenue management and yield optimization.

*Repositories are sorted in descending order by GitHub Stars_Count.*

| Repository / Project | Stars_Badge | Description | Primary Tech Stack |
| :--- | :---: | :--- | :--- |
| 🧮 **[Google OR-Tools](https://github.com/google/or-tools)** | [<img src="https://img.shields.io/github/stars/google/or-tools?style=social&color=white" alt="google/or-tools Stars"/>](https://github.com/google/or-tools/stargazers) | General-purpose optimization solver suite frequently used to implement custom EMSR, leg-based allocation, and network LP models. | C++, Python, Java, C# |
| 📐 **[SDDmiP](https://github.com/akulbansal5/SDDmiP)** | [<img src="https://img.shields.io/github/stars/akulbansal5/SDDmiP?style=social&color=white" alt="akulbansal5/SDDmiP Stars"/>](https://github.com/akulbansal5/SDDmiP/stargazers) | Multistage stochastic mixed-integer programming solver package featuring a dedicated benchmark implementation for Airline Revenue Management (ARM). | Julia, C++ |
| 🔬 **[RMOL (Revenue Management Open Library)](https://github.com/airsim/rmol)** | [<img src="https://img.shields.io/github/stars/airsim/rmol?style=social&color=white" alt="airsim/rmol Stars"/>](https://github.com/airsim/rmol/stargazers) | C++ simulation library for airline yield management—part of the Travel Market Simulator (`airsim`) research stack. | C++, CMake |
| 🛠️ **[stdair](https://github.com/airsim/stdair)** | [<img src="https://img.shields.io/github/stars/airsim/stdair?style=social&color=white" alt="airsim/stdair Stars"/>](https://github.com/airsim/stdair/stargazers) | Standard C++ library providing baseline structures for airline scheduling, inventory management, and revenue analytics. | C++ |
| ✈️ **[tvlsim](https://github.com/airsim/tvlsim)** | [<img src="https://img.shields.io/github/stars/airsim/tvlsim?style=social&color=white" alt="airsim/tvlsim Stars"/>](https://github.com/airsim/tvlsim/stargazers) | Travel Market Simulator library simulating passenger booking behavior, demand arrival processes, and fare queries. | C++ |
| 📦 **[airinv](https://github.com/airsim/airinv)** | [<img src="https://img.shields.io/github/stars/airsim/airinv?style=social&color=white" alt="airsim/airinv Stars"/>](https://github.com/airsim/airinv/stargazers) | Airline inventory management simulator library for leg-level bucket control and fare class availability queries. | C++ |
| 💡 **[Seatwise RM System](https://github.com/ahmetgokbulut/seatwise)** | [<img src="https://img.shields.io/github/stars/ahmetgokbulut/seatwise?style=social&color=white" alt="ahmetgokbulut/seatwise Stars"/>](https://github.com/ahmetgokbulut/seatwise/stargazers) | Dynamic airfare RM system combining TFT/XGBoost demand forecasting, sentiment pricing, and Monte-Carlo simulation vs EMSR-b. | Python, PyTorch |
| 🎮 **[rm-game Simulator](https://github.com/nickpaa/rm-game)** | [<img src="https://img.shields.io/github/stars/nickpaa/rm-game?style=social&color=white" alt="nickpaa/rm-game Stars"/>](https://github.com/nickpaa/rm-game/stargazers) | Interactive simulation game for educational hands-on training in airline capacity allocation and pricing policies. | JavaScript, HTML5 |
| 📓 **[Airline Revenue Optimization Notebooks](https://github.com/Payal3214/Airline-Revenue-Optimization)** | [<img src="https://img.shields.io/github/stars/Payal3214/Airline-Revenue-Optimization?style=social&color=white" alt="Payal3214/Airline-Revenue-Optimization Stars"/>](https://github.com/Payal3214/Airline-Revenue-Optimization/stargazers) | Educational notebooks implementing EMSR-a, EMSR-b, overbooking controls, and demand forecasting algorithms. | Python, Jupyter |
| 🌿 **[Airline Environmental Revenue Project](https://github.com/s-zubair-sy/airline-environmental-revenue-project)** | [<img src="https://img.shields.io/github/stars/s-zubair-sy/airline-environmental-revenue-project?style=social&color=white" alt="s-zubair-sy/airline-environmental-revenue-project Stars"/>](https://github.com/s-zubair-sy/airline-environmental-revenue-project/stargazers) | Data science analysis evaluating the impact of revenue management efficiency on passenger load factors and CO₂ emissions. | R, Python |

---

## 🛠️ Key Frameworks for Building Custom RM Systems

- **Discrete-Event Simulation**: Utilize the `airsim` C++ stack (`rmol`, `stdair`, `tvlsim`, `airinv`) for classical booking horizon simulations.
- **Machine Learning & Dynamic Pricing**: Combine forecasting tools (XGBoost, Temporal Fusion Transformers) with customer choice models (Multinomial Logit / MNL).
- **Network & Leg Optimization**: Prototype EMSR-a, EMSR-b, and Deterministic Linear Program (DLP) bid-price controls using Google OR-Tools or Julia JuMP.

---

## 🤝 How to Contribute

Contributions are highly appreciated! To submit a new SaaS platform or open-source repository:

1. 🍴 **Fork** this repository.
2. 📝 **Add/Update** entries in `README.md` following the tabular format.
3. 🔎 Ensure all links, descriptions, and factual pricing/funding data are accurate.
4. 🔀 **Submit a Pull Request (PR)** with a clear title and summary.

Please ⭐ star this repository if you find it helpful!

---

## 📜 Disclaimer

- This is a **community-curated** educational guide and directory.
- Live production airline revenue management requires certified enterprise PSS/reservation integrations. Open-source libraries are intended for research, educational prototyping, and offline simulation.
- Pricing, valuations, and feature sets are gathered from public corporate disclosures and industry reports.

---

## 💖 Support & Sponsorship

If you find this repository valuable for your aviation analytics, revenue science research, or industry benchmarking, please consider supporting the project!

- ⭐ **Star** this repository to show your appreciation!
- 🔀 **Fork** and share it with your network and colleagues.
- ☕ **Buy me a coffee / Sponsor**: Support ongoing maintenance via [GitHub Sponsors](https://github.com/sponsors/ishandutta2007).

Thank you for supporting open aviation and revenue management research! 🙌

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Airline-Revenue-Management&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Airline-Revenue-Management&type=date&legend=top-left)
