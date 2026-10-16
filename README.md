# Max Santana
### Data Analyst, Business Intelligence & Strategic Foresight Specialist

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=sqlite&logoColor=white) ![Power BI](https://img.shields.io/badge/Power_BI-F2C94C?style=for-the-badge&logo=powerbi&logoColor=black) ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)

---

Hi there 👋, welcome to my profile

### 👨‍💻 A brief about me

* 📊 I use **rigorous data analytics** and **strategic intelligence** to turn complex, messy data into actionable business intelligence 📈 and long-term strategic decisions 🎯.
* 🌐 International relations graduate specialised in data analysis and strategic foresight 🔮 — transforming chaos to clarity ✨ and moving from uncertainty to opportunities 💡.
* 🚀 Currently advancing into **Data analysis** and **Applied AI** & **Data Science Solutions** 🤖.
* ⚡ Fun fact: I love Dachshunds; hoping to fulfil my dream to have one or two little wieners to join me while I code

### 📬 Connect & Collaborate

* 📧 **Email:** msantana.r@outlook.com
* 📱 **Phone:** +52 220 501 4335
* 🌍 **Languages:** English & Spanish (Bilingual), Intermediate French
* 💻 **Availability:** High preference for Remote roles
* 🌐 **Portfolio:** [maxsantana-data2strategy.github.io](https://maxsantana-data2strategy.github.io/)

---

### 🛠️ Technical Stack & Capabilities

* **Data Analytics & BI:** SQL, Python (`pandas`, `numpy`, `seaborn`, `matplotlib`), R (`tidyverse`, `ggplot2`), Power BI, Tableau, RStudio, Jupyter, Google Colab.

* **Core Technical Focus:** End-to-end data pipelines, cleaning raw datasets (100k+ records), data modeling, statistical forecasting, and dynamic dashboard design.

* **Business & Strategy:** Business question-oriented analysis, KPI framework design, executive communication (CFI consulting framework), decision support, and stakeholder alignment, Project Management, Conflict resolution

* **Strategic Foresight & Risk Analysis:** Strategy facilitation, scenario planning, horizon scanning, geopolitical risk analysis, actor mapping, long-term scenario building under uncertainty, HUMINT, and OSINT.

* **Social Science & Research:** Qualitative research (expert consultations, interviews, surveys, focus groups), public policy analysis, and political economy.

---

### 📊 Data Analysis / BI

<img src="banner-data-analysis.gif" alt="Animated banner: a scatter plot resolving into a regression line, bar chart and correlation metric" width="100%">

Work that starts from a business question and ends with a decision someone can defend. Cleaning, modeling, and dashboard design across customer behavior, territorial profitability, experimentation, and public-sector indicators.

<details>
<summary><b>Where to Concentrate Marketing Spend Across Six Markets — Cycling Retail · SQL</b></summary>

#### 🎯 Objective
Determine where to allocate marketing spend for maximum ROI across territories by analyzing revenue, costs, and marketing investment.

[![Access to full project description and check Repository Files](https://img.shields.io/badge/📂_View_Repository_Files-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/maxsantana-data2strategy/adventure-works-profitability-analysis-SQL)
[![Download Infographic PDF](https://img.shields.io/badge/📥_Download_Infographic_PDF-2EA44F?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/adventure-works-profitability-analysis-SQL/main/outputs/assets/Infographic_AdventureWorks_EN_v2.pdf)

#### 🔧 What I Did
1. **Schema Integration** — Joined 6 tables (sales, products, categories, territories, campaigns) using `clave_territorio` and `clave_producto`
2. **Data Cleaning** — Calculated `ingreso_total` and `costo_total` per order, handled NULLs with COALESCE
3. **KPI Calculation** — Aggregated revenue, gross profit, margin %, and ROI % by territory
4. **Validation** — Reconciled totals across joins, confirmed no data anomalies

#### 🛠️ Technologies
SQL (JOINs, GROUP BY, aggregations, COALESCE, NULLIF) | Relational database with 6 tables | Data validation & QA

#### 📊 Results

| Country | Revenue | Margin % | ROI % |
|---------|---------|----------|-------|
| 🇺🇸 USA | $3.35M | 43.4% | **75.8%** ⭐ |
| 🇦🇺 Australia | $2.53M | 41.7% | **49.2%** |
| 🇬🇧 UK | $1.19M | 42.7% | **22.1%** |
| 🇩🇪 Germany | $1.07M | 42.9% | **20.3%** |
| 🇫🇷 France | $0.92M | 42.9% | **17.9%** |
| 🇨🇦 Canada | $0.71M | 44.8% | **17.4%** |

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/adventure-works-profitability-analysis-SQL/main/outputs/assets/Revenue_by_Country_EN_whitebg.png" alt="Revenue per country" width="600">
</p>

#### 💡 Key Insight
**USA leads with 75.8% ROI** on $1.92M spend. **Australia (49.2% ROI) punches above weight.** **UK underperforms** with only 22.1% ROI despite $2.3M investment. All margins healthy (41–45%), but ROI divergence driven by **marketing spend efficiency.**

**Recommendation:** Reallocate ~$500K from underperforming EU/CA markets to USA/Australia for 30–40% ROI improvement.

</details>

<details>
<summary><b>Which Customers Drive Value in Messy Usage Data — Telecom · Python</b></summary>

#### 🎯 Objective
Determine which customers drive the most value for a Latin American telecom by cleaning usage data, resolving data-quality issues, and segmenting customers by usage intensity and age.

[![Access to full project description and check Repository Files](https://img.shields.io/badge/📂_View_Repository_Files-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/maxsantana-data2strategy/connectatel-customer-behavior-analysis)
[![Download Infographic PDF](https://img.shields.io/badge/📥_Download_Infographic_PDF-2EA44F?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/connectatel-customer-behavior-analysis/main/assets/Infographic_ConnectaTel_EN.pdf)

#### 🔧 What I Did
1. **Data Quality Diagnosis** — Detected sentinel values (`age` = -999, `city` = '?'), impossible dates (40 records dated 2026), and confirmed `duration`/`length` nulls were Missing At Random by usage `type`
2. **Cleaning** — Replaced sentinels, standardized dates, and preserved MAR nulls as meaningful signal rather than imputing them away
3. **Feature Engineering** — Aggregated 40,000 usage records into a per-user profile (messages, calls, call minutes)
4. **Outlier & Segmentation Analysis** — Used IQR and Z-scores to identify power users, then segmented all 4,000 customers by usage (`Low`/`Medium`/`High use`) and age

#### 🛠️ Technologies
Python (pandas, numpy) | seaborn, matplotlib | IQR & Z-score outlier detection | Rule-based segmentation | Google Colab

#### 📊 Results
`Medium use` is the largest usage segment; a consistent minority of 21–47 users per metric are high-volume "power users" retained as an upsell target rather than cleaned away as noise. `Basic plan` dominates every segment, including the heaviest users, pointing to under-monetized power users.

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/connectatel-customer-behavior-analysis/main/assets/usage_and_age_segments_by_plan.png" alt="Customers by usage segment and age segment, split by plan (Basico vs Premium)" width="700">
</p>

#### 💡 Key Insight
**Outliers were the opportunity, not the noise.** The heaviest 21–47 users per usage metric were kept — not trimmed — since they represent ConnectaTel's clearest upsell segment.

**Recommendation:** Design an ultra-premium tier for these power users and target `Medium use` customers, already the largest segment, for migration incentives toward `High use`/`Premium`.

</details>

<details>
<summary><b>Which Customer Behaviors Track Annual Revenue — E-Commerce · Python & SciPy</b></summary>

#### 🎯 Objective
Determine which customer behavior factors are most strongly associated with annual revenue for a Latin American e-commerce platform, so the Growth and Retention team knows where to concentrate effort: purchase frequency, engagement volume, advertising intensity, or premium subscription.

[![Access to full project description and check Repository Files](https://img.shields.io/badge/📂_View_Repository_Files-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/maxsantana-data2strategy/novaretail-revenue-correlation-analysis)
[![Download Infographic PDF](https://img.shields.io/badge/📥_Download_Infographic_PDF-2EA44F?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/novaretail-revenue-correlation-analysis/main/assets/Infographic_NovaRetail_EN.pdf)

#### 🔧 What I Did
1. **Variable Typing** — Classified all 12 columns into numerical, binary, and categorical families, since variable type is what determines which correlation coefficient is valid
2. **Distribution Profiling** — Found `monthly_visits`, `monthly_purchases`, and `targeted_ad_spend` right-skewed with long tails, ruling out Pearson as a sole basis for the analysis
3. **Coefficient Selection** — Applied Spearman (numeric–numeric, robust to outliers), point-biserial (numeric–binary), and Cramér's V (categorical–categorical) across 15,000 customer records
4. **Robustness Check** — Computed all six unique pairs under both Pearson and Spearman and differenced them, measuring the impact of outliers instead of assuming it

#### 🛠️ Technologies
Python (pandas, numpy) | `scipy.stats` (spearmanr, pointbiserialr, chi2_contingency) | seaborn, matplotlib | Correlational inference & effect-size reasoning | Jupyter Notebook

#### 📊 Results

| Relationship | Coefficient | Value | Read |
|---|---|---|---|
| monthly_purchases ↔ annual_revenue | Spearman ρ | **0.97** | Dominant signal ⭐ |
| monthly_visits ↔ targeted_ad_spend | Spearman ρ | 0.56 | Ads buy traffic |
| monthly_visits ↔ annual_revenue | Spearman ρ | 0.32 | Secondary |
| targeted_ad_spend ↔ annual_revenue | Spearman ρ | 0.19 | Weak |
| annual_revenue ↔ premium_member | Point-biserial r | 0.09 (p = 3.1e-30) | Significant, negligible |
| device_type ↔ region | Cramér's V | 0.01 (p = 0.60) | No association |

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/novaretail-revenue-correlation-analysis/main/assets/figure_3_spearman_correlation_heatmap.png" alt="Spearman correlation heatmap of key behavioral variables against annual revenue" width="600">
</p>

#### 💡 Key Insight
**Statistical significance and practical relevance came apart.** Premium membership reached p ≈ 3e-30 against annual revenue and was still worth nothing as a lever: r = 0.09. With n = 15,000, any trivial effect clears a significance threshold, so effect size — not the p-value — was the decision-relevant quantity. Meanwhile advertising tracked visits (ρ = 0.56) far more than revenue (ρ = 0.19): it buys traffic, not money. And the standout ρ = 0.97 between purchases and revenue was flagged as a metric-construction warning rather than celebrated as a finding.

**Recommendation:** Optimize for conversion rather than traffic, judge campaigns on conversion-based return instead of spend, drop premium status as a growth lever, and validate the purchases–revenue overlap before any predictive modeling.

</details>

<details>
<summary><b>Which Homepage Version to Ship — E-Commerce A/B Test · Python & statsmodels</b></summary>

#### 🎯 Objective
Decide which version of an e-commerce homepage should be implemented — A (control) or B (variant) — by validating an A/B experiment across 40,000 exposed users on conversion rate and spend per converted user, and checking whether traffic channel or user type changes the answer.

[![Access to full project description and check Repository Files](https://img.shields.io/badge/📂_View_Repository_Files-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/maxsantana-data2strategy/landing-page-ab-test-analysis)
[![Download Infographic PDF](https://img.shields.io/badge/📥_Download_Infographic_PDF-2EA44F?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/landing-page-ab-test-analysis/main/assets/Infographic_LandingAB_EN.pdf)

#### 🔧 What I Did
1. **Data Validation** — Checked 40,000 rows × 9 columns for missing values, duplicate rows and repeated user IDs (none found), and compared group composition across region, device, traffic source and user type: 19,982 vs 20,018 users, largest gap 0.8 pp
2. **Assumption-Driven Test Selection** — Levene's test (p = 6.9e-08) ruled out equal variances and selected **Welch's t-test** over Student's for the spending comparison, rather than defaulting to one
3. **Effect Sizes Beside Every p-value** — Reported the 95% CI [+6.08, +9.24] and **Cohen's d = 0.25** with the Welch result, and **Cramér's V** with every chi-square, so significance is never read as relevance at n = 40,000
4. **Outlier Review** — Applied the IQR rule inside each version (2.83% of buyers in A, 2.79% in B), confirmed the extremes were genuine purchases rather than errors, and re-ran the comparison without them as a sensitivity check (+7.61 vs +7.66) before deciding to keep them
5. **Conversion & Segment Tests** — Two-proportion z-test for the conversion rate, and chi-square on contingency tables of **counts** for traffic source and user type, with expected-frequency validation

#### 🛠️ Technologies
Python (pandas, numpy) | `scipy.stats` (levene, ttest_ind Welch, chi2_contingency) | `statsmodels` (proportions_ztest) | Cohen's d & Cramér's V | seaborn, matplotlib | Jupyter Notebook

#### 📊 Results

| Result | Test | Value | Read |
|---|---|---|---|
| Conversion rate — A vs B | Two-proportion z-test | **+3.38 pp (+26.9%)** | 12.57% → 15.96%, p = 3.8e-22 ⭐ |
| Spending per converted user | Welch's t-test | **+7.66 (+12.5%)** | 61.09 → 68.75, 95% CI [+6.08, +9.24] |
| Size of the spending effect | Cohen's d | **0.25** | Small — the distributions overlap substantially |
| Extreme spending values | IQR rule + sensitivity re-test | 2.83% A · 2.79% B | Kept — genuine purchases, evenly split |
| Traffic source ↔ conversion | χ² on counts + Cramér's V | p = 0.034, V = 0.015 | Significant, negligible — 1.2 pp of spread |
| User type ↔ conversion | χ² on counts + Cramér's V | p = 0.474, V = 0.004 | No association |

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/landing-page-ab-test-analysis/main/assets/figure_2_conversion_rate_by_version.png" alt="Conversion rate by landing page version, A versus B, with the absolute and relative lift" width="600">
</p>

#### 💡 Key Insight
**Two significant results, two different weights.** B wins on both metrics, but they are not equal: the conversion gain is +26.9% relative, while the spending gain carries a Cohen's d of 0.25 — a real but modest shift inside two heavily overlapping distributions. Ranking them is what turns a positive test into a decision. The segment questions came back empty in the way that matters: channel reached significance (p = 0.034) and was still worth nothing as a lever, with Cramér's V = 0.015 and 1.2 pp separating the best channel from the worst. **A methodological note worth keeping:** chi-square must receive the table of counts — run on percentages, the same test returns p = 0.993 instead of p = 0.034, because the statistic scales with the table total.

**Recommendation:** Implement Landing Page B for all traffic and treat the conversion gain as the prize, not the spending difference. Do not reallocate budget by channel or segment the roll-out by user type. Before the roll-out is final, validate the allocation formally (sample-ratio-mismatch and covariate-balance tests) and run the interaction and resampling analyses listed as next steps in the repository.

</details>

<details>
<summary><b>Where a Development Bank Should Fund Transit — 15 LatAm Cities · Python</b></summary>

#### 🎯 Objective
Determine where a development bank should invest in transport infrastructure by analyzing how urban mobility (congestion, delay) relates to economic productivity (GDP per capita, unemployment) across 15 Latin American cities.

[![VIEW REPOSITORY FILES](https://img.shields.io/badge/VIEW%20REPOSITORY%20FILES-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/maxsantana-data2strategy/urbanmobility_economicproductivity)
[![DOWNLOAD INFOGRAPHIC](https://img.shields.io/badge/DOWNLOAD%20INFOGRAPHIC-2ea44f?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://github.com/maxsantana-data2strategy/urbanmobility_economicproductivity/blob/main/assets/Infographic_UrbanMobility_LatAm_HighRes_1.png)

- **Data Integration** — Merged TomTom traffic records with OECD city economic indicators using city and year keys
- **Data Cleaning** — Standardized column formats, parsed European numeric formatting, converted timestamps, filtered to 2024
- **Aggregation** — Grouped traffic records by city to calculate mean delay, congestion, and travel-time metrics per city-year
- **Analysis** — Computed a congestion-to-productivity ratio and ran correlation analysis across GDP, congestion, unemployment, and population

#### 🛠️ Technologies
Python (pandas, numpy) | seaborn, matplotlib | Data wrangling & correlation analysis | Jupyter Notebook

#### 📊 Results

| City | GDP/Capita | Ratio | Profile |
|---|---|---|---|
| 🇨🇴 Bogotá | $11,442 | 0.100 | Highest urgency ⭐ |
| 🇵🇪 Lima | $13,472 | 0.078 | Highest urgency ⭐ |
| 🇲🇽 Mexico City | $21,111 | 0.134 | High-scale congestion |
| 🇧🇷 São Paulo | $14,703 | 0.118 | High-scale congestion |
| 🇧🇷 Brasília | $16,251 | 0.006 | Efficient benchmark |
| 🇺🇾 Montevideo | $26,176 | 0.002 | Efficient benchmark |

![Jams delay and GDP per capita by city](https://github.com/maxsantana-data2strategy/urbanmobility_economicproductivity/blob/main/assets/figure_1.png?raw=true)

#### 💡 Key Insight
The correlation matrix suggests that traffic jam is driven mainly by population size (r = 0.88), not GDP per capita (r = 0.28) as initially expected. Bogotá and Lima combine high traffic friction with lower economic output — the clearest case for investment. Mexico City and São Paulo show the highest absolute congestion, but it's scale-driven, not inefficiency. Montevideo and Brasília stand out as efficient benchmarks.

![Correlation matrix](https://github.com/maxsantana-data2strategy/urbanmobility_economicproductivity/blob/main/assets/figure_2.png?raw=true)

**Recommendation:** Prioritize transit investment in Bogotá and Lima for the highest expected economic return per dollar spent.

</details>

<details>
<summary><b> Which Federal Institutions Carry Procurement Risk — Public Sector · R & Tableau</b></summary>

#### 🎯 Objective
Identify corruption risk in public procurement across 260+ Mexican federal institutions by evaluating compliance with three principles: competition, transparency, and rule of law.

[![Access to full project description and check Repository Files](https://img.shields.io/badge/📂_View_Repository_Files-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/maxsantana-data2strategy/risk-corruption-index-IMCO)
[![Download Infographic JPG](https://img.shields.io/badge/📥_Download_Infographic_JPG-2EA44F?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/risk-corruption-index-IMCO/main/assets/Infographic_IRC_IMCO_EN.jpg)

#### 🔧 What I Did
1. **Research Support** — Supported the IRC project in a research capacity, focused on interpreting procurement risk findings
2. **Results Presentation** — Helped translate analytical results into clear insights and presentation materials for public policy audiences
3. **Stakeholder Reporting** — Contributed to progress reporting to USAID as project funder

#### 🛠️ Technologies
R (data analysis) | Tableau (interactive dashboard) | Public policy & governance research

#### 📊 Results
[![View IRC Report](https://img.shields.io/badge/📄_View_IRC_Report-100000?style=for-the-badge&logo=readthedocs&logoColor=white)](https://imco.org.mx/indice-de-riesgos-de-corrupcion/)
[![View Interactive Dashboard](https://img.shields.io/badge/📊_View_Interactive_Dashboard-2EA44F?style=for-the-badge&logo=tableau&logoColor=white)](https://imco.org.mx/riesgosdecorrupcion)

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy.github.io/main/imco-irc-dashboard.png" alt="IRC dashboard — public procurement risk by institution" width="700">
</p>

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/risk-corruption-index-IMCO/main/assets/IRC_2020_High_Spending_Institutions.png" alt="IRC score 2020 — institutions with annual spend over MXN 3,000M (IMCO)" width="700">
</p>

#### 💡 Key Insight
Between 2018 and 2020, corruption risk increased in 147 of 247 federal institutions (59%), driven by weak competition, low transparency, and non-compliance. The tool was adopted as a reference in Mexican public policy debates on transparency and institutional integrity.

</details>

### 🧪 Data Science

<img src="banner-data-science.gif" alt="Animated banner: a classifier searching for a decision boundary, with loss curve and confusion matrix" width="100%">

Where description gives way to modeling — estimating what is likely, what is uncertain, and how much the data can actually support. Methods chosen to fit the problem, validated against data they haven't seen, and reported with their limits rather than without them.

<details>
<summary><b>Does Curve Structure Beat a Naive Forecast — Sovereign Debt · Python (PCA + VAR)</b></summary>

#### 🎯 Objective
Determine whether the common structure of Mexico's nominal yield curve — nine maturities from CETES 28 days to MBONOS 30 years, 240 months of monthly auction rates — helps forecast it, and whether the answer changes with the horizon. The benchmark to beat is persistence: assuming rates stay where they are.

[![Access to full project description and check Repository Files](https://img.shields.io/badge/📂_View_Repository_Files-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/maxsantana-data2strategy/forecasting-mexican-yield-curve)
[![Download Infographic JPG](https://img.shields.io/badge/📥_Download_Infographic_JPG-2EA44F?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/forecasting-mexican-yield-curve/main/assets/Infographic_YieldCurve_EN.jpg)
[![Read the Notebook](https://img.shields.io/badge/📓_Read_the_Notebook-0366D6?style=for-the-badge&logo=jupyter&logoColor=white)](https://maxsantana-data2strategy.github.io/forecasting-mexican-yield-curve/analisis_curva_banxico_notebook.html)

#### 🔧 What I Did
1. **Missingness Audit as a First-Class Result** — Reshaped 1,936 long-format records into a monthly matrix and found the gaps appear only on date alignment: 26.2% missing at 10 years, 28.7% at 20, 30.0% at 30, with just **40 of 240 months** observing all nine maturities
2. **Causal Forward-Fill, Order Documented** — Each gap takes the last past observation, never future information, and the fill is applied **before** trimming the sample rather than after — `run_ffill_comparison.py` exists to compare the two orderings instead of assuming they are equivalent (239 levels, 238 monthly changes)
3. **PCA on Levels, Unstandardized** — Estimated on the nine rates so that genuine differences in variability across maturities survive; loadings read as level, slope and curvature without being imposed
4. **Benchmark Selected, Not Assumed** — Compared persistence, expanding historical mean and 12-month moving average; persistence won and became the reference for every comparison, rather than picking the weakest of the three
5. **Expanding-Window Evaluation with PCA Re-Estimated at Every Origin** — Training ends Sep 2022, origins start Oct 2022: 45 origins at h = 3, 36 at h = 12, with the factors re-fitted at each origin so no future information leaks into them

#### 🛠️ Technologies
Python (pandas, numpy) | `sklearn.decomposition.PCA` (fit on levels, `inverse_transform` for reconstruction) | `statsmodels.tsa.api.VAR` (VAR(1) on changes and on factor scores) | matplotlib, PIL | Expanding-window out-of-sample evaluation | Jupyter Notebook

#### 📊 Results

| Model | h = 3 RMSE | h = 3 MAE | h = 12 RMSE | h = 12 MAE |
|---|---|---|---|---|
| Persistence (benchmark) | 0.5499 | 0.4450 | 1.2723 | 1.0584 |
| Direct VAR(1) | **0.5103** ⭐ | **0.3992** | 1.2808 | 1.0680 |
| PCA(3) + VAR(1) | 0.5266 | 0.4193 | **1.1630** ⭐ | **0.9384** |

Average across the nine maturities, percentage points. Three components explain **99.38%** of the variation (PC1 level 94.09%, PC2 slope 4.60%, PC3 curvature 0.69%) and reconstruct the curve to **15.07 bp**.

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/forecasting-mexican-yield-curve/main/assets/figure_model_rmse.png" alt="Average RMSE by model and horizon — direct VAR(1) wins at 3 months, PCA + VAR(1) at 12 months" width="700">
</p>

#### 💡 Key Insight
**Explaining the curve and forecasting it are different problems.** Three factors account for 99.38% of the variation, and that compression still *costs* accuracy at three months: direct VAR(1) beats PCA + VAR(1) by 0.0163 RMSE there. At twelve months the ranking inverts — PCA + VAR(1) lands 8.6% below persistence while direct VAR(1) ends up 0.7% *worse* than doing nothing. No single specification dominates, so the honest output is a rule for choosing, not a winner. The limitation is stated in the same breath as the result: forward-fill can produce monthly changes of exactly zero, which makes some evaluated errors measure the last available auction rather than a new forecast — so the findings are labelled exploratory and the tests that would settle them are listed, not implied.

**Recommendation:** Select by horizon — direct VAR(1) at 3 months, PCA + VAR(1) at 12 — and fix the auction-availability treatment (cross-sectional curve estimation for unobserved months) before any decision use, since it is the limitation most likely to move the ranking.

</details>

### 🔮 Foresight

<img src="banner-foresight.gif" alt="Animated banner: a three-dimensional futures cone branching into four named scenarios, with a wild card breaking outside the cone" width="100%">

Not forecasting. The goal is not to predict the future but to see its possibilities and shape it. Driver analysis, scenario building, and horizon scanning used to stress-test strategy under deep uncertainty.

<details>
<summary><b>Can AI Group Geopolitical Risk Signals Like an Expert — Mexico · Python NLP — (In Progress)</b></summary>

#### 🎯 Objective
Determine which geopolitical factors organizations with Mexico operations should prioritize, and to what extent AI + data analysis can support (not replace) strategic judgment in horizon scanning.

[![View Repository Files](https://img.shields.io/badge/📂_View_Repository-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/maxsantana-data2strategy/horizon-scanning-geopolitical-risk-mx)

> **Status: 🟡 In Progress** — Analysis and documentation are ongoing.

#### 🔧 What I Did
1. **Scan Design & Signal Collection** — Structured horizon scan of 43 geopolitical risk signals for Mexico (1–10 year horizon): security, political economy, supply chains, regulatory risk
2. **AI-Assisted Classification** — Used Claude Sonnet to classify signals by driver, time horizon, and impact; audited AI output against expert judgment
3. **Quantitative Analysis** — Signal frequency by driver, correlation between AI severity scores and expert assessments, priority risk clusters
4. **Human Review Layer** — Documented where AI adds value (rapid classification, pattern detection) and where human judgment is irreplaceable (contextual interpretation, strategic sense-making)

#### 🛠️ Technologies
Python (pandas, SciPy, matplotlib) | Claude Sonnet (AI-assisted classification) | Jupyter Notebook | PIL/Matplotlib

#### 📊 Results
43 signals → 7 drivers identified. AI classification aligned with expert grouping in ~78% of cases. Security-related drivers dominate; regulatory fragmentation and supply chain risk are secondary clusters.

![Impact/Uncertainty Matrix — 43 geopolitical signals plotted by impact and uncertainty](https://github.com/maxsantana-data2strategy/horizon-scanning-geopolitical-risk-mx/blob/main/figures/fig1_miu.png?raw=true)

![Risk vs. Novelty by Driver — highest-novelty drivers have lowest risk scores, revealing the novelty penalty](https://github.com/maxsantana-data2strategy/horizon-scanning-geopolitical-risk-mx/blob/main/figures/fig2_drivers.png?raw=true)

#### 💡 Key Insight
**AI accelerates the scan but cannot replace the analyst.** The clearest value-add is speed and bias auditing. The clearest limitation: AI cannot weigh geopolitical signals against organizational strategy or local context without explicit human framing.

</details>

<details>
<summary><b>Four Futures for Humanitarian Aid to 2040 — IARAN · Scenarios & CLA</b></summary>

#### 🎯 Objective

1. To analyse potential changes in the global context and aid system by 2040
2. To identify concrete pathways for organisational transformation 
3. To develop tools and guidelines to support organisations in kick starting a transformative journey
   
#### 📊 Key metrics (Phase 1)

| Metric | Value |
|---|---|
| Consultations | 50+ |
| Survey constributions | 877+ |
| From the Global South | 77% |
| From local NGOs / CSOs | 44% |
| With lived crisis experience | ~40% |

#### 🧭 Scenario Matrix
Four scenarios mapped across two axes: network cooperation vs. survival of the fittest, and multipolar blocs vs. empires and conflict.

<p align="center"><img src="https://github.com/user-attachments/assets/14ccf88d-eb73-421d-bc81-8c4fd0893e8d" alt="2040 Aid Scenarios Matrix — four future scenarios for global humanitarian aid" width="700"></p>

#### 🔧 What I Did
1. **Trend Research** — Led documentary research on global trends and drivers of change impacting the future of aid
2. . **Stakeholder Facilitation** — Facilitated consultations in Mexico and Colombia and coordinated multiple stakeholders (strategic partners, consulted organizations) within project governance
3. **Multi-Phase Delivery** — Contributed across the project's three phases: foundations (Causal Layered Analysis), scenarios, and transformation pathways

#### 🛠️ Key Methodologies and skills
Strategic Foresight | Horizon Scanning | Causal Layered Analysis (CLA) | Scenario Building | Stakeholder Alignment | Project Management | Data analysis


<p align="center">
<img src="https://images.squarespace-cdn.com/content/v1/593eb9e7b8a79bc4102fd8aa/7c0c2c4b-f214-4e3e-949c-77cd23ebf370/39050001_neamoscou+redux.jpg" alt="Future of Aid 2040: Navigating the Next Humanitarian Horizon" width="180">
<img src="https://images.squarespace-cdn.com/content/v1/593eb9e7b8a79bc4102fd8aa/1760035233995-XO5JPU0R82RQKIQM0SJ3/IMG_0087_neamoscou.jpeg" alt="Unpacking the Aid System" width="180">
<img src="https://images.squarespace-cdn.com/content/v1/593eb9e7b8a79bc4102fd8aa/1778567955102-E81RF7563TNEDZJ31XOV/1.JPG" alt="Pathways to Transformation — P2T Guide" width="180">
<img src="https://images.squarespace-cdn.com/content/v1/593eb9e7b8a79bc4102fd8aa/1778567241580-LWEGEV0TLR4BWCYQCVRC/b01850018.jpg" alt="Pathways to Transformation — From Analysis to Action" width="180">
</p>

[![Scenarios Report](https://img.shields.io/badge/📄_Scenarios_Report-100000?style=for-the-badge&logo=readthedocs&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy.github.io/main/docs/future-of-aid/FutureOfAid2040_Scenarios_Report.pdf)
[![Unpacking the Aid System](https://img.shields.io/badge/📄_Unpacking_the_Aid_System-2EA44F?style=for-the-badge&logo=readthedocs&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy.github.io/main/docs/future-of-aid/FutureOfAid2040_UnpackingAidSystem_CLA.pdf)
[![Pathways to Transformation](https://img.shields.io/badge/📄_Pathways_to_Transformation-0366D6?style=for-the-badge&logo=readthedocs&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy.github.io/main/docs/future-of-aid/FutureOfAid2040_P2T_AnalysisToAction.pdf)

#### 💡 Key Insight
Synthesizing 877+ voices from 50+ organizations — most from the Global South — into four scenario frameworks and an organizational toolkit for humanitarian resilience under high uncertainty.

</details>

<details>
<summary><b>Policy Framework for the Creative Economy Under Disruption — Nuevo León · Foresight</b></summary>

#### 🎯 Objective
Build a foresight-based framework to turn uncertainty into opportunity for Nuevo León's creative and cultural industries, facing accelerated digital disruption, AI integration, and post-pandemic pressure.

[![View Project at CONL](https://img.shields.io/badge/🔗_View_Project_at_CONL-100000?style=for-the-badge&logo=googlechrome&logoColor=white)](https://conl.mx/proyectos/tierra-incognita-insertar-a-las-industrias-creativas-en-cadenas-de-valor-complejas-en-nl/)
[![One Pager](https://img.shields.io/badge/📄_One_Pager-2EA44F?style=for-the-badge&logo=readthedocs&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy.github.io/main/docs/tierra-incognita/TierraIncognita_OnePager.pdf)
[![Full Report](https://img.shields.io/badge/📄_Full_Report-0366D6?style=for-the-badge&logo=readthedocs&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy.github.io/main/docs/tierra-incognita/TierraIncognita_DocumentoCompleto.pdf)

#### 🔧 What I Did
1. **Workshop Design & Facilitation** — Designed and led strategic foresight workshops with creative-sector actors and key decision-makers
2. **Policy Translation** — Translated the foresight exercise into an actionable public policy framework (Logical Framework Approach)

#### 🛠️ Key Methodologies
Horizon Scanning | Scenario Building | Strategic Facilitation | Logical Framework Approach

#### 📊 Deliverables
Horizon scanning report for the creative economy | 4 future scenarios for Nuevo León's creative industries | Public policy framework (Logical Framework Approach) | Published strategic policy report

</details>

---

<p align="center"><i>🌐 Full portfolio with live project filters: <a href="https://maxsantana-data2strategy.github.io/">maxsantana-data2strategy.github.io</a></i></p>

---
