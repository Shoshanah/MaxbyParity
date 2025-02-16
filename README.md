Given a string including digits and letters, output the maximal possible number by only switching even numbers with even numbers and odd numbers with odd numbers. 
Where letters or even punctuation appear in the given string, those non-numerical characters are removed. 
Their indexes are replaced by the nearest digit to the right.
If input string has non-numeric characters, the output string will have a length less than the input string. 
An example of input to output without letters or punctuation would be 1234 resulting in 3412. 
Another example would be 6178d43 resulting in 876143.
Removing characters that are not numbers is included, so input can have characters beside numbers, and still work effectively. 
