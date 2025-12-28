#  ✈️ US Flights Operations & Delay Analysis

## 1. Project Introduction

This project delivers an end-to-end analytical review of US domestic flight operations, with a focus on **delays, cancellations, reliability, economic cost, and environmental impact**. Using publicly available US flight data, the analysis transforms millions of flight records into decision-ready insights for airlines, airports, regulators, and operations teams.

The goal is not just reporting — but **diagnosing systemic operational inefficiencies** and highlighting where performance, reliability, cost control, and sustainability can be improved.

---

## 2. Tags & Badges

**Tags**
`Power BI` · `Data Analytics` · `Aviation Analytics` · `Operations Analytics` · `Business Intelligence` · `DAX` · `Data Modeling`

**Badges**

* 📊 Power BI Dashboard
* 🧠 Analytics Project
* 🏗️ Star Schema Modeling
* 🌍 Sustainability Analytics

---

## 3. Extended Introduction (Context & Scope)

Modern aviation systems are highly interconnected — a delay at one airport or route can cascade across an entire network. This project explores **how, when, where, and why** these disruptions occur.

Key themes explored:

* Network-wide operational performance
* Root causes of delays (carrier, weather, late aircraft, NAS, security)
* Airline and airport reliability benchmarking
* Route-level risk identification
* Financial and environmental externalities of inefficiency

The analysis spans **multiple years** and over **5.6 million flights**, enabling both trend analysis and structural performance comparisons.

---

## 4. Dashboard Summary

The Power BI report is organized into focused analytical dashboards:

### 📌 Executive Overview

* Overall system health (on-time performance, cancellations, delays)
* High-level KPIs for leadership and stakeholders

### ⏱️ Delay Patterns & Root Causes

* Delay contribution by cause
* Time-of-day, day-of-week, and yearly delay trends
* Identification of systemic operational bottlenecks

### 🏢 Airport Performance

* Worst-performing airports by average arrival delay
* Airports with the highest cancellation risk
* Ranking-based benchmarking across the national network

### ✈️ Airline Reliability

* Reliability score combining delay rate and severity
* Best vs worst-performing carriers
* Trade-off between punctuality and cancellation behavior

### 🛣️ Route Performance

* High-risk and consistently delayed routes
* Routes with 100% delay rates
* Reliability and cancellation behavior at route level

### 💰 Economic Impact

* Estimated cost of delays by year and time of day
* Identification of peak cost periods

### 🌱 Environmental Impact

* Estimated excess fuel burn from delays
* CO₂ emissions attributable to operational inefficiencies
* Airports contributing most to emissions

---

## 5. Analytical Process

1. **Data Understanding & Cleaning**

   * Reviewed raw flight-level data
   * Handled nulls, cancellations, and delay edge cases

2. **Data Modeling**

   * Designed a star schema
   * Created dimension tables for airports, airlines, dates, and routes
   * Managed active and inactive relationships for origin/destination logic

3. **Feature Engineering**

   * Calculated delay metrics, cancellation rates, reliability scores
   * Built route identifiers and performance flags

4. **DAX Development**

   * Advanced measures using `CALCULATE`, `RANKX`, `FILTER`, `USERELATIONSHIP`
   * Performance-aware aggregations

5. **Visualization & Storytelling**

   * Business-aligned dashboard design
   * Clear KPI framing and benchmarking logic

---

## 6. Key Insights (Summary)

> *Detailed insights are derived directly from the Power BI report and exported PDF.*

Highlights include:

* Late aircraft delays account for **~34%** of all delays, indicating network ripple effects
* Evening flights show the highest delay accumulation
* Smaller regional airports exhibit disproportionately high cancellation rates
* A **14-point reliability gap** exists between best and worst airlines
* Certain routes show **systemic failure patterns** with 100% delay rates
* Delay-related CO₂ emissions represent a significant sustainability risk

---

## 7. Purpose & Target Audience

**Purpose**

* Support operational decision-making
* Identify structural inefficiencies
* Enable performance benchmarking

**Audience**

* Airline operations & network planning teams
* Airport authorities
* Aviation regulators
* Business & data analysts
* Sustainability and ESG stakeholders

---

## 8. What I Learned

* Designing scalable data models for large datasets
* Translating operational metrics into business KPIs
* Using DAX for ranking, benchmarking, and conditional logic
* Balancing analytical depth with executive-level clarity
* Applying analytics beyond finance into **operations and sustainability**

---

## 9. Future Improvements

* Incorporate weather severity indices
* Add aircraft type and fleet-level analysis
* Introduce predictive delay modeling
* Integrate passenger impact metrics
* Compare pre- and post-COVID operational resilience

---

## 10. How to Use This Repository

* 📊 Open the `.pbix` file to explore interactive dashboards
* 📄 Review the exported PDF for a static executive summary
* 📁 Reference DAX logic and modeling decisions for learning or reuse

---

**Author:** Anne Wambaire Mwangi
**Focus:** Business Intelligence · Operations Analytics · Aviation Systems
