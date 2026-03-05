# 📊 HR Analytics Dashboard — AtliQ Technologies

A **Power BI dashboard** built to help HR managers at AtliQ Technologies monitor employee attendance trends, work-from-home patterns, and leave utilization across April–June 2022.

---

## 🖼️ Dashboard Preview

> _Add a screenshot of your Power BI dashboard here_
> `![HR Dashboard Preview](dashboard-preview.png)`

---

## 📌 Project Overview

HR teams often struggle to track attendance manually across spreadsheets. This project automates that process by transforming raw monthly attendance data into a dynamic, filterable Power BI dashboard — enabling data-driven decisions around workforce planning and hybrid work policies.

---

## 🎯 Problem Statement

The HR department at AtliQ Technologies needed visibility into:
- Overall employee **presence percentage** over time
- **Work From Home (WFH)** adoption trends
- **Sick leave** patterns (useful for health/wellness planning)
- Day-of-week trends to identify which days employees prefer WFH

---

## 📈 Key Metrics & KPIs

| Metric | Description |
|---|---|
| **Presence %** | % of working days an employee was physically present |
| **WFH %** | % of days worked from home |
| **Sick Leave %** | % of days taken as sick leave |
| **Leave Breakdown** | Paid, unpaid, birthday, bereavement, menstrual leave |

---

## 🗂️ Repository Structure

```
hr-analytics-atliq/
│
├── HR-Analytics-Atliq.pbix         # Power BI dashboard file
├── Attendance-Sheet-2022-2023.xlsx # Raw attendance data (source)
└── README.md
```

---

## 📋 Dataset Details

**File:** `Attendance-Sheet-2022-2023.xlsx`

**Coverage:** April 2022 – June 2022 (AtliQ Technologies employees)

**Sheets:**
- `Apr 2022`, `May 2022`, `Jun 2022` — Monthly attendance per employee
- `Attendance Key` — Legend for attendance codes

**Attendance Codes Used:**

| Code | Meaning |
|---|---|
| `P` | Present |
| `WFH` | Work From Home |
| `PL` | Paid Leave |
| `SL` | Sick Leave |
| `WO` | Weekly Off |
| `HO` | Holiday Off |
| `BL` | Birthday Leave |
| `BRL` | Bereavement Leave |
| `LWP` | Leave Without Pay |
| `ML` | Menstrual Leave |
| `FFL` | Floating Festival Leave |

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Dashboard development & DAX measures
- **Microsoft Excel** — Raw data source
- **Power Query (M Language)** — Data transformation & unpivoting monthly sheets
- **DAX** — Calculated measures for presence %, WFH %, sick leave %

---

## ⚙️ How to Use

1. **Clone this repository**
   ```bash
   git clone https://github.com/your-username/hr-analytics-atliq.git
   ```

2. **Open the dashboard**
   - Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
   - Open `HR-Analytics-Atliq.pbix`

3. **Refresh data** *(if needed)*
   - Go to `Home → Transform Data`
   - Update the file path to point to `Attendance-Sheet-2022-2023.xlsx` on your machine
   - Click `Close & Apply`

---

## 💡 Key Insights (from the data)

- 📅 **Fridays** had the highest WFH rates, suggesting employees prefer ending the week remotely
- 📉 Sick leave spikes were visible in **May**, indicating a potential seasonal health pattern
- 🏢 Overall **presence % declined** gradually from April to June, aligning with summer and hybrid work adoption

---

## 🔮 Potential Improvements

- [ ] Add headcount and department-level filtering
- [ ] Incorporate FY 2023 data for year-over-year comparison
- [ ] Add a leave forecasting model using historical patterns
- [ ] Publish to Power BI Service for live sharing

---

## 🙋 About

This project was built as part of a **data analytics portfolio** to demonstrate real-world HR analytics skills using Power BI, Power Query, and DAX.

**Connect with me:**
- 🔗 [LinkedIn](https://www.linkedin.com/in/vimala94-upputuru/)
- 💻 [GitHub](https://github.com/vimalau94)

---

## 📄 License

This project is for educational and portfolio purposes. The data used is fictional/sample data from AtliQ Technologies (a practice dataset).
