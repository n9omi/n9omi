[README.md](https://github.com/user-attachments/files/32832788/README.md)
# Naomi Tinga

### Professional Data Analyst and Graduate Student

My work combines probabilistic and statistical modeling, geospatial and remote-sensing methods, conceptual and exploratory frameworks to study **commodities, environmental risk, and geopolitical dynamics**. I’m interested in how environmental, spatial, economic, and political signals interact—and in developing the mathematical rigor and data infrastructure needed to translate those relationships into financial and policy insights.

Currently focused on: **critical minerals supply risk · energy market regime classification · physical climate risk modeling · geopolitical commodity exposure**

- 🪨 &nbsp; Critical minerals & metals · supply chain risk · geopolitical exposure modeling
- ⚡ &nbsp; Energy & commodity markets · price dynamics · regime classification
- 🛰️ &nbsp; Geospatial & remote sensing · satellite-derived risk signals · spatial analytics
- 📐 &nbsp; Stochastic processes · Markov chain models · probabilistic risk frameworks
- 🧱 &nbsp; AI & data infrastructure · governance · pipeline architecture
- 🎓 &nbsp; M.A. Economics · M.A. Applied Mathematics & Statistics — CUNY Hunter College *(in progress)*
- 📍 &nbsp; New York, NY

---

## 🔧 Methods & Tools

**Quantitative Methods:**
Stochastic processes · Markov chain & hidden Markov models · GMM regime classification · Gaussian-process & stochastic-volatility models · Lévy-process frameworks · time-series econometrics · probabilistic risk modeling · spatial & geospatial analysis · remote sensing analytics · GHG / carbon accounting

**Languages & Tools:**
Python · R · SQL / PostgreSQL · QGIS / ArcGIS · Google Earth Engine · Tableau · Power BI · Airflow · Snowflake · Databricks · AWS

---

## 📊 Projects

### Market & Climate Risk

- **[regime-risk-and-model-validation](https://github.com/n9omi/regime-risk-and-model-validation)** · *Python* — Market-risk and model-validation workflows on WTI, Brent and Henry Hub. Detects calm and turbulent regimes with a Markov-switching model, ranks EWMA, GARCH-t, HAR-RV and regime-based volatility forecasts, and backtests daily VaR/ES with Kupiec, Christoffersen and Basel traffic-light tests. A second study re-tests published commodity momentum and value strategies with purged cross-validation, the probability of backtest overfitting and the deflated Sharpe ratio. Every estimator is written from scratch. &nbsp; [Dashboard →](https://n9omi.github.io/regime-risk-and-model-validation/) · [Risk report (PDF) →](https://github.com/n9omi/regime-risk-and-model-validation/blob/main/reports/regime_risk_summary.pdf) · [Factor report (PDF) →](https://github.com/n9omi/regime-risk-and-model-validation/blob/main/reports/factor_validation_summary.pdf)

- **[climate-shock-energy-risk](https://github.com/n9omi/climate-shock-energy-risk)** · *Python* — How Gulf hurricanes and US winter storms move oil and gas prices, and whether daily risk models see it. Storms are selected from NOAA tracks and damage records rather than price moves, then tested with an event study against same-season placebo dates, regime shifts around each storm, VaR breach rates inside storm windows, a climate overlay learned from past storms, and historical-scenario stress tests on an energy book. Built on the regime-risk library as an installed package. &nbsp; [Dashboard →](https://n9omi.github.io/climate-shock-energy-risk/) · [Report (PDF) →](https://github.com/n9omi/climate-shock-energy-risk/blob/main/reports/climate_shock_energy_risk_report.pdf)

- **[risk-cc-market-toolkit](https://github.com/n9omi/risk-cc-market-toolkit)** · *R* — Two bank-style risk case studies built without black-box risk packages. **Market risk:** VaR and ES six ways on a $10mm multi-asset book, position-level risk attribution, stressed VaR, backtests since 2008, crisis replays, and Basel 2.5 / FRTB capital. **Counterparty credit risk:** Monte Carlo exposure for swaps and forwards with netting and collateral, CVA including wrong-way risk, and SA-CCR, IRB and BA-CVA capital. &nbsp; [Market risk report (PDF) →](https://github.com/n9omi/risk-cc-market-toolkit/blob/main/reports/market_risk_summary.pdf) · [CCR report (PDF) →](https://github.com/n9omi/risk-cc-market-toolkit/blob/main/reports/ccr_summary.pdf)

### Commodity ML & Geospatial

- **[commodity-deep-learning-lab](https://github.com/n9omi/commodity-deep-learning-lab)** · *Python / PyTorch* — Three commodity problems, each solved with a neural network and with the classical method it has to beat, on identical data and splits: LSTM, GRU and a Temporal Fusion Transformer against GARCH and HAR for energy returns and volatility; a U-Net against a random forest for mapping mines, stockpiles and cropland in Sentinel-2 imagery; and a double DQN against least-squares Monte Carlo for gas-storage trading. Multiple seeds, ablations, tracked experiments and a model card for every network. &nbsp; [Dashboard →](https://n9omi.github.io/commodity-deep-learning-lab/) · [Report (PDF) →](https://github.com/n9omi/commodity-deep-learning-lab/blob/main/reports/deep_learning_lab_report.pdf) · [Model cards →](https://github.com/n9omi/commodity-deep-learning-lab/tree/main/model_cards)

- **[commodity-geospatial-atlas](https://github.com/n9omi/commodity-geospatial-atlas)** · *Python* — Interactive map that turns free Earth-observation data into supply-side signals: Sentinel-1/2 change detection at a Permian drilling area and the Bingham Canyon and Thacker Pass mines, USGS 3DEP lidar stockpile volumes at power-plant coal yards, and kriged MODIS crop-condition surfaces with LISA hotspots across the Corn Belt. Each layer is scored against an independent reference. &nbsp; [Atlas →](https://n9omi.github.io/commodity-geospatial-atlas/) · [Report (PDF) →](https://github.com/n9omi/commodity-geospatial-atlas/blob/main/reports/geospatial_atlas_report.pdf)

- **[commodity-ml-dashboard](https://github.com/n9omi/commodity-ml-dashboard)** · *HTML / JavaScript* — Browser-based teaching dashboard for machine learning in commodity markets, built for ECO 760 at Hunter College. Interactive modules for Lasso / Ridge / ElasticNet, XGBoost, hidden Markov regime detection and a backtest engine, each with plain-English explanations. Runs on simulated price series. &nbsp; [Live demo →](https://n9omi.github.io/commodity-ml-dashboard/)

### Research Tools

- **[quant-paper-reading-assistant](https://github.com/n9omi/quant-paper-reading-assistant)** · *HTML / JavaScript* — Single-page app that uses Claude to break down technical papers in quant finance, economics and statistics: key equations with every symbol explained, concepts at three levels of depth, the method pipeline, and a phased replication plan with a starter Python script. Runs in the browser with your own API key. &nbsp; [Live app →](https://n9omi.github.io/quant-paper-reading-assistant/)

- **[commodity-research-utils](https://github.com/n9omi/commodity-research-utils)** · *Python* — Shared toolbox for commodity research: EIA and FRED loaders, data-contract validation, purged walk-forward splits and a consistent figure style. Paired with **[commodity-repo-template](https://github.com/n9omi/commodity-repo-template)**, an ingest → features → model → validate → report scaffold for new projects.

### Digital Scholarship

- **[sacred-memories-tangier](https://github.com/n9omi/sacred-memories-tangier)** · *HTML / CSS* — Website for the Sacred Memories in Tangier ethnographic research project, with researcher profiles, an archive and a Critical Border Studies section. Sponsored by CUNY John Jay College. &nbsp; [Visit →](https://sacredmemoriestanger.com)

---

## 📝 Published Work

### Academic

- **"Crisis as Infrastructure"** — Co-authored chapter in *[Routledge Handbook]*, with Esparza & Tinga. Analyzes necropolitics and European border governance through a structural lens. *(Routledge)*

### Data Journalism

- **Lead Contamination in Newark School Water** — *Gothamist.* &nbsp; Data investigation revealing elevated lead levels in Newark public-school drinking water, contradicting official assurances. &nbsp; [Read →](https://gothamist.com/news/newark-officials-said-there-was-no-lead-schools-water-data-shows-otherwise)
- **Racial Disparities in Queens Community Boards** — *Queens Eagle.* &nbsp; Demographic analysis of the representation gap between community boards and the residents they serve. &nbsp; [Read →](https://queenseagle.com/all/queens-community-boards-demographics-racial-disparities)
- **Mapping COVID in Queens** — *Queens Eagle.* &nbsp; Geospatial analysis of COVID testing access across Queens, highlighting persistent gaps in a former epicenter. &nbsp; [Read →](https://queenseagle.com/all/mapping-covid-in-queens-testing-expands-but-gaps-remain-in-former-crisis-epicenter)

### Reports

- **A Decade Undone: Youth Disconnection in the Age of Coronavirus** — *Measure of America / SSRC.* &nbsp; Contributing researcher and data analyst on a national report measuring youth disconnection. &nbsp; [PDF →](https://ssrc-static.s3.amazonaws.com/moa/ADecadeUndone.pdf)
- **A Portrait of Louisiana 2020** — *Measure of America / SSRC.* &nbsp; Contributing researcher, analyst, and writer on an American Human Development Index state profile. &nbsp; [PDF →](https://ssrc-static.s3.amazonaws.com/moa/A_Portrait_of_Louisiana_2020.pdf)

### Interactive Data Tools

Built at the Social Science Research Council — Measure of America:

- [data2go.nyc](https://data2go.nyc) — neighborhood well-being mapping platform *(featured at the Museum of the City of New York)*
- [data2gohealth.nyc](https://data2gohealth.nyc) — health-focused companion mapping tool
- [ourhome.nyc](https://ourhome.nyc) — housing and community data tool

---

## 📫 Connect

- 📧 &nbsp; ngtinga@gmail.com
- 🐙 &nbsp; [github.com/n9omi](https://github.com/n9omi)
