# Deterministic-Financial-Intelligence-Engine
A serverless financial modeling engine that performs automated 3-statement analysis, liquidity stress-testing, and risk detection using deterministic logic (non-LLM). Includes Excel ingestion and PDF reporting.
# 📈 FinSight: Deterministic Financial Intelligence Engine

> An institutional-grade financial analysis platform running entirely in the browser.

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Stack](https://img.shields.io/badge/tech-JavaScript%20%7C%20Tailwind%20%7C%20Chart.js-teal)

## 💡 Overview
FinSight is a **deterministic financial modeling tool** designed to automate the grunt work of equity research and credit analysis. Unlike LLMs which may hallucinate figures, this engine uses rigid accounting logic to analyze Income Statements, Balance Sheets, and Cash Flows.

It enables users to upload raw financial data, perform real-time sensitivity analysis, and generate automated risk assessment reports.

## 🚀 Key Features

*   **⚡ Automated 3-Statement Modeling:** Instantly links IS, BS, and CF to check for accounting discrepancies.
*   **🧠 Deterministic Logic Engine:** Rule-based algorithms that flag specific risks (e.g., "Negative CFO with positive Net Income," "Declining Interest Coverage").
*   **📂 Fuzzy-Logic Data Ingestion:** Intelligently parses uploaded Excel/CSV files, mapping non-standard line items (e.g., "Turnover" -> "Revenue") automatically.
*   **🎛️ Dynamic Scenario Planning:** Interactive sliders to stress-test key drivers like COGS inflation, Volume growth, and Interest rates.
*   **📊 Institutional Visualization:** Interactive, animated charts for Revenue Bridges, Cost Structures, and Cash Flow Dynamics.
*   **📄 Automated Reporting:** Generates downloadable PDF Investment Memos with analyst-grade commentary.

## 🛠️ Tech Stack

*   **Core:** Vanilla JavaScript (ES6+) - *No backend required*
*   **UI/Styling:** Tailwind CSS (Utility-first framework)
*   **Visualization:** Chart.js (Canvas-based rendering)
*   **Data Processing:** SheetJS (Excel parsing)
*   **Reporting:** jsPDF (Client-side PDF generation)

## 📊 Logic & Ratios Implemented

The engine automatically calculates and interprets:
*   **Profitability:** Gross Margin, EBITDA Margin, ROE, ROIC.
*   **Liquidity:** Current Ratio, Days Cash on Hand (DCOH), Working Capital Cycle.
*   **Solvency:** Net Debt/EBITDA, Interest Coverage Ratio, Altman Z-Score Proxy.
*   **Earnings Quality:** CFO-to-Net Income conversion ratios.


## 🚀 Getting Started

1.  Clone the repo:
    ```bash
    git clone https://github.com/yourusername/financial-intelligence-engine.git
    ```
2.  Open `index.html` in any modern web browser.
3.  Click **"Load Demo Data"** to see the simulation, or upload your own Excel file using the provided template.

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---
*Built by Ansh Kaushal for Financial Analysis & Engineering.*
