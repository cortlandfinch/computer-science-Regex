# Computer Science for JavaScript Challenge: Regex Tutorial

As a developer you must be able to write about code just as well as you are able to write code itself and understand the code that you are refactoring. During this tutorial I will explain the use of a regex function, also known as regular expression, which is a specific search pattern defined by a sequence of characters. After a user goes through this tutorial they will be able to understand how to use a Regex function that will match a string containing a United States zip-code. This function could be useful for developers during a form submit or requirement for a user to have an address that is located in the United States and this check would validate that user during their sign up. 
## Summary

The regex that I will be using will be "^\d{5}(?:[-\s]\d{4})?$", which will check for a United States zip code. This regex is useful for a form submit such as an e-commerce site that only ships to addresses in the United States, any user that is making a purchase would be required to provide their address during which this regex function would match or not match to a United States zip code and alert the user if they may continue. It may also be used for address verification in the United States or other United States employed companies for their employees during the onboarding or background check process. 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components


### Anchors
The Anchor of a regex function is used - not to match a character that the function is being used for but to start the position of the string that the function is being used to match within the string at the beginning or the end of the function. In this example the anchor of the function "^" is used before the starting number of the zip code number string and the "$" is used as the end of the string.
### Quantifiers
The quantifiers are used in a regex expression to quantify how many times the sequence pattern should be repeated within that given function. In this case the quantifier is repeated twice for the two different zipcode sequence patterns used. That is grouped by "{}" within the regex function.
### OR Operator
The OR Operator used in this regex function is "[-\s]" which is used to look for a whitespace character used in the function.
### Character Classes
The Character classes in this function "\d" is used  which matches a single character that represents a digit 0-9. "-\s" is also a character class in this function looking for a whitespace character.
### Flags
The Regex in this case is not delimited by two "/" at the start and end of the expression. The "^" and "$" enables the matching of the start and end of the pattern sequence. 
### Grouping and Capturing
The grouping that is used in this case by shown of the "()" groups the whitespace character and second sequence of numbers retrieved.
### Bracket Expressions
In this case the bracket expression that is used within the "[]" is the whitespace character which includes the "-\s".
### Greedy and Lazy Match
The greedy operators used in this example are within the "{}" which expands the match as far as possible through the provided sequence. In this example that would include the digits used that are provided.
## Author
Cortland Finch Link to regex github https://github.com/cortlandfinch/computer-science-Regex
