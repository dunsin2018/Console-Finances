### Console-Finances

#### Objective
Create a JavaScript program that analyzes financial data to calculate various statistics.

#### Tools Used
- JavaScript
- HTML
- CSS
- Visual Studio Code
- GitHub

#### Steps
1. Create a new GitHub repo called Console-Finances. Then, clone it to your computer.
2. Copy the starter files in your local git repository.
3. Analyze the given dataset composed of arrays with two fields, Date and Profit/Losses.

#### Results
- Total number of months included in the dataset (HTML element: `totalMonths`)
- Net total amount of Profit/Losses over the entire period (HTML element: `totalValue`)
- Average of the changes in Profit/Losses over the entire period (HTML element: `avgAmounts`)
- Greatest increase in Profit/Losses (date and difference in the amounts) over the entire period (HTML element: `greatestIncrease`)
- Greatest decrease in Profit/Losses (date and difference in the amounts) over the entire period (HTML element: `greatestDecrease`)

#### Code Structure
The code should be structured into functions that handle the different calculations:
- `totalMonths`: Function that calculates the total number of months included in the dataset and displays it in the `totalMonths` HTML element.
- `totalRows`: Function that calculates the net total amount of Profit/Losses over the entire period and displays it in the `totalValue` HTML element.
- ` totalAvgValueRow`: Function that calculates the average of the changes in Profit/Losses over the entire period and displays it in the `avgAmounts` HTML element.
- `findGreatestIncrease`: Function that finds the greatest increase in Profit/Losses (date and difference in the amounts) over the entire period and displays it in the `greatestIncrease` HTML element.
- `findGreatestDecrease`: Function that finds the greatest decrease in Profit/Losses (date and difference in the amounts) over the entire period and displays it in the `greatestDecrease` HTML element.

#### Preview
When you open your code in the browser, your resulting analysis should look similar to the following:

#### Financial Analysis
     Total Months: 8609
     Total: $38382578
     Average Change: $-2315.12
     Greatest Increase in Profits: Feb-2012 ($1926159)
     Greatest Decrease in Profits: Sep-2013 ($-2196167)


#### Conclusion
This JavaScript program will provide you with detailed financial analysis of the given dataset, including the total number of months, net total amount of Profit/Losses, average change, and the greatest increase and decrease in Profit/Losses over the entire period.
