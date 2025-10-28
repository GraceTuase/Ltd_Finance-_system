# **SMEs Business Accounting & Compliance Tool (UK)**

This is a comprehensive, all-in-one accounting and financial reporting tool built from scratch for UK small/micro limited companies. It's a single-file web application that runs entirely in the browser, requiring no backend or databases.

It is designed to solve the most common and complex accounting headaches for small business owners, from daily bookkeeping to automated, compliant statutory reporting for Companies House.

### **Key Features Implemented**

* **Multi-Profile Management:** A secure, client-friendly dropdown menu allows you to manage the accounts for multiple businesses from a single file, with all data saved locally in the browser.  
* **Full Double-Entry (Simplified):** A complete ledger for logging all transactions (income and expenses), customers, invoices, assets, and liabilities.  
* **Automated VAT Calculations:** The transaction log includes a VAT-rate selector, which automatically calculates VAT-in and VAT-out. The dashboard displays a real-time **"VAT Due to HMRC"** KPI.  
* **Live Dashboard:** A real-time dashboard with charts and KPIs for:  
  * Revenue vs. Budget  
  * Expense Breakdown  
  * Net Profit  
  * Cash at Bank  
  * Accounts Receivable (Overdue vs. Pending)  
* **Statutory P\&L Statement:** Automatically generates a complete, print-ready **Profit & Loss (P\&L) Statement** from the transaction log.  
* **Statutory Balance Sheet:** Automatically generates a print-ready, fully balancing **Balance Sheet** by pulling data from all modules (cash, assets, liabilities, and retained earnings from the P\&L).  
* **Comparative Reporting:** A bank-ready feature that allows you to "snapshot" your financials at year-end and generate a 3-5 year comparative report, essential for loan applications.  
* **Full Data Portability:** Every single data table (Transactions, Customers, Budgets, etc.) is fully exportable and importable via **CSV**.

### **Technologies Used**

* **HTML5:** For the core structure and layout.  
* **CSS3 (Custom):** All styling is hand-coded using modern, custom CSS for a clean, reliable, and high-contrast user interface. No frameworks were used.  
* **JavaScript (ES6+):** All logic is handled by client-side JavaScript, including:  
  * All financial calculations (P\&L, Balance Sheet, VAT).  
  * State management via localStorage for the multi-profile system.  
  * Chart.js for interactive dashboard visualisations.  
  * CSV import/export and PDF printing functions.
