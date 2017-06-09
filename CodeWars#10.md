## CodeWars #10 Invert values ![8 kyu](/img/kyu8.png)
![code wars badge](https://www.codewars.com/users/MateuszKawka/badges/small)
#### Check out this [kata](https://www.codewars.com/kata/5899dc03bc95b1bf1b0000ad)

### Description:

Given a set of numbers, return the additive inverse of each. Each positive becomes negatives, and the negatives become positives.

Python/JS/PHP/Java:

invert([1,2,3,4,5]) == [-1,-2,-3,-4,-5]
invert([1,-2,3,-4,5]) == [-1,2,-3,4,-5]
invert([]) == []
You can assume that all values are integers (and for C/C++: that all values are greater than INT_MIN).




## My Solution:

    function invert(array) {  
    return array.map( x => x === 0 ? x : -x);  
    }
