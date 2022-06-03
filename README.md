# Scavenger Hunt

Every item below refers to a specific function built into the JavaScript language. For each item, find:

1. The relevant page and section on MDN's [official JavaScript documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
1. At least one online resource (tutorial, etc.) **other than** Stack Overflow, w3cshools, or geekforgeeks explaining the function

## Scavenger Items

1. Given two numbers, tell me how to get the remainder after dividing the former by the latter.

   I give you `10` and `3`, you give me `1`.
1. Given two arrays, tell me how get a new array that consists of all the elements in the first array followed by all the elements in the second array.

   I give you `[10, 20, 40]` and `['one', 'two', 'three']`, you give me `[10, 20, 40, 'one', 'two', 'three']`.
1. Given two strings, tell me whether the second string appears anywhere in the first string.

   I give you `'one two three'` and `'two'`, you give me `true`.
1. Given a string and a target length, tell me how to pad the end with a specific character (up to the target length).

   I give you `'yes'` and `6` and tell you to pad with `'-'`, you give me `yes---`.
1. Given an array and some condition, tell me how to get a new array consisting of all the elements from the original array that match the condition.

   I give you `[12, 5, 8, 130, 44]` and the condition that a number must be `>= 10`, you give me `[12, 130, 44]`.
1. Tell me how to get the current year.
1. Given two strings (call them `haystack` and `needle`), tell me how to find the first index at which `needle` is found in `haystack`.
1. Given a string, tell me how to get the number of characters it contains.
1. Given a number, tell me how to get the largest integer less than or equal to that number.

   I give you `35.2` (or `35` or `35.9`), you give me `35`.
1. Given an array of numbers, tell me how to sort that array from smallest to largest.

   I give you `[4, 19, 5, 1, 3]`, you give me `[1, 3, 4, 5, 19]`.
1. Given a string, tell me how to get a copy of that string with all leading whitespace removed.

   I give you `'   hello   '`, you give me `'hello   '`.
1. Given an array, tell me how to get the number of elements in the array.

   I give you `['one', 17, 'pie', 'orange juice']`, you give me `4`.
1. Given an array, tell me how to remove the last element from the array and save its value in a variable.

   I give you `[5, 6, 22, -19]'` and you remove `-19`, saving its value in a variable.
1. Given a dictionary (object), tell me how to get an array of all its keys.

   I give you `{ name: 'Jesse', age: 36 }`, you give me `['name', 'age']`.

1. Given two strings, tell me whether the second string appears at the end of the first string.

   I give you `'running'` and `'ing'`, you give me `true`.
1. Given two or more numbers, tell me how to find the largest among them.

   I give you `8`, `-20`, and `42`, you give me `42`.
1. Given a string, tell me how to get an all-uppercase copy of that string.

   I give you `'HeLLo FrIenDs'`, you give me `'HELLO FRIENDS'`.
1. Given an array and a condition, tell me whether all elements in the array meet that condition.

   I give you `[3, 7, 9, 11]` and the condition "a number is odd", you give me `true`.
1. Tell me how to get the current month.
1. Given a string `str`, tell me how to find and replace every instance of some other string in `str`.

   I give you `'one two one three`' and ask you to replace `'one'` with `'potato'`, you give me back `'potato two potato three'`.
1. Tell me how to get a random decimal number between `0` and `1`.
1. Given an array and a value, tell me how to append that value to the array.

   I give you `[19, -42, 56.4]` and `'potato'`, you give me `['potato', 19, -42, 56.4]`.
1. Given a string, tell me how to get the character at a specific location (index) in the string.
1. Given a string containing the characters of an integer, tell me how to get an integer.

   I give you `'1657'`, you give me `1657`.
1. Given two or more numbers, tell me how to find the smallest among them.

   I give you `8`, `-20`, and `42`, you give me `-20`.
1. Given a string, tell me how to get a copy of that string with all trailing whitespace removed.

   I give you `'   hello   '`, you give me `'   hello'`.
1. Given an array and some condition, tell me how to get the first element that matches the condition.

   I give you `[5, 12, 8, 130, 44]` and the condition that a number must be `>= 10`, you give me `12`.
1. Given a string, tell me how to get a copy of that string with all leading and trailing whitespace removed.

   I give you `'   hello   '`, you give me `'hello'`.
