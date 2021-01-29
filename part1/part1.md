1. The console will log prices.length (because i has no block scope and was in the for loop; its final value will be prices.length)
2. The console will log the value (prices[prices.length - 1] * (1 - discount)). This is because that was the last value to which discountedPrice was set, and the variable is function scope.
3. The console will log the value (Math.round((prices[prices.length - 1] * (1 - discount)) * 100) / 100). This is because that was the last value of finalPrice, which is function scope.
4. [50, 100, 150]. Each value will be multiplied by (1-0.5) and then multiplied and divided by 100.
5. There will be an error because the variable i only exists in the scope of the for loop.
6. There will be an error because discountedPrice only exists in the scope of the for loop.
7. The console will log finalPrice (same as above) because finalPrice was declared outside the for loop and thus has function scope.
8. [50, 100, 150]. The scope of the variables does not affect function performance.
9. There will be an error because the variable i only exists in the scope of the for loop.
10. There will be an error because discountedPrice only exists in the scope of the for loop
11. The console will log 0 because finalPrice cannot deviate from the initialization (0).
12. []. The variable discounted cannot be updated (will encounter errors)
13. 
    1.  student.name
    2.  student["Grad Year"]
    3.  student.greeting();
    4.  student["Favorite Teacher"].name
    5.  student.courseLoad[0]
14. 
    1. '32'
       1. Because '3' is a string, it was considered a concatenation operation
    2.  1
        1. '3' was converted to an integer to support subtraction
    3.  3
        1.  null was interpreted as a 0/empty value to support addition
    4.  '3null'
        1.  Because '3' is a string, null was also considered a string to support concatenation
    5.  4
        1.  "true" was interpreted as 1 to support addition
    6.  0
        1.  false and null were both interpreted as 0 values to support addition
    7.  '3undefined'
        1.  Because "3" is a string, undefined was also considered a string to support concatenation
    8.  NaN
        1.  Unsupported operation (cannot subtract undefined from a string value)
15. 
    1.  true
        1.  '2' is converted to a number
    2.  false
        1.  '2' > '1', so '2' > '12'
    3.  true
        1.  '2' is converted to a number
    4.  false
        1.  Different types, so automatically unequal
    5.  false
        1.  true = 1, 1 != 2
    6.  true
        1.  Boolean(2) = true, so both are true Booleans
16. === is a strict equality operator and checks equality without type conversions. == supports conversions.
17. 2==true is false, but Boolean(2) is true, so the console will print 'How are you?'.
18. Separate file
19. [6, 8, 10]
    1.  For every element in the array, array[i] += 2 (because of doSomething) and then array[i] *= 2 (because of the second callback).
20. Separate file
21. 1 4 3 2