# Youtube-Distraction-Analysis
Analyzing YouTube usage data to understand distraction and productivity patterns.
📊 YouTube Watch History Analysis and Visualization
📌 Project Overview

This project focuses on analyzing and visualizing YouTube watch history data to understand user viewing behavior, preferences, and activity patterns. The objective is to extract meaningful insights from raw YouTube history data using data analysis and visualization techniques.

By processing the exported YouTube watch history file, this project identifies trends related to watch time, frequently viewed channels, popular categories, and daily/monthly activity patterns.

The analysis helps in understanding personal content consumption habits and supports data-driven decision-making for digital well-being and productivity improvement.

🎯 Objectives

The main objectives of this project are:

To extract and clean YouTube watch history data.

To analyze user viewing behavior over time.

To identify most watched channels and content types.

To visualize daily, weekly, and monthly watch trends.

To present insights using interactive and static charts.

To improve skills in data preprocessing, analysis, and visualization.

🛠️ Tools and Technologies Used

Programming Language: Python

Development Environment: Jupyter Notebook

Libraries:

Pandas – Data manipulation and cleaning

NumPy – Numerical operations

Matplotlib – Data visualization

Seaborn – Statistical visualizations

Plotly – Interactive charts (optional)

Data Source: Google Takeout (YouTube Watch History)

📁 Dataset Description

The dataset used in this project is obtained from Google Takeout, which allows users to download their YouTube activity data.

The main file includes:

Video Title

Channel Name

Watch Date and Time

Video URL

Device Type (if available)

Format: JSON / CSV / HTML (converted to CSV for analysis)

🔄 Data Collection Process

Logged into Google Account.

Downloaded YouTube history using Google Takeout.

Extracted watch history files.

Converted JSON/HTML files to CSV format.

Imported the dataset into Jupyter Notebook.

🧹 Data Preprocessing

The following preprocessing steps were performed:

Removed duplicate records.

Handled missing values.

Extracted date and time from timestamps.

Converted date columns to datetime format.

Standardized column names.

Filtered irrelevant entries.

Separated day, month, and year features.

These steps ensure data quality and consistency for analysis.

📈 Exploratory Data Analysis (EDA)

Exploratory Data Analysis was conducted to understand patterns in viewing behavior.

Key Analyses:

Total number of videos watched.

Average videos watched per day.

Most active viewing hours.

Most watched channels.

Most frequent video categories.

Distribution of watch activity by weekdays.

EDA helped in identifying trends and anomalies in the dataset.

📊 Data Visualization

Multiple visualizations were created to represent insights clearly.

Visualizations Included:

Line Chart: Watch activity over time

Bar Chart: Top 10 most watched channels

Pie Chart: Category-wise distribution

Heatmap: Viewing activity by hour and day

Histogram: Distribution of watch duration

Area Chart: Monthly watch trend

These visualizations improve interpretability and support better understanding of user habits.

💡 Key Insights

Some important findings from the analysis include:

Peak viewing hours occur mostly during evenings.

Weekends show higher watch activity.

A small number of channels account for most views.

Educational and entertainment content dominates watch history.

Monthly activity increases during holidays and breaks.

These insights help in understanding personal viewing behavior.

📌 Applications of This Project

Digital well-being monitoring

Productivity improvement

Content preference analysis

Recommendation system understanding

Personal habit tracking

⚙️ How to Run the Project
Prerequisites

Python 3.x

Jupyter Notebook

Installation
pip install pandas numpy matplotlib seaborn plotly

Execution Steps

Clone the repository.

Place dataset in the data/ folder.

Open youtube_analysis.ipynb.

Run all cells sequentially.

View generated charts and reports.

📋 Results and Outcomes

Cleaned and structured YouTube history dataset.

Interactive and static dashboards.

Detailed behavioral analysis report.

Improved understanding of personal data patterns.

Practical experience in data visualization.

🚀 Future Enhancements

Add sentiment analysis on video titles.

Implement recommendation prediction.

Build real-time dashboard.

Integrate Power BI / Tableau.

Include watch duration analysis.

Develop mobile-friendly dashboard.

👤 Author

Name: Sreeja Theegala

Role: Data Analyst Enthusiast

📜 License

This project is intended for educational and learning purposes only.
