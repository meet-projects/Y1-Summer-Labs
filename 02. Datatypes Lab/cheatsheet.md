# Datatypes Cheatsheet

## New Words

|Word|Meaning|Example|
|---|---|---|
|Integer|A whole number in python. It's special word is `int`.|`1`, `42`, `-5`|
|Float|A number with a decimal point in python--even if the decimal part is 0. It's special word is `float`|`3.14`, `4.0`, `-21.1`|
|Modulo|The remainder of a division--we use the `%` sign in python to get the `modulo` of two numbers.|`10 % 3` (this becomes `1`, because `3` goes into `10` `3` times, and leaves `1` left over)|
|Boolean|`True` and `False` in python. It's special word is `bool`|`True`, `False` (always capitalized!)|
|String|Text text in python. It's special word is `str`.|`"Hello world!"` (always in `"` quotes!)|
|Character|A single letter or symbol in a string. A string is like a list of characters.|`"H"`, `"e"`, `"l"`, `"l"`, `"o"`|



## Code Examples

|Code Example|Result|Description|
|---|---|---|
|`2 + 3`|`5`|Addition between two `int`s. This becomes `5` (another `int`).|
|`8 - 2`|`6`|Subtraction between two `int`s. This becomes `6` (another `int`).|
|`3 * 4`|`12`|Multiplication between two `int`s. This becomes `12` (another `int`).|
|`10 / 5`|`2.0`|Division between two `int`s. This becomes `2.0`--a `float`, not an `int`.|
|`4.2 + 2.5`|`7.7`|Addition between two `float`s. This becomes `7.7` (another `float`). All the examples above also work with `float`s!|
|`3.33 * 10`|`33.3`|Multiplication between a `float` and an `int`. This becomes `33.3`, a `float`. Whenever you add, subtract, multiply, or divide with an `int` and a `float`, the result is always a `float`.|
|`10.5 // 5`|`2`|Integer division between a `float` and an `int`. This means we throw away any decimal part to make the result an `int`.|
|`10 % 3`|`1`|Modulo between two `int`s. This is the remainder after dividing the first number by the second number. This becomes `1`, because `3` goes into `10` `3` times, and leaves `1` left over.|
|`4 ** 2`|`16`|Exponentiation between two `int`s. This is saying "4 multiplied by itself, 2 times, so it becomes `16`.|
|`5 == 5`|`True`|An equalitly comparison. This becomes `True` (a `bool`) because 5 equals 5. Don't worry too much about this, we'll explore comparisons more later.|
|`1 > 2`|`False`|A greater-than comparison. This becomes `False` (a `bool`) because 1 _isn't_ greater than 2. Don't worry too much about this, we'll explore comparisons more later.|
|`"5" + 5`|`TypeError`|Addition between a `str` and an `int` ⚠️ Warning ⚠️ this will cause a `TypeError`, because `str`s and `int`s can't be added together.|
|`5 + True`|`6`|Addition between an `int` and a `bool`. This evaluates to `6`! When you try to add a number and a `bool`, `True` becomes `1` and `False` becomes `0`.|
