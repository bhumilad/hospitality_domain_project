# 🏨 Hospitality Domain Analytics Dashboard

## 📌 Project Overview
This project analyzes hospitality data to uncover trends, identify improvement areas, and provide actionable insights for revenue growth and customer satisfaction.  
The analysis covers **occupancy rates, ADR (Average Daily Rate), booking platforms, cancellations, and city-wise performance**, with recommendations for business strategy improvements.  

The dashboard was built in **Power BI** with interactive visuals and DAX measures to enable deeper exploration of the data.

---

## 📊 Dataset
- **Source**: Hospitality booking data (provided for project use) 
- **Key Columns**:
  - `Booking Date`, `Check-In Date`, `Check-Out Date`
  - `Booking Platform` (MakeyourTrip, LogTrip, Tripster, etc.)
  - `Room Category` (Luxury, Business, etc.)
  - `ADR` (Average Daily Rate)
  - `Occupancy %`
  - `Status` (Completed, Cancelled)
  - `City`
- **Volume**: ~X,XXX records

---

## 🛠 Tools & Techniques
- **Data Cleaning & Transformation**: Power Query
- **Data Analysis**: Power BI (DAX), Excel
- **Visualization**: Interactive Power BI dashboard
- **Key Metrics Calculated**:
  - ADR (Average Daily Rate)
  - Occupancy %
  - Realizations % (Utilized Room Nights / Booked Room Nights)
  - Revenue WoW Change %
  - Booking % by Platform
- **Modeling**:
  - Star schema: `Fact_Bookings` with multiple `Dim_` tables
  - DAX measures for KPI calculations

---

## 📷 Dashboard Preview

![]("D:/st.clair-D/personal projects/Hospitality Domain/dashboard.png")

---

## 🔍 Key Findings
1. **Pricing Model Gap** – No dynamic or weekend/weekday pricing observed; flat pricing is applied.  
   ➡ Recommend implementing a **dynamic pricing model** to capture high-demand periods.

2. **Occupancy & Ratings** – Positive correlation found.  
   ➡ Suggest using **NLP on reviews** to identify and address common service issues.

3. **High ADR in Cancellations (Direct Offline)** – Direct offline bookings attract high-value customers but show higher cancellation rates.  
   ➡ Offer **discounts or loyalty incentives** to convert these bookings into stays.

4. **Business Category Underperformance** – Luxury category dominates revenue; business segment lags.  
   ➡ Target **corporate contracts** and **bundle offers** (e.g., meeting space + meals).

5. **City-Wise Revenue** – Mumbai generates ~40% of total revenue; Delhi underperforms despite good occupancy and ratings.  
   ➡ Explore **expansion in Delhi** with competitive pricing and new properties.

---

## 📌 Conclusion
This analysis shows significant opportunities for:
- Introducing **dynamic pricing** to maximize revenue
- Leveraging **customer feedback** for service improvements
- Reducing cancellations in high-ADR bookings
- Expanding the **business category** with targeted offers
- Balancing revenue distribution across cities

The Power BI dashboard enables stakeholders to monitor KPIs in real-time and make **data-driven decisions** for improving performance.

---

## 📂 Repository Structure
├── Data/ # Raw and cleaned datasets
├── Dashboard/ # Power BI (.pbix) file
├── Images/ # Dashboard screenshots
├── README.md # Project documentation


---

## 📬 Contact
If you have any feedback, suggestions, or collaboration ideas, feel free to connect on [LinkedIn](https://www.linkedin.com/in/your-profile/) or open an issue in this repository.

