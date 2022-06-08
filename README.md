# stock-analysis
# Overview of Project:
The purpose of this project is to conduct a concise analysis on the financial data of “green energy” stocks in an effort to help a great friend, Steve. In researching these stocks, key variables that are analyzed include: Total daily volume, and the yearly return. These key data points will be compared from the years 2017 and 2018 in the final assessment. 

![VBA_Challenge_2017.png](https://github.com/Calebmkelly/stock-analysis/blob/main/Resources/Analysis%20photos%20by%20year/VBA_Challenge_2017.png)![VBA_Challenge_2018.png](https://github.com/Calebmkelly/stock-analysis/blob/main/Resources/Analysis%20photos%20by%20year/VBA_Challenge_2018.png)
# Results: 

Stock Performance:
- When taking a look at the photos above, there are two tables that are representative of “green energy” stocks: the table on the left represents the year 2017 while the table on the right represents the year 2018. When considering the yearly return, “green energy” stocks In the year 2017 preformed fairly well; 11 out of 12 stocks had a positive return, with 6 out of the 11 stocks yielding a return of 50 percent or higher. In the year of 2018, only two stocks had a positive return, with ticker symbols: ENPH and RUN. Both of these stocks yielded a return greater than 81 percent. The daily volume over the year increased for 7 out of the 12 stocks. Focusing on ENPH, the daily volume increased by nearly two and a half times, and RUN had an increase in volume by almost double.

![2017.png](https://github.com/Calebmkelly/stock-analysis/blob/main/Resources/Execution%20Time/2017/2017.png)![2017 Refactored.png](https://github.com/Calebmkelly/stock-analysis/blob/main/Resources/Execution%20Time/2017/2017%20Refactored.png)

The photos above show the execution time for the code that analyzed “green energy” stocks for a given year, with the original code being represented on the left and the refactored code being represented on the right. It is evident that the refactored code has a faster run time than the original.
![2018.png](https://github.com/Calebmkelly/stock-analysis/blob/main/Resources/Execution%20Time/2018/2018.png)![2018 Refactored.png](https://github.com/Calebmkelly/stock-analysis/blob/main/Resources/Execution%20Time/2018/2018%20Refactored.png)

Following a similar format, the execution time for the year 2018 is presented. Again, the refactored code runs significantly faster than the original. 

![Original.png](https://github.com/Calebmkelly/stock-analysis/blob/main/Resources/Code/Original.png)
Original code: 
- Here, the original code utilizes nested for-loops and only has one array, “tickers().”  
![Refactored.png](https://github.com/Calebmkelly/stock-analysis/blob/main/Resources/Code/Refactored.png)
Refactored:
- Compared to the original code, the refactored code does not have a nested for-loop, but does utilize more arrays. One reason that the refactored code may run faster than the original is because sorting the data into arrays is quicker and more efficient than using a nested for-loop to initialize each stock to a row. 

# Summary: 
What are the advantages or disadvantages of refactoring code? 

Advantages: 
- Refactoring code can allow programmers to make their code more efficient and clean. Having some time away from the project you’re working on and coming back to it allows for programmers to have a fresh, new perspective on their code, which can be very important when refactoring code. 

Disadvantage: 
- While making code flow better is great, refactoring can be tedious and complicated. Refactoring code can make it better, but at the cost of your time and effort. It can also be challenging to decide whether the code should be edited for efficiency or if new code is needed from scratch.

How do these pros and cons apply to refactoring the original VBA script?
- The VBA script did take time and effort to refactor, yet in exchange a hastier and more agile piece of code was created. 
