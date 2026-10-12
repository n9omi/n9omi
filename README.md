[README-2(2).md](https://github.com/user-attachments/files/33359802/README-2.2.md)
# Naomi Tinga

### Professional Data Analyst and Graduate Student

My work combines probabilistic and statistical modeling, geospatial and remote-sensing methods, and conceptual and exploratory frameworks to study **commodities, global markets, environmental risk, and geopolitical dynamics**. I am particularly interested in integrating Earth-observation, geospatial, demographic, socioeconomic, and market data to estimate latent system states, identify regime changes, quantify risk/uncertainty, and study how shocks propagate through commodities markets, supply chains, and the global economy. I complement these quantitative methods with behavioral, game-theoretic, network analysis, social and critical theory, and other qualitative frameworks.

More broadly, I study how environmental, socioeconomic, and geopolitical systems interact across time and networks; how those relationships can be measured through **probability theory, stochastic processes, complex dynamical systems, spatial and network models, time-series methods, optimization, and ML/statistical learning**; and how data infrastructure and computational tools can be developed to forecast outcomes, evaluate risk, and translate empirical findings into realized insights and implications.

Professionally, I've worked in data for 7+ years applying data engineering and data science methods in compliance-heavy industries — energy, healthcare, real estate and infrastructure, public sector, and economic and policy research — spanning data sourcing, pipeline development, data governance, forecasting, demography, geospatial and statistical modeling, owning data products end to end, turning structured and unstructured data into statistical and qualitative insights delivered as compliance analytics, data products, tools, and reports for decision makers and stakeholders.

**Currently focused on:**

- **Commodity market risk, regimes & model validation:** detecting changes in energy-market states, forecasting volatility and tail risk, and testing whether risk and factor models remain reliable out of sample
- **Climate shocks & commodity transmission:** measuring how hurricanes, winter storms and other physical shocks propagate into oil and gas prices, volatility, VaR breaches and portfolio stress
- **Geospatial supply intelligence:** turning satellite, radar, lidar and crop-condition data into observable supply-side signals for energy, agriculture and critical minerals
- **Commodity ML & deep learning:** benchmarking neural networks and reinforcement learning against strong statistical and econometric baselines rather than treating ML as a black box
- **Market & counterparty risk:** modeling portfolio VaR/ES, stress loss, derivatives exposure, collateral, CVA and wrong-way risk under bank-style risk frameworks
- **Reproducible quantitative research infrastructure:** building reusable data loaders, validation utilities, purged backtests, research templates, reports and interactive dashboards for commodity research

---

## 🔧 Methods & Tools

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

## 📊 Projects

### Commodity Market Risk & Model Validation

- **[regime-risk-and-model-validation](https://github.com/n9omi/regime-risk-and-model-validation)** · *Python* — End-to-end energy market-risk and model-validation research on WTI, Brent and Henry Hub. Implements Markov-switching regime detection, EWMA / GARCH-t / HAR-RV volatility forecasts, daily VaR/ES backtesting, and formal coverage tests. A second workflow re-tests published commodity momentum and value strategies using purged cross-validation, probability of backtest overfitting and the deflated Sharpe ratio. Core estimators and validation statistics are implemented from scratch. &nbsp; [Dashboard →](https://n9omi.github.io/regime-risk-and-model-validation/) · [Risk report →](https://github.com/n9omi/regime-risk-and-model-validation/blob/main/reports/regime_risk_summary.pdf) · [Factor report →](https://github.com/n9omi/regime-risk-and-model-validation/blob/main/reports/factor_validation_summary.pdf)

- **[climate-shock-energy-risk](https://github.com/n9omi/climate-shock-energy-risk)** · *Python* — Studies how Gulf hurricanes and US winter storms transmit into oil and gas prices and whether standard daily risk models capture the resulting stress. Combines NOAA storm selection, event studies, same-season placebos, regime shifts, VaR breach analysis, a learned climate overlay and historical-scenario stress testing on an energy portfolio. Built on the reusable regime-risk package. &nbsp; [Dashboard →](https://n9omi.github.io/climate-shock-energy-risk/) · [Report →](https://github.com/n9omi/climate-shock-energy-risk/blob/main/reports/climate_shock_energy_risk_report.pdf)

- **[risk-cc-market-toolkit](https://github.com/n9omi/risk-cc-market-toolkit)** · *R* — Bank-style market and counterparty-credit risk case studies implemented without black-box risk packages. Covers multi-method VaR/ES, position-level risk attribution, stressed VaR, crisis replays and Basel/FRTB capital; plus Monte Carlo swap/forward exposure, netting, collateral, CVA, wrong-way risk and SA-CCR / IRB / BA-CVA capital. &nbsp; [Market-risk report →](https://github.com/n9omi/risk-cc-market-toolkit/blob/main/reports/market_risk_summary.pdf) · [CCR report →](https://github.com/n9omi/risk-cc-market-toolkit/blob/main/reports/ccr_summary.pdf)

### Commodity Geospatial, ML & Decision Models

- **[commodity-geospatial-atlas](https://github.com/n9omi/commodity-geospatial-atlas)** · *Python* — Converts free Earth-observation data into observable commodity supply signals. Includes Sentinel-1/2 change detection for drilling and mining sites, USGS 3DEP lidar stockpile-volume estimation at coal yards, and kriged MODIS crop-condition surfaces with LISA hotspots across the Corn Belt. Each layer is evaluated against an independent reference. &nbsp; [Atlas →](https://n9omi.github.io/commodity-geospatial-atlas/) · [Report →](https://github.com/n9omi/commodity-geospatial-atlas/blob/main/reports/geospatial_atlas_report.pdf)

- **[commodity-deep-learning-lab](https://github.com/n9omi/commodity-deep-learning-lab)** · *Python / PyTorch* — Tests where deep learning actually adds value in commodity research by pairing each network with a classical benchmark on identical data and splits: LSTM / GRU / Temporal Fusion Transformer vs GARCH / HAR for energy volatility, U-Net vs random forest for Sentinel-2 land-use mapping, and Double DQN vs least-squares Monte Carlo for gas-storage trading. Uses multiple seeds, ablations, tracked experiments and model cards. &nbsp; [Dashboard →](https://n9omi.github.io/commodity-deep-learning-lab/) · [Report →](https://github.com/n9omi/commodity-deep-learning-lab/blob/main/reports/deep_learning_lab_report.pdf) · [Model cards →](https://github.com/n9omi/commodity-deep-learning-lab/tree/main/model_cards)

- **[commodity-ml-dashboard](https://github.com/n9omi/commodity-ml-dashboard)** · *HTML / JavaScript* — Interactive teaching and experimentation dashboard for commodity-market ML. Demonstrates regularization, XGBoost, hidden-state regime detection and backtesting with plain-language explanations and simulated price series. &nbsp; [Live demo →](https://n9omi.github.io/commodity-ml-dashboard/)

### Quantitative Research Infrastructure

- **[commodity-research-utils](https://github.com/n9omi/commodity-research-utils)** · *Python* — Shared commodity-research library for EIA/FRED ingestion, data-contract validation, purged walk-forward splits and standardized research outputs. Paired with **[commodity-repo-template](https://github.com/n9omi/commodity-repo-template)**, a reusable ingest → features → model → validate → report project scaffold.

- **[quant-paper-reading-assistant](https://github.com/n9omi/quant-paper-reading-assistant)** · *HTML / JavaScript* — Research interface for decomposing technical papers in quantitative finance, economics and statistics into equations, concepts, method pipelines and staged replication plans with starter code. &nbsp; [Live app →](https://n9omi.github.io/quant-paper-reading-assistant/)

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
