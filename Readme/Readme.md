# Airline Data Analytics: Occupancy & Revenue Optimization ✈️

## Project Overview
This project analyzes airline operational data using SQLite and Python to identify
opportunities for improving aircraft occupancy rates and enhancing revenue efficiency
at the route level.

The airline industry faces challenges such as rising fuel prices, high operational
costs, intense competition, and fluctuating demand. This analysis focuses on using
data-driven insights to support strategic decision-making without increasing fleet size.

---

## Business Problem
Airlines operate in a highly cost-sensitive environment where profitability depends
heavily on efficient seat utilization and pricing strategies. Key challenges include:
- Low aircraft occupancy on certain routes
- Rising fuel and operational costs
- High competition on popular routes
- Inefficient capacity allocation

The goal of this project is to evaluate route-level performance and identify actionable
strategies to improve overall efficiency and revenue generation.

---

## Objectives
- Analyze aircraft occupancy rates across flights and routes
- Evaluate revenue performance at flight and seat levels
- Identify high-performing and underperforming routes
- Provide data-driven strategic recommendations for improvement

---

## Dataset
The analysis is based on a SQLite database (`travel.sqlite`) containing airline-related
data, including:
- Flights and routes
- Aircraft and seat configurations
- Ticket sales
- Passenger boarding information
- Booking-level revenue data

---

## Tools & Technologies
- Python
- SQLite
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Analysis Performed
- Database exploration and schema understanding
- Aircraft occupancy rate calculation
- Route-level occupancy comparison
- Revenue per flight analysis
- Revenue per seat (unit economics) evaluation
- Strategic route prioritization

---

## Key Insights
- Certain routes consistently demonstrate very high occupancy, indicating strong
  passenger demand and efficient capacity utilization.
- Some routes generate high revenue per seat despite lower passenger volumes, suggesting
  strong pricing power or premium demand characteristics.
- Low-occupancy routes present opportunities for optimization through pricing, scheduling,
  or capacity reallocation.

---

## Limitations
- The dataset does not include operational cost details such as fuel, labor, or maintenance
  expenses.
- As a result, true profit-based metrics could not be calculated, and revenue-based
  indicators were used as proxy measures for performance evaluation.

---

## Conclusion
This project demonstrates how airline operational and revenue data can be leveraged to
identify performance gaps and support strategic decisions. By focusing on occupancy
optimization and revenue per seat, airlines can improve financial performance even in
challenging market conditions.

---

## Future Scope
- Incorporate operational cost data to enable true profitability analysis
- Build demand forecasting models for route-level planning
- Apply dynamic pricing simulations based on historical demand patterns
