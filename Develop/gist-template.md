# Phone Number RegEx

Phone number regular expressions are among several of comonly used regexs. I choose this one for the fact that it is a much simpler approach to understanding RegExs in general.

## Summary

The phone number regex is a simple and effective way to insert a phone number technically into your machine. It's very simple once you understand the components of the Regex. Your phone number Regex should look like: ^\(?(\d{3})\)?[- ]?(\d{3})[- ]?(\d{4})$

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
^\(?(\d{3})\)?[- ]?(\d{3})[- ]?(\d{4})$

### Anchors
- Beginning of the regex starts with a simple carrot top as shown --> ^
- Ending of the regex is a doller sign as shown --> $ this means that this is the end of the line or string of the regex. 

### Quantifiers
- Matches 3 of the proceeding tokens (0-9)
- Second user input includes 3 of the proceeding tokens (0-9)

### OR Operator
- Sqaure Brackets // Character Set [] which in this case will match a space with (-) or a blank !

### Character Classes

### Flags
- There are no flags in this expression, but if their were it would like like a .dot character, technically reffered to as the "wildcard character" which just basically matches everything except newline characters.

### Grouping and Capturing
- There are three total capturing groups in this specific expression, one being the first which in this case matches any digit character (0-9)
- It also has a quantifier of three, which means that thre specific numbers between the capturing set (0-9) will be used to execute this.

### Bracket Expressions
- A bracket expression is a list of characters enclosed by ' [ ' and ' ] '. It matches any single character in that list.

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

My name is Sabrina Elkins, I am a certified Power Yoga instructor. I bartend and serve at the Secret bar at the W Hotel, while also helping one of my close buddies with his startup company SunShader Inc. I am new to the coding world, but truly in love with the enviorment of it. I have a passion for learning and being in the University of Austin Coding Bootcamp is not only rewarding, but a huge opportunity for my future and the career field I aspire to be in.

GitHub: https://github.com/sabrinaelkins
