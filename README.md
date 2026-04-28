Huntsville Community Blood Supply: Predictive Analytics
Academic Community Engagement (ACE) Project
Course: COSC5302 - Python Programming & Data Analytics (Spring 2026)

Instructor: Dr. Qingzhong Liu

Team: Afolarin Faluyi

Community Partner: Huntsville Regional Health & Donor Center

Project Overview
This project leverages Python-based data analytics to solve critical donor retention and inventory challenges for a local healthcare partner. By analyzing historical donor logs and daily inventory levels, we provide actionable insights to prevent blood shortages and improve engagement within the Huntsville community.

Key Objectives
De-identify and Analyze: Clean donor data while maintaining strict HIPAA-standard privacy.

Identify At-Risk Donors: Predict which donors are likely to lapse (no donation > 180 days).

Inventory Optimization: Visualize supply trends to identify critical shortages in specific blood groups (O-Negative).

Repository Structure
To ensure reproducibility, this repository follows a modular directory structure:

Plaintext
├── data/
│   ├── donor_data_clean.csv      # De-identified donor demographic data
│   └── inventory_levels.csv      # 60-day historical blood unit levels
├── visuals/                      # Generated charts for the final report
├── ACE_Final_Analysis.ipynb      # Main Jupyter Notebook containing the pipeline
├── requirements.txt              # List of Python dependencies
└── README.md                     # Project documentation (this file)


Getting Started
Prerequisites
Ensure you have Python 3.9+ installed. You will need the following libraries:

pandas

numpy

seaborn

matplotlib

Installation
Clone this repository:

Bash
git clone https://github.com/your-username/huntsville-blood-analytics.git
Navigate to the directory:

Bash
cd huntsville-blood-analytics
Install dependencies:

Bash
pip install -r requirements.txt
Usage
Open the ACE_Final_Analysis.ipynb in Jupyter Notebook or VS Code and run all cells. The script will automatically:

Load datasets from the data/ folder.

Calculate donor recency and "At-Risk" status.

Export high-resolution plots to the visuals/ directory.

Data Ethics & Privacy
In accordance with course guidelines (Section 8.2), this project utilizes de-identified data. All Personally Identifiable Information (PII) such as names, phone numbers, and addresses have been removed. Data is handled through unique alphanumeric donor_ids to ensure anonymity.
