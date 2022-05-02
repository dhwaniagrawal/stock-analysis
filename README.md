# VBA Module 2 Challenge #

## Overview of the Project ##
Steve wants to include the entire dataset this time, he belives previous code may work but if it does then might take a longer run time. 

### Purpose ###
To refactor the The Module 2 solution code to loop through data once in order to get the same information. And also to determine whether refactoring the the Module 2 solution code successfully made the VBA script run faster.

## Results ##
 1. In 2017 all the stocks returned positive except TERP and in 2018 TERP gained momentum but still closed in loss.
 2. DQ saw the biggest drop from 2017 to 2018 as it dropped from 200% up to 63% down.
 3. RUN saw the biggest jump from 2017 to 2018 where it went from only 5.5% up to 84% up.
 4. Overall the market looked very strong in 2017 compared to 2018.

![This is an image](https://github.com/dhwaniagrawal/stock-analysis/blob/main/Resources/All%20Stocks%202017.png)

![This is an image](https://github.com/dhwaniagrawal/stock-analysis/blob/main/Resources/All%20Stocks%202018.png)

5. Run time for the refactored script was faster than the original one.

![This is an image](https://github.com/dhwaniagrawal/stock-analysis/blob/main/Resources/Run%20time%20for%20original%20script%202018.png)

![This is an image](https://github.com/dhwaniagrawal/stock-analysis/blob/main/Resources/Run%20time%20for%20refactored%20script%202018.png)

## Summary ##

1. ### Advantage ###
Faster run time, less number of lines of code better quality of code.
Improve readability
1. ### Disadvantage ###
It is not very intuitive, it takes time to code.

2. ### Advantage ###
It is faster run time than the original script.

2. ### Disadvantage ###
While it has faster runtime it takes more memory as it has 3 additional arrays totalVolume, tickerstartingPrice and tickerendingPrice.

