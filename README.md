\# 🏦 Bank Loan Insights — Power BI Project



\## 📌 Overview

This project delivers \*\*data-driven insights into bank loan performance\*\* using \*\*Power BI\*\*.  

It leverages a structured financial loan dataset and builds interactive dashboards to analyze borrower behavior, repayment performance, risk segmentation, and profitability.  



The objective is to \*\*empower stakeholders\*\* with actionable intelligence for \*\*credit risk management, loan approval strategies, and revenue optimization\*\*.



---



\## 📂 Project Structure



Bank Loan Insights/

│── analytical\_BI\_report.pdf # Exported BI report in PDF format

│── bank\_loan\_data\_insights (1).pbix # Power BI dashboard file

│── financial\_loan.xlsx # Raw loan dataset

│── bank\_logo.jpg # Project branding/logo

│── overview.jpg # Overview dashboard screenshot

│── details.jpg # Detailed insights dashboard screenshot

│── summary.jpg # High-level summary dashboard screenshot

│── README.md # Project documentation


---



\## 📊 Dataset Description



\- \*\*Source File\*\*: `financial\_loan.xlsx`  

\- \*\*Records\*\*: ~38,500  

\- \*\*Attributes\*\*: 24 (borrower profile, loan details, repayment behavior, credit scores, etc.)



\### Key Columns

| Field | Description |

|-------|-------------|

| `loan\_amount` | Original loan principal issued |

| `int\_rate` | Interest rate charged |

| `installment` | Monthly installment |

| `loan\_status` | Repayment outcome (Fully Paid, Charged Off, Current, etc.) |

| `annual\_income` | Reported borrower income |

| `dti` | Debt-to-Income ratio |

| `grade` / `sub\_grade` | Credit grade assigned |

| `emp\_length` | Borrower’s employment length |

| `home\_ownership` | Rent, Mortgage, Own, etc. |

| `address\_state` | Borrower’s state of residence |



---



\## 🎯 Business Objectives



1\. \*\*Portfolio Health Monitoring\*\*  

&nbsp;  - Loan performance by status (Fully Paid, Charged Off, Current).  



2\. \*\*Revenue \& Risk Analysis\*\*  

&nbsp;  - Loan amount issued vs. total payments collected.  



3\. \*\*Borrower Segmentation\*\*  

&nbsp;  - By income, employment length, home ownership, and geography.  



4\. \*\*Credit Risk Evaluation\*\*  

&nbsp;  - Default rate by credit grade, DTI, and interest rate.  



5\. \*\*Geographical Risk Mapping\*\*  

&nbsp;  - Regional exposure and charge-off concentrations.  



---



\## 📈 Dashboards \& Reports



\### 🔹 1. Overview Dashboard

High-level KPIs and loan performance metrics.  

!\[Overview Dashboard](overview.jpg)



---



\### 🔹 2. Detailed Insights

Loan distributions, borrower segmentation, repayment performance.  

!\[Detailed Insights](details.jpg)



---



\### 🔹 3. Summary Dashboard

Concise insights for management-level reporting.  

!\[Summary Dashboard](summary.jpg)



---



\## 📑 Reports



\- \*\*\[Analytical BI Report (PDF)](analytical\_BI\_report.pdf)\*\*  

\- \*\*\[Interactive Power BI Dashboard (.pbix)](bank\_loan\_data\_insights%20(1).pbix)\*\*  



---



\## 🛠️ Tools \& Technologies



\- \*\*Data Storage\*\*: Excel dataset (`.xlsx`)  

\- \*\*Visualization\*\*: Power BI  

\- \*\*Data Transformation\*\*: Power Query (ETL)  

\- \*\*Languages\*\*: SQL, DAX for calculated fields and KPIs  



---



\## 📌 Key Insights Delivered



\- 🔹 Borrowers with \*\*higher debt-to-income (DTI) ratios\*\* show higher default probability.  

\- 🔹 \*\*Grade E \& F loans\*\* carry higher risk but also higher interest revenue.  

\- 🔹 \*\*Renters with <1 year employment\*\* show elevated charge-off rates.  

\- 🔹 Certain \*\*states\*\* exhibit higher delinquency patterns, requiring targeted credit policy.  



---



\## 🚀 How to Use



1\. Clone this repository:  

&nbsp;  ```bash

&nbsp;  git clone https://github.com/dev-iz/Bank-Loan-Insights.git



2.Navigate to the Bank Loan Insights folder.



3\. Open the .pbix file in Power BI Desktop for interactive analysis.



4\. Review analytical\_BI\_report.pdf for a static version of insights.



5\. Use financial\_loan.xlsx as the data source if reloading or modifying dashboards.



📢 Acknowledgement



This project is part of a broader BI Projects Collection showcasing end-to-end analytics workflows using Power BI.

