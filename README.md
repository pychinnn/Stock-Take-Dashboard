# Stock Take Dashboard (Power BI)
## Executive Summary
This project presents an interactive Stock Take Dashboard built using Power BI to monitor inventory accuracy, financial variance, and stock counting efficiency across 17 outlets and product categories.
The dashboard is designed to support both operational monitoring and decision-making, helping users quickly identify discrepancies and their root causes.

## Objectives
* Track stock accuracy trends over time
* Analyse financial variance (surplus vs shortage)
* Identify high-risk categories and outlets
* Highlight the top 3 contributing SKUs causing variance
* Evaluate stock counting efficiency

## Data-Driven Insight and Bottleneck Identification
### 1. Stock Take Dashboard Front Page
Overall stock accuracy improved from **June 2024 to July 2024**. However, the net financial variance across the two months is **-RM68,265**, comprising a surplus of **RM205,851** and a shortage of **-RM274,117**.
**Store01** recorded the **highest stock accuracy** (88.8%), while **Store16** showed the **lowest net financial variance** (RM159.23).
Across all 10 categories, **MEAT** is the most problematic, with **RM134,896** in surplus and **-RM107,148** in shortage. **Store04** has the **highest variance** in this category, while **Store13** has the lowest, suggesting that **operational processes** are likely the root cause.
<img width="1307" height="735" alt="image" src="https://github.com/user-attachments/assets/07cbd6a4-dd21-43e3-ac1c-cb4e8f343096" />

### 2. Overall Monthly Stock Accuracy Trend
In July 2024, a total of **11,353 items** were counted across 17 outlets. Of these, **1,428 items** did not match system records, resulting in an overall accuracy rate of **87.42%**. 
<img width="1309" height="735" alt="image" src="https://github.com/user-attachments/assets/5a85322f-f741-4370-b076-1c1d41d9354e" />

### 3. Stock Accuracy and Financial Variance by Outlets 
**Store01** achieved the **highest stock accuracy** among all outlets. Its overall financial variance is **-RM3,779** across **163 items**.
The **highest first-count accuracy** (92.25%) suggests a shorter stock counting period, **minimizing operational disruption**.
<img width="1307" height="735" alt="image" src="https://github.com/user-attachments/assets/db6ea3ed-9785-4ba2-8795-f51574f9ad9b" />

### 4. Financial Variance by Category
The **MEAT** category recorded **-RM134,896** in shortage and **RM107,148** in surplus, contributing **50.42% of total variance**.
However, the **largest financial loss** among all categories is attributed to **DRYGOODS**.
<img width="1309" height="735" alt="image" src="https://github.com/user-attachments/assets/b9c25f0f-a5d2-41a1-9a81-bd399bcd49ab" />

### 5. Overall Variance by Categories and Outlets
There is a suspected **contra** issue between **Kampung Eggs 10s** and **QL Sandy Egg Nature Feed**. This may be due to **staff confusion** between similar internal products. 
<img width="1308" height="735" alt="image" src="https://github.com/user-attachments/assets/bd957bb5-ceb1-487e-adc9-df744e16be55" />

### 6. Overall Result in June 2024
When filtered for June 2024, the net financial variance across all outlets is -RM42,013.
The primary issue remains within the Meat category, indicating that process improvements are required in handling and stock counting.
<img width="1307" height="736" alt="image" src="https://github.com/user-attachments/assets/aa6c0771-f07f-49c5-99a2-c2c95439fb96" />

### 7. Result for Meat in July 2024
In July 2024, Store14 achieved the highest accuracy in the Meat category, suggesting that its operational process could serve as a benchmark. 
<img width="1307" height="734" alt="image" src="https://github.com/user-attachments/assets/d59b867c-2558-4305-9831-6f29c027b028" />

### 8. Result for Store 01 in July 2024
The dashboard indicates a contra issue involving egg products within the same month. There is a high likelihood of reversal in the following month.
While MEAT is the main issue across most outlets, Store17 shows significant variance in DRYGOODS.
<img width="1307" height="735" alt="image" src="https://github.com/user-attachments/assets/f49a3436-41d7-416e-b88b-c4216f1af7b0" />

## Recommendations
Based on the data analysis, I proposed the following turnaround strategy to the client:
* **Standardize Stock Count Procedures**: Implement a consistent stock counting process across all outlets, using Store14 as a benchmark for best practices (especially for Meat).
* **Target High-Risk Categories (Meat & Dry Goods)**: Introduce tighter controls, frequent cycle counts, and clearer handling procedures for categories with the highest variance.
* **Improve Staff Training on Product Identification**: Address contra issues (like similar egg products) by enhancing product knowledge and labelling clarity.
* **Introduce Cycle Counting**: Conduct daily cycle counts to detect the discrepancies earlier.
* **Strengthen Accountability by Outlet**: Track and review performance at the outlet level, focusing on high-variance stores such as Store04.

*Note: The data in this repository has been anonymized to protect client confidentiality.*
