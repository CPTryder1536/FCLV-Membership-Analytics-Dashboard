# FCLV Membership & Fan Engagement Analytics Dashboard

## Project Overview

This project is a multi-page Power BI dashboard built for a fictional professional soccer club, **FCLV**, using synthetic membership, attendance, merchandise, and ticketing data. The goal was to create an executive reporting solution that provides visibility into membership revenue, fan retention, attendance behavior, merchandise spending, and overall fan engagement.

The dashboard simulates the types of business questions commonly faced by professional sports organizations, including:

* Which fan segments generate the most revenue?
* How effectively are members renewing their memberships?
* Which member groups are most engaged with the club?
* How does merchandise spending vary across fan segments and seat types?
* Which membership products and seating areas drive business performance?

---

## Business Problem

Sports organizations rely on membership and ticket revenue as key drivers of financial performance. However, revenue alone does not provide a complete picture of fan behavior.

Leadership teams need visibility into:

* Membership growth and retention
* Revenue generation by customer segment
* Fan attendance and engagement
* Merchandise purchasing behavior
* Performance across seating categories and membership products

This dashboard was designed to help decision-makers monitor both financial and engagement-related KPIs in a single reporting solution.

---

## Tools & Technologies

* Power BI Desktop
* Power Query
* DAX (Data Analysis Expressions)
* Data Modeling
* CSV Data Sources
* Interactive Slicers & Filtering
* Dashboard Design & Data Visualization

---

## Data Sources

The project uses entirely synthetic data generated for portfolio purposes.

### Tables Included

**Members**

* MemberID
* Membership Status
* Renewal Status
* Segment
* Seat Type
* Join Date

**MembershipSales**

* Sales Transactions
* Membership Types
* Revenue
* Payment Status
* Season Information

**Attendance**

* Match Attendance Records
* Ticket Usage
* Match Participation

**Matches**

* Match Details
* Opponents
* Attendance Figures
* Theme Nights

**Merchandise**

* Merchandise Purchases
* Product Categories
* Revenue
* Purchase Activity

---

## Data Modeling

A star-schema-inspired data model was created using MemberID and MatchID relationships to connect membership, attendance, merchandise, and sales data.

Data preparation included:

* Cleaning and standardizing categorical values
* Correcting inconsistent seat-type labels
* Validating relationships across tables
* Creating reusable DAX measures for reporting
* Building interactive filters for segmentation analysis

---

# Dashboard Page 1: Executive Overview

## Purpose

Provide club leadership with a high-level view of membership performance, revenue generation, retention, and attendance.

### Key Performance Indicators

* Total Revenue
* Total Members
* Renewal Rate
* Churn Rate
* Active Members
* Attendance Rate

### Visualizations

#### Revenue by Segment

Highlights which member segments generate the highest revenue.

#### Membership Distribution by Seat Type

Shows the composition of the membership base across seating categories.

#### Attendance Rate by Segment

Identifies which fan segments demonstrate the highest engagement through attendance.

### Interactive Filters

* Segment
* Seat Type
* Membership Type

---

# Dashboard Page 2: Fan Engagement

## Purpose

Provide deeper insight into member engagement and purchasing behavior beyond ticket revenue.

### Key Performance Indicators

* Total Merchandise Revenue
* Average Merchandise Spend
* Attendance Rate
* Active Members

### Visualizations

#### Merchandise Revenue by Segment

Analyzes merchandise purchasing behavior across member segments.

#### Merchandise Revenue by Seat Type

Examines merchandise performance across seating categories.

#### Attendance Rate by Segment

Highlights differences in engagement levels among member groups.

### Interactive Filters

* Segment
* Seat Type
* Membership Type

---

## Key Insights

Analysis of the synthetic dataset revealed several notable patterns:

* Corporate members generated the highest overall revenue.
* Supporters Club members demonstrated the strongest attendance rates.
* Merchandise spending varied significantly across fan segments.
* Premium seating categories accounted for a disproportionate share of revenue.
* Fan engagement metrics did not always align with revenue generation, highlighting the importance of tracking both financial and behavioral KPIs.

---

## Skills Demonstrated

### Business Intelligence

* KPI Development
* Executive Reporting
* Dashboard Design
* Data Visualization

### Data Analytics

* Data Cleaning
* Data Validation
* Segmentation Analysis
* Revenue Analysis
* Retention Analysis

### Power BI

* Power Query Transformations
* Data Modeling
* Relationship Management
* DAX Measures
* Interactive Reporting

---

## Screenshots

### Executive Overview Dashboard

*Insert executive-overview.png*

### Fan Engagement Dashboard

*Insert fan-engagement-dashboard.png*

---

## Disclaimer

This project was created for portfolio and educational purposes. All data used is synthetic and does not represent any actual club, organization, customer, or financial information.
