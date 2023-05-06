# CMPS 2200 Assignment 5
## Answers

**Name:**Isabelle Chow


Place all written answers from `assignment-05.md` here for easier grading.





- **1a.**
We can take as many coins of the largest denomination possible to get as few coins as possible that sum to N. Once the amount remaining is no longer divisible by a whole number (you cannot have half/decimal portion of a coin), we can drop to the next lower denomination, repeating until we have exact change or a denomination that equals 1 (2^0). 2^k (coins) <= N (dollars), recursively subtract until N = 0, no more dollars. Optimal for this situation because all cins are in denominations of 2^k. 

**1b.** The work and span for this algorithm would be O(log n) because N is being reduced by a factor of base 2 (2^0, 2^1...). 






- **2b.**

Let's say the bank in this country only has denominations of 12, 10, 6, 3, and 1 k coins and we have 16 N dollars. Greedy algorithm would go for the largest denomination first, which would be 12, then 3, then a 1. You end up with 3 coins plus one extra dollar assuming you cannot take more than one of each coin in a pass with the greedy algorithm. As this is not the smallest number of possible coin combinations, this shows that a greedy algorithm would not be optimal in this case because it takes the largest denomination without considering other optimal solutions. 
The optimal solution would be two coins, an 10 and an 6. 


- **3a.**






- **3b.**






- **3c.**



