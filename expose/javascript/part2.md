### Part Two Answers

1. 3 will be logged because the length of prices is 3 so when the for loop terminates i equals 3 and is a var which has function scope.
2. 150 will be logged because discoutedPrice = prices[2] * (1 - 0.5) = 300 * 0.5 = 150 after the for loop terminates and is a var which has function scope.
3. 150 will be logged because after the for loop terminates because finalPrice = Math.round(150 * 100) / 100 = 150 and finalPrice is a var which has function scope.
4. The function will return [ 50, 100, 150 ] because when i = 0, finalPrice = 50, when i = 1, finalPrice = 100, and when i = 2, finalPrice = 150 and i is a var which has function scope.
5. The code will return an error because i does not exist outside of the block it is defined in since it is a let which has block scope.
6. The code will return an error because discountedPrice does not exist outside of the block it is defined in since it is a let which has block scope.
7. 150 will be logged because i = 3 when the for loop terminates and Math.round(150 * 100) / 100 = 150, and the log call is made within the block that discountedPrice is defined in and it is a let which has block scope.
8. The code will return [ 50, 100, 150 ] because because when i = 0, finalPrice = 50, when i = 1, finalPrice = 100, and when i = 2, finalPrice = 150, and the return call is made inside the block that discounted was defined in and it is a let which has block scope.
9. The code will return this error because i is not defined outside of the for loop since it is a let which has block scope.
10.  3 will be logged because the length of prices is 3 and the call is made within the block that length is defined in and length is a const which has block scope.
11.  The code will return [ 50, 100, 150 ] because because when i = 0, discountedPrice = 50, when i = 1, discountedPrice = 100, and when i = 2, discountedPrice = 150, and the return call is made inside the block that discounted was defined in and discounted is a const which has block scope.
12. 
        A. student.name
        B. student['Grad Year']
        C. student.greeting()
        D. student['Favorite Teacher'].name
        E. student.courseLoad[0]
13. 
        A. '3' + 2 = '32' since integers map to their exact string representation
        B. '3' - 2 = 1 since strings map to their exact integer representation
        C. 3 + null = 3 since null is empty, 0 as an integer
        D. '3' + null = '3null' since null maps to its exact string representation
        E. true + 3 = 4 since true maps to 1
        F. false + null = 0 since false and null both map to 0
        G. '3' + undefined = '3undefined' since undefined maps to its exact string representation
        H. '3' - undefined = NaN since undefined does not map to a number
14. 
        A. '2' > 1 = true since 2 maps to its exact integer representation
        B. '2' < '12' = false since 2 and 12 map to their exact integer representations
        C. 2 == '2' = true since 2 maps to its exact integer representation
        D. 2 === '2' = false since the 2s are different datatypes 
        E. true == 2 = false since true maps to 1
        F. true === Boolean(2) = true since the datatypes are the same 
15. The difference between the == and === operators is that == ignores the datatype of the variable while === doesn't
16. see seperate file
17. The result will be [ 2, 4, 6 ] because doSomething is called every time an element is pushed to the array and those elements are multiplied by 2.
18. see seperate file
19. 
1
4
3
2