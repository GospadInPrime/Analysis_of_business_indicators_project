# Analysis_of_business_indicators_project
Analysis of the Procrastinate Pro entertainment application+
##### The problem:
Despite huge investments in advertising, the company has been suffering losses for the last few months.
##### Task:
To understand the causes of catfish and help the company to come out in a plus.
#### Basic information:
There is data on users attracted from May 1 to October 27, 2019:
<br>1. server log with data about their visits,
2. unloading their purchases for this period,
3. advertising expenses.
#### Need to learn:
<br>1.where do users come from and what devices do they use,
2.how much does it cost to attract users from various advertising channels;
3.how much money does each client bring,
4.when the cost of attracting a client pays off,
<br>5.what factors prevent attracting customers.
### Information about data and its structure:
The visits_info_short.csv file stores the server log with information about site visits, orders_info_short.csv — information about orders, and costs_info_short.csv — information about advertising expenses.
##### visits_info_short.csv structure:
<br>User Id — unique user ID,
<br>Region — user's country,
<br>Device — user's device type,
<br>Channel — ID of the transition source,
<br>Session Start — date and time of the session start,
<br>Session End — date and time of the end of the session.
##### orders_info_short.csv structure:
<br>User Id — unique user ID,
<br>Event Dt — date and time of purchase,
<br>Revenue — the amount of the order.
##### costs_info_short.csv structure:
<br>dt — date of the advertising campaign,
<br>Channel — the identifier of the advertising source,
<br>costs — expenses for this campaign.
### Project execution plan:

#### Step 1. Download the data and prepare it for analysis
#### Step 2. Define functions for calculating and analyzing LTV, ROI, retention and conversion.
#### Step 3. Research Data Analysis
<br> 3.1 Let's make user profiles. We will determine the minimum and maximum dates for attracting users.
3.2 Let's find out from which countries users come to the application and which country accounts for the most paying users. Let's build a table showing the number of users and the share of payers from each country.
3.3 Which devices are used by customers and which devices are preferred by paying users. Let's build a table reflecting the number of users and the share of those paying for each device.
3.4 Let's study the advertising sources of attraction and determine the channels from which the most paying users came. Let's build a table reflecting the number of users and the share of payers for each attraction channel.
#### Step 4. Marketing
4.1 Let's calculate the total amount of marketing expenses.
4.2 Let's find out how the expenses are distributed by advertising sources, that is, how much money was spent on each source.
4.3 Let's build a visualization of the dynamics of expenditure changes over time (by weeks and months) for each source. Let's reflect this on one graph.
4.4 Find out how much it cost on average to attract one user (CAC) from each source. We use user profiles.
#### Step 5. Evaluation of the payback of advertising
5.1 Let's analyze the payback of advertising using LTV and ROI graphs, as well as LTV, CAC and ROI dynamics graphs.
5.2 Let's check the user conversion and the dynamics of its changes. We will do the same with user retention. Let's build and study conversion and retention charts.
5.3 Let's analyze the payback of advertising by device. Let's plot LTV and ROI graphs, as well as LTV, CAC and ROI dynamics graphs.
5.4 Let's analyze the payback of advertising by country. Let's plot LTV and ROI graphs, as well as LTV, CAC and ROI dynamics graphs.
5.5 Let's analyze the payback of advertising by advertising channels. Let's plot LTV and ROI graphs, as well as LTV, CAC and ROI dynamics graphs.
#### Step 6. Conclusions on the project
6.1 Highlight the reasons for the inefficiency of attracting users.
6.2 Formulate recommendations for the marketing department.
