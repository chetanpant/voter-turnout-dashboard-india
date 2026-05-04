# Voter Turnout Dashboard (India 2014–2024)

## Overview

This project analyzes voter turnout trends across selected Indian Lok Sabha constituencies using data visualization and storytelling techniques.

The objective is to build an interactive dashboard that highlights turnout patterns across time, gender, and constituencies.

This project was completed as part of the Data Visualization and Storytelling course at BITS Pilani.

---

## Objective

The project focuses on:

- building a clean dataset from election reports
- creating meaningful visualizations
- designing an interactive dashboard
- applying visualization principles for clarity and storytelling

---

## Data Source

Data was collected from the Election Commission of India (ECI) statistical reports for:

- 2014 Lok Sabha Election
- 2019 Lok Sabha Election
- 2024 Lok Sabha Election :contentReference[oaicite:2]{index=2}  

---

## Dataset

The dataset was manually curated for 10 constituencies across India:

- Andaman & Nicobar Islands  
- Dibrugarh  
- Muzaffarpur  
- Ahmedabad East  
- Mumbai North  
- Bangalore South  
- Ernakulam  
- Lucknow  
- Kolkata Dakshin  
- Bhubaneswar :contentReference[oaicite:3]{index=3}  

---

## Key Variables

- Total electors
- Votes polled (male, female, postal)
- Total votes
- Turnout percentage (overall, male, female, postal)

All calculations were directly derived from official ECI data without assumptions :contentReference[oaicite:4]{index=4}  

---

## Visualizations

The dashboard includes four key visualizations:

### 1. Turnout Trend Over Time
- line chart
- shows change in overall turnout across elections

### 2. Gender-wise Turnout Trend
- multi-line chart
- compares male vs female participation

### 3. Turnout Across Constituencies (Time)
- clustered column chart
- compares turnout across 3 elections

### 4. Turnout Across Constituencies (Gender)
- clustered bar chart
- compares gender turnout across constituencies

These visual choices follow visualization best practices and clarity principles :contentReference[oaicite:5]{index=5}  

---

## Dashboard Features

- year slicer for filtering data
- constituency slicer
- cross-highlighting across charts
- consistent color scheme for gender comparison

---

## Key Insights

### Overall Turnout
- slight decline observed from 2014 to 2024

### Gender Participation
- female turnout is close to male turnout in most cases
- variation exists across constituencies

### Constituency Variation
- Ernakulam and Bangalore South show higher turnout
- Mumbai North and Muzaffarpur show lower turnout

### Postal Voting
- postal turnout remains very low compared to overall turnout :contentReference[oaicite:6]{index=6}  

---

## Why This Project Matters

This project demonstrates how data visualization can be used to:

- simplify complex data
- highlight key trends
- support decision-making
- communicate insights effectively

It focuses on storytelling, not just charts.

---

## Repository Structure
voter-turnout-dashboard-india/

├── README.md
├── docs/
│ └── project_report.pdf
├── dashboard/
│ └── voter_turnout_dashboard.pbix
├── data/
│ └── voter_turnout_dataset.xlsx


---

## How to Use

1. Open the `.pbix` file in Power BI
2. Explore filters using:
   - year slicer
   - constituency slicer
3. Interact with charts to see cross-highlighting

---

## Project Context

This project was developed as part of the Data Visualization and Storytelling course.

It demonstrates:

- dataset creation
- visualization design
- dashboard development
- storytelling through data
