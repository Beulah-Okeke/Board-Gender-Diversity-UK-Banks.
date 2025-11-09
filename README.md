# 🌟 Project Title: Board Gender Diversity and Corporate Financial Performance in UK Commercial Banks (FTSE 100)

## 👩‍💼 Summary

This dissertation project presents a quantitative panel data analysis of four leading UK commercial banks (Barclays, HSBC, Lloyds, and NatWest) from 2010 to 2023. The study investigates the relationship between corporate governance variables and financial performance (Return on Assets, ROA), applying advanced econometric techniques to address key questions in modern corporate governance.

## 🎯 Key Findings & Policy Implications

The Random Effects Model results yielded clear, policy-relevant findings:

* **Gender Diversity Matters:** Board Gender Diversity demonstrated a statistically **significant positive impact** on Return on Assets (ROA). An increase in the board's gender diversity by 1% is associated with a 2.05% improvement in financial performance, holding other factors constant (Random Effects Regression Coefficient: **0.0205**, $p < 0.05$. This supports the idea that diverse boards enhance decision-making and is in line with the UK's corporate governance reforms.
* **Leverage Risk:** The control variable, Leverage (Total Liabilities/Total Assets), showed a strong and statistically **significant negative relationship** with ROA (Coefficient: **-0.0011**, $p < 0.01$ ). This highlights that higher reliance on debt financing is linked to lower profitability, aligning with the concept that higher financial risk negatively impacts performance.
* **Non-Significant Factors:** The study found **no statistically significant impact** of Board Size or Board Independence on financial performance (ROA).

## 🛠️ Methodology

The analysis was conducted using a **Balanced Panel Data** approach, covering **56 observations** across the four banks from 2010 to 2023.

| Aspect | Detail |
| :--- | :--- |
| **Model** | **Random Effects Model (REM)** , validated by a **Hausman Test** (p-value = 0.8671). |
| **Variables** | **Dependent:** Return on Assets (ROA). **Independent (Core):** Gender Diversity, Board Size, Board Independence. **Control:** Firm Size (Total Assets), Leverage. |
| **Software** | **RStudio** for data manipulation, panel data estimation (`plm`), and visualization (`ggplot2`). |

## 📊 Analysis and Visual Results

The project is driven by visual analysis of trends and robust econometric results.

### Descriptive Statistics & Correlation

| Table/Chart | Insight |
| :--- | :--- |
| **** | Shows the high average level of Board Independence (74%) and the progression of Gender Diversity (average 29.8%). |
| **** | Confirmed a moderately positive correlation between Gender Diversity and ROA (0.3192), and a significant negative correlation for Leverage and ROA (-0.5561). |

### Key Variable Trends (2010–2023)

| Governance/Performance Variable | Bank Example | Key Trend |
| :--- | :--- | :--- |
| **Gender Diversity** |  | [As shown below in the visualization] Shows a consistent and strong upward trend, nearing the 40% mark, reflecting adherence to corporate governance initiatives[cite: 277, 278]. |
| **ROA** |  | [As shown below in the visualization] Illustrates significant profitability enhancement, moving from negative to consistent positive values post-2015. |
| **Board Independence** |  | [As shown below in the visualization] Shows a generally high level of independence, albeit with some volatility, underscoring the role of non-executive directors. |
| **Board Size** |  | [As shown below in the visualization] Demonstrates efforts to maintain a consistent board size, which is noted to be less volatile than some peers. |

### Control Variable Trends

| Control Variable | Bank Example | Key Trend |
| :--- | :--- | :--- |
| **Firm Size** |  | [As shown below in the visualization] Illustrates the asset movement of a large, volatile bank, reflecting diverse asset management and operational approaches. |
| **Leverage** |  | [As shown below in the visualization] Shows a general decline until the mid-2010s, followed by an increase, reflecting post-crisis deleveraging and later expansion strategies. |

### Final Econometric Results

| Test/Model | Result/Significance |
| :--- | :--- |
| **Hausman Test** | [As shown below in the visualization] (P-value: 0.8671) – **Fail to Reject Null** (Random Effects suitable). |
| **Random Effects Model** | [As shown below in the visualization] (Gender Diversity $p < 0.05$, Leverage $p < 0.01$) – The model is statistically significant with an F-statistic of **37.37*** ($p < 0.01$). |

---

## 🔗 Repository Structure

* `/data/`: Raw data collected from annual reports (not included).
* `/analysis/`: **Contains the full set of visualizations and econometric outputs.**
    * `Board_Independence_*`
      **BARCLAYS Visualization**
      ![my first screenshot](images/Board_Independence_BARCLAYS.png)
      **HSBC Visualization**
       ![my first screenshot](images/Board_Independence_HSBC.png)
      **LLOYDS Visualization**
       ![my first screenshot](images/Board_Independence_LLOYDS.png)
      **NATWEST Visualization**
       ![my first screenshot](images/Board_Independence_NATWEST.png)

    * `Board_Size_*`
      **BARCLAYS Visualization**
      ![my first screenshot](images/Board_Size_BARCLAYS.png)
      **HSBC Visualization**
       ![my first screenshot](images/Board_Size_HSBC.png)
      **LLOYDS Visualization**
       ![my first screenshot](images/Board_Size_LLOYDS.png)
      **NATWEST Visualization**
       ![my first screenshot](images/Board_Size_NATWEST.png)
    * `ROA_*`
      **BARCLAYS Visualization**
      ![my first screenshot](images/ROA_BARCLAYS.png)
      **HSBC Visualization**
       ![my first screenshot](images/ROA_HSBC.png)
      **LLOYDS Visualization**
       ![my first screenshot](images/ROA_LLOYDS.png)
      **NATWEST Visualization**
       ![my first screenshot](images/ROA_NATWEST.png)
      
    * `Gender_Diversity_*.png`
      **BARCLAYS Visualization**
      ![my first screenshot](images/Gender_Diversity_BARCLAYS.png)
      **HSBC Visualization**
       ![my first screenshot](images/Gender_Diversity_HSBC.png)
      **LLOYDS Visualization**
       ![my first screenshot](images/Gender_Diversity_LLOYDS.png)
      **NATWEST Visualization**
       ![my first screenshot](images/Gender_Diversity_NATWEST.png)
    * 
  
