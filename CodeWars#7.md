## CodeWars #7 Remove anchor from URL [5 kyu]  :white_check_mark:

#### Check out this [kata](https://www.codewars.com/kata/where-my-anagrams-at/javascript)

### Description:  
What is an anagram? Well, two words are anagrams of each other if they both contain the same letters. For example:  
    'abba' & 'baab' == true  
    'abba' & 'bbaa' == true  
    'abba' & 'abbba' == false  

Write a function that will find all the anagrams of a word from a list. You will be given two inputs a word and an array with words. You should return an array of all the anagrams or an empty array if there are none.


### Example:

    anagrams('abba', ['aabb', 'abcd', 'bbaa', 'dada']) => ['aabb', 'bbaa']  

    anagrams('racer', ['crazer', 'carer', 'racar', 'caers', 'racer']) => ['carer', 'racer']  

    anagrams('laser', ['lazing', 'lazy',  'lacer']) => []    


## My Solution:

    function anagrams(word, words) {  
      return words.filter(function(item){  
        return item.split("").sort().join("") === word.split("").sort().join("");  
    });}

