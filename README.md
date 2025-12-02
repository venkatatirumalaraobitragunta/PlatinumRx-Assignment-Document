📘 **PlatinumRx Data Analyst Assignment – Complete Solution**

This repository contains the complete solution for the PlatinumRx Assignment, covering three main areas:

* **SQL Proficiency**
* **Spreadsheet Proficiency**
* **Python Proficiency**

Each section outlines the approach taken to solve the tasks, without including full code snippets.

---

🗂️ **Repository Structure**

```
PlatinumRx_Assignment/
│
├── SQL/
│   ├── 01_Hotel_Schema.sql
│   ├── 02_Hotel_Queries.sql
│   ├── 03_Clinic_Schema.sql
│   └── 04_Clinic_Queries.sql
│
├── Spreadsheets/
│   └── Ticket_Analysis.xlsx
│
├── Python/
│   ├── 01_Time_Converter.py
│   └── 02_Remove_Duplicates.py
│
└── README.md
======================================================

 🟦 **SECTION 1 — SQL PROFICIENCY**

 ======================================================

**Hotel Management System**

For the hotel management system, the following tasks were performed:

1. **Latest Booked Room for Each User**:
   We used a window function to partition bookings by user and sort by date, selecting the most recent booking per user.

2. **Total Billing Amount for Bookings in November 2021**:
   We joined booking and item tables, filtered by the booking date, and summed up item quantities and rates to calculate the total.

3. **Bills Over 1000 in October 2021**:
   By grouping bills by their date and summing amounts, we identified those exceeding a specified threshold.

4. **Most and Least Ordered Items Each Month**:
   We ranked items by order frequency per month to determine the top and bottom items.

5. **Customers with the Second Highest Bill Each Month**:
   Using a ranking function, we identified the second-highest bill values and the corresponding customers for each month.

**Clinic Management System**

For the clinic management system, we solved the following:

1. **Revenue by Sales Channel**:
   We grouped sales data by channel and summed the amounts to determine revenue distribution.

2. **Top 10 Most Valuable Customers**:
   By aggregating customer spending and sorting, we identified the highest-spending customers for the year.

3. **Monthly Revenue, Expense, and Profit Status**:
   We combined sales and expenses data to compute monthly profit and labeled each month as profitable or not.

4. **Most Profitable Clinic by City**:
   We calculated profit per clinic and identified the top clinic in each city for a given month.

5. **Second Least Profitable Clinic by State**:
   Using a similar ranking method, we determined the clinic with the second-lowest profit in each state for a given month.


======================================================

 🟨 **SECTION 2 — SPREADSHEET PROFICIENCY**

 ======================================================
 **Ticket and Feedback Data Analysis**

 **1. Linking Data Between Sheets**

We used a lookup formula to populate the `ticket_created_at` field in the feedback sheet by matching `cms_id` to the ticket sheet.

**2. Time-Based Analysis with Helper Columns**

Helper columns were added to the ticket sheet to determine if a ticket was created and closed on the same day or within the same hour.

**3. Outlet-Wise Ticket Counts**

We used these helper columns to count how many tickets were created and closed on the same day or hour for each outlet, demonstrating the process using COUNTIFS or Pivot Tables.

======================================================

🟩 **SECTION 3 — PYTHON PROFICIENCY**

======================================================

**1. Time Conversion Script**

We wrote a Python script to convert a number of minutes into a human-readable format (e.g., "130 minutes" becomes "2 hrs 10 minutes").

**2. String Deduplication Script**

Another script was created to remove duplicate characters from a string using a simple loop, resulting in a unique-character string.


 🏁 **Final Notes**

This README provides an overview of the steps and logic used to solve each part of the assignment. Full SQL queries, Excel formulas, and Python scripts are included in their respective directories for detailed reference.


If you need any more adjustments or another section added, just let me know!
