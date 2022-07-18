# Financial Planner for Emergencies and Retirement

This analysis uses the Python requests library and Alpaca's API to calculate present value of a customer's cryptocurrency, stock, and bond portfolio. The application compares their current portfolio value to a 3 month emergency fund based on the customer's monthly income. The application also executes Monte Carlo simulations for a stock and bond portfolio for a 30-year and 10-year time horizon.

![MC_Simulation.png](https://github.com/rrmangum/Financial_Planner_Emergencies_-_Retirement/blob/main/Images/MC_Simulation.png?raw=true)

---

## Technologies

This analysis uses python Python 3.9.12 and the following libraries:
* [Pandas](https://pandas.pydata.org/) - Provides the calculating functions, and data manipulation necessary to conduct this analysis.
* [os](https://docs.python.org/3/library/os.path.html) - Provides the path for files.
* [requests](https://pypi.org/project/requests/) - Allows sending of HTTP/1.1 requests.
* [json](https://docs.python.org/3/library/json.html) - Provides data interchange.
* [dotenv](https://pypi.org/project/python-dotenv/) - Reads key-value pairs from a .env file and sets them as environment variables.
* [alpaca_trade_api](https://github.com/alpacahq/alpaca-trade-api-python) - Provides real time asset pricing.
* MCForecastTools.py - Builds and executes the Monte Carlo Simulations.

---

## Installation Guide

An installation is not required for this analysis if you are only wanting to review the analysis. If you wish to alter the inputted values, follow the steps below:

1. Download [Anaconda](https://www.anaconda.com/products/distribution) to your computer. In your terminal or gitbash, navigate to the directory you saved the analysis files. Enter the following command:

```python
jupyter lab
```
2. To install dotenv, in your terminal or gitbash, navigate to the directory you saved the analysis files. Enter the following command:

```python
pip install python-dotenv
```
3. To install the Alpaca Trade API, in your terminal or gitbash, navigate to the directory you saved the analysis files. Enter the following command:

```python
pip install alpaca-trade-api
```

4. Be sure to supply your own API keys into a new .env file.

---

## Usage

This analysis is not meant as financial advice, and is purely a comparison of portfolio value to emergency savings funds and a simulation of potential future returns or losses of a retirement portfolio across a 30-year and 10-year time horizon.

---

## Contributors

Ryan Mangum - [LinkedIn](https://www.linkedin.com/in/ryanrmangum/) | rrmangum@gmail.com

---

## License

[MIT License](https://choosealicense.com/licenses/mit/)

Copyright (c) [2022] [Ryan Mangum]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.