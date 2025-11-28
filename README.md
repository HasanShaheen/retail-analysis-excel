# Revenue Leakage & Market Analysis Dashboard 📊

![Dashboard Screenshot]([link-to-your-image.png](https://github.com/user-attachments/assets/45698432-1784-4289-996a-c534d52a6a5b))


## 📌 Project Overview
**The Context:**
A UK-based online retailer generated over 1 million transaction records (2009–2011). The data was siloed in raw CSV files, contained significant noise, and lacked a unified reporting structure.

**The Problem:**
Stakeholders had no visibility into "Revenue Leakage" (returns cost) and could not separate domestic (UK) performance from international growth markets. The dataset size (~1M rows) exceeded standard Excel sheet limits.

**The Solution:**
I developed a full-stack Excel BI solution using Power Query (ETL) and Power Pivot (Data Modeling) to deliver an interactive dashboard that identifies loss-making products and growth regions.

---

## 🛠️ Tools & Technologies Used
* **Microsoft Excel (365):** The core platform.
* **Power Query:** Used for ETL (Extract, Transform, Load) to clean duplicates and flag "Service" transactions.
* **Power Pivot (Data Model):** Used to compress 800k+ rows and bypass the 1M row sheet limit.
* **DAX (Data Analysis Expressions):** Used to create dynamic measures for `[Return Value]` and `[Total Sales]`.

---

## 🚀 Key Features & Insights
1.  **Revenue Leakage Analysis:** Identified that the *Regency Cakestand* was a top 3 loss-making product due to high return rates.
2.  **Market Segmentation:** Created a "Domestic vs. International" architecture to prevent UK sales from skewing the visualization of emerging markets like EIRE and Germany.
3.  **Interactive Filtering:** Implemented Slicers for Year and Month, allowing sub-second filtering of 800,000 rows.

---

## 📂 How to Use This File
1.  Download the file `Online_Retail_Analysis.xlsx` from this repository.
2.  Open the file and click **"Enable Content"** to allow the Data Model to load.
3.  Go to the **"Executive Dashboard"** tab.
4.  Use the Slicers to filter by Year (2010/2011) or Country.

---

## 💡 Author
**[Hasan_Shaheen]**
* [LinkedIn Profile](Link)
* [Portfolio Link](Link)
