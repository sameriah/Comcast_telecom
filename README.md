# Comcast_telecom

**Description:** 
Comcast, a major telecommunications provider in the U.S., has been facing widespread dissatisfaction due to poor customer service. In October 2016, the company was fined $2.3 million after receiving over 1,000 consumer complaints. The objective of this project is to analyze these complaints to understand the root causes and help Comcast improve its service delivery.

**Approach:**
Loaded the dataset and performed data cleaning, including handling outliers, missing values, dropping zero variance columns, and reformatting the data for better readability and analysis; Ensuring the date column was in the correct date format, and converting any text columns with only two unique values into binary type.

Performed daily and monthly trend analysis to visualize how complaint volumes changed over time.
Extracted and tabulated the most common method of complaint submission (via Internet or customer care calls).

Created a new variable to categorize complaint statuses into binary options (Open or Closed); “Open” and “Pending” were grouped as Open, and “Closed” and “Solved” were grouped as Closed.

Produced a stacked bar chart showing the status of complaints across different states, identifying the state with the highest number of complaints and the state with the highest percentage of unresolved complaints.

Calculate the percentage of complaints resolved (via Internet and customer care calls), which can help measure the efficiency of customer support and guide the company in allocating resources more effectively.
