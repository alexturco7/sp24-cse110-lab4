1. It will print "4". The value of i will be printed as it is a var and can be used anywhere in the function. The value of i will be 1 greater than the length of the prices array.
2. It will print "150". The value of the last discountedPrice calculated will be printed as it is var and can be used anywhere in the function.
3. It will print "150". The value of the last finalPrice calculated will be printed as it is var and can be used anywhere in the function.
4. The function will return [50, 100, 150]. The function takes the original array, and calculates the disounted prices based off the discount, and returns the discounted prices.

5. There will be an error. i uses let which means it can't be used outside the for loop.
6. There will be an error. discountedPrice uses let which means it can't be used outside the for loop.
7. It will print "150". The value of the last finalPrice calculated will be printed as it is let, but is declared before the for loop and therefore can be used anywhere in the function (after its declaration).
8. The function will return [50, 100, 150]. The function takes the original array, and calculates the disounted prices based off the discount, and returns the discounted prices.

9. There will be an error. i uses let which means it can't be used outside the for loop.
10. It will print 3. Length is declared as a const outside of the loop, which means it can be used anywhere after its declaration. The length of the array is printed.
11. The function will return [50, 100, 150]. The function takes the original array, and calculates the disounted prices based off the discount, and returns the discounted prices. The array is declared as const, which means you cannot assign it with new data. However, you can use push to manipulate the data, meaning the function will still work.

12. \
  a. student.name \
  b. student['Grad Year'] \
  c. student.greeting() \
  d. student['Favorite Teacher'].name \
  e. student.courseLoad[0] 

13. Arithmetic \
  a. '3' + 2 = '32', because number (2) are mapped to strings. \
  b. '3' - 2 = 1, because subtraction can't be done on strings, so strings are mapped to numbers. \
  c. 3 + null = 3, because null is mapped to number value (0). \
  d. '3' + null = '3null', because null is mapped to string value ('null'). \
  e. true + 3 = 4, because true is mapped to number value (1). \
  f. false + null = 0, because both false and null are mapped to number value (0). \
  g. '3' + undefined = '3undefined', because undefined is mapped to string value 'undefined'. \
  h. '3' - undefined = NaN, because undefined can't be apped to a string value. 

14. Comparison \
  a. '2' > 1 = true, because string value is mapped to a number (2). \
  b. '2' < '12' = false, because the strings lexicographical values are compared, and 2 has a less value than the first part of '12' (1). \
  c. 2 == '2' = true, because the string is mapped to a number (2). \
  d. 2 === '2' = false, because === is strict equality, types are not changed. \
  e. true == 2 = false, because true is mapped to number value (1). \
  f. true === Boolean(2) = true, because Boolean(2) returns true as it gets a nonzero number. 
15. === is strict equality comparison, while == is losse equality comparison with the chance of type coercion. 

16. Code

17. This returns [2, 4, 6]. modifyArray takes in an array and a function that is used to modify that array. The code calls doSomething on each element of the array [1, 2, 3]. doSomething then multiplies each element by 2, and modify array updates each element to reflect that.

18. code

19. here




  
