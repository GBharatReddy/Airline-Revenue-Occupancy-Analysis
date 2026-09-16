# Airline-Revenue-Occupancy-Analysis

# ✈️ Airline Revenue & Occupancy Analysis

## 📌 Project Overview

This project analyses airline booking, ticketing, aircraft and revenue data to identify opportunities for improving **aircraft occupancy and profitability**.

The analysis uses SQL queries and Python to examine booking trends, aircraft performance, fare conditions, revenue generation and occupancy rates.

## 🎯 Business Objective

The primary objective is to identify opportunities to increase the occupancy rate of low-performing flights and evaluate how higher occupancy could contribute to increased airline profitability.

The analysis also examines pricing patterns and aircraft-level revenue performance to support data-driven revenue optimisation.

## 📊 Business Questions

- Which aircraft generate the highest and lowest revenue?
- How do ticket bookings and revenue change over time?
- How do average fares differ across aircraft and fare conditions?
- Which aircraft have lower occupancy rates?
- What would be the potential revenue impact of increasing occupancy?
- How can pricing strategies be used to improve aircraft utilisation?

## 🗄️ Dataset

The project uses the `travel.sqlite` relational SQLite database.

The database contains the following tables:

- `aircrafts_data`
- `airports_data`
- `boarding_passes`
- `bookings`
- `flights`
- `seats`
- `ticket_flights`
- `tickets`

The notebook connects directly to the SQLite database and extracts the required tables using SQL queries.

## 🛠️ Tools & Technologies

- SQL
- SQLite
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔍 Analysis Performed

### 1. Data Exploration
- Database and table exploration
- Data extraction using SQL
- Data validation and missing-value analysis
- Aircraft and booking data analysis

### 2. Revenue Analysis
- Total revenue by aircraft
- Average revenue per ticket
- Revenue trends over time
- Ticket booking trends

### 3. Fare Analysis
- Average fare by aircraft
- Comparison of Business, Economy and Comfort fare conditions
- Aircraft-level pricing patterns

### 4. Occupancy Analysis
- Average booked seats by aircraft
- Seat capacity comparison
- Occupancy-rate calculation
- Identification of aircraft with lower occupancy

### 5. Revenue Impact Analysis
- Simulation of a 10% increase in occupancy
- Estimation of potential additional annual turnover

## 📈 Key Findings

The analysis identified differences in revenue generation, ticket volumes, pricing and occupancy across aircraft.

Some notable findings from the analysis include:

- Aircraft capacity varies substantially across the fleet.
- Ticket bookings and total revenue show similar trends over time.
- Business-class fares are generally higher than Economy fares across the aircraft analysed.
- Aircraft differ considerably in both revenue generation and occupancy.
- The analysis estimates the potential revenue impact of increasing occupancy by 10%.

The report identifies occupancy optimisation and aircraft-specific pricing as important areas for further analysis. :contentReference[oaicite:4]{index=4} :contentReference[oaicite:5]{index=5}

## 📊 Visual Analysis

### Ticket Bookings Over Time

![Ticket Bookings Over Time](Images/Ticket_Bookings_Over_Time.png)

### Revenue Over Time

![Revenue Over Time](Images/Revenue_Over_Time.png)

### Average Fare by Aircraft

![Average Fare by Aircraft](Images/Fare_by_Aircraft.png)

### Revenue by Aircraft

![Revenue by Aircraft](Images/Aircraft_Revenue.png)

### Occupancy Rate by Aircraft

![Occupancy Rate](Images/Occupancy_Rate.png)

### Potential Revenue Impact of Higher Occupancy

![Revenue Impact](Images/Revenue_Impact_10pct_Occupancy.png)

## 💡 Business Insight

The analysis suggests that airline profitability can be examined through a combination of:

- Aircraft occupancy
- Ticket volume
- Average revenue per ticket
- Fare structure
- Aircraft capacity

The analysis further explores how a 10% increase in occupancy could affect annual turnover, providing a framework for evaluating the financial impact of occupancy improvement initiatives. :contentReference[oaicite:6]{index=6}

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `Data_Analysis_Airlines.ipynb` | Complete SQL and Python analysis |
| `travel.sqlite` | Airline relational database |
| `Images/` | Key analysis visualisations |
| `README.md` | Project documentation |

## 👤 Author

**Bharat Reddy**

Data Analytics | Business Analytics | SQL | Python | Power BI
