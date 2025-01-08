# Payback-analysis
## Aim
Consider we just developed a new mobile app for sleep tracking on a subscription basis and want to see its commercial performance. \
In this project, I use Python to answer 3 business questions about the app's success.

## Data & Problem statement
The app is free for the first 14 days, and then user sees a paywall and needs to buy a subscription to continue using it. \
We have data in the following format:        
| user_id  | date_of_use |
| ------------- | ------------- |
| 0  | 12.11.2023  |
| 0  | 13.11.2023  |
| 0  | 14.11.2023  |
| 1  | 10.11.2023  |
| 1  | 11.11.2023  |

With this data, we want to answers questions like:
- Does the total payment for all first subscribtions cover the total cost of acquisition?
- What percentage of users buy the subscription immediately on day 14?
- By how many percentage points does n-day retention drop after showing the paywall? 
