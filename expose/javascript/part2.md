Question1: It will output an error saying"i is not defined". This is because 'i' is declared with "var" keyword and inside the for loop block.

Question2: Now the it will print each item's discoutned price in the prices array. [50,100,150],Because this time 'discountedPrice' is declared with 'var' keyword inside 'for' loop, and the for loop iterates over each item in 'price' array.

Question3: Now the it will print each item's final price in the prices array. [50.00,100.00,150.00],Because this time 'finalPrice' is declared with 'var' keyword inside 'for' loop, and the for loop iterates over each item in 'price' array.then rounds the discounted price to two decimal places using Math.round(discountedPrice * 100) / 100;, and then pushes the rounded value to the discounted array.

Question4: The code will return an array with final discounted prices, since discount array is declared at the beginning of the function and for loop iterates each item and pushed the final discoutned prices into the array. so it will print [50,100,150].

Question5: The funciton will throw "ReferenceError" saying i is not defined since 'i' is declared with 'let' keyword this time and it's inside the for loop so it's only accessible wihtin the block scope of the for loop.

Question6: It will print the discounted price of each item in the console. Since discountedPrice is a variable that is defined within the for loop, it will only exist within the scope of that loop. Therefore, it will print the discounted price for each item as the loop iterates over them, and after the loop ends, the value of discountedPrice will no longer exist.

Question7: Now the it will print each item's final price in the prices array. [50.00,100.00,150.00],Because this time 'finalPrice' is declared with 'let' keyword inside 'for' loop, and the for loop iterates over each item in 'price' array.then rounds the discounted price to two decimal places using Math.round(discountedPrice * 100) / 100;, and then pushes the rounded value to the discounted array.finalPrice is updated with the discounted price of each item in the prices array, and on the last iteration of the loop, it will hold the discounted price of the last item. 

Question8: The function will return an array of discounted prices [50.00,100.00,150.00]. This is because i is declared with let inside the for loop, so it only exists within the scope of the loop.

Question9: At line 11, the code is trying to push the value of finalPrice into the discounted array, which is initialized to 0 and never changed in the loop. Therefore, the discounted array will end up containing multiple copies of 0, since the variables are declared with 'const' so can't not the updated. Also, the variable i is declared inside the for loop with the let keyword, so it will not be accessible outside of the loop. Therefore, attempting to log i at line 13 will result in a ReferenceError because i is not defined in that scope.

Question10: It will return 3, since there are 3 elements in the price array, the length of price is the number of elements so is 3.

Question11: The function will return an empty array since 'finalPrice' is not defined so when pushing finalPrize to dsicounted, nothing will be pushed.

Question12:
A. Accessing the value of the name property in the student object: student.name

B.Accessing the value of the Grad Year property in the student object:student['Grad Year']

C. Calling the function for the greeting property in the student object: student.greeting()

D. Accessing the name property of the object in the Favorite Teacher property in student: student['Favorite Teacher'].name

E. Access index zero in the array of the courseLoad property of the student object: student.courseLoad[0]

Question13: Arithmetic
A. ‘3’ + 2: ‘3’ + 2 outputs '32'.+ operator performs string concatenation when one of the operands is a string. In this case.

B. ‘3’ - 2: ‘3’ - 2 outputs 1. Null is converted to the number 0, so the expression 3 + null evaluates to 3.

C. 3 + null: 3 + null prints '3'. The + operator performs string concatenation when one of the operands is a string. 

D. ‘3’ + null: ‘3’ + null prints '3null'. The + operator performs string concatenation when one of the operands is a string. 

E. true + 3: It will output '4', true is converted to 1 and 1+3 is 4.

F. false + null: It will output 0, false is converted to 0 and null is converted to 0 too. 

G. '3' + undefined: It will output '3undefined'. + operator performs string concatenation when one of the operands is a string. The string '3' is concatenated with the string representation of undefined, which is the string 'undefined'.

H. '3' - undefined: It will print 'NaN','-' performs substrctions and tries to convert its operands to numbers. '3' is converted from a string to number, however, 'undefined' can't be converted to number, so 'NaN'

Question 14: Comparison
A. ‘2’ > 1： outputs 'true', '2' is converted to a number 2 and it's true that 2>1.

B. ‘2’ < ‘12’: outputs true, dictionary comparison, first char "2" is greater than the first char "1".

C. 2 == ‘2’ : true, '==' will try to convert different types into same type before compaing, so after coverting them both into numbers, 2=2 is true.

D. 2 === ‘2’: outputs false. '===' won't perform type coercion, since they are different types, it will return false.

E. true == 2: ouput false, '==' will perform type coercion and convert true to a number 1, and 1 is not equal to 2, so false.

F. true === Boolean(2): outputs true. '===' will compare the types first and since Boolean(2) returns true, since any non-zero number is considered truthy in JavaScript, and is same as true, so output true.

Question15: '===' is a strict equality operator, === checks the equality without type conversion. In other words, if a and b are of different types, then a === b immediately returns false without an attempt to convert them.
However, '==' will do type coercion before comparing, even tho types of operands are different, it can still compare, it will first convert both into a same type then compare.

Question17: it will return [ 2, 4, 6 ]. So first the funciton 'modifyArray' will creat an empty array 'newArr', then it interates through by using the for loop, and pushes the result to 'newArr' and return it. Then in the 'doSomething' func, it will muliple the input array by 2, so every element in the array will be multipled by 2 and then returned, so input [1,2,3] will output as [2,4,6].

Question19: 
1
4
3
2

