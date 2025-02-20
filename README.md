# Payback-analysis
## Table of contents
* [Project background](https://github.com/Azidalus/Buisness-metrics-analysis-in-Pandas#Project-background)
* [Data structure](https://github.com/Azidalus/Buisness-metrics-analysis-in-Pandas#Data-structure)
* [Executive summary](https://github.com/Azidalus/Buisness-metrics-analysis-in-Pandas#Executive-summary)

## Project background 
Consider we just developed a new mobile app on a subscription basis and want to see its commercial performance. The app is free for the first 14 days, and then user sees a paywall and needs to buy a subscription to continue using it.\
This project aims to answer business questions about the app's success.

## Data structure
Data has the following format:        
| user_id  | date_of_use |
| ------------- | ------------- |
| 0  | 12.11.2023  |
| 0  | 13.11.2023  |
| 0  | 14.11.2023  |
| 1  | 10.11.2023  |
| 1  | 11.11.2023  |

## Executive summary
With this data, the following questions are answered:
- Does the total payment for all first subscribtions cover the total cost of acquisition?
- What percentage of users buy the subscription immediately on day 14?
- By how many percentage points does n-day retention drop after showing the paywall? 
