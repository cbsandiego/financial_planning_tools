# Financial Planning
---
![Financial Planning.](images/mod5.jpg)

Our financial planning tool will allow users to visualize their current savings and determine if there is enough reserves for an emergency fund.  It will also include a financial retirement tool which will forecast a users current porfolio's performance in 30 years and in 10 years while adjusting its weight between stocks and bonds.

---   

## Installation Guide

Install the python-dotenv Library
```python
    pip install python-dotenv
```

Install the Alpaca SDK
```python
    pip install alpaca-trade-api
```
    
---
    
## Required Libraries and Dependencies

* [JupyterLab Notebook]
* [Pandas] 
* [Alpaca] - create a hidden .env to store your ALPACA_API_KEY and ALPACA_SECRET_KEY
* [MCSimulation] Monte Carlo Simulation
    Import *MCForecastTools.py* into JupyterLab Notebook

Import libraries and dependencies  
```python
    import os
    import requests
    import pandas as pd
    from dotenv import load_dotenv
    import alpaca_trade_api as tradeapi
    from MCForecastTools import MCSimulation
```