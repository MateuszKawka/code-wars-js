## CodeWars #2 Friend or Foe? [7 kyu]  :white_check_mark:

#### Check out this [kata](http://www.codewars.com/kata/55b42574ff091733d900002f)

### Description:

Make a program that filters a list of strings and returns a list with only your friends name in it.

If a name has exactly 4 letters in it, you can be sure that it has to be a friend of yours!

Example: Input = ["Ryan", "Kieran", "Jason", "Yous"], Output = ["Ryan", "Yous"]



## My Solution:

    function friend(friends){  
    return friends.filter(function (item) { return item.length === 4 });  
    }
