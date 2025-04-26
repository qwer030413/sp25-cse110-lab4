# Part 2. A Little More of a Challenge...

1. line 12 will print out 3 since the for loop is running 3 times because the price array that was passed as params have an length of 3. Since we declared i as a var, we will print out 3, which was the final and last value that we had for var i

2. line 13 will print out 150 since the discountedPrice is a var and the last recording value for it would be 150. This is because the last element in prices is 300 and we      multiply that by 0.5, getting us 150

3. line 14 will also print out 150 since the last final price recorded is 150

4.  discounted would return [50, 100, 150], which is the half prices of the prices array since we are giving a 50% discount

5. line 12 will give an error because we used let to define i and it is not defined in the same scope as line 12

6. this will also give an error since we are using let instead of var

7. this will stil return 150 since final is declared in the same scope as line 14

8. this should also return [50, 100, 300] since it is the half the price of the original array [100, 200, 300]

9. this should give us an error since we are trying to change our const variables for discountedPrice. we will get an error before we can print i. We will also get an error since i is defined as let

10. length should print 3 since we are not changing the length variable after the initial definition. however, due to us trying to change discountedPrice, we will get an error before we prints line 12

11. again, this will not return anything and give an error since we are trying to change the discounted price variable when it is a const

## Data Types

12. notations:
* a: student.name
* b: student["Grad Year"]
* c: student.greeting()
* d: student["Favorite Teacher"].name
* e: student.courseLoad[0]
  
13. Arithmetic
* A: '32'
* B: 1
* C: 3
* D: '3null'
* E: 4
* F: 0
* G: '3undefied'
* H: NaN

14. comparison
* A: true
* B: false
* C: true
* D: false
* E: false
* F: true

15. difference between == and === is that == only compares the content when === also compares the content and the type. this matters in JavaScirpt because JS doesnt care that much about types as shown in 13, 14

16. for loop:(in js file)

17. 

