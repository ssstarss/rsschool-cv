# Sergey Starchenko

## Contacts
* \+7 (913)234-4444
* s.s.star@mail.ru
***
## About me

A long time ago in a galaxy far away I studied to be a programmer, then  worked in other directions. 
Now I feel an irresistible craving and the opportunity to return to the roots.
Basic skills. - I understand the basic terminology, data types, arrays, loops, conditions...
***
## Code Example:

**DESCRIPTION:**

**ROT13** is a simple letter substitution cipher that replaces a letter with the letter 13 letters after it in the alphabet.
**ROT13** is an example of the Caesar cipher. Create a function that takes a string and returns the string ciphered with **Rot13**.
If there are numbers or special characters included in the string, they should be returned as they are. 
Only letters from the latin/english alphabet should be shifted, like in the original Rot13 "implementation".
***
```
function rot13(message){
  var regExp=/[A-Za-z]/ig;
  return message.replace(regExp,function(match){
    if (match.charCodeAt(0)<78) 
        return String.fromCharCode(match.charCodeAt(0)+13);
    if (match.charCodeAt(0)<=90) 
        return String.fromCharCode(match.charCodeAt(0)-13);
    if (match.charCodeAt(0)<110) 
        return String.fromCharCode(match.charCodeAt(0)+13);
    return String.fromCharCode(match.charCodeAt(0)-13);
 
  }); 
}
```
***
## Education

Applied Mathematics
***
## Skills:

* JS Basic
* HTML, CSS Basic
***
## Languages:

* Russian : Native
* English : Intermediate
 ***
