## CodeWars #4 Create Phone Number [6 kyu]  :white_check_mark:

#### Check out this [kata](https://www.codewars.com/kata/create-phone-number/javascript)

### Description:



* Write a function that accepts an array of 10 integers (between 0 and 9), that returns a string of those numbers in the form of a phone number.

Example:

createPhoneNumber([1, 2, 3, 4, 5, 6, 7, 8, 9, 0]) // => returns "(123) 456-7890"
The returned format must be correct in order to complete this challenge. 
Don't forget the space after the closing parenthese!*

## My Solution:

  function createPhoneNumber(numbers){  
  var left = numbers.slice(0,3);    
  var middle = numbers.slice(3,6);  
  var right = numbers.slice(6,10);   
  var fatality = "(" + left.join("") + ")" + " " + middle.join("") + "-" + right.join("");  
  return fatality;  
}
