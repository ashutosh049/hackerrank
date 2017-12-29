Buying Show Tickets


There are n people standing in line to buy show tickets. Due to High Demand, The Venue sells tickets according to the following rules: 
1. The person at the head of the line can by exactly one ticket and must exit the line 
2. If a person needs to purchase additional tickets, they must re-enter the end of the line in wait to be sold the next ticket (assume exit and re-entry takes 0 seconds) 
3. Each ticket sale takes exactly one second. 

We express the initial line of n people as an array, tickets = [ticket(0),ticket(1),...,ticket(n-1)] where each tickers, denotes the number of tickets that person [i] wishes to buy. 

If Jesse is standing at a position p in this line, find out how much time it would take for him to buy all tickets. Complete the waiting time function. 

It has two parameters:

An array, tickets, of n positive integers describing initial sequence of people standing in line. Each ticket [i] describes number of
tickets that a person waiting at initial place.

An integer p, denoting Jesse's position in tickets.

Sample Input 5 2 6 3 4 5 2 Sample Output 12
Sample Input 4 5 5 2 3 3 Sample Output 11

For example, if tickets = [1, 2, 5] and p=1 the first five secods of ticket look like this:

[image missing]
