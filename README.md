 **Problem Statement**

A dataset containing information about Gen Z social media usage is provided.
Analyze the dataset to understand user behavior, platform preferences, addiction levels, and their impact on mental health using Python libraries.

Tasks to Perform

🔹 Part A: Data Preparation (Pandas)
Load the dataset genz_social_media_usage_1M.csv using Pandas.
Display the first 5 rows and dataset information.
Clean the dataset:
Remove missing values
Standardize column names
Rename column:
primary_platform → platform

🔹 Part B: Feature Engineering (NumPy + Pandas)
Create a new column addiction_risk based on:
High → usage > 6 hours
Medium → usage between 3–6 hours
Low → usage < 3 hours
Create age groups using:
Teen (10–15)
Late Teen (16–18)
Young Adult (19–22)
Adult (23–30)
Create an additional feature (optional):
Engagement score using available columns

🔹 Part C: Data Analysis
Find:
Total number of users
Average daily usage
Most used platform
Identify:
Most addicted age group
Platform with highest usage

🔹 Part D: Data Visualization (Matplotlib & Seaborn)

Create the following charts:

📈 Line Chart
👉 Age vs Average Usage
📊 Bar Chart / Countplot
👉 Platform popularity
🥧 Pie Chart
👉 Addiction level distribution
📦 Boxplot
👉 Usage by age group
🔵 Scatter Plot
👉 Daily usage vs mental health score
🌡️ Heatmap
👉 Correlation between numerical features
📉 Histogram
👉 Distribution of daily usage hours
