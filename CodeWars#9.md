## CodeWars #9 Reverse words [6 kyu]  :white_check_mark:

#### Check out this [kata](https://www.codewars.com/kata/reverse-words/javascript)

### Description:  

Write a reverseWords function that accepts a string a parameter, and reverses each word in the string. Every space should stay, so you cannot use words from Prelude.

### Example:

        reverseWords("This is an example!"); // returns  "sihT si na !elpmaxe"
        reverse_words("This is an example!") # returns  "sihT si na !elpmaxe"
        reverseWords "An example!"    -- "nA !elpmaxe"
        reverseWords "double  spaces" -- "elbuod  secaps" 


## My Solution:

        function reverseWords(str){
        return str.split("").reverse().join("").split(" ").reverse().join(" ");
        }
