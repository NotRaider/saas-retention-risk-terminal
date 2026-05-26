# SaaS Retention & Risk Infrastructure Terminal

An interactive, real-time business intelligence monitoring terminal built in Power BI to isolate, quantify, and alert operators to systemic subscription churn and revenue risk.


## 🕹️ Interactive Dynamic States
### 🟢 Baseline State (System Operational)
*Global metrics evaluate to stable thresholds; retention remains within bounded safe parameters.*

### 🔴 1. Crisis State (Retention Collapse Selected)
*Selecting the Q4 volatility peaks instantly triggers a systemic cross-filtering event. Daily churn spikes to 4.32%, and the integrated DAX engine fires an automated high-visibility alert.*

<img width="1273" height="712" alt="image" src="https://github.com/user-attachments/assets/f914f914-13d7-47ec-ba7b-165c950d43a9" />

### 🟢 2. Baseline State (System Operational)
*When global macro filters are cleared, the dashboard dynamically resets to an operational baseline layout. The status banner updates to emerald green, confirming that active cumulative parameters fall within safe bounded thresholds.*

<img width="1267" height="710" alt="image" src="https://github.com/user-attachments/assets/3fbe2501-e834-4fa4-b940-356bbbc3bd24" />

## 📊 Core Infrastructure Features
* **Dynamic Risk Alert System:** Hand-coded DAX logic engine that monitors real-time daily churn thresholds (2% upper bound) and dynamically updates status messaging and interface background states (`#D4EFDF` Emerald vs. `#FADBD8` Crimson).
* **Revenue Deficit Meter:** Implemented financial exposure modeling using targeted baseline offsets to quantify cumulative cash-flow leakage ($825.22K macro deficit identified in Q4).
* **Cross-Filtering Diagnostics:** Enabled localized node filtering, allowing operators to click volatility peaks on macro timelines to instantly calculate localized impact parameters.

## 🛠️ Technical Stack & Frameworks
* **Analytics Engine:** Power BI Desktop
* **Data Modeling:** Star Schema Optimization (`fact_subscription_metrics`)
* **Logic Framework:** Advanced DAX (Data Analysis Expressions)

  ## 🚀 How to Use This Terminal

### 1. Local Exploration (Template Static Demo)
1. Clone this repository or download the `SaaS_Retention_Risk_Terminal.pbix` file directly.
2. Open the file using **Power BI Desktop** (latest version recommended).
3. Interact with the central timeline visual to explore cross-filtered states, dynamic alert responses, and financial meter modifications.

### 2. Custom Business Deployment (Production Grade)
This terminal architecture is optimized for a standard B2B SaaS star schema layout (`fact_subscriptions`, `dim_customers`, `dim_calendar`). To adapt this interface framework to your live corporate infrastructure:
* Ensure your schema mirrors the entity-relationship metrics outlined in the engineering documentation.
* Map your primary MRR/ARR keys to the target DAX metric folders.

*For custom enterprise deployment pipelines, database gateway configurations, or live API integration inquiries, feel free to open an issue or contact me directly via my profile.*
