# Hotel Booking Analysis Dashboard | Power BI

This repository contains an interactive Power BI dashboard project that analyzes hotel booking data from a city hotel and resort hotel. The dashboard provides valuable insights into customer behavior, booking trends, cancellations, market segments, and revenue performance.

---

## Dashboard Overview

The Power BI dashboard helps answer key business questions for hotel managers and analysts, such as:

- When are bookings most frequent throughout the year?
- What is the cancellation rate by customer type or deposit policy?
- Which market segments and distribution channels are most effective?
- How does guest demographic vary across hotels?
- What is the average daily revenue (ADR) per booking?

---

## Dataset Summary

The dataset used comes from real-world hotel booking records and contains over 119,000 rows with the following key features:

- `hotel`: Resort or City
- `arrival_date_year`, `month`, `week`, `day_of_month`
- `lead_time`, `stays_in_weekend_nights`, `stays_in_week_nights`
- `adults`, `children`, `babies`
- `meal`, `country`, `market_segment`, `distribution_channel`
- `is_repeated_guest`, `previous_cancellations`, `booking_changes`
- `deposit_type`, `agent`, `company`, `days_in_waiting_list`
- `adr` (Average Daily Rate), `required_car_parking_spaces`
- `reservation_status`, `reservation_status_date`

---

## Key Insights

- Peak Booking Months: Most bookings occur during summer and early autumn.
- Cancellation Patterns: High cancellation rates are linked with longer lead times and non-refundable bookings.
- Market Segmentation: Online travel agents are the most common source of bookings.
- Guest Behavior: Most guests travel in pairs (2 adults), and repeated guests are more loyal to city hotels.
- Revenue Trends: Resort hotels tend to have higher ADR during peak months.

---

## Tools & Techniques

- Power BI Desktop  
- Power Query Editor for data cleaning  
- DAX for calculated measures (e.g., cancellation rate, total revenue)  
- Interactive visualizations: bar charts, slicers, maps, pie charts, trend lines  

---

## Files in this Repository

- `hotel project power bi.pbix` — Power BI project file  
- `hotel_bookings.csv` — Dataset file used in the project  
- `README.md` — Project overview and documentation  

---

## 🧠 Use Cases

This dashboard is ideal for:
- Hospitality business intelligence and performance monitoring  
- Customer segmentation and loyalty analysis  
- Strategic planning based on booking behavior and seasonality  
- Academic or portfolio demonstration of Power BI skills

---

## 📬 Contact

For questions, suggestions, or collaborations, feel free to reach out via [GitHub Issues](https://github.com/).

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

