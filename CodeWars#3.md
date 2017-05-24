
## CodeWars #3 Is a number prime? [6 kyu]  :white_check_mark:

#### Check out this [kata](https://www.codewars.com/kata/is-a-number-prime/)

### Description:

Define a function isPrime that takes one integer argument and returns true or false depending on if the integer is a prime.

Per Wikipedia, a prime number (or a prime) is a natural number greater than 1 that has no positive divisors other than 1 and itself.

Example

isPrime(5)
=> true
Assumptions

You can assume you will be given an integer input.
You can not assume that the integer will be only positive. You may be given negative numbers.


## My Solution:

*************************************************************************************************

    function isPrime(num) { 
    if (num < 2) return false;  
    for (var i=2; i<num; i++) {`  
    if (num % i == 0) {  
    return false;}}  
    return true;  
    }
    
 *************************************************************************************************
