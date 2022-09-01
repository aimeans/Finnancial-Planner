## Finnancial Planner

The first part is a financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

The Second part is A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.



## Technologies
[Language]: Python 3.9.12

[Libraries] used:

[Pandas] - For the creation and visualization of Data Frames

[Jupyter-Labs] - An ipython kernel for interactive computing in python

[OS] - Miscellaneous operating system interface

[Dotenv] - Module to load environment variables

[Alpaca-Trade-API] - API for the Alpaca trading platform

[MC-Forecast-Tools] - A copy of this module is included in the downloadable files for this project

## Installation Guide

If you are using an anaconda or a conda environment chances are pandas, os and jupyter labs are already installed in your virtual environment 

If they are not then run:
```python
    pip install pandas
    pip install jupyterlab
    pip install os
```

dotenv and alpaca_trade_api need to be installed separately as they do not come in the anaconda environment.
You will need to run:
```python
    pip install dotenv
    pip install alpaca-trade-api
```

## Contributors
Created by Austin Means
>contact info: austinmeans92@gmail.com

## License

[MIT](LICENSE)
