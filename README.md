📌 Problem Statement

-Flight ticket prices vary based on multiple factors such as airline, route, booking time, seat class, and number of stops.

The objective of this project is to perform exploratory data analysis (EDA) on a dataset of 300,000+ flight records to:

Understand how different factors affect flight prices
Identify patterns in booking behavior and pricing trends
Analyze airline performance and route demand
Provide insights to help users make better booking decisions

🛠️ Tech Stack
Programming Language: Python
Libraries Used:
Pandas – Data cleaning & manipulation
NumPy – Numerical operations
Matplotlib – Data visualization
Seaborn – Advanced statistical visualization

📂 Dataset Description
The dataset contains 300,153 flight records with the following key features:
Airline (6 unique airlines)
Source & Destination cities (6 cities)
Departure & Arrival time
Number of stops
Seat class (Economy / Business)
Duration of flight
Days left before departure
Ticket price (Target variable)

⚙️ Project Workflow
1. Data Cleaning
Removed unnecessary columns (index)
Checked for missing values (none found)
Verified data types and consistency
2. Data Exploration
Generated statistical summaries
Analyzed distributions of duration, price, and booking days
3. Data Visualization
Created bar charts, line plots, and relational plots
Compared multiple variables affecting ticket prices

📊 Key Analysis Performed
✈️ Airline Analysis
Identified 6 airlines with Vistara and Air India dominating the dataset
Compared average ticket prices across airlines

🕒 Time-Based Analysis
Studied departure and arrival time distributions
Found that ticket prices vary significantly depending on time slots

🌍 Route Analysis
Analyzed source and destination city trends
Identified high-traffic routes and their pricing patterns

💰 Price vs Booking Time
Analyzed how ticket price changes with days left before departure
Observed that:
Prices are highest when booked close to departure (1–3 days)
Prices decrease when booked earlier

🪑 Class-Based Analysis
Compared ticket prices between Economy and Business class

👉 Key finding:
Economy Average Price: ~₹6,500
Business Average Price: ~₹52,500

🔍 Case Study Analysis
Example: Vistara flights from Delhi to Hyderabad (Business class)
Average price found: ~₹47,939

📈 Key Insights
📊 Flight prices increase as departure date approaches
🛫 Certain airlines (like Vistara) have significantly higher pricing
🪑 Business class tickets are ~8x more expensive than Economy
🌍 Popular routes (Delhi, Mumbai, Bangalore) dominate traffic
🕒 Night and peak-hour flights tend to be more expensive
📅 Early booking can significantly reduce ticket cost

🚀 Outcomes
Built a complete data analysis pipeline (cleaning → analysis → visualization)
Extracted real-world insights from a large dataset (300K+ records)
Improved understanding of pricing strategies in the airline industry
Demonstrated strong skills in:
Data cleaning
Exploratory Data Analysis (EDA)
Data visualization
Insight generation

⭐ Unique Value of This Project
Large-scale dataset (300K+ records)
Multiple factor analysis (time, route, airline, class)
Real-world insights useful for travelers and businesses
Combination of statistical analysis + visualization

