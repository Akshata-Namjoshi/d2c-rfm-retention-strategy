# Part 2: RFM Segmentation & Retention Strategy

## 📌 Project Overview
This is Part 2 of the D2C Churn Prediction Capstone. 
In this module, we moved beyond simple exploratory analysis to build a robust RFM (Recency, Frequency, Monetary) segmentation engine. 

Instead of a generic RFM model, we enriched the scoring logic with "Unhappiness Signals" (Support Tickets) and "Cost Signals" (Returns) to identify profitable but dissatisfied customers who might be overlooked by standard revenue metrics.

## 📂 Repository Contents
| File | Description |
| :--- | :--- |
| `rfm_segmentation.ipynb` | The Python code that performs feature engineering and assigns the 7 segment labels. |
| `segments.csv` | Final Output: The tagged dataset containing RFM scores and Segment Names for all 2,400 customers. |
| `retention_strategy.md` | A strategic business report outlining budget allocation and actions for each segment. |
| `manual_review_cases.md` | A detailed audit of 10 specific edge-case customers (e.g., High Spenders with >3 complaints). |
| `rfm_segments_chart.png` | Visualization of customer distribution (Recency vs Frequency). |
| `requirements.txt` | List of Python libraries required to run this project. |

## 📊 Key Insights & Methodology
We classified customers into 7 distinct segments using quintile scoring (1-5 scale).

### The "High Maintenance" Discovery
We identified a critical segment of 103 customers we labeled as "High Maintenance".
- Behavior: They are our highest spenders (Avg LTV: $6,644), but they are extremely unhappy (Avg 3.4 support tickets).
- Risk: Standard RFM would label them "Champions" due to high spend, masking their high churn risk.
- Action: We prioritized this group for a "White Glove" manual service audit.

### The "At Risk" Opportunity
We identified 228 customers as "At Risk".
- Behavior: High historical frequency (Avg 6.2 orders) but haven't visited in over 6 months.
- Action: Allocated 50% of the retention budget to win-back campaigns for this specific group.

## 🚀 How to Run
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
