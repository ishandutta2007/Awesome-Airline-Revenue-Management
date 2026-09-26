# Awesome-Airline-Revenue-Management

# Top Airline Revenue Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Yield Management, Dynamic Pricing, Inventory Control, Demand Forecasting & O&D Revenue Optimization*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Airline Revenue Management (RM)**. These systems forecast demand, allocate seats by fare class, set dynamic prices, and optimize network revenue—core to airline profitability.

**Examples** include PROS Revenue Management, Amadeus Revenue Management, Sabre AirVision Revenue Optimizer, Fetcherr, Flyr Labs, AirGain / RateGain, Datalex, and Lufthansa Systems NetLine/ProfitLine (the category leaders).

**Open-source emphasis**: Production airline RM is almost entirely commercial. Open work is research-oriented—**RMOL**, **Seatwise**-style simulators, and academic optimization notebooks. This section lists every significant relevant project found.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[PROS Revenue Management](https://pros.com/)**  
  Leading enterprise RM and dynamic pricing platform used across airlines and other industries.

- **[Amadeus Revenue Management, Sabre AirVision Revenue Optimizer](https://amadeus.com/)**  
  GDS-linked airline RM suites for inventory control, forecasting, and network optimization.

- **[Lufthansa Systems NetLine / ProfitLine](https://www.lhsystems.com/)**  
  Airline operations and revenue management solutions from a major airline IT provider.

- **[Fetcherr, Flyr Labs, RateGain AirGain, Datalex](https://www.fetcherr.com/)**  
  Modern AI-driven pricing and revenue platforms focused on continuous pricing and ancillary optimization.

- **[Other commercial airline RM platforms](https://pros.com/)**  
  Additional inventory and pricing systems integrated with PSS and offer management.

## Open-Source GitHub Projects

- **[RMOL (Revenue Management Open Library)](https://github.com/airsim/rmol)**  
  Open C++ simulation library for airline revenue management—part of the broader Travel Market Simulator / airsim ecosystem.

- **[stdair, airinv, tvlsim (airsim stack)](https://github.com/airsim)**  
  Open simulation libraries for airline inventory, travel market, and related RM components used in research.

- **[Seatwise](https://github.com/ahmetgokbulut/seatwise)**  
  Research-grade dynamic airfare RM system—demand forecasting (TFT/XGBoost), sentiment-aware pricing, and Monte-Carlo simulation vs EMSR baselines.

- **[Academic airline RM / optimization notebooks](https://github.com/Payal3214/Airline-Revenue-Optimization)**  
  Open educational projects covering demand forecasting, fare-class allocation, overbooking, and pricing analysis.

- **[OR-Tools / custom EMSR & DP implementations](https://github.com/google/or-tools)**  
  General open solvers frequently used to prototype leg-based and network RM heuristics.

- **[Customer choice model research code](https://github.com/search?q=airline+customer+choice+OR+EMSR+revenue+management)**  
  Academic open implementations of buy-up, diversion, and choice models.

- **[Fare and schedule data open pipelines](https://github.com/search?q=airline+fare+OR+GDS+data+open+source)**  
  Community tools for working with public or sample schedule/fare datasets in RM experiments.

- **[Discrete-event booking simulators](https://github.com/search?q=airline+booking+simulation+OR+yield+management+simulation)**  
  Open simulators for testing pricing policies under stochastic demand.

### Additional Strong Open-Source Options

- **Simulation research**: RMOL and airsim libraries for classical RM experiments.
- **ML pricing research**: Seatwise-style forecasting + simulation stacks.
- **Optimization building blocks**: OR-Tools for custom allocation prototypes.
- Commercial RM remains mandatory for live airline inventory and PSS integration.

**Frameworks for building custom systems**:  
Open **RMOL** / **airsim** and research repos support education and offline experimentation.  
Live airline revenue management requires commercial systems (PROS, Amadeus, Sabre, Lufthansa Systems, Fetcherr, Flyr, etc.) tightly coupled to reservations and inventory.  
Universities and analytics teams use open tools for method development; carriers run certified commercial RM. Fully open production airline RM is not a realistic substitute for vendor platforms.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Airline revenue management affects fares, overbooking, and customer treatment. Pricing and inventory decisions are subject to competition law, consumer protection, and operational constraints. Incorrect models can destroy revenue or harm passengers.
- Open-source projects are for research and learning—not certified production RM. Commercial platforms provide the integration, support, and controls airlines require. Always validate with revenue management professionals.

---

**Made for airline revenue managers, pricing scientists, and aviation analytics teams.**  
Let's support open RM research while recognizing that production airline revenue management depends on proven commercial platforms.
