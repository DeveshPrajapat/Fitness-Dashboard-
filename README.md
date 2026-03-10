🏋️‍♂️ Fitness Club Analytics Dashboard

A data analytics and business intelligence project that analyzes gym member demographics, membership trends, and fitness metrics using an interactive Power BI dashboard.

This project demonstrates data cleaning, KPI analysis, and data visualization techniques to generate actionable insights that can help fitness centers improve operational efficiency and member engagement.

📌 Project Overview

The Fitness Club Analytics Dashboard analyzes gym membership data to understand member demographics, health metrics, and membership patterns.

Using Microsoft Power BI, the dataset was transformed into an interactive dashboard that allows stakeholders to easily monitor and analyze:

Member demographics

Membership status (Active vs Inactive)

Health metrics such as BMI, height, and weight

Membership trends

Trainer allocation and workload

The dashboard enables data-driven decision-making for improving gym operations, customer engagement, and membership retention.

🎯 Business Problem / Objective

Fitness centers require insights into member demographics and health indicators to improve their services and deliver better customer experiences.

The main objectives of this project are to:

Analyze member demographics

Monitor active vs inactive memberships

Track health indicators such as BMI

Evaluate trainer distribution

Identify trends in membership types

These insights can help fitness centers:

Improve customer retention

Offer personalized training programs

Optimize trainer allocation

Design better membership plans

Enhance health tracking services

📂 Dataset Description
Attribute	Details
Dataset Type	Gym Membership Dataset
File Format	Excel (.xlsx)
Total Records	100
Total Columns	14
Dataset Fields
Column	Description
UserID	Unique member ID
UserName	Member name
Age	Age of the member
Gender	Member gender
JoinDate	Date when the member joined
Goal	Member fitness goal
Trainer Name	Assigned trainer
Membership	Membership type
MembershipStart	Membership start date
MembershipEnd	Membership expiration date
Status	Active or inactive membership
Height_cm	Member height in centimeters
StartingWeight	Starting body weight
BMI	Body Mass Index
🧹 Data Cleaning & Preparation

Data preparation was performed using Power BI Power Query.

Data Cleaning Steps

Removed inconsistent or incorrect values

Converted date fields to the correct date format

Checked and handled missing values

Standardized membership categories

Validated numeric values for BMI, height, and weight

Data Transformation

Created calculated measures using DAX

Grouped members by gender, age group, and membership type

Built KPIs for active membership tracking and BMI analysis

📊 Dashboard Features

The Power BI dashboard includes several analytical components designed for easy data exploration.

📈 Key Visualizations

Membership distribution charts

Gender demographic analysis

Age distribution visualization

Trainer assignment overview

BMI distribution analysis

Active vs inactive membership tracking

🎛 Interactive Features

Membership type filters

Trainer-based filtering

Membership status filtering

Drill-down analysis for deeper insights

📌 Key Metrics / KPIs
KPI	Description
Total Members	Total number of registered gym members
Active Members	Members with active memberships
Average BMI	Average body mass index
Average Age	Mean age of gym members
Trainer Allocation	Members assigned to each trainer
Membership Type Distribution	Breakdown of membership plans
🔍 Insights & Findings

The dashboard reveals several useful insights:

Most members belong to the young to middle-age demographic group.

Some trainers are responsible for a higher number of members.

BMI distribution indicates different fitness levels across members.

Membership data shows patterns between active and expired memberships.

Certain membership plans are significantly more popular than others.

These insights can help gyms:

Optimize trainer allocation

Design targeted fitness programs

Improve membership retention strategies

Develop personalized training plans

🛠 Tools & Technologies Used
Tool	Purpose
Power BI	Dashboard development and visualization
Power Query	Data cleaning and transformation
DAX	Calculated measures and KPIs
Microsoft Excel	Dataset source
GitHub	Project version control and hosting
🖥 Dashboard Preview

(Add screenshots of your Power BI dashboard here)

Example:

Images/
dashboard1.png
dashboard2.png
dashboard3.png
📁 Project Structure
Fitness-Club-Analytics
│
├── Dataset
│   └── fitness_dataset.xlsx
│
├── Dashboard
│   └── Dashboard.pbix
│
├── Images
│   ├── dashboard1.png
│   ├── dashboard2.png
│   └── dashboard3.png
│
└── README.md
🚀 How to Use This Project
Step 1 — Clone the Repository
git clone https://github.com/yourusername/fitness-club-analytics.git
Step 2 — Open the Dashboard

Open the .pbix file using Microsoft Power BI Desktop.

Step 3 — Explore the Dashboard

Use filters and slicers to analyze:

Membership types

Trainer distribution

BMI insights

Demographic trends

🔮 Future Improvements

Possible enhancements for future versions of the project:

Add member fitness progress tracking

Integrate real-time fitness data

Apply predictive analytics for membership churn

Develop a web-based dashboard

Implement machine learning models for health risk prediction
