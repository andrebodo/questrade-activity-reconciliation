# Questrade Activity Statment Reconciliation
Tool to take activity statement from questrade and generate excel report.


## Sample Output for my Advised RRSP Portfolio
I am the sole advisor for a friends RRSP portfolio, shown below. My discretionary advice seeks to capitalize on market trends and outperform the S&P 500 for the long run. After an initial trial period in 2018 to early 2019, my advisory decisions became entrusted by my friend so I took a more active approach. 

To improve the meaningfulness of the Sharpe ratio as a performance metric, I calculate it as the average of the 12 month rolling sharpe ratio.
![sample output](https://github.com/andrebodo/questrade-activity-reconciliation/blob/main/sample_output.jpg "RRSP Portfolio")


## Description
This tool takes Questrade activity statment excel output and generates a performance report for the portfolio over time. The current version only supports CAD and USD assets. The report contains the latest positions, some rolling performance metrics and asset class allocations. 
