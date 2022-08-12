---
title: Facebook/META
permalink: /facebook/
sidebar:
  nav: "facebook"
--- 


## Company reported data
{: #reported }
Facebook/META [releases financials](https://investor.fb.com/financials/?section=quarterlyearnings) once per quarter. The table below outlines the key metrics reported on:

| Metric | Description | Breakdowns |
| ------ | ----------- | ---------- |
| Earnings per share | Total profit divided by number of outstanding shares | No breakdown |
| Total revenue | Total revenue across all of METAs properties | Regional breakdown |
| Advertising revenue | Total revenue from advertising (e.g. excluding Reality Labs) across all of METAs properties | Regional breakdown |
| Costs | Total costs across all of META | G&A, M&S, R&D, CoS, Taxes |
| Capital Expenditures | Total capital expenditures across META | No breakdown |
| Family Daily Active People | (this is a new user metric) Total number of people (as best determined by META) active on a specific day across all META properties (Facebook, Instagram, Messenger, Whatsapp) | No breakdown |
| Family Monthly Active People | (this is a new user metric) Total number of people (as best determined by META) active at least once over the last 30 days across all of META | No breakdown |
| Facebook Daily Active Users | Total number of people active on a daily basis on the Facebook property only | Regional breakdown |
| Facebook Monthly Active Users | Total number of people active on a monthly basis on the Facebook property only | Regional breakdown |
| Facebook Average Revenue per User | Total revenue for the Facebook property divided by the average Monthly Active Users | Regional breakdown |
| Ad impressions | Increase/decrease in number of ad impressions served | No breakdown |
| Price per impression | Increase/decrease in the price paid per impression | No breakdown |
| Headcount | Total number of employees | Indicative breakdown by R&D, S&M, G&A |
| RSU changes | Granted, vested, forfeited RSUs (key component of compensation for R&D) | No breakdown |
| CFO Outlook | Guidance on (1) revenue/cost next quarter, (2) expenses for full year | No breakdown |

## Analyst consensus data
Facebook/META is covered by 40-50 sell-side analysts, aggregated (Refinitiv, Bloomberg, FactSet, S&P Capital IQ, Zacks) into consensus on Earnings per Share and Revenue only. [StreetAccount](https://www.streetaccount.com/) provides some expectation on Daily Active Users, Monthly Active Users and Average Revenue per User.

## Analysis of recent quarterly reports
{: #reported-swings }

Facebook/META releases their quarterly results after market close. The table below shows the share price movements following these releases:

| Earnings date | Price before release ("close" day of) | Price after release ("open" day after) | Change
| ------ | ------ | ------ | ------ |
| July 27 2022 | $169.58 | $161.06 | -9.5% |
| April 27 2022 | $174.95 | $202.92 | 16.0% |
| February 2 2022 | $323.00 | $244.65 | -24.3% |
| October 25 2021 | $328.69 | $328.26 | -0.1% |
| July 28 2021 | $373.28 | $361.00 | -3.3% |
| April 28 2021 | $307.10 | $330.12 | 7.5% |
| January 27 2021 | $272.14 | $277.18 | 1.9% |
| October 29 2020 | $280.83 | $274.50 | -2.3% |
| July 30 2020 | $234.50 | $255.82 | 9.1% |

February 2 2022 loss was due to weak user growth:
> Facebook loses users for the first time in its history ([Washington Post](https://www.washingtonpost.com/technology/2022/02/02/facebook-earnings-meta/))

> Meta Faces Historic Stock Rout After Facebook Growth Stalled ([Bloomberg](https://www.bloomberg.com/news/articles/2022-02-02/facebook-shares-plunge-as-users-stall-forecast-falls-short#xj4y7vzkg)

April 27 2022 gain was largely due to an upswing in user growth:
> Facebook holds on to users, stock soars ([Washington Post](https://www.washingtonpost.com/technology/2022/04/27/facebook-earnings-stock-increase/))

> Meta Shares Soar as Facebook Returns to User Growth ([Bloomberg](https://www.bloomberg.com/news/articles/2022-04-27/meta-platforms-facebook-returns-to-user-growth-shares-soar#xj4y7vzkg))

July 27 2022 drop was largely due to missed revenue, driven by a lower degree of monetization:
> Facebook reports first-ever decline in revenue ([Washington Post](https://www.washingtonpost.com/technology/2022/07/27/facebook-revenue-declines-2nd-quarter-earnings/))

> Meta Falls as Sales Miss Estimates in First-Ever Quarterly Drop ([Bloomberg](https://www.bloomberg.com/news/articles/2022-07-27/meta-falls-as-sales-miss-estimates-decline-for-first-time))


## Discussion of quarterly reporting
On the reported metrics, it seems that Users and Monetization are the most important metrics:
- Users: Facebook/META as a platform completely depends on its ability of attracting users. A decline in overall user engagement is read by the market as a signal of the platform being unhealthy (e.g. Feb 2 2022 drop), and any increase in user engagement is a signal of the platform being in a good state (e.g. April 27 2022 gain). A large part of the market cap is subscribed to future potential earnings (EBITDA multiple of ~30x), and the share price is therefore very sensitive to any indication of the long-term potential being at risk.
- Monetization: The monetization component of the revenue is important, but it seems that the market is viewing this as less of an indication of future performance. That said, changes to the level of performance does also have an impact on the share price (July 27 2022 drop).
- Costs: It seems that costs and profitability is of little importance. The guidance given is viewed as accurate and trustworthy.

The ability of the market to predict swings in the key metrics of Users and Monetization seems very poor:
- July 27 2022: The change in monetization (average revenue per person) -5.4% while the market believed that it would come out positive
- April 27 2022: The increase in users (daily active users) was 2% while the market feared it would be flat
- February 2 2022: The increase in users (daily active users) flat while the market believed it would be 1-2%

A model able of predicting users and monetization within ~1% on a quarterly basis would likely be smarter than the current market.

# Modeled real-time metrics
{: #alternative }
Facebook has a very rich digital footprint. In particular the public user engagement, and the metrics exposed through their advertising products. If you want to understand in detail how the below metrics are put together, please read through the [methodology]({{site.baseurl}}/facebook/#methodology) section.

## User engagement data

The user engagement in Facebook/METAs quarterly reports is on Monthly and Daily active people/users for the Facebook app and for the whole family of apps (Facebook, Instagram, Messenger and Whatsapp).

Below is the reported data for Daily Active People for the whole family of apps (Facebook, Instagram, Messenger, Whatsapp), including the derived real-time measurements:

![alt](https://docs.google.com/spreadsheets/d/e/2PACX-1vQQzQX605torI6EKbIyL9gZaeeeRW_AXkyVLgd8X7sPeXzgnqyR_-GYm_2arC1DMRVelK1wpjCaTj7k/pubchart?oid=1639133568&format=image)

Do note that the Q3'22 result for Facebook will be the average of the July, August and September measurements. The July, August and September are an aggregation of the daily view below:

![alt](https://docs.google.com/spreadsheets/d/e/2PACX-1vQQzQX605torI6EKbIyL9gZaeeeRW_AXkyVLgd8X7sPeXzgnqyR_-GYm_2arC1DMRVelK1wpjCaTj7k/pubchart?oid=461057490&format=image)

When looking at the daily chart it's important to note that the first day of the quarter (July 5) can not be directly compared to the reported number fore Q2'22 as the reported number for Q2'22 is the average of all the days across all of Q2'22, and the first day of the quarter is only a continuity from the last day of the quarter (which is not reported on). Similarly, even though the last daily measurement for the quarter (September 30) may be substantially higher than the reported number for Q2'22, the actually reported number for Q3'22 will be an average of all the daily values for all of Q3'22. To form an idea of what the reported number for Q3'22 will be the best way is to take the average of the above shown values for July, August and September (as September populates with confidence towards the end of the quarter).

For Monthly Active People, please see reported data with monthly measurements, as well as daily underlying measurements below:

![alt](https://docs.google.com/spreadsheets/d/e/2PACX-1vQQzQX605torI6EKbIyL9gZaeeeRW_AXkyVLgd8X7sPeXzgnqyR_-GYm_2arC1DMRVelK1wpjCaTj7k/pubchart?oid=1473773026&format=image)

![alt](https://docs.google.com/spreadsheets/d/e/2PACX-1vQQzQX605torI6EKbIyL9gZaeeeRW_AXkyVLgd8X7sPeXzgnqyR_-GYm_2arC1DMRVelK1wpjCaTj7k/pubchart?oid=547934901&format=image)

Below is the equivalent chart for Daily Active Users for Facebook only (including daily measurements by region):

![alt](https://docs.google.com/spreadsheets/d/e/2PACX-1vQQzQX605torI6EKbIyL9gZaeeeRW_AXkyVLgd8X7sPeXzgnqyR_-GYm_2arC1DMRVelK1wpjCaTj7k/pubchart?oid=1019087059&format=image)

![alt](https://docs.google.com/spreadsheets/d/e/2PACX-1vQQzQX605torI6EKbIyL9gZaeeeRW_AXkyVLgd8X7sPeXzgnqyR_-GYm_2arC1DMRVelK1wpjCaTj7k/pubchart?oid=28526200&format=image)

![alt](https://docs.google.com/spreadsheets/d/e/2PACX-1vQQzQX605torI6EKbIyL9gZaeeeRW_AXkyVLgd8X7sPeXzgnqyR_-GYm_2arC1DMRVelK1wpjCaTj7k/pubchart?oid=910259771&format=image)

![alt](https://docs.google.com/spreadsheets/d/e/2PACX-1vQQzQX605torI6EKbIyL9gZaeeeRW_AXkyVLgd8X7sPeXzgnqyR_-GYm_2arC1DMRVelK1wpjCaTj7k/pubchart?oid=1429312093&format=image)

![alt](https://docs.google.com/spreadsheets/d/e/2PACX-1vQQzQX605torI6EKbIyL9gZaeeeRW_AXkyVLgd8X7sPeXzgnqyR_-GYm_2arC1DMRVelK1wpjCaTj7k/pubchart?oid=835800087&format=image)

And below is the equivalent for Monthly Active Users for Facebook only (including daily measurements by region):

![alt](https://docs.google.com/spreadsheets/d/e/2PACX-1vQQzQX605torI6EKbIyL9gZaeeeRW_AXkyVLgd8X7sPeXzgnqyR_-GYm_2arC1DMRVelK1wpjCaTj7k/pubchart?oid=471088397&format=image)

![alt](https://docs.google.com/spreadsheets/d/e/2PACX-1vQQzQX605torI6EKbIyL9gZaeeeRW_AXkyVLgd8X7sPeXzgnqyR_-GYm_2arC1DMRVelK1wpjCaTj7k/pubchart?oid=1803887422&format=image)

![alt](https://docs.google.com/spreadsheets/d/e/2PACX-1vQQzQX605torI6EKbIyL9gZaeeeRW_AXkyVLgd8X7sPeXzgnqyR_-GYm_2arC1DMRVelK1wpjCaTj7k/pubchart?oid=73177859&format=image)

![alt](https://docs.google.com/spreadsheets/d/e/2PACX-1vQQzQX605torI6EKbIyL9gZaeeeRW_AXkyVLgd8X7sPeXzgnqyR_-GYm_2arC1DMRVelK1wpjCaTj7k/pubchart?oid=153160194&format=image)

![alt](https://docs.google.com/spreadsheets/d/e/2PACX-1vQQzQX605torI6EKbIyL9gZaeeeRW_AXkyVLgd8X7sPeXzgnqyR_-GYm_2arC1DMRVelK1wpjCaTj7k/pubchart?oid=274548782&format=image)

If anyone is interested in accessing the underlying data for any of this, please [contact me]({{site.baseurl}}/contact) and I'll either give you a one-time dump or build a system that delivers the data on a daily basis to you.


## Monetization data

I have experimental versions of this and I hope to publish them soon. If you're interested in seeing what I have so far, please [contact]({{site.baseurl}}/contact) me.


# Methodology
{: #methodology }
Facebook/META exposes data through a large set of interfaces, but one major area is through their advertising products which happen to also be the driver of the vast majority of revenue for Facebook. Through the advertising products Facebook/META allows anyone to run advertising campaigns where against payment anyone can reach their users. As part of this, Facebook reports on how many users were reached and what the cost was for the ad campaign. To allow for advertisers to plan and evaluate their campaigns they expose a large set of statistics and data.

Most notably, they give out data on the reach of campaigns. Below is an example of this reported for a certain geographical, demographic and placement/property targeting:

![alt]({{site.baseurl}}/docs/assets/images/Reach.png)

The parameters can be varied along a large set of parameters, including:
* Location (country, region, etc)
* User age
* Gender
* Interests
* Language spoken
* Platform (Facebook, Instagram, Messenger)

This gives the ability of extracting data about the total reach available at any given time for a subset of these parameters.

Furthermore, information is given about the cost of reaching this audience:

![alt]({{site.baseurl}}/docs/assets/images/Reach_2.png)

This gives information about the prices Facebook is charging for engaging and reaching their audience (e.g. monetization data).

Currently, ~600 data points are pulled four times per day in order to accurately derive the reported metrics.

When it comes to the user data, there are two bias issues:
- Only users that are "monetizeable" are measured. This excludes for example users under the age of 13
- No ads are shown on Whatsapp, and therefore any users only using Whatsapp would not be covered by this data (a problem for the reported "Family" statistics)

Overall though the under-reporting due to the two issues above can be calculated and is 15-20% depending on the platform and geography. Furthermore, in predicting revenue the issues above are actualle non-issues as the missed out measured audiences anyway are not generating any revenue for Facebook.

# Raw data download #
{: #download }

All data shown above can be downloaded [here](https://docs.google.com/spreadsheets/d/e/2PACX-1vQQzQX605torI6EKbIyL9gZaeeeRW_AXkyVLgd8X7sPeXzgnqyR_-GYm_2arC1DMRVelK1wpjCaTj7k/pub?gid=1923224639&single=true&output=csv). Please note that this file is updated on a daily basis.
