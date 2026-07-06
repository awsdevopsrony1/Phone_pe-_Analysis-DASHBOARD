# PhonePe Analysis Dashboard

**Payment insights, powering Bharat.**
*Secure. Simple. Seamless.*

An interactive analytics dashboard built to visualize PhonePe transaction data — covering transaction trends, user demographics, service-wise value distribution, and top-user activity — designed to help understand payment behavior across India.

![Dashboard Preview](./dashboard_preview.png)
> Replace `dashboard_preview.png` with the actual dashboard screenshot filename in your repo.

---

## 📊 Overview

This dashboard provides a consolidated, filterable view of PhonePe transaction data, allowing users to track growth, monitor transaction success rates, and identify key usage patterns across services, age segments, and time periods.

### Key Metrics Tracked
- **Total Transactions** — overall transaction count with Month-over-Month (MOM) growth
- **Total Value** — aggregate transaction value (₹) with MOM growth
- **Unique Users** — count of distinct active users
- **Successful Rate** — percentage of successful transactions

---

## 🔍 Features

### Filters
- **Month** — filter all visuals by a specific month or view "All"
- **Payment Status** — filter by Failed, Pending, or Successful transactions

### Visualizations
| Chart | Description |
|---|---|
| **Transactions Over Time** | Area chart comparing total transaction count vs. total transaction value trends |
| **Age Segment Contribution** | Donut chart breaking down transactions by generation — Gen X, Millennial, Gen Z, Boomers |
| **Service Transaction Value Analysis** | Bar chart comparing value across services: Loans, Insurance, Money Transfer, Recharge & Bills |
| **Top 5 Users (By Transaction Value)** | Ranks the highest-value users by total transaction amount |
| **Weekday vs Weekend Usage** | Donut chart comparing transaction share on weekdays vs weekends |
| **Insights Panel** | Auto-generated highlights, e.g. top-performing service and peak transaction day |

---

## 📈 Sample Insights

- Loan services generate the **highest transaction value** among all service categories.
- **Gen Z** and **Millennials** together contribute over **58%** of total transactions.
- Weekday usage (**~85.7%**) significantly outweighs weekend usage (**~14.3%**).
- Transaction volume peaks were observed mid-month, with a noted spike on a specific Tuesday.

---

## 🛠️ Tech Stack

> Update this section with the actual tools used to build the dashboard.

- **Tool:** Power BI / Tableau / Excel *(replace with the one you used)*
- **Data Source:** PhonePe transaction dataset (CSV/Excel)
- **Data Prep:** *(e.g., Power Query, Pandas, Excel)*

---

## 📂 Repository Structure

```
Phone_pe-_Analysis-DASHBOARD/
│
├── data/                  # Raw and cleaned datasets
├── dashboard_preview.png  # Dashboard screenshot
├── PhonePe_Dashboard.pbix # Dashboard file (Power BI) — rename as applicable
└── README.md              # Project documentation
```

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/awsdevopsrony1/Phone_pe-_Analysis-DASHBOARD.git
   ```
2. Open the dashboard file in the relevant application (e.g., Power BI Desktop).
3. Load/refresh the data source if prompted.
4. Use the **Month** and **Payment Status** filters to explore insights.

---

## 📌 Future Enhancements

- Add geographic/state-wise transaction analysis
- Include year-over-year comparison view
- Add drill-through pages for individual user transaction history
- Automate data refresh from a live source

---

## 🙋 Author

**Rony** — [awsdevopsrony1](https://github.com/awsdevopsrony1)

---

## 📄 License

This project is open-sourced for learning and portfolio purposes. Feel free to fork and build upon it.
