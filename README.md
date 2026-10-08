### 1. Project Title 
**Loan Default Risk Analysis & Portfolio Strategy Dashboard**
An executive-level Power BI and Python analytics suite designed to uncover the true predictive drivers of loan defaults—moving beyond raw credit scores to evaluate multidimensional risk across income bandwidth, employment stability, and financial leverage.

### 2. Short Description 
This project provides a robust, data-driven framework for minimizing loan default risks. By leveraging Python for rigorous Exploratory Data Analysis (EDA) and Power BI for interactive portfolio monitoring, the dashboard equips risk managers and product strategists to identify toxic borrower cohorts, adjust approval matrices, and optimize credit policies.

### 3. Tech Stack
The project was built using the following tools and technologies:
* 🐍 **Python (Jupyter Notebook, Pandas, Seaborn, Matplotlib)** – Executed comprehensive EDA, statistical profiling, univariate/bivariate analysis, feature engineering (DTI quintiles, custom bins), and visual hypothesis testing on a pristine dataset.
* 📊 **Power BI Desktop** – Designed the interactive tracking dashboard with a clean, executive UI, dynamic visuals, and synchronized slicers.
* 🧠 **DAX (Data Analysis Expressions)** – Engineered calculated measures for core KPIs (e.g., Overall Default Rate) and dynamic categorical grouping via `SWITCH` statements (e.g., Income Bands, Credit Score Bands).
* 📄 **File Format** – `.ipynb` for analytical methodology, `.pbix` for dashboard development, and `.png` for repository previews.

### 4. Data Source
**Source:** Historical Bank Loan Data
* Analyzed a fully populated dataset of 255,347 loan applications.
* **Attributes included:** 19 distinct features ranging from continuous financial metrics (Income, Loan Amount, Interest Rate, DTI Ratio) to categorical borrower traits (Employment Type, Loan Purpose, Co-Signer Status).
* **Time period:** 2013-2018.

### 5. Features / Highlights

**Business Problem**
The institution faces a baseline loan default rate of 11.61%. Relying on traditional, one-dimensional metrics like raw credit scores creates evaluation blind spots, leading to capital erosion through non-performing assets. A holistic, multidimensional framework is required to understand how compounding factors like low income, debt leverage, and employment type interact to elevate risk.

**Goal of the Dashboard**
To operationalize data-driven insights into a continuous monitoring tool. The dashboard empowers decision-makers to track portfolio health, isolate structural risks, and implement targeted credit policies—such as capping DTI limits or introducing dynamic co-signer requirements for high-risk profiles.

**Walkthrough of Key Visuals**
* **Executive KPI Ribbon:** A unified header tracking vital portfolio health metrics: Default Rate (11.61%), Total Defaults (30K), Average Credit Score (559), Average Loan ($144.52K), and Average DTI Ratio (0.51).
* **Income vs. Credit Score Matrix:** Highlights the critical finding that absolute income bandwidth outweighs historical credit scores, with "Low" income borrowers defaulting at high rates regardless of their credit tier.
* **Co-Signer Risk Buffer:** Visualizes the protective impact of co-signers, showing a drop in average default rates from 12.87% (unbacked) to 10.36% (backed).
* **Employment & Loan Purpose:** Tracks the outsized default risk presented by unemployed and part-time applicants across all loan products (Auto, Business, Education, Home).

### 6. How to Navigate This Project (For Recruiters & Non-Technical Viewers)
If you are reviewing this portfolio and do not have analytical software installed, you can still easily explore the full project directly in your browser:

Read the Business Case: Click on Loan Defaults Report.pdf to read the complete executive summary, data findings, and strategic business recommendations.

View the Dashboard: You do not need Power BI to see the final dashboard. Click on Page_1_dashboard.PNG and Page_2_dashboard.PNG to view high-resolution screenshots of the final interactive tool.

Explore the Code: Click on Loan_Default_EDA.ipynb to view the Python code, statistical breakdowns, and charts used to test the business hypotheses. GitHub will render this file directly in your browser.

Interact with the Dashboard (Technical Users): If you have Power BI Desktop installed, download the Loan_Defaults_Dashboard.pbix file to click through the interactive filters and explore the data model yourself.

### 7. Contact
If you have any questions about this project or would like to discuss data and product analytics opportunities, feel free to reach out.

Yash Baghel

LinkedIn:[ (https://www.linkedin.com/in/yash-baghel-linkdin/?isSelfProfile=true)](https://www.linkedin.com/in/yash-baghel-linkdin/?isSelfProfile=true)

Email: yashbaghel47z@gmail.com



