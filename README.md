# 🏨 Hotel Booking Cancellation Analysis 📉

## 🏢 Business Problem
In recent years, both the **City Hotel** and **Resort Hotel** have seen a significant spike in cancellation rates. This has led to a cascade of issues, including lost revenue and inefficient room utilization. The primary objective of this analysis is to pinpoint the causes of these cancellations and provide data-driven strategies to stabilize revenue and improve operational efficiency.

---

## ❓ Research Questions
1. What are the key variables influencing hotel reservation cancellations?
2. How can we optimize the reservation process to reduce cancellation rates?
3. How can hotels be better assisted in making strategic pricing and promotional decisions?

---

## 🧪 Hypotheses
* **H1:** More cancellations occur when prices (ADR) are higher.
* **H2:** When there is a longer waiting list, customers tend to cancel more frequently.
* **H3:** The majority of clients are coming from offline travel agents to make their reservations.

---

## 📊 Learn About Data
This dataset contains **119,390 observations** for a City Hotel and a Resort Hotel. Each observation represents a hotel booking between **July 1st, 2015, and August 31st, 2017**.

<details>
<summary>📑 View Full Data Dictionary (All 36 Columns)</summary>

| Column | Description |
| :--- | :--- |
| `hotel` | Resort Hotel or City Hotel. |
| `is_canceled` | Value indicating if the booking was canceled (1) or not (0). |
| `lead_time` | Number of days between booking and arrival date. |
| `arrival_date_year` | Year of arrival date. |
| `arrival_date_month` | Month of arrival date (January to December). |
| `arrival_date_week_number` | Week number of arrival date. |
| `arrival_date_day_of_month` | Day of the month of the arrival date. |
| `stays_in_weekend_nights` | Number of weekend nights (Sat or Sun) stayed. |
| `stays_in_week_nights` | Number of week nights (Mon to Fri) stayed. |
| `adults` | Number of adults. |
| `children` | Number of children. |
| `babies` | Number of babies. |
| `meal` | Type of meal booked (BB, HB, FB, etc.). |
| `country` | Country of origin. |
| `market_segment` | Market segment designation (TA = Travel Agents, TO = Tour Operators). |
| `distribution_channel` | Booking distribution channel. |
| `is_repeated_guest` | Value indicating if the guest is a repeated one (1) or not (0). |
| `previous_cancellations` | Number of previous bookings canceled by the customer. |
| `previous_bookings_not_canceled` | Number of previous bookings not canceled. |
| `reserved_room_type` | Code of room type reserved. |
| `assigned_room_type` | Code for the type of room assigned. |
| `booking_changes` | Number of changes/amendments made to the booking. |
| `deposit_type` | No Deposit, Non-Refund, or Refundable. |
| `agent` | ID of the travel agency that made the booking. |
| `company` | ID of the company/entity responsible for the booking. |
| `days_in_waiting_list` | Days the booking was in the waiting list before confirmation. |
| `customer_type` | Group, Transient, Transient-party, or Contract. |
| `adr` | Average Daily Rate (Sum of lodging transactions / Total nights). |
| `required_car_parking_spaces` | Number of car parking spaces required. |
| `total_of_special_requests` | Number of special requests made. |
| `reservation_status` | Check-Out, Canceled, or No-Show. |
| `reservation_status_date` | Date at which the last status was set. |
| `name` | Name of the Guest (Not Real). |
| `email` | Email of the Guest (Not Real). |
| `phone-number` | Phone number of the Guest (Not Real). |

</details>

---

## 🛠️ Tools & Methodology
To ensure high accuracy and deep insights, this project was executed using a dual-tool approach:

### 1. Python (Advanced Analysis & Visualization)
* **Libraries:** `Pandas` for data cleaning, `Matplotlib` and `Seaborn` for advanced EDA.
* **Analysis:** Used Python to handle large data volumes, perform complex filtering, and generate statistical visualizations of cancellation trends.

### 2. Microsoft Excel (Dynamic Reporting)
* **Functions:** Leveraged Pivot Tables for data aggregation.
* **Dashboards:** Created interactive Excel reports with Slicers for quick data exploration.

---

## 🔗 Project Deliverables & Reports
<p> 
  🚀 <b>Python Anlysis and Visualization:</b> 
  <a href="python/">View Python Folder</a>
</p>

<p> 
  📁 <b>Excel Dashboard:</b> 
  <a href="excel/">View Excel Folder</a>
</p>

<p> 
  📑 <b>Static Analysis Report:</b> 
  <a href="Presentation.pdf">Presentation.pdf</a> 
  (Findings and Suggestions)
</p>



---
