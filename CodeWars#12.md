## CodeWars #12 Time-like string format![5 kyu](/img/kyu5.png)
![code wars badge](https://www.codewars.com/users/MateuszKawka/badges/small)
#### Check out this [kata](https://www.codewars.com/kata/51e000d070fe4414000003f0)

### Description:

Build up a method that takes an integer and formats it to a 'time - like' format. The method must raise an exception if its hour length is less than 3 digits and greater than 4.

### Example:

*solution(800); // should return '8:00'*  
*solution(1000); // should return '10:00'*  
*solution(1451); // should return '14:51'*  
*solution(3351); // should return '33:51'*  
*solution(10000); // should raise an exception*  

## My Solution:

    function solution(hour) {  
    var input = hour.toString();  
    if(input.length === 3 | input.length === 4)   
    return input.split(/^(\d{1,2})(\d\d$)/).filter(Boolean).join(":");  
    else throw input;  
    }
