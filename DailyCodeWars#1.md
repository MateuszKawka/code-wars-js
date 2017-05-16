## Daily CodeWars #1 Two Joggers [5 kyu]  :white_check_mark:

#### Check out this [kata](https://www.codewars.com/kata/5274d9d3ebc3030802000165)

### Description:



*Bob and Charles are meeting for their weekly jogging tour. They both start at the same spot called "Start" and they each run a different lap, which may (or may not) vary in length. Since they know each other for a long time already, they both run at the exact same speed.*


### Task:

*Your job is to complete the function nbrOfLaps(x, y) that, given the length of the laps for Bob and Charles, finds the number of laps that each jogger has to complete before they meet each other again, at the same time, at the start.*

The function takes two arguments:

- The length of Bob's lap (larger than 0)
- The length of Charles' lap (larger than 0)

The function should return an array containing exactly two numbers:

- The first number is the number of laps that Bob has to run
- The second number is the number of laps that Charles has to run*

## My Solution:

    var nbrOfLaps = function (x, y) {  
    var fatality = [], Bob = x, Charles = y;  
    while (Bob !== Charles) {  
    (Bob > Charles)? Charles += y : Bob += x;}  
    fatality.push(Bob/x);  
    fatality.push(Charles/y);  
    return fatality;  
    }
