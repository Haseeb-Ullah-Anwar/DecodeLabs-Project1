# 📊 Project 1: Data Sanitization & Cleaning Masterclass
**DecodeLabs Data Analytics Internship | Data Ingestion & Spreadsheet Engineering Pipeline**

## 🏷️ Project Title
**Enterprise E-Commerce Transactional Ledger Sanitization & Structural Audit**

## 📝 Detailed Project Overview
Raw business data is inherently messy and filled with structural formatting anomalies that distort statistical distributions and relational database analytics. This project serves as the foundational data ingestion layer, focusing on the rigorous sanitization, normalization, and auditing of an enterprise e-commerce transactional database containing exactly **1,200 unique records across 14 data columns** using Microsoft Excel [image_jRa_8y.png].

---

### 🛠️ Step-by-Step Spreadsheet Data Engineering Operations

#### 1. Identification & Treatment of Missing Data (Null Imputation)
* **The Anomaly:** Deep data profiling revealed massive missing data gaps and empty blank cells within the `CouponCode` structural array. Leaving these records blank would cause major miscalculations and null errors during dynamic database aggregation runs and criteria-based queries.
* **The Resolution:** Executed a systematic spreadsheet imputation layer to scan the column and automatically populate every empty/null cell with a standardized default string identifier: **`NO_COUPON`** [image_jRa_8y.png]. This step preserves the statistical baseline of promotional campaigns while safeguarding structural records.

#### 2. Text Normalization & Syntactic Integrity (Scrubbing Data Noise)
* **The Anomaly:** Multi-source data entry methods introduced hidden leading/trailing whitespace noise, formatting irregularities, and inconsistent lettering setups across fields like `PaymentMethod` and `OrderStatus` [image_jRa_8y.png].
* **The Resolution:** Deployed spreadsheet functions to strip away hidden spaces and hardcoded all key character variables into a clean, uniform casing structure [image_jRa_8y.png]. This guarantees flawless exact text-match queries.

#### 3. Column Datatype Verification & Volume Audit
* **The Anomaly:** Numeric data formats and transactional attributes needed complete baseline matching to prevent data truncation or failure during SQL Server migrations [image_jRa_8y.png].
* **The Resolution:** Executed a comprehensive structural check across all **1,200 transactions**, locking proper numeric formatting and scale values for financial column features including `OrderID`, `Quantity`, `UnitPrice`, and `TotalPrice` [image_jRa_8y.png].

---

### 🖼️ Operational Excel Sanitized Data View
Below is the verified spreadsheet data grid showing the operational columns and successful null value imputations structured within Microsoft Excel [image_jRa_8y.png]:

![Excel Cleaned Data Grid](Cleaned%20Data.png)

---

### 📈 Structural Analytics & Key Takeaways
* **Dataset Scale:** 1,200 pristine, fully-audited spreadsheet rows ready for database insertion [image_jRa_8y.png].
* **Operational Columns:** 14 feature fields including client identification, regional address strings, and marketing acquisition routes [image_jRa_8y.png].
* **Pipeline Readiness:** Secured 100% syntactic data consistency across all fields, completely eliminating calculation errors prior to SQL ingestion pipelines [image_jRa_8y.png].

## ⚙️ How to Run & Replicate This Project
1. Open or download the primary operational spreadsheet artifact: **`Dataset for Data Analytics(Cleaned).xlsx`**.
2. Launch the file inside Microsoft Excel or any standard spreadsheet application [image_jRa_8y.png].
3. Review the `CouponCode` column to inspect the successfully populated, clean string structures [image_jRa_8y.png].
