# Azure Cloud Cost Optimization Advisor

![Azure Cost Optimization](https://img.shields.io/badge/Microsoft_Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white)

An intelligent tool that analyzes Azure billing data to:
- Identify top cost drivers
- Recommend service-specific optimizations
- Visualize spending trends
- Generate actionable savings plans

## 📦 Repository Contents
Azure Cloud Cost Optimization Advisor/
├── Azure_Cost_Optimization_Advisor.ipynb # Main notebook

├── azure_cost_data_sample.csv # Sample dataset

├── requirements.txt # Python dependencies

└── README.md # This file

## 🚀 Quick Start

1. **Prerequisites**:
   - Python 3.10+
   - Jupyter Lab/Notebook
   - Azure billing data (CSV export)

2. **Setup**:
   ```bash
   git clone https://github.com/yourusername/azure-cost-optimizer.git
   cd azure-cost-optimizer
   pip install -r requirements.txt
   jupyter notebook
Usage:

Upload your Azure billing CSV

Run all notebook cells

Review optimization recommendations

🔍 Key Features
Cost Visualization:

1. Daily/Monthly spend trends

2. Service-wise cost breakdown

AI-Powered Recommendations:

1. VM right-sizing suggestions

2. Storage tier optimization

3. Database cost reduction

Azure-Specific Insights:

1. Reserved Instance analysis

2. Spot VM opportunities

3. Service tier comparisons


📁 Data Requirements
Supported Azure billing formats:

Cost Management Exports:

1.CostInBillingCurrency column required

2. Date range filtering supported

3. EA/Billing Portal Exports:

4. Automatically normalized during import

5. Sample CSV included


