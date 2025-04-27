1. Line 9 will print 'values added: 20'
2. Line 13 will print 'final result: 20'
3. You should not use var because it is function scoped instead of block scoped. This means it can unintentionally leak outside of blocks into the entire function. It is also hoisted in a way that can cause bugs.
4. Line 9 will print 'values added: 20'
5. Line 13 will result in an error. This is because 'result' was defined wth 'let', meaning the variable only has block scope, and is inaccessible to anything outside of it. 
6. Line 9 will result in an error. This is because 'result' was defined with 'const', meaning its value cannot be modified after initialization. Since we are trying to add 'num1' and 'num2' to the 'const result', it will result in an error. 
7. Line 13 will not execute, since the code runs into an error on Line 9. Even if it did execute, it would result in an error, as 'const' is also block scope, meaning it is inaccesible at Line 13. 
