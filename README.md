# US Flight Delay Analysis using Python

## Project Overview

This project focuses on analysing US flight data from 2015 to understand flight delays, cancellations, diversions, airline performance, and airport activity.

The analysis was performed using Python to identify patterns in departure delays, arrival delays, monthly trends, weekly trends, and reasons for flight delays.

## Dataset Information

- Dataset: US Flight Delays and Cancellations (2015)
- Total Records: 5,819,079
- Original Columns: 31
- Year: 2015
- Unique Airlines: 14
- Duplicate Records: 0

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Project Workflow

1. Loaded the flight dataset.
2. Explored dataset structure using `head()`, `info()`, and `describe()`.
3. Checked missing values and their percentages.
4. Checked duplicate records.
5. Analysed cancelled and diverted flights.
6. Analysed flight distribution across airlines.
7. Added airline names using airline codes.
8. Calculated average departure delays by airline.
9. Calculated average arrival delays by airline.
10. Compared departure and arrival delays.
11. Analysed monthly flight delays.
12. Analysed weekday flight delays.
13. Identified the top 10 busiest origin airports.
14. Identified the top 10 busiest destination airports.
15. Analysed reasons for flight delays.
16. Analysed flight cancellation reasons.
17. Calculated overall flight statistics and percentages.

## Key Analysis and Findings

### 1. Airline Analysis

- Spirit Airlines recorded the highest average departure delay of approximately 15.94 minutes.
- Spirit Airlines also recorded the highest average arrival delay of approximately 14.47 minutes.
- Hawaiian Airlines had the lowest average departure delay of approximately 0.49 minutes.
- Alaska Airlines had an average arrival delay of approximately -0.98 minutes.

### 2. Monthly Analysis

- June recorded the highest average departure delay of approximately 13.99 minutes.
- June also recorded the highest average arrival delay of approximately 9.60 minutes.
- September and October had negative average arrival delays, indicating that flights arrived slightly early on average.

### 3. Day-wise Analysis

- Monday recorded the highest average departure delay of approximately 10.87 minutes.
- Monday also recorded the highest average arrival delay of approximately 6.00 minutes.
- Saturday recorded the lowest average departure delay of approximately 7.83 minutes.
- Saturday also recorded the lowest average arrival delay of approximately 1.85 minutes.

### 4. Airport Analysis

The busiest origin and destination airport was ATL.

Top 5 origin airports by flight count:

| Airport | Flights |
|---|---:|
| ATL | 346,836 |
| ORD | 285,884 |
| DFW | 239,551 |
| DEN | 196,055 |
| LAX | 194,673 |

### 5. Flight Delay Reasons

Based on the total recorded delay minutes:

- Late Aircraft Delay: 24,961,931 minutes
- Airline Delay: 20,172,956 minutes
- Air System Delay: 14,335,762 minutes
- Weather Delay: 3,100,233 minutes
- Security Delay: 80,985 minutes

Late aircraft delays contributed the highest total delay time.

### 6. Flight Cancellation Analysis

- Weather: 48,851 cancellations
- Airline: 25,262 cancellations
- National Air System: 15,749 cancellations
- Security: 22 cancellations

Weather was the most common recorded cancellation reason.

## Overall Project Statistics

| Metric | Result |
|---|---:|
| Total Flights | 5,819,079 |
| Cancelled Flights | 89,884 |
| Diverted Flights | 15,187 |
| Average Departure Delay | 9.37 minutes |
| Average Arrival Delay | 4.41 minutes |
| Flights with Departure Delay | 2,125,618 |
| Cancellation Percentage | 1.54% |
| Diversion Percentage | 0.26% |
| Departure Delay Percentage | 36.53% |

## Visualizations

The project includes visualizations for:

- Number of flights by airline
- Average departure delay by airline
- Average arrival delay by airline
- Departure vs arrival delays by airline
- Monthly departure delays
- Monthly arrival delays
- Monthly departure vs arrival comparison
- Day-wise departure delays
- Day-wise arrival delays
- Day-wise departure vs arrival comparison
- Top 10 busiest origin airports
- Top 10 busiest destination airports
- Total delay time by reason
- Flight cancellation reasons

## Conclusion

This analysis helped identify patterns in US flight delays and cancellations during 2015.

The findings show that Spirit Airlines had the highest average departure and arrival delays. June was the most delayed month, while Monday recorded the highest average delays among weekdays.

Late aircraft delays contributed the highest total recorded delay time, and weather was the leading reason for flight cancellations.

This project helped me practise data analysis using Python, Pandas, and Matplotlib and improve my understanding of exploratory data analysis and data visualization.

## Project Type

Beginner-level Python Exploratory Data Analysis Project.

## Author

Pranali Pakere
