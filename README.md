# Loan Management System

A loan management automated system using OOPS concept in C++ using data structures.

## My assumptions while designing this system are:-

1. The total amount is given by the user and is thus, not static.
2. The time period is given by the user and is thus, not static.
3. The principal EMI is given by the user and is thus, not static.
4. The interest EMI is given by the user and is thus, not static.
5. The start date, start month and the start year is given by the user and is thus, not static.
6. The next EMI installment is given every 30 days.
7. The calculateNETAmount() function receives 8 arguments which are the reference of the database, the total amount, the time period, the
principal EMI, the interest EMI, the start date, the start month, and the
start year.

## Input format:

```
1000
12
83.33
10
10
may/May
2020

```
## Ouput Format:

```
1. Loan creation date : 10 th April 2020
2. Principal Amount : 1,000
3. No Of EMI’s : 12
4. Total payable amount : 1,000 (Principal) + 120 (Interest for 12 months) = 1,120
5. EMI Details :
a. EMI No : 1, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10 th May 2020, Principal remaining : 1026.67
b. EMI No : 2, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10 th June 2020, Principal remaining : 933.34
c. EMI No : 3, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10 th July 2020, Principal remaining : 840.01
d. EMI No : 4, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10 th Aug 2020, Principal remaining : 746.68
e. EMI No : 5, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10 th Sept 2020, Principal remaining : 653.35
f. EMI No : 6, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10 th Oct 2020, Principal remaining : 560.02
g. EMI No : 7, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10 th Nov 2020, Principal remaining : 466.69
h. EMI No : 8, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10 th Dec 2020, Principal remaining : 373.36
i. EMI No : 9, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10 th Jan 2021, Principal remaining : 280.03
j. EMI No : 10, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10 th Feb 2021, Principal remaining : 186.70
k. EMI No : 11, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10 th March 2021, Principal remaining : 93.37
l. EMI No : 12, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10 th April 2021, Principal remaining : ~0

```
## Time Complexity:

1. The time complexity of the system is inserting the records will be O(1).
2. The time complexity for producing the output from the database will be O(n) where n is the total number of records in the database.


