# Walmart Retail Analysis

## Description

One of the leading retail stores in the US, Walmart, would like to predict the sales and demand accurately. There are certain events and holidays that impact sales on each day. Sales data for 45 Walmart stores are available, and the challenge is to predict demand accurately by considering factors like economic conditions including CPI, Unemployment Index, etc.

Walmart runs promotional markdown events that precede prominent holidays: Super Bowl, Labor Day, Thanksgiving, and Christmas. These holiday weeks are weighted five times higher in evaluation than non-holiday weeks. Modeling markdown effects during holiday weeks without complete historical data is a challenge. Historical sales data for 45 Walmart stores are provided.

### Dataset Description

This dataset covers sales from 2010-02-05 to 2012-11-01 and includes the following fields:

- Store: Store number
- Date: Week of sales
- Weekly_Sales: Sales for the given store
- Holiday_Flag: 1 for holiday week, 0 for non-holiday week
- Temperature: Temperature on the day of sale
- Fuel_Price: Cost of fuel in the region
- CPI: Prevailing consumer price index
- Unemployment: Prevailing unemployment rate

### Holiday Events

- Super Bowl: 12-Feb-10, 11-Feb-11, 10-Feb-12, 8-Feb-13
- Labor Day: 10-Sep-10, 9-Sep-11, 7-Sep-12, 6-Sep-13
- Thanksgiving: 26-Nov-10, 25-Nov-11, 23-Nov-12, 29-Nov-13
- Christmas: 31-Dec-10, 30-Dec-11, 28-Dec-12, 27-Dec-13

## Analysis Tasks

### Basic Statistics Tasks

1. Which store has the maximum sales?
2. Which store has the maximum standard deviation (sales vary a lot)? Also, find the coefficient of mean to standard deviation.
3. Which store/s have a good quarterly growth rate in Q3’2012?
4. Identify holidays with higher sales than the mean sales in the non-holiday season for all stores together.
5. Provide a monthly and semester view of sales in units and provide insights.

### Statistical Model

For Store 1:
- Build prediction models to forecast demand.
- Utilize variables like date and restructure dates as 1 for 5 Feb 2010 (starting from the earliest date in order).
- Hypothesize if CPI, unemployment, and fuel price impact sales.
- Change dates into days by creating a new variable.
- Select the model that provides the best accuracy.

All the best!!
