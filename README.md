 **Hotel Bookings Data Analysis**

Exploratory Data Analysis (EDA) of hotel booking data — includes data cleaning, feature engineering, and visualizations to uncover booking patterns, customer behavior, and business insights.

**Features**

Data Cleaning:

Handling missing values (children, babies)

Removing duplicates

Filtering out invalid ADR values

Feature Engineering:

Total stay nights

Party size

Month mapping

Visualizations:

Lead time distribution

Monthly booking trends

Stay length vs ADR

Special requests distribution

Cancellation rate by market segment

ADR by distribution channel

Quick Business Insights:

Median booking lead time

Cheapest stay lengths

Customers with most special requests

Overall cancellation rate

**Project Structure**

hotel-bookings-analysis/
│── data/ # Dataset (if available)
│── hotel_bookings_analysis.py # Main analysis script
│── requirements.txt # Dependencies
│── .gitignore # Ignore unnecessary files
│── README.md # Project documentation

**Getting Started**
1. Clone the repository

git clone https://github.com/your-username/hotel-bookings-analysis.git

cd hotel-bookings-analysis

2. Install dependencies

pip install -r requirements.txt

3. Add dataset

Place your dataset in the data/ folder and rename it to:
Hotel Bookings.csv

4. Run the script

python hotel_bookings_analysis.py

**Requirements**

Dependencies are listed in requirements.txt:

pandas

numpy

matplotlib

**Example Outputs**

The script generates interactive plots such as:

Histogram of booking lead times

Bar chart of monthly bookings

Scatter plot of stay length vs ADR

Cancellation rate by market segment

Average ADR by distribution channel

** Topics**

hotel-bookings · data-analysis · eda · data-visualization · python · matplotlib · pandas · business-insights

**License**

This project is licensed under the MIT License — feel free to use and adapt.
