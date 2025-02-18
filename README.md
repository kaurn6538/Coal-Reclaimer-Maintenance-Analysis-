# Coal Reclaimer Maintenance Analysis - Tableau Project
## Project Overview

This project was conducted to assess which of the five coal reclaimer machines at a coal terminal require maintenance in the upcoming month. These machines operate 24/7 throughout the year, and downtime results in significant financial losses. The coal terminal follows a maintenance criterion that states:

A reclaimer-type machine requires maintenance when, in the previous month, there was at least one 8-hour period where the average idle capacity exceeded 10%.

## Idle Capacity Calculation:

Idle Capacity = (Actual Tonnage - Nominal Capacity) / Nominal Capacity

The analysis was performed using Tableau to identify machines exceeding this threshold and to provide actionable recommendations for executive stakeholders.

Disclaimer: This is a mock-up dashboard used exclusively for analysis purposes. All data used for this analysis is fake. The developer of this dashboard is not affiliated with DBTC.

## Findings & Recommendations

## Reclaimer Machines:

## RL1 - Requires Maintenance

Exceeded the 10% threshold multiple times:

2nd September: 14% (Rolling Average)

14th September: 12% (Rolling Average)

21st September: 15% (Rolling Average)

21st September: 13% (Rolling Average)

Trend Analysis: The data indicates an upward trend in idle capacity. If the trend persists, idle capacity will increase by approximately 0.05% per hour in the long run.

Recommendation: Schedule maintenance for RL1 in the upcoming month.

## RL2 - No Maintenance Required

Did not exceed the 10% threshold at any point.

Observation: The chart shows a plateau on 10th September 2015, indicating sustained full-capacity operation.

Further Analysis: Data suggests that RL2’s full-capacity operation might have caused SR6 to sacrifice some of its utilization. This aspect is discussed in SR6’s analysis.

Stacker Reclaimer Machines:

## SRL1 - No Maintenance Required

Did not exceed the 10% threshold at any point.

Observation: A data gap from 10th September 00:00 to 16th September 23:00 is attributed to the machine performing stacking tasks during this period.

## SR4A - Monitor Performance

Did not exceed the 10% threshold at any point.

Trend Analysis: The data indicates an upward trend in idle capacity. If the trend persists, idle capacity will increase by approximately 0.12% per hour in the long run.

Recommendation: It is highly recommended to review the performance of this machine in the coming weeks as preventive maintenance may be required.

Observation: A data gap from 13th September 00:00 to 16th September 23:00 is attributed to the machine performing stacking tasks during this period.

## SR6 - Further Investigation Required

A surge in the 8-hour moving average idle capacity was observed around 10th September 2015.

Possible Cause: Conflict between SR6 and RL2 when operating on the same line in the stockyard.

When both machines reach the middle of the line simultaneously, they struggle to access the stack efficiently.

RL2 operates at full capacity, forcing SR6 to sacrifice part of its capacity.

Recommendation: Since SR6 did not exceed the 10% threshold at any other point, maintenance is likely not required. However, further operational adjustments are recommended to mitigate conflicts between RL2 and SR6.

## Project Deliverables

Tableau Story: Interactive visualization showcasing idle capacity trends, machine performance, and maintenance recommendations.

Data Analysis Report: Documenting the methodology, findings, and recommendations.

GitHub Repository: Contains Tableau workbook (.twb or .twbx), raw dataset, and README documentation.

## How to Use This Repository

Clone the Repository:

git clone https://github.com/kaurn6538/coal-reclaimer-analysis.git

## Open the Tableau Workbook:

Ensure you have Tableau Desktop installed.

Open the .twb or .twbx file to explore the dashboard.

## Explore the Data:

Filter by machine type and date ranges.

Review idle capacity trends and threshold breaches.

## Use Insights for Decision-Making:

Identify machines requiring maintenance.

Analyze trends and conflicts between reclaimers.

## Conclusion

This project successfully identifies coal reclaimer machines requiring maintenance based on their idle capacity. The findings enable proactive decision-making to minimize downtime and optimize operational efficiency.

Disclaimer: This is a mock-up dashboard used exclusively for analysis purposes. All data used for this analysis is fake. The developer of this dashboard is not affiliated with DBTC.

For any questions or contributions, feel free to open an issue or submit a pull request!

Author: Navdeep Kaur
Date: February 2025
