# 🚀 Power BI Dashboard: ServiceNow Enhancements & Azure DevOps Features

## 📝 Overview
This project presents an **interactive Power BI dashboard** that bridges ServiceNow enhancement requests with Azure DevOps (ADO) features. The dashboard provides insights for both **customers** and **internal teams**, enabling efficient tracking of work status, progress, and developer allocation.

Additionally, **missing values** in the dataset were intelligently **predicted using dspy**, ensuring comprehensive analysis.

## 📊 Key Features
- **Work Status Tracking**: Real-time updates on enhancement request progress.
- **Completion Progress**: Displays percentage completion of each request.
- **Estimated Start Date**: Predicts start dates for pending tasks.
- **Customer Distribution**: Visualizes customer enhancement requests.
- **Developer Allocation**: Shows task distribution among developers.
- **Summarization of Long Descriptions**: Uses NLP to create concise summaries.

## 📁 Files Included
- `DEN_Hack.ipynb` - Jupyter Notebook for **data preprocessing & prediction of missing values using dspy**.
- `DEN_Dashboard-2.pdf` - Final **Power BI dashboard** with interactive visualizations.

## 🛠️ Installation & Setup
### **Power BI Dashboard**
1. Open **Power BI Desktop**.
2. Load the dataset (ensure correct paths).
3. Use the **Power Query Editor** for any modifications.
4. View interactive insights through dashboard elements.

### **Jupyter Notebook (dspy-based Predictions)**
1. Install dependencies:  
   ```bash
   pip install dspy pandas numpy matplotlib
   ```
2. Open the notebook:  
   ```bash
   jupyter notebook DEN_Hack.ipynb
   ```
3. Run all cells to process data and predict missing values.

## 🔮 Insights & Impact
This dashboard enhances decision-making by:
✅ Empowering customers with real-time progress tracking.  
✅ Helping internal teams balance workload & project timelines.  
✅ Predicting missing data for more **accurate insights**.  
✅ Improving transparency & efficiency in enhancement request handling.

## 🎯 Future Improvements
🔹 Implement **real-time data sync** with ServiceNow & Azure DevOps APIs.  
🔹 Enhance **predictive modeling** for task timelines.  
🔹 Integrate **automated anomaly detection** for request delays.  
