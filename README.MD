DividenderX is a module that helps to visualize the snow-ball effect of an underlying asset through time.


The parameters needed to run these tools are: 
    Price of the Ticker
    How much the ticker pays dividend per share monthly/Quarterly?
    How many months/quarters you would like to estimate?
    Optional: The name of the Ticker.

For example: 

getDividendMonthly(13, #Price
                    0.095, #Dividend per share 
                    8, #Months amount of dividend payments Quarterly/Monthly
                    "PFLT" #Name
)

getDividendQuarter(54, #Price
                    2, #Dividend per share 
                    8, #Months amount of dividend payments Quarterly/Monthly
                    "IEP" #Name
)