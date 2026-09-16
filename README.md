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

![Ticket Bookings Over Time](Ticket%20Bookings%20Over%20Time.png)

### Revenue Over Time

![Revenue Over Time](Revenue%20Over%20Time.png)

### Average Fare by Aircraft

![Average Fare by Aircraft](Average%20Fare%20by%20Aircraft.png)

## 📊 Occupancy Analysis

Occupancy rate was calculated by comparing booked seats with the total number of seats available for each aircraft.

The analysis was used to identify differences in aircraft utilisation and to estimate the potential financial impact of increasing occupancy. :contentReference[oaicite:5]{index=5}

A 10% increase in occupancy was also evaluated to estimate its potential impact on annual turnover. :contentReference[oaicite:6]{index=6}

## 💡 Key Findings

- Aircraft vary significantly in seating capacity, ticket volume and revenue generation.
- Ticket bookings and revenue show similar trends over time.
- Fare levels differ across aircraft and fare conditions.
- Business-class fares are generally higher than Economy fares.
- Occupancy rates differ across aircraft, highlighting potential areas for optimisation.
- A simulated 10% increase in occupancy was used to estimate the potential improvement in annual turnover.

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
