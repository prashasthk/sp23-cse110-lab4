1. The number 3 will be logged in the console because after the for loop, `i` will have been incremented to 3 and we will log it to the console without errors because `i` has function scope.
2. 150 will be logged to the console because on the last iteration of the for loop, `discountedPrices` will get updated to 150 and because it has function scope, it will be logged without errors.
3. 150 will be logged to the console because on the last iteration of the for loop, `finalPrice` will get updated to Math.round(150 * 100) / 100 = 150 and because it has function scope, it will be logged with no errors. 
4. The function will return [50, 100, 150] because `discounted` has function scope and after the for loop, it holds all the final prices calculated. 
5. Error because `i` only has block scope in the for loop, so we can not log it outside of the for loop.
6. Error because `discountedPrice` only has block scope in the for loop, so we can not ever log it outside of the for loop.
7. 150 will be logged to the console because `finalPrice` has block scope across the function body, so on the last iteration of the for loop, `finalPrice` will get updated to 150 and then logged on line 14.
8. The function will return [50, 100, 150] because `discounted` has block scope across the function body so the final prices will get pushed to the list and the function will return the variable without errors.
9. Error because `i` only has block scope in the for loop, so we can not log it outside of the for loop.
10. 3 will be logged to the console because `length` has block scope in the function body and is never reassigned, so it will be logged on line 12 without errors.
11. The function will return [50, 100, 150] because although we are pushing values to `discounted`, we are never reassigning it and because it has block scope across the function body, it will return the list of discounted prices without any error. There are no other violations of const reassigning that would throw an error.
12. A, B, C, D, E answers below
    1.  student.name
    2.  student['Grad Year']
    3.  student.greeting()
    4.  student['Favorite Teacher'].name
    5.  student.courseLoad[0]
13. A, B, C, D, E, F, G, H answers below
    1. '32' because 2 maps to '2'
    2. 1 because '3' maps to 3 then subtract by 2
    3. 3 because null maps to 0
    4. '3null' because null maps to 'null' and is concatenated
    5. 4 because true maps to 1
    6. 0 because false maps to 0 and null maps to 0
    7. '3undefined' because undefined maps to 'undefined'
    8. NaN because undefined maps to NaN and can not subtract from '3'
14. A, B, C, D, E, F answers below
     1. true because '2' maps to 2
     2. false because '2' is lexicographically larger than '12'
     3. true because '2' maps to 2
     4. false because 2 and '2' are of different types
     5. false because true maps to 1
     6. true because Boolean(2) maps to true and both inputs are of same type
15. == checks equality with type conversion while === checks equality without type conversion 
16. See part2-question16.js
17.  The function will return [2, 4, 6] since we pass the callback function doSomething into modifyArray and call doSomething for every value in the array, passing the value as a parameter. The value is then doubled, returned, and then pushed into newArr, resulting in the array [2, 4, 6].
18. See part2-question18.js
19. 1 <br>
    4 <br>
    3 <br>
    2