# Predeclared Types In Go

## Introduction

<p> Like other programming languages, Golang has its own types which define the variables that are declared. While you may have experince on other languages types, 
there are subtle differences in Go.<b>This article aims to help you understand the go types and how to use them effectively.<b> The article is ideal for novice go developers or someone who is coming from another language and they want to get started in Go. Incase you have stayed for sometime without programming in go and you may have rusted, you can brush with this article.<b>By the time you are done with this article you will have learnt Go built in types and how they work best in Go. /p>

## Predeclared Types

The types that are built in the language are called *predeclared types*. <b>
They are ;
 - Integers
 - Boolean
 - String
 - Floats

## The Zero Value

Go assigns a default zero value to a variable that is declared but not assigned a value.

## Literals
A go literal is an explicitly defined character, number or a string.

### 1. Integer literals
- This is a sequence of numbers.
- Its of base 10
- It maybe expressed in other bases such as binary(ob), ocatal(0o) and hexadecimal(base 16).

### 2. Floating-point literals
- It has a decimal to indicate a fraction.
- They can also have an exponent eg. (6.03e23).

### 3. Rune literal
- Represents a character surrounded by single quotes eg 'a'.
- In go single quotes are not interchangable with double quotes.
- There are several backslashed escaped rune literals eg newline('\n'), tab('\'), single quote('\'') and ('\\').

#### 4. String literal
- using double quotes("") creates ***interpreted string literal***.
  - They contain 0 or more rune literals.
  - Both numeric and backslash escaped.
  - for such string, newline, backslashes and double quotes have to be escaped. **"Greetings and \n\"Salutations\""**
- Using backquotes(``) creates a ***Raw String***
  - They contain any character except a backquote. 
  eg ```
  `Greetings and 
  "Salutations"`
  ```

## Booleans
