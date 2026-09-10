# 📊 Customer Churn & Retention Correlation Analysis

Interactive dashboard to analyze the correlation between **Expired** and **Active** customer subscription data.

## 🚀 Live Demo
[View Dashboard](https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/)

## 📁 How to Use with Your Data

### Option 1: Upload Files Directly
1. Open the dashboard
2. Click "Upload Expired Data" and select your `.xlsx` or `.csv` file
3. Click "Upload Active Data" and select your `.xlsx` or `.csv` file
4. Dashboard auto-analyzes!

### Option 2: Load from Repository
1. Place your Excel files in the `/data/` folder:
   - `data/expired_customers.xlsx`
   - `data/active_customers.xlsx`
2. Click "Load from Repository /data/ Folder" button
3. Dashboard loads and analyzes!

### Option 3: Simulation Mode
- Adjust parameters (count, overlap %) and click "Run Simulation"

## 📋 Expected Excel Format

| Subscription Id | CompGUID | GSTIN | current_bls_expiry |
|---|---|---|---|
| SUB-100001 | a1b2c3d4-... | 27AAACR5055K1Z5 | 2024-12-31 |
| SUB-100002 | b2c3d4e5-... | 29AABCU9603R1ZP | 2025-03-15 |

> Column names are auto-detected. Close matches work too!

## 📊 What It Analyzes
- **CompGUID Overlap** — Companies present in both datasets (partial churn)
- **GSTIN Overlap** — Same legal entity in both datasets
- **Churn Rate** — % of companies that fully left
- **At-Risk Customers** — Active subscriptions nearing expiry
- **State-wise Churn** — Geographic churn patterns from GSTIN
- **Subscription Density** — Multi-subscription companies

## 🛠️ Setup on GitHub Pages
1. Fork/Clone this repo
2. Go to Settings → Pages → Source: `main` branch
3. Your dashboard is live!

## 📥 Downloads Available
- Full analysis report (CSV/Excel)
- Overlap customer data
- Template Excel file
