# AgroCal - Agribusiness Economic Viability Calculator

AgroCal is a web-based application designed to help users assess the economic viability of agribusiness projects. It provides a comprehensive set of tools for inputting project details, costs, revenues, and then calculates key financial indicators, performs sensitivity analysis, and helps in outlining a basic marketing plan.

## Features

* **Project Information:** Define basic project parameters such as name, type of business (aquaculture, livestock, agriculture, industrial production, etc.), duration, initial investment, Minimum Acceptable Rate of Return (MARR/TMA), SELIC rate, and expected inflation.
* **Cost Management:**
    * **Fixed Costs:** Input and manage Capital Expenditures (CAPEX) and Operational Expenditures (OPEX) with monthly values.
    * **Variable Costs:** Input and manage costs based on unit value and monthly quantity.
* **Revenue Management:** Define revenue streams with unit price, monthly quantity, and projected annual growth.
* **Tax Calculation:** Input relevant tax rates (e.g., ICMS, PIS, COFINS, Income Tax, CSLL) to be factored into financial projections.
* **Financial Indicators:**
    * Calculates Net Present Value (NPV / VPL).
    * Calculates Internal Rate of Return (IRR / TIR).
    * Determines Simple Payback and Discounted Payback periods.
    * Shows Average Annual Net Profit and Profitability.
    * Generates an annual Cash Flow table.
* **Sensitivity Analysis:**
    * Analyze the impact of changes in key variables (Revenue, Fixed Costs, Variable Costs, Initial Investment) on the project's NPV.
    * Visualize results through tables and charts.
* **Marketing & Neuromarketing Plan:**
    * Sections to outline a basic Marketing Plan (product description, target audience, competitive differential, pricing, channels, communication).
    * Sections to consider Neuromarketing aspects (emotional appeal, cognitive ease, storytelling, sensory elements, behavioral triggers).
* **Reporting & Data Management:**
    * View a summary of financial reports and key indicators.
    * Generate a detailed full project report.
    * **Save & Load Data:** Persist project data locally in the browser using localStorage.
    * **Clear Data:** Option to reset all inputs.
* **Export Options:**
    * Export reports and data to various formats:
        * PDF (Summary, Full Report, Cash Flow)
        * Excel (Summary, Full Data, Cash Flow)
        * CSV
        * JSON
* **User Interface:**
    * User-friendly interface built with Bootstrap.
    * Includes a Dark/Light theme toggle for user preference.
    * Interactive charts for visualizing financial data and sensitivity analysis (using Chart.js).
    * Tabbed navigation for easy access to different sections.
* **Language:** The application interface is in Portuguese (pt-BR).

## How to Use

1.  Open the `Agro2.html` file in a web browser.
2.  Navigate through the tabs on the left-hand menu to input your project data:
    * **Informações Básicas (Basic Information):** Fill in the general details of your project.
    * **Custos Fixos (Fixed Costs):** Add all fixed monthly costs (CAPEX and OPEX).
    * **Custos Variáveis (Variable Costs):** Add all variable costs.
    * **Receitas (Revenues):** Define your revenue sources and growth expectations.
    * **Impostos e Taxas (Taxes and Fees - implicitly part of Revenue/Financials):** Ensure tax rates are set correctly in their respective input fields (usually under the Revenue or a dedicated tax section if present).
3.  Once all data is entered, click the "Calcular Tudo" (Calculate All) button, typically found in the "Informações Básicas" or a summary section, to process the calculations.
4.  Explore the results:
    * **Indicadores Financeiros (Financial Indicators):** Review NPV, IRR, Payback, and other metrics. Analyze the cash flow table.
    * **Análise de Sensibilidade (Sensitivity Analysis):** Perform sensitivity tests on different variables.
    * **Plano de Marketing (Marketing Plan):** Fill in details for your marketing and neuromarketing strategy.
    * **Relatórios (Reports):** View summary reports and generate detailed ones.
5.  Use the "Dados" (Data) menu to Save your current data, Load previously saved data, or Clear all inputs.
6.  Use the "Exportar" (Export) menu to download your data/reports in PDF, Excel, CSV, or JSON formats.

## Technologies Used

* HTML
* CSS (with Bootstrap 5.3.0)
* JavaScript
* Bootstrap Icons 1.10.0
* Chart.js (for charts)
* jsPDF (for PDF export)
* XLSX (SheetJS) (for Excel export)

---
