# Module 5 Challenge: Financial Planner

### Package Requirments
`pip install x` where x is the below listed packages
* python
* numpy
* pandas

### Purpose of Use
* Create two financial analysis tools, a financial planner for emergencies and a financial planner for retirement. 
* The code is two parts:
    1. Financial Planner for Emergencies

        a. Use the Python Requests library and the Alpaca SDK to determine current values of savings.
   
    2. Financial Planner for Retirement
    
        a. Use the previously pulled data from the Aplaca SDK and the MCForecastTools library to create a Monte Carlo simulation to determine future portfolio value.

### Files Navigation
* `financial-planner.ipynb`: Code explanation, building, some data visulaization, and divided by parts
* `MCForecastTools.py`: Executable script alternative for the jupyter notebook

### Solution
* After creating the first analysis tool, users can determine if they have enough savings in an emergency fund.
* The second tool measures retirement funds and it's made clear that even if weighting a portfolio with more stocks than bonds, that does not necessarily mean an early retirement.