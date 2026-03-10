🏋️‍♂️ Fitness Club Analytics Dashboard

A data analytics project that analyzes gym member demographics, membership trends, and fitness metrics using an interactive Power BI dashboard.

This project demonstrates data cleaning, KPI analysis, and business intelligence visualization to help fitness centers make better operational and marketing decisions.

📌 Project Overview

This project analyzes data from a fitness club to understand member behavior, health metrics, and membership patterns.

Using Microsoft Power BI, the dataset was transformed into an interactive dashboard that allows stakeholders to monitor:

Member demographics

Membership status

Fitness metrics (BMI, weight, height)

Membership trends

Trainer allocation

The dashboard enables data-driven insights for improving gym operations and customer retention.

🎯 Business Problem / Objective

Fitness centers need insights into member demographics and health data to improve services and engagement.

The objectives of this project are:

Analyze member demographics

Monitor active vs inactive memberships

Track health indicators like BMI

Evaluate trainer distribution

Identify trends in membership types

These insights can help gyms improve:

Customer retention

Personalized training programs

Membership offerings

Health tracking services

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
JoinDate	Date when user joined
Goal	Fitness goal
Trainer Name	Assigned trainer
Membership	Membership type
MembershipStart	Membership start date
MembershipEnd	Membership expiration date
Status	Active/Inactive membership
Height_cm	Member height
StartingWeight	Starting body weight
BMI	Body Mass Index
🧹 Data Cleaning & Preparation

Data preparation was performed using Power BI Power Query.

Cleaning Steps

Removed inconsistent values

Converted date columns to proper date format

Checked for missing values

Standardized membership categories

Verified numeric values for BMI, height, and weight

Data Transformation

Created calculated measures using DAX

Grouped members by gender, age group, and membership

Created KPIs for active memberships and BMI trends

📊 Dashboard Features

The Power BI dashboard includes several analytical components:

📈 Key Visualizations

Membership distribution charts

Gender demographics analysis

Age distribution visualization

Trainer assignment overview

BMI distribution analysis

Active vs inactive membership tracking

🎛 Interactive Features

Filters by membership type

Trainer-based filtering

Membership status filtering

Drill-down analysis

📌 Key Metrics / KPIs
KPI	Description
Total Members	Total number of registered gym members
Active Members	Members with active memberships
Average BMI	Average body mass index
Average Age	Mean age of gym members
Trainer Allocation	Members assigned per trainer
Membership Type Distribution	Breakdown of membership plans
🔍 Insights & Findings

Some insights derived from the analysis include:

Most members fall within the young to middle-age group.

Certain trainers handle larger numbers of members.

BMI distribution shows varied fitness levels among members.

Membership data reveals patterns in active vs expired memberships.

Some membership types are significantly more popular than others.

These insights can help gyms:

Optimize trainer allocation

Design targeted fitness programs

Improve membership retention

Develop personalized training plans

🛠 Tools & Technologies Used
Tool	Purpose
Power BI	Dashboard creation
Power Query	Data cleaning
DAX	Calculated measures
Excel	Dataset source
GitHub	Project hosting

🖥 Dashboard Preview
<img width="1327" height="743" alt="Screenshot 2026-03-10 093225" src="https://github.com/user-attachments/assets/ff67183c-81a9-4b50-84b6-995ed8f14d49" />
<img width="1328" height="743" alt="Screenshot 2026-03-10 093259" src="https://github.com/user-attachments/assets/a23b2965-2830-4b7b-8d0c-0bb2765e7a90" />
<img width="1326" height="746" alt="Screenshot 2026-03-10 093320" src="https://github.com/user-attachments/assets/c85d4fb5-7697-4995-8816-9155d8bb3db6" />
<img width="1326" height="743" alt="Screenshot 2026-03-10 093339" src="https://github.com/user-attachments/assets/b3afde16-642e-4e89-a998-91170a1cde6c" />

📁 Project Files Structure
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
🚀 How to Use the Project
Step 1 — Clone the Repository
git clone https://github.com/yourusername/fitness-club-analytics.git
Step 2 — Open Dashboard

Open the .pbix file using Power BI Desktop.

Step 3 — Explore the Dashboard

Use filters and slicers to analyze:

Membership types

Trainer distribution

BMI insights

Demographic trends

🔮 Future Improvements

Possible future enhancements:

Add member progress tracking

Integrate real-time fitness data

Implement predictive analytics for membership churn

Build a web-based dashboard

Add machine learning models for health risk prediction
