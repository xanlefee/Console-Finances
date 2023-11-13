# Console-Finances
#JavaScript analysing Financial Records of a company

This is a response to a challenge utilising for loops and math functions to analyse the financial records of a company such as net profits and losses, the average monthly profits and losses as well as the greatest and smallest profits/losses out of all months recorded. 


Firslty, I calculated the total amount of months in the dataset by getting the length of the finances array. Secondly, created a for loop to add all number values in the array to get the total amount of losses or profits over the entire period. Then, in two parts, I used a for loop to track the difference in profits/losses month to month and stored this data in a new array. Then I worked out the average of changes in profits/losses for the dataset by dividing the sum of the total differences by the months included - 1. 

I was able to nest conditional operators in a for loop to work out the highest and lowest profit/losses simultaneously. I then printed to the console, concatinating variable data to represent both string and numeric values. 

I want to work on finding a method to store both the string value and the number value in the differences array and this is somethimng I will work towards. 

DEPLOY LINK
https://xanlefee.github.io/Console-Finances/



<img src="images/M4 Challenge xeh.png" width="800" />



## Installation

Load the repo in google chrome.


## Usage 

Once loaded in google chrome, right-click inspect and open the console to view the solutions.



## Credits

Starter content provided by Edex.


## License
MIT License

Copyright (c) 2023 Xanthe E. Horner

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
