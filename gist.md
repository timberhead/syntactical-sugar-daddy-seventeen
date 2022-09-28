



# 🐛 Regular Expression Tutorial



 A Regular Expression, or a "Regex", is a string of characters that is used to define the pattern of the subject that is being searched.  The string of characters is made up of upper and lower case letters, digits/numbers, whitespace, and special characters.  The subject that is being searched could be as simple as one word, or more complex like an email address.  

## 🌼 Summary

/^([0-9a-zA-Z_\.-]+)@([\da-zA-Z\.-]+)\.([a-z\.]{2,6})$/

This is a Regex that is used to verify the proper format of an email address.  This Regex has seven parts:

/^

1.  The forward slash with the caret indicates the begining of the string.  The regular expression is the string of characters that follows the forward slash and the caret.  

([0-9a-zA-Z_\.-]+)

2.  The brackets indicate it is seaching for any single character that is inside of the brackets.  In this case, any digits from 0 and 9, any lowercase letters from a to z, any uppercase letters from A to Z, any underscores, any dashes, and any periods or dots.  The backslash before the dot has a special purpose in a Regex.  The backslash is an escape symbol for the character that follows it. The backslash followed by a dot indicates that it is searching for a dot or a period. A dot or a period without the backslash is used to match any single character.  The parenthesis capture everything contained within as a string. 

@

3.  The @ symbol indicates that it is searching for the literal exact match of an @ symbol.  Every email address format contains an @ symbol.

([\da-zA-Z\.-]+)

4.  This example is nearly identical to part 2.  The difference is the backslash and d.  The backslash and d indicates that it is searching for a digit (equal to [0-9]).  

\.

5.  The backslash before the dot is the same as in part 2.  Every email address format contains a dot (.com, .org, etc).

([a-z\.]{2,6})

6.  The brackets indicate it is seaching for any single character that is inside of the brackets.  In this case, any lowercase letters from a to z.  Once again, the backslash before the dot has a special purpose in a Regex.  The backslash is an escape symbol for the character that follows it. The backslash followed by a dot indicates that it is searching for a dot or a period. A dot or a period without the backslash is used to match any single character.  The curly brackets indicate a quantifier.  In this example, {2, 6} will search for a number of matches between 2 and 6 of the item that precedes it.  There are no digits in the item/brackets that precedes this quantifier.  The parenthesis capture everything contained within as a string.

$/

7.   The dollar sign with the forward slash indicates the end of the string.  The regular expression is the string of characters that ends before the dollar sign and the forward slash.  


## 🌼 Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## 🌼 Regex Components

### Anchors

### Quantifiers

{2, 6}

### Grouping Constructs

### Bracket Expressions

### Character Classes

\d

### The OR Operator

### Flags

### Character Escapes

\.

## 🦋 Author

Hi, my name is Christopher Boyle. I hope you liked my Regular Expression Tutorial.  The link to my Github repository is:  https://github.com/timberhead  



