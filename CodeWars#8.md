## CodeWars #8 Kebabize [6 kyu]  :white_check_mark:

#### Check out this [kata](https://www.codewars.com/kata/kebabize/javascript)

### Description:  
Modify the kebabize function so that it converts a camel case string into a kebab case.

The returned string should only contain lowercase letters
### Example:

    kebabize('camelsHaveThreeHumps') // camels-have-three-humps  
    kebabize('camelsHave3Humps') // camels-have-humps 


## My Solution:

    function kebabize(str) {  
    return str.replace(/[0-9]/g, '').split(/(?=[A-Z])/).join('-').toLowerCase()  
}

