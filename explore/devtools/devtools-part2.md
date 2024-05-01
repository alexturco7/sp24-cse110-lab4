1. result is becoming a string, therefore num1 and num2 are just getting concatenated instead of added.
2. I would add the function call parseInt() around the code of num1 and num2 to make sure they are ints, and therefore result will not be treated as a string.
