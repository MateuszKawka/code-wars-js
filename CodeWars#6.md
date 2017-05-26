## CodeWars #6 Remove anchor from URL [6 kyu]  :white_check_mark:

#### Check out this [kata](https://www.codewars.com/kata/remove-anchor-from-url/javascript)

### Description:

Complete the function/method so that it returns the url with anything after the anchor (#) removed.


EXAMPLE

     // returns 'www.codewars.com'   
    removeUrlAnchor('www.codewars.com#about')    

    // returns 'www.codewars.com?page=1'    
    removeUrlAnchor('www.codewars.com?page=1')   


## My Solution:

    function removeUrlAnchor(url){  
        return url.replace( /#.*/ , '' )  
    }

