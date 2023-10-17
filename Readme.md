# Stock Portfolio Analysis and Watchlist

![Alt text](<Crawford_Dividend Growth.jpg>)



## This Python script is designed for analyzing a stock portfolio and managing a watchlist. It includes functionalities to perform the following tasks:

## Stock Portfolio Analysis:
* Downloads historical data for a list of stocks (such as JNJ, PG, KO, MCD, T).
* Calculates and displays the current stock values and dividend yields for the selected stocks.
* Conducts a Monte Carlo simulation to predict future stock price trends for a specified stock (e.g., JNJ).

## Dividend History:
* Retrieves and displays dividend history for the selected stocks over a 5-year period.

![Alt text](<dividend history plot.png>)


## Dividend Safety Score:
* Calculates a dividend safety score for each stock based on metrics like dividend yield, payout ratio, and trailing EPS.
* Displays the dividend safety score for each stock and visualizes it in a bar chart.

![Alt text](<Safety score-1.png>)


## Watchlist Management:
* Allows users to create and manage a watchlist of stocks.
* Provides options to add and remove stocks from the watchlist.
* Displays the current watchlist.

![Alt text](Watchlist.png)

# Prerequisites
Before running the script, make sure you have the necessary Python libraries installed. You can install them using pip:

```bash
pip install yfinance 
pip install pandas 
pip install matplotlib 
pip install numpy 
```
## Usage
* Clone or download this repository to your local machine.
* Open the Python script in your preferred development environment.
* Modify the stocks list to include the stocks you want to analyze in your portfolio.
* Run the script. It will perform the specified analysis and generate visualizations.
* Follow the on-screen prompts to add or remove stocks from your watchlist.
* Review your watchlist and exit the script when you are done.
# Sample Output
The script will generate various visualizations and provide information about your stock portfolio and watchlist.

# Authors 
John Messing, 
Jan Gutt