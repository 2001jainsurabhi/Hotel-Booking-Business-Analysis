# TravClan Hotel Booking Analysis

## Business Analyst Internship Assignment

### Overview

This project analyzes hotel booking transactions from an online travel platform specializing in hotel reservations. The objective was to identify booking trends, understand cancellation behavior, perform root cause analysis, and provide actionable business recommendations to improve profitability and customer retention.

---

## Project Objectives

* Analyze booking trends and customer behavior.
* Compare booking performance across channels, room types, and star ratings.
* Identify cancellation patterns and their potential causes.
* Evaluate revenue and profitability drivers.
* Recommend business strategies to reduce cancellations and improve revenue.

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
* Power BI

---

## Dataset Information

The dataset contains hotel booking transactions with information related to:

* Customer Details
* Property Information
* Booking Channels
* Room Types
* Star Ratings
* Booking Values
* Cancellation Status
* Refund Information
* Cashback & Coupon Usage
* Check-in / Check-out Dates

Total Records: **30,000**

---

## Key Findings

### 1. Booking Performance

* Total Bookings: **30K**
* Total Revenue: **₹752.42M**
* Total Profit: **₹209M**
* Average Booking Value: **₹25.08K**
* Average Stay Length: **4 Days**

### 2. Channel Analysis

* Web channel generated the highest revenue.
* Mobile App contributed moderate revenue.
* Travel Agent bookings showed the highest cancellation rate.

### 3. Room Type Analysis

* Standard rooms generated the highest booking volume.
* Deluxe rooms performed moderately.
* Suite rooms represented a smaller premium segment.

### 4. Star Rating Analysis

* 4-star hotels generated the highest revenue.
* Customers showed strong preference for mid-premium properties.
* Revenue declined for both lower and higher star categories.

### 5. Cancellation Analysis

* Overall cancellation rate: **20.23%**
* Travel Agent bookings experienced the highest cancellations.
* Standard rooms recorded the highest cancellation volume.

---

## Root Cause Analysis

### Why are cancellations high?

* Travel Agent bookings demonstrate lower customer commitment.
* Standard room customers are more price-sensitive.
* Flexible booking options may encourage cancellations.
* Seasonal demand fluctuations impact booking stability.

### Why do some channels perform better?

* Direct Web bookings generate higher-value transactions.
* Website customers show stronger booking commitment.
* Travel Agent bookings contribute lower revenue and higher cancellations.

### Seasonal Trends

* Revenue fluctuates across months, indicating seasonality.
* Peak demand periods present opportunities for dynamic pricing.
* Average stay duration remains concentrated around short trips.

---

## Business Recommendations

### Reduce Cancellations

* Introduce prepaid and partially non-refundable bookings.
* Send automated booking reminders.
* Offer incentives for confirmed bookings.

### Improve Profitability

* Increase focus on direct website bookings.
* Promote premium room categories.
* Implement dynamic pricing strategies.

### Increase Repeat Bookings

* Launch loyalty and rewards programs.
* Provide personalized offers to returning customers.
* Improve customer retention initiatives.

### Optimize Channel Strategy

* Reduce dependency on high-cancellation channels.
* Invest more in direct acquisition channels.
* Monitor channel performance regularly.

---

## Power BI Dashboard

### Page 1 – Executive Overview

Add your first dashboard screenshot here:

```markdown
![Executive Overview](images/Executive_Summary_Page.png)
```

This page provides:

* KPI Overview
* Revenue Analysis
* Booking Status Distribution
* Cancellation Analysis
* Channel Performance
* Room Type Performance

---

### Page 2 – Root Cause Analysis & Business Insights

Add your second dashboard screenshot here:

```markdown
![Root Cause Analysis](images/Root_Cause_Business_Insights.png)
```

This page provides:

* Monthly Revenue Trend
* Revenue by Star Rating
* Cancellation by Room Type
* Stay Length Analysis
* Business Insights
* Strategic Recommendations

---

## Project Structure

```text
TravClan-Hotel-Booking-Analysis
│
├── README.md
├── TravClan_Hotel_Booking_Analysis.ipynb
├── Dashboard
│   └── TravClan_Surbhi_Assignment.pbix
│
├── Images
│   ├── Executive_Summary_Page.png
│   └── Root_Cause_Business_Insights.png
│
└── Dataset
    └── Hotel_bookings_final.csv
```

---

## Conclusion

The analysis revealed strong revenue performance, with Web bookings and 4-star properties emerging as key business drivers. However, cancellation rates remain a significant challenge, particularly for Travel Agent bookings and Standard rooms. Implementing targeted cancellation reduction strategies, strengthening direct booking channels, and optimizing pricing can significantly improve profitability and customer retention.
