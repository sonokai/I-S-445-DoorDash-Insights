# I-S-445-DoorDash-Insights
DoorDash New Verticals: 3-Sided Marketplace Analysis
Project Overview: An end-to-end data engineering and business analytics exercise focusing on optimizing the relationship between Consumers, Dashers, and Merchants.

**Executive Summary**

This project analyzes a sample of DoorDash transaction data to transition from a "flat" data structure to a relational database model. By cleaning and normalizing the data, I identified key bottlenecks in the Dasher-Merchant handoff and proposed actionable strategies for market growth.

**Tech Stack**

Database Design: SQL (DDL for schema creation, 1NF/2NF normalization)

Data Wrangling: Python (Pandas)

Visualizations: R (ggplot2) and PowerBI

Documentation: Markdown

**Database Architecture**

To eliminate data redundancy and ensure data integrity, I normalized the original dataset into a 3-sided marketplace schema:

Users: Consumer demographics and ordering habits.

Merchants: Store categories, location data, and prep-time metrics.

Dashers: Delivery partner vehicle types and efficiency ratings.

Orders: The central fact table linking the three entities via Foreign Keys.

Assumptions Made

Key Business Insights

Recommendations

**Repository Structure**
Plaintext
├── data/               # (Hidden via .gitignore for privacy)
├── sql/                # Schema creation and Normalization scripts
├── notebooks/          # Python/R scripts for EDA
├── visualizations/     # PowerBI screenshots and exported charts
└── README.md

**License**
This project is licensed under the MIT License.
