# Manali Airbnb Budget Analysis

## Business Context

Manali is one of India’s most popular tourist destinations, attracting a large number of budget-conscious travelers. With hundreds of Airbnb listings available at varying price points, travelers often struggle to identify accommodations that offer **maximum value within a limited budget**.

This case study uses **data analysis** to simplify the decision-making process by identifying **high-quality Airbnb listings under ₹5,000 per night**.

---

## Business Problem

Travelers face difficulty in answering the following questions:

* Which Airbnb listings in Manali are truly **worth the price**?
* Do higher prices always indicate better amenities or ratings?
* Which neighborhoods provide the **best value for money**?

---

## Business Objective

To analyze Airbnb listing data and:

* Identify **budget-friendly, high-value accommodations**
* Understand the relationship between **price, amenities, location, and guest ratings**
* Provide **data-driven recommendations** for travelers

---

## Data Overview

* Dataset: Airbnb listings data
* Location: **Manali, India**
* Key Variables:

  * Price per night
  * Amenities
  * Guest ratings
  * Neighborhood
  * Guest capacity
  * Availability

---

## Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## Analytical Approach

### 1️⃣ Data Cleaning & Preparation

* Removed duplicate listings
* Handled missing and inconsistent values
* Converted pricing and rating columns to numeric formats
* Filtered dataset to include only **Manali-based listings**

---

### 2️⃣ Feature Engineering

* Extracted guest capacity from listing descriptions
* Created binary features for key amenities:

  * WiFi
  * Kitchen
  * Mountain View
* Calculated amenity count to measure listing quality

---

### 3️⃣ Exploratory Data Analysis (EDA)

* Analyzed distribution of prices across listings
* Compared amenity availability with price and ratings
* Identified neighborhood-level pricing patterns

---

### 4️⃣ Correlation & Insights

* Studied correlations between:

  * Price and amenities
  * Amenities and guest ratings
  * Location and pricing
* Found that **amenity richness impacts ratings more strongly than price**

---

### 5️⃣ Budget Optimization Strategy

* Filtered listings priced **≤ ₹5,000**
* Shortlisted listings with:

  * Strong guest ratings
  * High amenity scores
* Grouped results by **neighborhood** for actionable recommendations

---

## Key Findings

* Multiple listings under ₹5,000 deliver **high perceived value**
* Premium amenities significantly improve guest ratings
* Some neighborhoods consistently outperform others in affordability and quality

---

## Business Impact

* Enables travelers to make **data-backed accommodation choices**
* Demonstrates how data analysis can **optimize budget decisions**
* Provides a repeatable framework for analyzing accommodation markets

---

## Final Recommendation

Travelers seeking value-for-money stays in Manali should prioritize:

* Listings with higher amenity counts
* Neighborhoods identified as budget-friendly
* Listings with strong guest ratings rather than higher prices

---

## Future Scope

* Analyze seasonal demand and pricing fluctuations
* Build predictive models for price optimization
* Develop an interactive dashboard using **Power BI or Tableau**

---


