# 🌍 Global Inflation Dynamics (1980-2024) - A Comparative Power BI Analysis

## Project Overview

This Data Analytics project investigates historical and recent trends in annual average inflation (CPI) across the globe, with a specific focus on quantifying and visualizing the **economic stability gap** between **G7 (Developed)** and **BRICS (Emerging)** economic blocs.

The core challenge addressed was handling massive hyperinflationary outliers (e.g., Venezuela) that distort standard averages. The solution uses robust data engineering and advanced DAX metrics to provide reliable, action-oriented insights for financial risk analysts and economic policymakers.

## 🎯 Project Goals

1.  **Data Transformation:** Convert wide-format time-series data into a clean, long-format model using **Power Query's Unpivot Columns**.
2.  **Outlier Handling:** Implement the **`MEDIAN`** DAX measure to create reliable KPIs, ensuring the global average is not skewed by extreme inflation.
3.  **Comparative Analysis:** Visualize long-term inflation trajectories to clearly expose the historical volatility difference between G7 and BRICS.
4.  **Policy Insight:** Provide interactive filters and controls for stakeholders to quickly analyze synchronous global shocks versus isolated local inflation events.

## 📊 Key Analytical Insights

The dashboard confirms two major findings:

1.  **The Stability Gap:** Historically (1990s-2010s), the BRICS bloc maintained a median inflation rate significantly **higher and more volatile** than the G7 bloc, validating a persistent financial risk differential between the two groups.
2.  **Post-2020 Synchronization:** The period following 2020 shows an aggressive, simultaneous inflation spike across *both* G7 and BRICS, indicating that this crisis was driven by shared, **global supply-side shocks** rather than just isolated policy failures.
3.  **Data Integrity:** The dashboard validates the use of the Median metric by showcasing how stable countries (e.g., Japan, Switzerland) would otherwise be visually flattened by hyperinflationary outliers (e.g., Venezuela).

## 💻 Technical Stack

| Category | Tool / Language | Purpose |
| :--- | :--- | :--- |
| **Data Visualization** | **Power BI Desktop** | Dashboarding and Report Design |
| **Data Transformation** | **Power Query (M)** | Data Loading, Unpivot, Conditional Column (Bloc Categorization) |
| **Data Modeling** | **DAX** | Creation of robust measures (`Median Inflation`, KPIs) |
| **Data Source** | `global_inflation_data.csv` | Source of annual CPI rates (1980-2024) |
| **Version Control** | **Git / GitHub** | Project structure and submission |

## 📦 Project Deliverables

This repository contains all final files required for the project submission:

| File Name | Description |
| :--- | :--- |
| `global_inflation_dashboard.pbix` | **The final interactive Power BI Dashboard file.** |
| `DA_Final_Project_Report.pdf` | The complete, page-wise report documenting all phases (Problem, Prep, Design, Analysis, Future Scope). |
| `global_inflation_data.csv` | The raw source data file used in Power BI. |
| `Project_Demonstration.mp4` | Video walkthrough demonstrating the dashboard and key findings. |

## 🚀 How to Use the Dashboard

1.  **Clone the Repository:** Download the project files to your local machine.
2.  **Open Power BI:** Open the `global_inflation_dashboard.pbix` file using **Power BI Desktop**.
3.  **Interact:** Use the **Year Slider** to focus on specific periods (e.g., post-2020), or use the **Country Slicer** to compare a nation against the bloc median.
