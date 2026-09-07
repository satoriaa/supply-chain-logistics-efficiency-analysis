# Supply Chain Logistics & Operational Efficiency Analysis

## 📌 Project Overview
This project focuses on diagnostic Exploratory Data Analysis (EDA) of global supply chain logistics. As a Data Analyst, the objective is to evaluate operational bottlenecks, analyze cost efficiencies, track disruption risks, and provide actionable business recommendations to optimize supply chain performance without relying on complex predictive machine learning models.

## 📊 Dataset Information
* **Source:** Supply Chain Dataset (Kaggle - Natasha0786)
* **Key Metrics Analyzed:** Shipping costs, lead time days, customs clearance time, disruption likelihood score, supplier reliability, and order fulfillment status.

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Google Colab, Tableau Public

## 🔍 Key Steps & Workflow
1. **Data Cleaning & Preprocessing:** Handling missing values, standardizing columns, and validating data types.
2. **Feature Engineering:** Creating calculated fields such as cost per demand, delay indicators, and risk groupings.
3. **Exploratory Data Analysis (EDA):**  
   * Analyzing correlation matrices to evaluate linear dependencies among operational variables.
   * Aggregating supplier performance metrics across different countries.
4. **Diagnostic Insights:** Assessing distribution patterns of logistics bottlenecks and operational risks.

## 📈 Key Findings & Business Insights
* **Variable Independence:** Correlation matrix analysis reveals that primary operational metrics (such as shipping costs, lead times, and disruption likelihood scores) operate independently in a linear context, indicating that high shipping costs do not inherently guarantee shorter lead times.
* **Risk Consistency:** Disruption likelihood scores remain consistently high across various supplier regions, highlighting systemic vulnerabilities rather than localized anomalies.
* **Cost vs. Performance:** Evaluating cost per demand allows stakeholders to identify disproportionate logistics expenditures relative to regional order volumes.

## 🚀 Strategic Business Recommendations
* **Vendor Diversification:** Supply chain management should re-evaluate high-cost or high-risk supplier regions to negotiate better SLAs.
* **Bottleneck Mitigation:** Focus operational monitoring on customs clearance times and lead-time variabilities to improve predictability.
* **BI Dashboard Integration:** Transition these analytical findings into an interactive Tableau dashboard for real-time executive monitoring.

## 📊 Tableau Interactive Dashboard
The final diagnostic metrics have been compiled into an executive dashboard to monitor shipping costs and lead times by supplier country interactively.



![Supply Chain Performance Overview](./Screenshot%202026-09-08%20002410.png)

## 📂 Repository Structure
```text
nama-proyek-supply-chain/
│
├── screenshoot             
├── data/                    
│   └── cleaned_supply_chain_data.csv # Cleaned dataset used for visualization
├── notebook/                
│   └── supply_chain_eda.ipynb      # Google Colab notebook for data preprocessing & EDA
└── README.md                # Project documentation
