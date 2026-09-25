# NYC Taxi Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on New York City Yellow Taxi trip data.

The objective is to analyze taxi trip patterns, revenue, demand, trip duration, pricing, tips, and route-level performance to identify useful operational insights.

## Dataset

The analysis uses NYC Yellow Taxi trip data for 2023.

Key columns include:

* Pickup and drop-off date/time
* Passenger count
* Trip distance
* Pickup and drop-off locations
* Fare amount
* Tip amount
* Total amount
* Payment type
* Congestion surcharge
* Airport fee

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* GeoPandas
* Jupyter Notebook
* Git & GitHub

## Analysis Performed

### Data Preparation

* Loaded and inspected the taxi dataset
* Checked data types and missing values
* Identified and handled data quality issues
* Created derived features such as pickup date, pickup hour, and trip duration
* Identified potential outliers

### Exploratory Data Analysis

The project analyzes:

* Trip demand by hour
* Weekday vs weekend patterns
* Monthly and quarterly revenue
* Trip distance and duration
* Fare and tip patterns
* Payment methods
* Busy and slow periods
* Pickup and drop-off zones
* Route-level performance
* Average trip speed
* Night-time taxi activity
* Correlations between numerical variables

### Geographic Analysis

NYC taxi zone shapefiles are used to analyze geographic patterns in pickup and drop-off activity.

## Key Business Questions

The analysis aims to answer questions such as:

1. What are the busiest hours for taxi trips?
2. How does demand differ between weekdays and weekends?
3. Which periods generate the highest revenue?
4. Which routes and zones have high or low demand?
5. How do trip distance and duration affect revenue?
6. What factors are associated with higher tips?
7. When are taxis most likely to experience longer trips?
8. How can cab positioning be optimized based on demand patterns?
9. What pricing adjustments could potentially improve revenue?

## Project Structure

```text
NYC/
│
├── EDA_Assg_NYC_Taxi_Starter.ipynb
├── README.md
├── taxi_zones/
│   └── NYC taxi zone shapefile files
│
└── .gitignore
```

## How to Run

1. Clone the repository.
2. Open the Jupyter Notebook.
3. Install the required Python libraries.
4. Place the required dataset in the appropriate local folder.
5. Run the notebook cells sequentially.

## Skills Demonstrated

* Exploratory Data Analysis
* Data Cleaning
* Feature Engineering
* Data Visualization
* Statistical Analysis
* Geographic Data Analysis
* Business Insight Generation
* Python Programming
* Pandas and NumPy
* Git and GitHub

## Author

**Amita Dhandha**

Data Analyst | Python Developer | AI & GenAI Learner
