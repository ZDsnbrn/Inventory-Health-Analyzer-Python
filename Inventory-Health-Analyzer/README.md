
# 🚀 Inventory Health Analyzer + Reorder Alert System (Python)

This project analyzes inventory performance for a fictional aerospace company, **AstroDynamics**, using Python. It identifies critical SKUs at risk of stockouts and provides a streamlined alert system using real inventory logic.

## 📂 Project Structure
```
Inventory-Health-Analyzer/
├── data/
│   └── AstroDynamicsCleaned_Dataset.csv
├── notebooks/
│   └── inventory_analysis.ipynb
├── output/
│   └── critical_inventory_alerts.xlsx
├── src/
│   └── [placeholder for modular scripts]
└── README.md
```

## 📊 KPIs & Business Logic
- **Days of Supply** = Current Stock / Avg Daily Usage
- **Inventory Turnover** = (Avg Daily Usage * 365) / (Current Stock / 2)
- **Reorder Alert** = Current Stock ≤ Reorder Point
- **Critical Alert** = Status = CRITICAL or Supply Gap = UNDERORDERED

## 🔎 Key Features
- Flags inventory health risks using reorder and risk logic
- Visualizes top 10 critical parts by inventory value
- Exports alert summary to Excel
- Clean and readable code for real-world interview prep

## 📈 Tools Used
- `Pandas` for data handling
- `Matplotlib` + `Seaborn` for visualization
- `Jupyter Notebook` for analysis workflow
- `Excel` for final output

## ✅ Use Cases
Ideal for Inventory Analysts, Supply Chain Planners, or Data Analysts looking to showcase applied Python in a business context.

---

Built by Z Sanborn | Portfolio Project • 2025
