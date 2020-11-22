# Questrade Activity Statment Reconciliation
Tool to take activity statement from questrade and generate excel report.


## Sample Output for my Advised RRSP Portfolio
I am the sole advisor for a friends RRSP portfolio, shown below. My discretionary advice seeks to capitalize on market trends and outperform the S&P 500 for the long run. After an initial trial period in 2018 to early 2019, my advicory decisions became entrusted by my friend so I took a more active approach. 

To improve the meaninfulness of Sharpe ratio, I calculate it as the average of the 12 month rolling sharpe ratio. Doing so provides a more consistent view of performance rather than an instantanous metric. By doing so I have significantly penalized the performance over the last year, which has a Sharpe ratio north of 1.3.
![sample output](https://github.com/andrebodo/questrade-activity-reconciliation/blob/main/sample_output.jpg "RRSP Portfolio")


## Description
This tool takes Questrade activity statment excel output and generates a performance report for the portfolio over time. The current version only supports CAD and USD assets. The report contains the latest posistions, some rolling performance metrics and asset class allocaitons. 
