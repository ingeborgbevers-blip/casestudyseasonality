# casestudyseasonality
Case study of daily bike rental data using seasonality as the starting focus

# Bike Sharing Demand & Seasonality Analysis | Power BI Case Study

## Problem

Seasonality is often treated as predictable. Summer brings higher demand, winter slows things down, and weather patterns broadly follow expectation.

But real-world operational data rarely behaves that neatly.

This case study explores daily bike rental demand using the UCI Bike Sharing dataset, focusing on how weather conditions and external events can disrupt expected seasonal behaviour. The goal was not simply to identify trends, but to understand where normal seasonal assumptions begin to break down.

The analysis investigates how factors such as temperature, humidity, and major weather events influenced rental patterns between 2011 and 2012.

---

## Approach

The project was developed in Power BI using the day-level dataset from the UCI Machine Learning Repository.

### Data Preparation

* Reviewed the dataset documentation and variable definitions
* Imported the daily CSV dataset into Power BI
* Cleaned and transformed fields for reporting use
* Added:

  * Month names and numbers
  * Season name translations
  * Measures for averages and comparisons
* Removed unnecessary summarisation behaviour from integer fields to improve analysis accuracy

### Analytical Focus

The analysis explored:

* Daily rental trends over time
* Differences between casual and registered users
* Seasonal demand patterns
* Relationships between weather conditions and total rentals
* Outlier events where demand deviated from expected seasonal behaviour

### Investigation Areas

Two significant demand drops were identified for deeper analysis:

#### Early September 2011

At first glance, the timing suggested a possible behavioural effect linked to the approaching 10-year anniversary of 9/11. However, closer analysis showed that changing weather conditions, particularly a spike in humidity combined with falling temperatures, provided a more likely operational explanation for the reduction in demand.

#### Late October 2012

The second major drop aligned with Hurricane Sandy, where severe weather conditions clearly disrupted normal seasonal rental patterns.

### Visual Design

The dashboard was designed to remain accessible to non-technical audiences while still supporting exploratory analysis.

Features included:

* Daily trend line charts
* Seasonal comparisons
* Weather factor analysis
* Scatter plots with explanatory subtitles
* Executive summary storytelling
* Linked narrative flow between overview and deep-dive pages

---

## Solution

The analysis demonstrated that seasonality alone does not fully explain customer behaviour.

Key findings included:

* Weather volatility can override expected seasonal demand
* Humidity appeared to have a stronger operational effect than initially expected
* External events create visible behavioural disruption even within otherwise stable trends
* Clear visual storytelling helps non-technical users interpret statistical patterns more confidently

The project also highlighted the importance of investigating anomalies rather than dismissing them as noise.

In short: trends explain the expected. Outliers explain the reality.

---

## Demo

A PDF walkthrough of the Power BI dashboard is included in this repository.

The PDF contains:

* Executive summary
* Dashboard screenshots
* Weather and seasonality analysis
* Investigation of major demand drops
* Operational observations and conclusions

---

## How to Run

### Requirements

* Power BI Desktop

### Steps

1. Download or clone this repository
2. Open the `.pbix` file in Power BI Desktop
3. Refresh the dataset if required
4. Explore the visuals and filters interactively

### Repository Contents

* `Bike_Sharing_Seasonality.pbix`
* `Bike_Sharing_Case_Study.pdf`
* `README.md`

### Data Source

UCI Machine Learning Repository — Bike Sharing Dataset

---

## About StraightLine Data & Training

StraightLine Data & Training focuses on turning operational complexity into practical insight through:

* Data analysis
* Power BI reporting
* ERP/SAP reporting support
* Training and user enablement

Clarity. Insight. Confidence.

Sometimes the most valuable insight arrives when the numbers stop behaving the way we expected them to.
