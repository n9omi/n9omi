[README-2(2).md](https://github.com/user-attachments/files/33359802/README-2.2.md)
# Naomi Tinga

### Data Professional and Graduate Student

My work explores probabilistic and statistical modeling, geospatial and remote-sensing methods, conceptual and exploratory frameworks to study **commodities, global markets, environmental risk, data/AI infrastructure, and geopolitical dynamics**. I am particularly interested in combining Earth-observation, geospatial, demographic, socioeconomic, and market data to estimate latent system states, identify regime changes, quantify risk/uncertainty, and study how shocks propagate through commodities markets, supply chains, and the global economy. I complement these quantitative methods with behavioral, game-theoretic, network analysis, social and critical theory, and other qualitative frameworks.

More broadly, I study how environmental, socioeconomic, and geopolitical systems interact across time and networks; how those relationships can be measured through probability theory, stochastic processes, complex dynamical systems, spatial and network models, time-series methods, optimization, and ML/statistical learning; and how data infrastructure and computational tools can be developed to forecast outcomes, evaluate risk, and translate empirical findings into realized insights and implications.

Professionally, I've worked in data for 7+ years applying data engineering and data science methods in compliance-heavy industries — energy, healthcare, real estate and infrastructure, public sector, and economic and policy research — spanning data sourcing, pipeline development, data governance, forecasting, ethnography, demography, geospatial and statistical modeling, owning data products end to end, turning structured and unstructured data into statistical and qualitative insights delivered as compliance analytics, data products, tools, and reports for decision makers and stakeholders.

**Currently focused on:**

- **Commodity market regimes & risk:** modeling volatility, tail risk, regime shifts, strategy robustness, and model failure across energy and broader commodity markets through [regime-risk-and-model-validation](https://github.com/n9omi/regime-risk-and-model-validation), [climate-shock-energy-risk](https://github.com/n9omi/climate-shock-energy-risk), and [risk-cc-market-toolkit](https://github.com/n9omi/risk-cc-market-toolkit).

- **Geospatial, network & physical-supply intelligence:** combining GIS, spatial analysis, machine learning, Earth-observation data, and network methods to study commodity production, infrastructure, trade dependencies, supply-chain concentration, and disruption through [GIS-ML-Commodities-Network](https://github.com/n9omi/GIS-ML-Commodities-Network) and [commodity-geospatial-atlas](https://github.com/n9omi/commodity-geospatial-atlas).

- **Geopolitical & geoeconomic intelligence:** studying how conflict, sanctions, trade policy, political instability, and cross-border disruptions propagate through commodity flows, supply chains, energy markets, and financial conditions through [geopol-risk-monitor](https://github.com/n9omi/geopol-risk-monitor).

- **Climate-shock transmission:** measuring how hurricanes, winter storms, floods, and other physical hazards transmit into commodity prices, volatility, infrastructure exposure, and portfolio risk through [climate-shock-energy-risk](https://github.com/n9omi/climate-shock-energy-risk).

- **Commodity ML & decision models:** testing deep learning, reinforcement learning, and statistical-learning methods against classical econometric and stochastic benchmarks through [commodity-deep-learning-lab](https://github.com/n9omi/commodity-deep-learning-lab) and [commodity-ml-dashboard](https://github.com/n9omi/commodity-ml-dashboard).

- **Quantitative research infrastructure:** building reproducible systems for data ingestion, feature engineering, backtesting, model validation, research replication, and reporting through [commodity-research-utils](https://github.com/n9omi/commodity-research-utils), [commodity-repo-template](https://github.com/n9omi/commodity-repo-template), and [quant-paper-reading-assistant](https://github.com/n9omi/quant-paper-reading-assistant).

---

## Methods & Tools

**Time Series, Risk & Econometrics:**  
Markov-switching / hidden-state models · EWMA · GARCH-t · HAR-RV · volatility forecast comparison · VaR / Expected Shortfall · historical & filtered historical simulation · stress testing · event studies · placebo testing · Monte Carlo simulation · CVA / counterparty exposure · time-series and cross-sectional momentum · value factors

**Model Validation & Statistical Learning:**  
Kupiec and Christoffersen coverage tests · Basel traffic-light testing · ES backtesting · QLIKE and Diebold–Mariano tests · purged walk-forward and combinatorial purged cross-validation · probability of backtest overfitting · probabilistic / deflated Sharpe ratios · Newey–West inference · simulation-based parameter recovery · no-look-ahead testing · ablation studies

**Machine Learning & Deep Learning:**  
Lasso · Ridge · Elastic Net · XGBoost · random forests · hidden Markov models · LSTM · GRU · Temporal Fusion Transformer · U-Net · Double DQN · classical-vs-ML benchmark design · model cards and experiment tracking

**Geospatial & Earth Observation:**  
Sentinel-1/2 change detection · MODIS crop-condition monitoring · USGS 3DEP lidar stockpile estimation · kriging / spatial interpolation · LISA hotspot analysis · spatial validation · commodity supply mapping across drilling, mining, stockpiles and agriculture

**Research Engineering & Tools:**  
Python · R · PyTorch · NumPy / SciPy-style numerical workflows · HTML / JavaScript · SQL / PostgreSQL · QGIS / ArcGIS · Google Earth Engine · Git / GitHub Pages · EIA / FRED / World Bank commodity data · reusable Python packages · automated reports and dashboards

---

## Projects

### Market, Climate & Geopolitical Risk

- **[regime-risk-and-model-validation](https://github.com/n9omi/regime-risk-and-model-validation)** · *Python* — Energy market-risk and model-validation suite for WTI, Brent, and Henry Hub, covering regime detection, volatility forecasting, VaR/ES backtesting, and commodity-factor robustness tests. Core estimators and validation statistics are implemented from scratch.  
  [Dashboard →](https://n9omi.github.io/regime-risk-and-model-validation/) · [Risk report →](https://github.com/n9omi/regime-risk-and-model-validation/blob/main/reports/regime_risk_summary.pdf) · [Factor report →](https://github.com/n9omi/regime-risk-and-model-validation/blob/main/reports/factor_validation_summary.pdf)

- **[climate-shock-energy-risk](https://github.com/n9omi/climate-shock-energy-risk)** · *Python* — Event-study and stress-testing framework linking Gulf hurricanes and U.S. winter storms to oil and gas prices, volatility regimes, VaR breaches, and portfolio losses.  
  [Dashboard →](https://n9omi.github.io/climate-shock-energy-risk/) · [Report →](https://github.com/n9omi/climate-shock-energy-risk/blob/main/reports/climate_shock_energy_risk_report.pdf)

- **[geopol-risk-monitor](https://github.com/n9omi/geopol-risk-monitor)** — Geopolitical and geoeconomic monitoring system connecting conflict, sanctions, trade policy, political instability, and cross-border disruptions to commodity, supply-chain, and market risk.

- **[risk-cc-market-toolkit](https://github.com/n9omi/risk-cc-market-toolkit)** · *R* — Market- and counterparty-risk toolkit covering VaR/ES, stress loss, risk attribution, derivatives exposure, collateral, CVA, wrong-way risk, and regulatory capital.  
  [Market-risk report →](https://github.com/n9omi/risk-cc-market-toolkit/blob/main/reports/market_risk_summary.pdf) · [CCR report →](https://github.com/n9omi/risk-cc-market-toolkit/blob/main/reports/ccr_summary.pdf)

### Geospatial, Network & Physical-Supply Intelligence

- **[GIS-ML-Commodities-Network](https://github.com/n9omi/GIS-ML-Commodities-Network)** — Integrated GIS, machine-learning, and network-analysis research for studying commodity production, infrastructure, trade relationships, supply-chain concentration, and disruption exposure.

- **[commodity-geospatial-atlas](https://github.com/n9omi/commodity-geospatial-atlas)** · *Python* — Earth-observation atlas for extracting physical commodity-supply signals from Sentinel imagery, lidar, and crop-condition data across drilling, mining, coal stockpiles, and agriculture.  
  [Atlas →](https://n9omi.github.io/commodity-geospatial-atlas/) · [Report →](https://github.com/n9omi/commodity-geospatial-atlas/blob/main/reports/geospatial_atlas_report.pdf)

### Commodity ML & Decision Models

- **[commodity-deep-learning-lab](https://github.com/n9omi/commodity-deep-learning-lab)** · *Python / PyTorch* — Benchmark laboratory comparing deep-learning and reinforcement-learning models against classical statistical methods for energy volatility, satellite-image classification, and gas-storage decisions.  
  [Dashboard →](https://n9omi.github.io/commodity-deep-learning-lab/) · [Report →](https://github.com/n9omi/commodity-deep-learning-lab/blob/main/reports/deep_learning_lab_report.pdf) · [Model cards →](https://github.com/n9omi/commodity-deep-learning-lab/tree/main/model_cards)

- **[commodity-ml-dashboard](https://github.com/n9omi/commodity-ml-dashboard)** · *HTML / JavaScript* — Interactive commodity-ML environment demonstrating regularization, XGBoost, hidden-state regime detection, and backtesting with interpretable examples.  
  [Live demo →](https://n9omi.github.io/commodity-ml-dashboard/)

### Quantitative Research Infrastructure

- **[commodity-research-utils](https://github.com/n9omi/commodity-research-utils)** · *Python* — Shared research library for commodity-data ingestion, validation, purged walk-forward splits, and standardized outputs. Paired with **[commodity-repo-template](https://github.com/n9omi/commodity-repo-template)** for reproducible ingest → features → model → validate → report workflows.

- **[quant-paper-reading-assistant](https://github.com/n9omi/quant-paper-reading-assistant)** · *HTML / JavaScript* — Research interface for decomposing quantitative papers into equations, concepts, methodological pipelines, and staged replication plans.  
  [Live app →](https://n9omi.github.io/quant-paper-reading-assistant/)
---

## Other Work

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
- 💼 &nbsp; [linkedin.com/in/naomitinga](https://www.linkedin.com/in/naomitinga)
- 🐙 &nbsp; [github.com/n9omi](https://github.com/n9omi)

___

"What you're really doing is checking the intuition not the mathematics" - Leonard Susskind