1. Given an array and a value, tell me how to get the first index at which that value is found.

   I give you `['woof', 17, -45, 'woof', 'oranges', 'hawk']` and the value `'hawk'`, you give me `4` (the index of `'hawk'`).
1. Given two strings, tell me whether the second string appears at the start of the first string.

   I give you `'alphabet'` and `'alpha'`, you give me `true`.
1. Given a variable, tell me how to get that variable's type (number, string, etc.).

   I give you `5`, you give me `'number'`.

   I give you `'hello'`, you give me `'string'`.

   I give you `true`, you give me `'boolean'`.
1. Given an array and some condition, tell me how to get the index of the first element that matches the condition.

   I give you `'['one', 'three', 'waffles', 'beep']` and the condition that the length of the element is `> 4`, you give me `2` (the index of `'waffles'`).
1. Given a string `str` and a number `num`, tell me how to create a new string that consists of `num` copies of `str` glued together.

   I give you `'bark'` and `3`, you give me `'barkbarkbark'`.
1. Given a string and a separator string, tell me how to get an array of all the parts of the string between occurrences of the separator.

   I give you `'pie|potato|waffle'` and `'|'`, you give me `['pie', 'potato', 'waffle']`.
1. Given an object, tell me how to get an array of all its values.

   I give you `{ name: 'Jesse', age: 36 }`, you give me `['Jesse', 36]`.
1. Given an array and a value, tell me how to append that value to the array.

   I give you `[19, -42, 56.4]` and `'potato'`, you give me `[19, -42, 56.4, 'potato']`.
1. Given a string and an index, tell me how to get the string consisting of all the characters starting at that index.

   I give you `'arglebargle'` and `5`, you give me `'bargle'`.
1. Tell me how to get the number of milliseconds since 12AM UTC, January 1st, 1970 (called [Unix time](https://en.wikipedia.org/wiki/Unix_time)).
1. Given an object and a string, tell me whether that string occurs as a key in the object.

   I give you `{ name: 'Jesse', age: 36 }` and `'age'`, you give me `true`.

   I give you `'potato'`, you give me `false`.
1. Given a string, tell me how to get an all-lowercase copy of that string.

   I give you `'HeLLo FrIenDs'`, you give me `'hello friends'`.
1. Given a number, tell me how to get a string containing that numbers.

   I give you `1675`, you give me `'1657'`.
1. Given an array, tell me how to get a reversed copy of that array.

   I give you `['one', 'two', 'three']`, you give me a new array that looks like `['three', 'two', 'one']`.
1. Given a number, tell me how to get the smallest integer greater than or equal to that number.

   I give you `8.2` (or `8` or `8.9`), you give me `9`.
1. Given a string `str`, tell me how to find and replace the first instance of some other string in `str`.

   I give you `'one two one three`' and ask you to replace `'one'` with `'potato'`, you give me back `'potato two one three'`.
1. Given a string and a target length, tell me how to pad the start with a specific character (up to the target length).

   I give you `'yes'` and `6` and tell you to pad with `'-'`, you give me `---yes`.
1. Given string representing your birthday, tell me how to get the day of the week it fell on.

   I give you `'June 23, 1986'`, you give me a value that represents Monday.
1. Given an array, tell me how to remove the first element from the array and save its value in a variable.

   I give you `[5, 6, 22, -19]'` and you remove `5`, saving its value in a variable.
1. Given an array and a condition, tell me whether there are any elements in the array that meet that condition.

   I give you `[3, 2, 9, 11]` and the condition "a number is even", you give me `true`.
1. Given two strings, tell me the first location (index) at which the second string appears in the first.

   I give you `'one two one two'` and `'two'`, you give me `4`.
1. Given an array and a value, tell me how to check whether the array contains that value (as an element).

   I give you `['woof', 17, -45, 'oranges', 'hawk']` and the value `'hawk'`, you give me `true`.
1. Given an array and an index, tell me how to get a new array consisting of all elements from the original array starting at that index.

   I give you `['one', 'two', 'three', 'four']` and `2`, you give me `['three', 'four']`.
1. Given two strings, tell me the last location (index) at which the second string appears in the first.

   I give you `'one two one two'` and `'two'`, you give me `12`.
