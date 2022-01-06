# Stock-Analysis
Analyze data from a group of stocks to ascertain their performance over a two-year period. 
## Overview
Steve has just graduated with a finance degree and has taken on his first client, his parents. Steve’s clients are looking to invest in green energy and want to fully invest in DAQO New Energy Corp(ticker **DQ**).  Steve wishes to complete an analysis of several green energy stocks, including DAQO, to assist his clients in making an informed decision on where to invest their money. Steve is hoping to help his clients to diversify their portfolio and avoid “putting all their eggs in one basket”.
### Analysis Results
  * **Stock Analysis** - Based on **_both_** stock analysis macros, **DQ** (and most green energy stocks) experienced a substantial shift in return values from one year to the next. Most stocks did well in 2017 but did not do well in 2018. Looking at the return figures, **TERP** stayed closest to constant in terms of return over both years. This could point to potential volatility in the market with regards to green energy stocks, something for Steve and his clients to consider. 

![Year_Value_OG](https://github.com/agordon16/Stock-Analysis/blob/c5717586fae9de35bc9450e336a7a4be07f627d7/VBA%20Challenge%20Images/Year_Value_Original_Comparison.png)

  * **Macro Review** - The most obvious difference came in execution times for each macro. After refactoring the “yearValueAnalysis” macro, the run time was much shorter thus making it more efficient. In fact, the speed of execution improved by around 85%.
 
**_Original Macro_**
![All_Stocks_Analysis_2017_OG](https://github.com/agordon16/Stock-Analysis/blob/c5717586fae9de35bc9450e336a7a4be07f627d7/VBA%20Challenge%20Images/All_Stocks_Analysis_2017_OG(YearEnd).png)

**_Refactored Macro_**
![VBA_Challenge_2017](https://github.com/agordon16/Stock-Analysis/blob/c5717586fae9de35bc9450e336a7a4be07f627d7/VBA%20Challenge%20Images/VBA_Challenge_2017.png)

## Summary
Creating macros helps to automate data analysis when working with larger data sets and helps you to put that information in a more readable format. 
    
- An advantage to using existing code is that you can save time by not having to write the entire macro from scratch. This gives you the opportunity to utilize pieces of code that have worked well on projects while also allowing for minor changes and/or additions to fit the specific data you might currently be working with.
- Disadvantages could be, finding an appropriate set of code to analyze your data or struggling to edit the code properly. When you attempt to edit existing code, you need to be aware of how each command functions. You could end up with inaccurate results if you miss a necessary piece of code or edit part of the existing macro that is vital to its function. In some cases, it could be more efficient to write a new macro to fit what you are trying to accomplish.   

In our present scenario, it was advantageous to refactor the existing code so that the macro presented the results in a shorter run time. This makes it quicker to run the analysis and create a good comparison.
We incorporated an indexing variable, along with some additional loop functions, that allowed our macro to run through the data a bit faster.  This delivered a slightly quicker executable. Making a macro run more efficiently allows for more efficient reporting.

![Code](https://github.com/agordon16/Stock-Analysis/blob/c5717586fae9de35bc9450e336a7a4be07f627d7/VBA%20Challenge%20Images/Code.png)

