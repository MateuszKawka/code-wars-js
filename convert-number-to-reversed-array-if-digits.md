## CodeWars #15 Convert number to reversed array of digits![8 kyu](/img/kyu8.png)
![code wars badge](https://www.codewars.com/users/MateuszKawka/badges/small)
#### Check out this [kata](https://www.codewars.com/kata/convert-number-to-reversed-array-of-digits/javascript)

### Description:

Convert number to reversed array of digits

Given a random number:

C#: long;
C++: unsigned long;
You have to return the digits of this number within an array in reverse order.


### Example:

*348597 => [7,9,5,8,4,3]*

## My Solution:

    let digitize = (n) => n.toString().split("").reverse().map((v) => parseInt(v));
