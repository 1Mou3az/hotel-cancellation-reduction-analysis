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
| `lead_time` | Number of days that elapsed between the entering date of the booking and the arrival date. |
| `arrival_date_year` | Year of arrival date. |
| `arrival_date_month` | Month of arrival date (January to December). |
| `arrival_date_week_number` | Week number of arrival date. |
| `arrival_date_day_of_month` | Day of the month of the arrival date. |
| `stays_in_weekend_nights` | Number of weekend nights (Sat or Sun) the guest stayed or booked. |
| `stays_in_week_nights` | Number of week nights (Mon to Fri) the guest stayed. |
| `adults` | Number of adults. |
| `children` | Number of children. |
| `babies` | Number of babies. |
| `meal` | Type of meal booked (BB, HB, FB, etc.). |
| `country` | Country of origin. |
| `market_segment` | Market segment designation (TA = Travel Agents, TO = Tour Operators). |
| `distribution_channel` | Booking distribution channel. |
| `is_repeated_guest` | Value indicating if the booking name was from a repeated guest (1) or not (0). |
| `previous_cancellations` | Number of previous bookings canceled by the customer prior to the current one. |
| `previous_bookings_not_canceled` | Number of previous bookings not canceled prior to current booking. |
| `reserved_room_type` | Code of room type reserved (Anonymized). |
| `assigned_room_type` | Code for the type of room assigned (may differ from reserved). |
| `booking_changes` | Number of changes/amendments made to the booking. |
| `deposit_type` | No Deposit, Non-Refund, or Refundable. |
| `agent` | ID of the travel agency that made the booking. |
| `company` | ID of the company/entity responsible for the booking. |
| `days_in_waiting_list` | Number of days the booking was in the waiting list before confirmation. |
| `customer_type` | Group, Transient, Transient-party, or Contract. |
| `adr` | Average Daily Rate (Sum of lodging transactions / Total staying nights). |
| `required_car_parking_spaces` | Number of car parking spaces required by the customer. |
| `total_of_special_requests` | Number of special requests made (e.g., twin bed, high floor). |
| `reservation_status` | Check-Out, Canceled, or No-Show. |
| `reservation_status_date` | Date at which the last status was set. |
| `name` | Name of the Guest (Not Real). |
| `email` | Email of the Guest (Not Real). |
| `phone-number` | Phone number of the Guest (Not Real). |

</details>

---

## 🔗 Project Deliverables & Reports
<p> 
  🚀 <b> Dashboard:</b> 
  <a href="INSERT_YOUR_POWERBI_LINK_HERE">View Live Interactive Version</a>
</p>

<p> 
  📑 <b>Static Analysis Report:</b> 
  <a href="Presentation.pdf">Presentation.pdf</a> 
  (Full implementation and findings)
</p>

---
