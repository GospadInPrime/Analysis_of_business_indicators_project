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
