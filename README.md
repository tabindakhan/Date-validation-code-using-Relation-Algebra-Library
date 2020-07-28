# Date-validation-code-using-Relation-Algebra-Library

<b>Introduction</b>

A RegEx, or Regular Expression, is a sequence of characters that forms a search pattern.<br>
Python has a built-in package called re, which can be used to work with Regular Expressions.

<b>RE Functions</b><br>
The re module offers a set of functions that allows us to search a string for a match.
<br>
<br>
<em>findall:</em> Returns a list containing all the matches.
<br><em>search:</em> Returns a match object if there is a match in anywhere in the string.
<br><em>split:</em> Return the list where the string has been split at each match.
<br><em>sub:</em> Replaces one or many matches with the strings.
<b>Date validation</b><br>
<br>
For Date validation firstly re expression is declared and saved in “pat” variable.<br>
Input taken from the user and saved it in a variable named as “da”.<br>
Totally there are 2 valid patterns as shown in picture.<br>
Now passing “pat” & “da” in the function of RE i.e “re.search”.<br>

In the end validation of Date is checked using if else.
