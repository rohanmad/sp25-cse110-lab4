1. Line 12 will print '3', since the last value of 'i' before the loop condition fails is 3. 
2. Line 13 will print '150', since the last value of 'discountedPrice' before the loop finishes is 150. 
3. Line 14 will print '150', since the last value of 'finalPrice' before the loop finishes is 150. 
4. The function 'discountPrices' will return an array of the 'finalPrices'. In our case, the function will return '[50, 100, 150]'
5. Line 12 will result in an error. 'let' is block-scope, meaning 'i' is only defined in the for-loop block, and is inaccessible outside of it. Therefore, trying to print the value of 'i' will result in an error. 
6. Line 13 will also result in an error. 'let' is block-scope, meaning 'discountedPrice' is only accesible inside the for-loop block, and is inaccessible outside of it. Therefore, trying to print the value of 'discountedPrice' will result in an error. 
7. Line 14 will print '150', since the last value of 'finalPrice' before the loop finishes is 150. Accessing 'finalPrice' does not result in an error because it is defined as 'let' at the top of the function, meaning it is accessible throughout the entire function. 
8. The function 'discountPrices' will return an array of the 'finalPrices'. In our case, the function will return '[50, 100, 150]'
9. Line 11 will result in an error. Since 'i' is declared as 'let', it only has access inside the block it is declared in. In our case, since we are trying to access the 'let' variable outside the for-loop it was declared in, it will result in an error. 
10. Line 12 will print '3', as that is the length of the 'prices' array.
11. The function 'discountPrices' will return an array of the 'discountedPrice'. In our case, the function will return '[50, 100, 150]'
12. A. student["name"];
    B. student["Grad Year"];
    C. student.greeting();
    D. student["Favorite Teacher"]["name"];
    E. student["courseLoad"][0];
13. Arithmetic
    A. '3' + 2 will output '32' since integers map to their exact string representation.
    B. '3' - 2 will output '1' because the string is mapped to the integer representation.
    C. 3 + null will output '3' because null gets converted to 0 automatically. 
    D. '3' + null will output '3null' because null gets converted directly into a string. 
    E. true + 3 will output '4' since true evaluates to 1. 
    F. false + null will output '0' since false evaluates to 0 and null also evaluates to 0.
    G. '3' + undefined will output '3undefined' since undefined gets converted directly into a string. 
    H. '3' - undefined will output 'NaN' because '3' gets converted into an integer, while undefined gets converted to NaN(not a number) and 3 - NaN will always result in 'NaN'
14. Comparison
    A. '2' > 1 will evaluate to true, as '2' gets converted to an integer, and 2 is greater than 1. 
    B. '2' < '12' will evaluate to false, as both strings are being compared to eachother, and '2' comes after '1' in unicode, meaning it is greater than '1', which is why it will evaluate to false. 
    C. 2 == '2' will evaluate to true, as '2' gets converted into an integer, and 2 is equal to 2. 
    D. 2 === '2' will evaluate to false, as === checks equivalency without performing type conversion. Since 2 and '2' are different types, when comparing them, they are not equivalent, resulting in a value of false.  
    E. true == 2 will evaluate to false, as true gets converted into an integer of 1, and when comparing if 1 is equal to 2, it will evaluate to false.
    F. true === Boolean(2) will evaluate to true, as Boolean() converts any nonzero number into the Boolean value of true. Since we are comparing if true is equal to true, the comparison will evaluate to true. 
15. The == and === are very similar except for one small thing. == checks for equivalency and will perform type conversion, while === checks for equivalency without performing any forms of type conversion. 
16. Answered in part2-question16.js
17. When the function is called with the parameters modifyArray([1,2,3], doSomething), it will double each value in the original array. In the modifyArray function, it loops through every value in the array, then uses the callback function to modify the value of the number in the array, and then pushes into the new array which will be returned. In our case, the callback function returns the original value multiplied by 2, and when run on the entire array, will return the whole array multipled by 2. 
18. Answered in part2-question18.js
19. The function printNums() will output '1 4 3 2'. The function will print 1 and 4 first, as those prints are not tied to a setTimeout() function. Since 3 has a timeout of 0, it will print immediately, but still after all the original prints without a timeout. Then, one second later, 2 will print, as it is tied to a timeout value of 1000, which is one second. 
20. 