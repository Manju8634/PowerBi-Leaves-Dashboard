
Employees Leave Analytics Dashboard – Power BI

A data-driven HR analytics dashboard built using Power BI, using mock employee and leave data for years 2023–2025.
The dashboard provides insights into employee leave patterns, helping HR teams and management make better operational and workforce planning decisions.

Dashboard Overview

--Leaves Dashboard--

* Total employees
* On leave today
* Weekly, Monthly, Quarterly, Yearly leave counts
* Weekly & Monthly averages
* YOY comparison
* Working hours and effective hours
* Year, Month, Week slicers

--Leave Details--

* Monthly leave trend
* Leave count by designation
* Top 10 employees by leave days
* Employee-level leave details table
* Filters for Year & Designation

--Employee Leave Details--

* Monthly leave trend (week-based)
* Employee-level sortable table (code, name, designation, leave days)
* Filters for Year, Employee Code, Employee Name

Business Purpose

This dashboard helps HR teams monitor and analyze leave activities, identify patterns of absenteeism, and support better capacity & workforce planning.


Project Structure

```
Employees-Leave-Dashboard
│
├── Dashboard/
│   ├── Employees_Leaves_Dashboard.pbix
│
├── Datasource/
│   ├── Employee_List.xlsx
│   ├── Leave_List.xlsx
│   ├── Holidays_List.xlsx
│
├── Docs/
│   ├── Data_Model.png
│   ├── Purpose_Of_Dashboard.docx
│
├── Screenshots/
│   ├── Dashboard_Overview.png
│   ├── Employee_Details.png
│   ├── Leave_Details.png
│
├── README.md
│
└── .gitignore
```


