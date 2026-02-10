# From Spark to Inferno: A Data Chronicle of COVID-19

![Project Status](https://img.shields.io/badge/Status-Completed-success) ![Language](https://img.shields.io/badge/Python-3.8%2B-blue) ![Library](https://img.shields.io/badge/Library-Pandas%20%7C%20PySpark-orange)

## 📖 Overview

**Data is just a collection of numbers until you find the "why" behind them.**

This project is not just a statistical report; it is a data-driven narrative of the COVID-19 pandemic. Using global datasets, we trace the timeline from the initial "whisper" of scattered cases in January 2020 to the "vertical wall" of infection in March, and finally to the massive regional inequalities of 2021.

The goal of this analysis is to uncover the **human story** hidden in the rows and columns—identifying how the virus moved, where containment failed, and how the world raced against time to improve survival rates.

## 📊 Key Storytelling Insights

Through rigorous data cleaning and time-series analysis, this project revealed four distinct chapters of the pandemic:

### 1. The Deceptive Spark (Jan 2020)
* **The Observation:** On Day 1 (Jan 22, 2020), data showed only single-digit cases in Mainland China.
* **The Insight:** This "calm" was an illusion. The virus had already fragmented across multiple provinces, seeding the ground for exponential growth before the world realized the danger.

### 2. The Vertical Wall (March 2020)
* **The Observation:** Daily cases jumped from ~500 to ~100,000 in weeks.
* **The Insight:** Containment failed. The curve didn't just rise; it hit a "chaotic plateau," proving that the virus was no longer knocking at the door—it had kicked it down.

### 3. The Engines of Infection (Regional Hotspots)
* **The Observation:** National totals were driven by massive regional outliers.
* **The Insight:** The pandemic was intensely local.
    * **England** accounted for **87%** of UK cases.
    * **Maharashtra** (India) alone had more cases (5.7M) than the entire country of Russia.
    * **Hubei** accounted for **75%** of early cases in China.

### 4. The Survival Gap (2020 vs. 2021)
* **The Observation:** Mortality rates dropped from ~4.9% (Q1 2020) to ~2.08% (Q2 2021), yet total deaths continued to rise.
* **The Insight:** Science won the battle for *survival* (better treatments), but lost the battle for *containment* (faster spread). A less lethal virus that infects millions is ultimately deadlier than a lethal one that moves slowly.

## 🛠️ Technologies Used

* **Python:** Core programming language.
* **Pandas / PySpark:** For high-performance data manipulation and aggregation.
* **Matplotlib & Seaborn:** For generating trend lines, bar charts, and comparative visualizations.
* **SQL:** Used for querying and filtering specific country-level data.

## 📂 Dataset

The analysis is based on time-series data containing:
* `ObservationDate`: Daily tracking of the timeline.
* `Country/Region` & `Province/State`: Geospatial granularity.
* `Confirmed`, `Deaths`, `Recovered`: Core impact metrics.

## 🚀 How to Run This Project

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/sohan-bot/Covid19-Data-Analysis.git](https://github.com/sohan-bot/Covid19-Data-Analysis.git)
    ```

2.  **Install dependencies:**
    ```bash
    pip install pandas matplotlib seaborn pyspark
    ```

3.  **Run the Analysis:**
    * Open the Jupyter Notebook `analysis.ipynb` to see the step-by-step storytelling.
    * Or run the script:
        ```bash
        python main.py
        ```

## 📈 Visualizations included
* **Daily Growth of New Cases:** A bar/line combo chart showing the transition from linear to exponential growth.
* **Active Cases vs. Deaths:** A dual-axis comparison showing the widening gap between infection rates and mortality.
* **Hotspot Concentration:** Tables highlighting the top provinces/states driving national numbers.

## 👤 Author
**Sohan**
* [GitHub Profile](https://github.com/sohan-bot)
* [LinkedIn](https://www.linkedin.com/in/sohan-phadikar-199a19191)

---
*This project is for educational and analytical purposes.*
