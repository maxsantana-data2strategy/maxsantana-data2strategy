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

## 📁 Projects

### 📊 Data Analysis / BI

<details>
<summary><b>Territorial Profitability Analysis — Adventure Works</b></summary>

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
<summary><b>ConnectaTel — Customer Behavior & Usage Segmentation</b></summary>

#### 🎯 Objective
Determine which customers drive the most value for a Latin American telecom by cleaning usage data, resolving data-quality issues, and segmenting customers by usage intensity and age.

[![Access to full project description and check Repository Files](https://img.shields.io/badge/📂_View_Repository_Files-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/maxsantana-data2strategy/connectatel-customer-behavior-analysis)

#### 🔧 What I Did
1. **Data Quality Diagnosis** — Detected sentinel values (`age` = -999, `city` = '?'), impossible dates (40 records dated 2026), and confirmed `duration`/`length` nulls were Missing At Random by usage `type`
2. **Cleaning** — Replaced sentinels, standardized dates, and preserved MAR nulls as meaningful signal rather than imputing them away
3. **Feature Engineering** — Aggregated 40,000 usage records into a per-user profile (messages, calls, call minutes)
4. **Outlier & Segmentation Analysis** — Used IQR and Z-scores to identify power users, then segmented all 4,000 customers by usage (`Low`/`Medium`/`High use`) and age

#### 🛠️ Technologies
Python (pandas, numpy) | seaborn, matplotlib | IQR & Z-score outlier detection | Rule-based segmentation | Google Colab

#### 📊 Results
`Medium use` is the largest usage segment; a consistent minority of 21–47 users per metric are high-volume "power users" retained as an upsell target rather than cleaned away as noise. `Basic plan` dominates every segment, including the heaviest users, pointing to under-monetized power users.

#### 💡 Key Insight
**Outliers were the opportunity, not the noise.** The heaviest 21–47 users per usage metric were kept — not trimmed — since they represent ConnectaTel's clearest upsell segment.

**Recommendation:** Design an ultra-premium tier for these power users and target `Medium use` customers, already the largest segment, for migration incentives toward `High use`/`Premium`.

</details>

<details>
<summary><b>Urban Mobility & Economic Productivity — Latin America</b></summary>

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
<summary><b> Risk Corruption Index (IRC in Spanish) — IMCO</b></summary>

#### 🎯 Objective
Identify corruption risk in public procurement across 260+ Mexican federal institutions by evaluating compliance with three principles: competition, transparency, and rule of law.

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

#### 💡 Key Insight
Between 2018 and 2020, corruption risk increased in 147 of 247 federal institutions (59%), driven by weak competition, low transparency, and non-compliance. The tool was adopted as a reference in Mexican public policy debates on transparency and institutional integrity.

</details>

### 🔮 Foresight

<details>
<summary><b>Future of Aid 2040 — IARAN</b></summary>

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
<summary><b>Geopolitical Risk & Horizon Scanning</b></summary>

#### 🎯 Objective
Actor mapping and strategic intelligence under conditions of high uncertainty for executive decision-making.

#### 🛠️ Key Methodologies
OSINT | Strategic Intelligence | Qualitative Risk Analysis

</details>

<details>
<summary><b>Tierra Incógnita: The Future of the Creative Economy — Nuevo León</b></summary>

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
