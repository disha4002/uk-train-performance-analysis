## 🚆UK Train Rides Analysis | Power BI
## Project Background

The UK rail network handles a high volume of daily ticket transactions across multiple ticket classes, ticket types, railcards, and payment methods. This project analyzes a transactional dataset of UK train ticket sales (sourced from Maven Analytics) to uncover revenue patterns, customer purchasing behavior, and demand trends across time, ticket categories, and payment preferences.
<br>
Insights and recommendations are provided across the following key areas:
<br>
Revenue Trends: Evaluation of monthly revenue patterns to understand demand fluctuations over time.
<br>
Ticket Class & Type Performance: Analysis of revenue contribution by ticket class (e.g. Standard vs. First Class) and ticket type.
<br>
Railcard Usage: Assessment of how railcard ownership (or lack thereof) influences revenue.
<br>
Payment Method Preferences: Breakdown of revenue by payment method to understand customer payment behavior.
<br>
Purchase Timing: Analysis of ticket purchase volume by hour of day to identify peak booking windows.
<br>

An interactive Power BI dashboard was built to explore these insights, with slicers for Ticket Class, Ticket Type, and Payment Method.
<br>

## Data Structure

The dataset consists of individual train ticket transaction records, including fields such as ticket class, ticket type, railcard type, payment method, purchase time, and ticket price. Each row represents a single ticket transaction.

## Executive Summary
Overview of Findings
<br>
Out of 31,653 total transactions, the dashboard shows a total revenue of $7,41,921 with an average ticket price of $23.44. Monthly revenue remained relatively stable across the four months analyzed, ranging between $159K and $200K, with no single month dominating overall revenue.
<br>
Standard class tickets account for the large majority of revenue ($0.59M) compared to First Class ($0.15M), reflecting the expected skew toward budget-conscious travelers on a national rail network. Revenue by railcard shows that the majority of ticket revenue ($574K) comes from passengers with no railcard, while Adult, Disabled, and Senior railcard holders contribute smaller, comparable shares — suggesting railcard discount usage is a secondary factor in overall revenue rather than the primary driver.
<br>

Ticket purchases by hour show a distinct peak pattern during the day, with transaction volume rising through the morning, peaking in the afternoon window, and tapering off in the evening — consistent with typical commuter and daytime travel behavior rather than late-night demand.
<br>
(Ticket Type and Payment Method category labels should be added here once confirmed from the underlying dataset field names, to specify exactly which ticket type and payment method lead in revenue.
<br>

## Insights Deep Dive

1. Revenue is stable month-over-month, with no extreme seasonality. Monthly revenue fluctuates modestly (159K–200K), suggesting relatively consistent ridership demand across the periods analyzed, rather than sharp seasonal spikes.
<br>
2. Standard class tickets drive the majority of revenue. At roughly 4x the revenue of First Class, Standard tickets are clearly the primary revenue driver, which should inform where operational and marketing focus is placed.
<br>
3. Most revenue comes from passengers without a railcard. Since "None" dominates the Railcard breakdown, railcard discount programs currently represent a minority share of total revenue — useful context for evaluating the cost/benefit of railcard promotional campaigns.
<br>
4. Ticket purchases follow a clear intraday pattern. Purchase volume by hour shows identifiable peak and off-peak windows, which could inform dynamic pricing strategies or targeted promotions during low-demand hours.
<br>
## Dashboard Features
KPI Cards: Total Transactions, Revenue, Total Tickets Sold, Average Ticket Price
<br>
Revenue by Month: Horizontal bar chart showing monthly revenue trend
<br>
Revenue by Ticket Class: Comparison of Standard vs. First Class revenue
<br>
Revenue by Ticket Type: Breakdown of revenue across ticket type categories
<br>
Revenue by Railcard: Treemap visualization of revenue by railcard segment
<br>
Total Tickets Sold by Purchase Hour: Hourly ticket purchase volume distribution
<br>
Revenue by Payment Method: Revenue breakdown across payment methods
<br>
Interactive Slicers: Filter by Ticket Class, Ticket Type, and Payment Method
<br>
## Tools Used
Power BI: Data modeling, DAX measures, and interactive dashboard design
<br>
Dataset Source: Maven Analytics
<br>
Recommendations:
<br>
Focus operational planning and capacity around Standard class demand, given its outsized share of revenue.
<br>
Investigate whether railcard promotions are being effectively marketed, given their comparatively low share of total revenue.
<br>
Consider dynamic pricing or targeted promotions during identified off-peak purchase hours to smooth demand.
<br>
Monitor month-over-month revenue trends over a longer time horizon to detect emerging seasonality not visible in the current data window.
<br>

## Screenshot of the dashboard:
