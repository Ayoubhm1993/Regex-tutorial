# Email Regular Expression Tutorial 

This is a simple explanation of Regular expression "Regex" for matching an Email 

## Summary

Regex are extremely useful in extracting information from any text by searching for one or more matches of a specific search pattern , or replacing string .

Also , The Email Regex used to verify email validation.
eg : "test_25@gmail.com" 
That's means the structure of the email must follow the expression bellow that contain three principal sections eg :
              ** first section of the email : "test_25" = ' ([a-z0-9_\.-]+) '
              ** secound section : "gmail" = ' ([\da-z\.-]+) '
              ** third section :"com" = ' ([a-z\.]{2,6}) '


/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)



## Regex Components

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

As we can see this expression stands on some components 

* Anchors — ^ and $
* Quantifiers — * + ? and {}
* Character classes — \d \w \s and .
* Grouping and capturing — ()
* Bracket expressions — []


### Anchors

We used a couple of Anchors in our regular expression 

 1 - " ^ " means you can matches any string starts after this sign 
 2- " $ " means you can matches a string ends before this sign

In our case we have the anchors by the start and by the end , that's mean exact string match 

### Quantifiers

In our Email regular expression we used '+' sign 

" [a-z0-9_\.-]+ " , " [\da-z\.-]+ "

That's means you can matches a string that followed by one or more characters or letter


### Character Classes

In our Email regular expression we used ' . '

Means matching any character or letter from the grouping and capturing as our exemple

" [a-z0-9_\.-]+ " , " [\da-z\.-]+ "

### Grouping and Capturing

In our Email regular expression we used ' ([a-z0-9_\.-]+) ' , ' ([\da-z\.-]+) ' , ' ([a-z\.]{2,6}) '

Parantheses create a capturing group and so useful when need to extract information from strings or data using any preferred programming languages

### Bracket Expressions

In our Email regular expression we used ' [a-z0-9_\.-] ' , ' [\da-z\.-] ' , ' [a-z\.] '

[a-z] = matches a string that has letters lowercase from a to z .
[0-9] = matches a string that has a character from 0 to 9 .

[a-z0-9_\.] = matches a string that has lowercase letters and characters and special characters.

## Author

#### Ayoub Hammouch

##### Full Stack Developer

##### Gmail :ayoubhm1993@gmail.com

### [Github](https://github.com/Ayoubhm1993/Regex-tutorial) 