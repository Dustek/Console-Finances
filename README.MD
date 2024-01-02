# Console-Finances

## Overview

The purpose of this project is to create a javascript code that calculates various required calculations from financial data in an array, and displays them in a web console log.

## Background

The project uses basic foundations of Javascript such as for loops, elements, arrays and if statements to make caluclations based on the initial data in the "finances" array element.

## Usage

To use the project, simply open the HTML file in Chrome and open the developer console (F12)

## Creation Process

First, I calculated the total length of months of the data using finances.length

Secondly, I calculated the net total profit by creating an array featuring only the integers using .map, then adding all of the integers together using a for loop

Thirdly, I calculated the average change in profit/loss month-to-month by creating an array containing all the changes month to month, by making month 1 = A, month 2 = B a-b, then increment A and B by +1 and repeat.

I then found the average of the differences by adding them together and dividing by their total number, before also rounding down to 2 numbers after the . using toFixed(2)

Fourthly, I calculated the Greatest increase in profit by creating a function that loops through the finances array calculating the increase month-to-month by subtracting current profit from previous profit, profit, then incrementing by 1. The function keeps track of the difference and replaces it with a bigger difference if it finds it. It also keeps track of the month the difference took place on.

Finally, I made a similar function for the greatest decrease, except it calculates by subtracting previous profit from current profit


## Acknowledgements

I would like to give credit to my instructor, Abdul, as well as all the TA's and fellow students who have helped me learn how to complete this project.

## Link to website:

https://dustek.github.io/Bootstrap-Portfolio/





## Screenshot:

![screenshot](https://github.com/Dustek/Console-Finances/blob/master/screenshots/screenshot.png)


