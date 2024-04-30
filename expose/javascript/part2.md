1. This will log the value of i after the loop, which will be prices.length. In this case, the code outputs 3.
2. On line 12, `console.log(discountedPrice);` logs the value of discountedPrice to the console. The last value assigned to discountedPrice is from the last iteration of the for loop, when `i = 2` and `prices[i] = 300`. The discounted price is `300 * (1 - 0.5)`, which equals 150. Therefore, 150 is logged to the console.
3. After the for loop, the code logs the value of finalPrice to the console. Since finalPrice was last assigned the value 150, that's what gets logged.
4. When you call `discountPrices([100, 200, 300], 0.5)`, it returns `[50, 100, 150]` because each price in the array `[100, 200, 300]` is reduced by 50%.
5. This code causes an error because 'i' is block-scoped due to the 'let' keyword.
6. This code causes an error because 'discountedPrice' is block-scoped due to the 'let' keyword.
7. This code logs the last computed value of finalPrice, which in this case is 150.
8. The function discountPrices iterates over the array of prices, applies a 50% discount to each price, and stores the discounted prices in a new array, which it then returns. Hence, it returns [50, 100, 150].
9. This line throws an error because it tries to log the variable i which is not accessible outside the for loop, as variables declared with let have block scope, so i only exists within the for loop.
10. This line prints 3, which is the length of the input array in this case, and does not throw an error since `length` is scoped to the entire function.
11. The function discountPrices iterates over the array of prices, applies a 50% discount to each price, and stores the discounted prices in a new array, which it then returns. Hence, it returns [50, 100, 150].
12. 
A: student.name
B: student['Grad Year']
C: student.greeting()
D: student['Favorite Teacher'].name
E: student.courseLoad[0].

13. 
A: The output is `'32'` since the number `2` is concetenated to the string `'3'`
B: The output is the number `1` since the string `'3'` is converted to a number, and `2` is subtracted.
C: The output is `3` since `null` is treated as a `0` when addition occurs.
D: The output is `'3null'` since `null` is converted to a string and concatenated to `'3'`.
E: The output is `4` since `true` is treated as a `1` when addition occurs with `3`.
F: The output is `0` since `false` and `null` are both treated as `0` in arithmetic operations.
G: The output is `'3undefined'` as `undefined` is treated as a string and is concatenated to `'3'`.
H: The output is `NaN` since `undefined` is treated as `NaN` in arithmetic operations such as subtraction.    

14.
A: The output is `true` as the string `'2'` is converted to the number `2`, which is greater than `1`.
B: The output is `false` as lexicographical (dictionary) order is used because both operands are strings. In this order, `'2'` is considered greater than the `'1'` starting `'12'`, hence `'2' < '12'` is false.
C: The output is `true` since JavaScript performs type coercion, converting the string `'2'` to the number `2` before comparing.
D: The output is `false` since strict equality (`===`) checks both value and type without conversion, so a number compared with a string results in false.
E: The output is `false` since true is converted to 1, and since 1 is not equal to 2, the result is false.
F: The output is `true` because Boolean(2) is true, and they are of the same type, which is needed for the strict equality operator.

15. The `==` operator checks for equality after performing any necessary type conversions. The `===` operator checks for equality without performing type conversions, and it requires both values to be of the same type.
16. [part2-question16.js](./part2-question16.js)
17. When the function `modifyArray([1, 2, 3], doSomething)` is called, it processes each element of the array by doubling its value through the `doSomething` callback. This results in a new array `[2, 4, 6]`, showing an example of how functions can be used as arguments to manipulate array data in JavaScript.
18. [part2-question18.js](./part2-question18.js)
19. The output of the code is: `1 4 3 2`.