Nasa-rover
==========
@Author: John Souris
@Date: 12/05/2013

Enclosed are three programming problems.  We ask that you read all three descriptions thoroughly then create a program to solve **ONE** of the problems.
If you choose to do more than one problem, we will choose and evaluate only one of your solutions.

For the solution, you can use any programming language of your choice, but it would be ideal if it could be submitted in plain HTML and Javascript, making it easy for us to test.
You may include any Javsacript libraries you like, such as JQuery etc. Please don’t worry about design/css, this is a purely functional test.

You may also include a brief explanation of your design and assumptions along with your code.

Please email a zip of your completed solution to us within three days.  As a general rule, we allow three days from the date that you receive this email to submit your code, but you may request more time if needed.

==========

INTRODUCTION TO THE PROBLEMS

All problems below require some kind of input. Ideally, if you could provide an HTML form that accepts input through a textarea, that would be great.
You should provide sufficient evidence that your solution is complete by, as a minimum, indicating that it works correctly against the supplied test data.


PROBLEM TWO: SALES TAXES

 

Basic sales tax is applicable at a rate of 10% on all goods, except books,

food, and medical products that are exempt. Import duty is an additional

sales tax applicable on all imported goods at a rate of 5%, with no

exemptions.

 

When I purchase items I receive a receipt which lists the name of all the

items and their price (including tax), finishing with the total cost of the

items, and the total amounts of sales taxes paid. The rounding rules for

sales tax are that for a tax rate of n%, a shelf price of p contains

(np/100 rounded up to the nearest 0.05) amount of sales tax.

 

Write an application that prints out the receipt details for these shopping

baskets...

INPUT:

 

Input 1:

1 book at 12.49

1 music CD at 14.99

1 chocolate bar at 0.85

 

Input 2:

1 imported box of chocolates at 10.00

1 imported bottle of perfume at 47.50

 

Input 3:

1 imported bottle of perfume at 27.99

1 bottle of perfume at 18.99

1 packet of headache pills at 9.75

1 box of imported chocolates at 11.25

 

OUTPUT

 

Output 1:

1 book : 12.49

1 music CD: 16.49

1 chocolate bar: 0.85

Sales Taxes: 1.50

Total: 29.83

 

Output 2:

1 imported box of chocolates: 10.50

1 imported bottle of perfume: 54.63

Sales Taxes: 7.63

Total: 65.13

 

Output 3:

1 imported bottle of perfume: 32.19

1 bottle of perfume: 20.89

1 packet of headache pills: 9.75

1 imported box of chocolates: 11.85

Sales Taxes: 6.70

Total: 74.68

==========