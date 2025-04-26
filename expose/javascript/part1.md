# intro to Javascript
1. What is printed by line 9? If the code returns an error, explain why. ^^^^^
  * In line 9, we print "values added:" and then we pring the sum of the 2 values that we got from the params num1 and num2, which is 20. we are running this because we passed true for the add parameter and we are running it if add is true

2. What is printed by line 13? If the code returns an error, explain why. 
  * line 13 will also print out "final result:" and then the result which is the sum of 2 numbers, which is 20. even if result is not defined outside of the if statement, it is still accessable since it is a var

3. Why should you not use var? Explain why. 
  * We should not use var because it is declared globally and it might cause errors if the var names are the same.

4. What is printed by line 9? If the code returns an error, explain why. ^^^^^
   * same as before, it will print out 20, which is the sum of num1 and num2

5. What is printed by line 13? If the code returns an error, explain why. 
   * line 13 will have an error since we are using let to define the result. result is only defined in the if statement so the console log in line 13 will not recognize the element "result"

6. What is printed by line 9? If the code returns an error, explain why. ^^^^^
   * We will get an error since we are trying to re assign a result into the sum of the 2 nums, which is not allowed since result is a const

7. What is printed by line 13? If the code returns an error, explain why. 
   * we will still get an error since we are trying to re assign result into the sum of 2 nums in line 7.

  