## CodeWars #13 Regex Password Validation![5 kyu](/img/kyu5.png)
![code wars badge](https://www.codewars.com/users/MateuszKawka/badges/small)
#### Check out this [kata](https://www.codewars.com/kata/regex-password-validation/javascript)

### Description:

You need to write regex that will validate a password to make sure it meets the following criteria:

At least six characters long
contains a lowercase letter
contains an uppercase letter
contains a number
Valid passwords will only be alphanumeric characters.

## My Solution:

    let validate = (p) => /^(?=.*[A-Z])(?=.*[0-9])(?=.*[a-z])[a-zA-Z0-9]{6,}$/.test(p);
