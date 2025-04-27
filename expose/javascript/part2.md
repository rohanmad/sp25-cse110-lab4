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
