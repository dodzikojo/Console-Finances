# Console Finances
An exercise to apply javascript to real world mathematical concepts by analyzing the financial records of a company.

# Preview of Dataset
    var finances = [
    ['Jan-2010', 867884],
    ['Feb-2010', 984655],
    ['Mar-2010', 322013],
    ['Apr-2010', -69417],
    ['May-2010', 310503],
    ['Jun-2010', 522857],
    ['Jul-2010', 1033096],
    ['Aug-2010', 604885],
    ['Sep-2010', -216386],
    ['Oct-2010', 477532],
    ....

# Requirements
JavaScript code that analyzes the records to calculate each of the following:

* The total number of months included in the dataset.

* The net total amount of Profit/Losses over the entire period.

* The average of the **changes** in Profit/Losses over the entire period.
  * You will need to track what the total change in profits are from month to month and then find the average.
  * (`Total/Number of months`)

* The greatest increase in profits (date and amount) over the entire period.

* The greatest decrease in losses (date and amount) over the entire period.

# Results
When the program is run using the provided dataset, it'll return the following in the console log:

```javascript
Financial Analysis
----------------------------
Total Months: 86
Total: $38382578
Average Change: $-2288.20
Greatest Increase in Profits: Feb-2017 ($671099)
Greatest Decrease in Profits: Jan-2017 ($138230)              
```

# Additional Information
Additional code has been provided to show more information in the console log during testing.

```javascript
console.log("---------------------"+(loopCounter+1)+"---------------------");
console.log("Current Month is: "+  currentMonthYear);
console.log("Previous Month Value is: $"+previousMonthValue);
console.log("Current Month Value is: $"+currentMonthValue );
console.log("Change Value: $"+currentChangeValue);
```

The above code will output:
```javascript
---------------------1---------------------
Current Month is: Jan-2010
Previous Month Value is: $0
Current Month Value is: $867884
Change Value: $867884
---------------------2---------------------
Current Month is: Feb-2010
Previous Month Value is: $867884
Current Month Value is: $984655
Change Value: $116771
Current is greater :$984655
Previous is lower :$867884
---------------------3---------------------
Current Month is: Mar-2010
Previous Month Value is: $984655
Current Month Value is: $322013
Change Value: $-662642
Previous is greater :$984655
Current is lower :$322013
---------------------4---------------------
Current Month is: Apr-2010
Previous Month Value is: $322013
Current Month Value is: $-69417
Change Value: $-391430
Current is greater :$-69417
Previous is lower :$322013
```


[Live Preview](https://dodzikojo.github.io/Console-Finances/ "Live Preview")