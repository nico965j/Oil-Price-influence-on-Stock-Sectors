# Oil-Price-influence-on-Stock-Sectors
## Master Thesis scripts and figures.

### Repository Structure:


📁 Dataset Creation
Notebook: Dataset Creation

Description: Constructs the full dataset used in the analysis. Includes daily data for each sector, WTI spot prices, and the VIX, along with engineered features.

📁 Literature Review Figures
Notebook: Recreating Graphs for Literature Review

Description: Reproduces key figures cited in the thesis literature review to provide visual context and baseline relationships.

📁 Preliminary Analysis
Notebook: Preliminary Analysis

Description: Performs initial exploratory analysis This includes distribution assessments and stationarity.

📁 Econometric Analysis
Notebook: Granger-Causality, GIRFs and Return Analysis

Description: Examines dynamic relationships between oil, VIX, and sector returns using Granger causality, Generalized Impulse Response Functions (GIRFs), and return behavior across regimes.

📁 Crisis-Specific Analysis
Notebook: Results with Crisis Zoom-In

Description: Focuses on relationships during major crisis periods, investigating shifts in sensitivity and predictive power.

📁 Forecasting
Notebook: Forecasting

Description: Applies XGBoost models to forecast sector returns using insights from prior analyses. Includes model tuning, validation, and evaluation against baselines.