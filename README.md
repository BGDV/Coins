# Coins
Coins making 

It's just an exercise!

You have N grams of silver, from which it is planned to issue coins. For a coin, a blank weighing K gram is made, after which coins of M gram each are made from each blank (the maximum possible number from each blank). 
If something remains of the blanks after that, then the material is returned to the beginning of the production cycle and fused with what was left during the manufacture of the blanks. 
Thus, the process will stop when there are less than K grams of silver left in the alloy.
  Write a program that calculates how many coins will be smelted from N grams of silver.
  Input data format
  The numbers N,K,M (1≤ N,M,K ≤200) are entered in one line separated by a space.
  Output format
  Print a single number — the number of coins produced.
  Comment
  In the first test, the process looks like this: from 10 grams of silver, a 5 gram blank is made, from which you will make 2 coins of 2 gram each. The remaining silver will return to the alloy, leaving 6 grams. By repeating the process, we will get 2 more coins, and 2 grams will remain in the alloy, which is no longer enough for the workpiece. Thus, we will get 4 coins.
  

  Data examples:
  
  Example 1:
  Input 10 5 2
  Output 4
  
  Example 2:
  Input 13 5 3
  Output 3
  
  Example 3:
  Input 14 5 3
  Output 4
  
  Example 4:
  Input 13 9 4
  Output 2
