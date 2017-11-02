## General

  - All JavaScript functionality should leverage the jQuery JavaScript library
  - JavaScript should be used to enhance the user experience and all XHTML pages must be functional without the use of JavaScript. 
  - JavaScript files deployed to production should be minified with YUI Compressor
  - Files should contain multiple functions and classes, to reduce the number of external script files required

## Formatting

  - Code must be indented with spaces (soft tabs) set to 2 spaces instead of hard tabs
  - Braces must be the sole character on a line 
  - Braces should be used in situations where they are technically optional 
  - Operators should be surrounded by spaces
  - Commas and colons should be followed by a space
  - Semi-colons should not be preceded with a space

## Naming Conventions

  - Names should be short, semantically correct, human readable and avoid abbreviations
  - All names must be written in English
  - Abbreviations and acronyms should only have the lead character capitalized
	parseXml(), getRss()

## Files

  - Names should be lowercase, with words separated with dashes
    `jquery-extensions.js`
  - Inclusion of version information in the name is optional
  - Version information should be separated with periods
  - Version information should be appended to the name before the file extension
			jquery-1.2.6.js, jquery-1.2.6.min.js
## Variables

  - Names should be mixedCase capitalization
  - Names should avoid using abbreviations
  - Variables within a large scope should avoid terse naming to ensure a globally ambiguous name
  - Plural form must be used to name collections
  - Variables that represent a number or count, should be prefixed with num or count 
  - Variables of different types must be declared in different statements; variables of the same type may be declared in a common statement

## Constants

  - Names must be in upper case with words separated by underscores
  - When possible, constants should be encapsulated within an object that emulates an enum

## Classes

  - Names must be nouns
  - Names must be written using CamelCase capitalization
  - Class members intended to be private must have names prefixed with an underscore
  - Class names should reflect class inheritance, with the parent class name appearing as a suffix
    `MenuClickHandler extends ClickHandler`

## Functions

•	Names must be verbs or verb phrases
•	Names must be written using mixedCase capitalization
•	Function names / calls should not have a space between the name and opening parenthesis
•	The argument list should not be surrounded by spaces
•	Argument names must be mixedCase capitalization
•	Argument names should have the same name as their type

## Prefixes
  - get / set should be used for private variable accessors
  - is / has / can should be used for methods that return a Boolean value and must be named with a positive assertion

```javascript```
  isValid / canEdit / hasData
  Sample
  function doSomething(arg1, arg2)
  {
	// Code
  }
```

## Control Structures

  - Control statements should have one space between the control keyword and opening parenthesis
  - Semi-colons in for loops should have a preceding space
  - When multiple conditions are being evaluated, each conditional group must be wrapped in parenthesis if not a short-hand Boolean evaluation

```javascript
if ((var1 < var2) && !var3 && (var4 > var5))
if ((var1 < var2) && (var3 != false) && (var4 > var5))
```


