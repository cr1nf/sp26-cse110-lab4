1. At line 12, it will print the length of prizes, which would be 3, because var is initialized in the beginning and it ignores code blocks, so it can be accessed anywhere, even if its a part of a block.
2. At line 13, it will print the discounted price for the last price in the list, which would be 150, because var is initialized in the beginning and it ignores code blocks, so it can be accessed anywhere, even if its a part of a block.
3. At line 14, it will print the the final price accounted for rounding, whihc would be 150, because var is initialized in the beginning and it ignores code blocks, so it can be accessed anywhere, even if its a part ofo a block.
4. The function would return the list of all the discounted prices (`[50, 100, 150]`). This is following the actual function itself, since the variable is in the same block.
5. The code will cause an error because the `i` variable is not in the same block as the call.
6. The code will cause an error because the `discountedPrice` variable is not in the same block as the call.
7. The code will cause an error because the `finalPrice` variable is not in the same block as the call.
8. The function would return the list of all the discounted prices (`[50, 100, 150]`). This is following the actual function, where it loops through the prices and creates a new list of discounted prices.
9. The code will cause an error because the `i` variable is not in the same block as the call.
10. At line 12, it will return the length of the variable price, which would return `3` since the constant variable is in the same block as the call to the variable.
11. The function would return `[50, 100, 150]` because a constant variable is mutatable and would still be able to push item inside of it.
12. List:
    1.  `student.name`
    2.  `student["Grad Year"]`
    3.  `student.greeting()`
    4.  `student["Favorite Teacher"]["name"]`
    5.  `student.courseload[0]`
13. List:
    1.  `'32'` because using the `+` symbol with a string indicates string concatentation
    2.  `1` because using the `-` symbol indicates numerical subtraction
    3.  `3` because `null` gets converted to a `0` and its just `3-0`
    4.  `'3null'` because `null` gets converted to `'null'` and you concatenate `'3'` and `'null'` together
    5.  `4` because `true` converted to `1` and it gets added to `3`
    6.  `0` because `false` and `null` both get converted to 0 and get added together
    7.  `'3undefined'` because `undefined` gets converted to `'undefined'` and gets concatenated with `3`
    8.  `NaN` because `'3'` gets converted to a `3` and `undefined` gets converted to `NaN` because `undefined` is not a number. When they get numerically subtracted, `NaN` is the result
14. List: 
    1.  `true` because the string gest converted to an int first then gets compared to 1
    2.  `false` because you are comparing 2 strings and `2` comes after `1`, so `2` would be greater
    3.  `true` because the double equals means that the string gets converted then it checks equality
    4.  `false` because the triple equals means that it checks equality without converting.
    5.  `false` because `true` gets converted to `1`, which does not equal `2`.
    6.  `true` because `boolean(2)` gets converted to true and the triple equals compares `true` and `true`
15. The difference between the `==` operator and the `===` operator is that the triple equals accounts for different types, while double equals doesn't
16. [Check It Out Here](part2-question16.js)
17. The result of the function would be `[2, 4, 6]` because for each number in the old array, you are inputting that number into the `callback` function and modifying it before pushing it into the new array.
18. [Check It Out Here](part2-question18.js)
19. The outupt of the code was `1` the `4` then `3` then `2`