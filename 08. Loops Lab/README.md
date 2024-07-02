# Loops Lab

## Objective: 
In this lab, you will learn how to start writing and using **loops**! And apply a lot of previous topics we learned from before with loops! (Some good **input/output** examples as well!!)

<img src="https://www.system-concepts.com/wp-content/uploads/2020/02/excited-minions-gif-360x163.gif">


> Before we start, navigate to Repl.it and `+ Create Repl` with the title `Loops - Your Name`

## Instructions:

### 1) Lovely Grandma
<img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExem5xYTF1ZDlybjN1a2V4ZGQ4cjR3OWx1dWNsbnpydzAyOW92b3J2aiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l1J9CUENbuod5zl8A/giphy.webp" width="400">

1. Today we're spending time with our grandma. *Define* a variable `text`, which gets input from the user that allows us to speak. (Hint: `input()`)
    - If you shout something to grandma (type in all capital letters), she can hear you (or at least she thinks so) and yells back, `NO, THINGS WERE BETTER IN OUR DAYS!`.
        - _Hint_: Look up the string method `isupper()` to help you check for capitalization!
    - Otherwise, whatever you say to grandma (whatever you type in), she should respond with `HUH?!  SPEAK UP, SONNY!`

2. Grandma decided she wants to keep talking to you and won't let you leave. Change your program so that it keeps running until you shout `"BYE"`.
    - _Hint_: You will probably want to use a `while` loop to keep the program running.
    
### 2) Searching out closet

Our closet is pretty messy. But we can write code that helps us find stuff in our closet using loops!

1. *Define* a new variable, `my_item`, using `input()`, which represents an item you are looking for.

2. Copy and paste the following list, which represents all the items in our closet:

```python
my_closet = [
 "running shoes",
 "dress shoes",
 "red shirt",
 "blue shirt",
 "brown pants",
 "bagel",
 "book",
]
```

3. Write code to go over each item in `my_closet` until it finds `my_item` you are searching for!
    - If the item is there, print `"I found my [item]"`.
    - If it's not there, your code should print `"I can't find my [item]"`.
        - Hint: You might need an extra variable to keep track of whether you've found `my_item`.

4. We can make our loop faster by breaking out of it as soon as we find our item!
    - Use `break` when finding `my_item` and stop the loop.
    
    

[![](https://i.gifer.com/7tB1.gif)]()
### Great job!

### Wrapping up:
- Please show your work to an Instructor or TA!
- When you're done, click on the submission link: 
- Copy your replit lab url, and paste it in the right place in the survey.
- Submit the survey!

<!-- 

### Wrapping up:
- Please show your work to an Instructor or TA!
- When you're done, make sure to submit the lab with the Submit button on the top right.


## Wrapping up:

Run the test.
- If it passes:
    - You can go on to try the bonus problems at the bottom of the lab. Be sure you don't change any of the code you already wrote!
    - When you're done, make sure to submit the lab with the `Submit` button on the top right.
- If it fails:
    - Review the lab to see if you missed any steps. You need to follow the steps _exactly_ to pass.
    - If you have questions, ask a classmate, or call over an Instructor or TA!
-->

## Bonus Problems:

### 1. FizzBuzz
Write code to print numbers from 1 to 100, where multiples of 3 are replaced with "fizz", multiples of 5 with "buzz", and multiples of both 3 and 5 with "fizzbuzz." 

Example:

`1, 2, fizz, 4, buzz, fizz, 7, 8, fizz, buzz, 11, fizz, 13, 14, fizzbuzz, 16, 17, ...`


### 2. Dictionary Printer!

1. Copy and paste the following dictionary into the python editor:

```
data = {
"Name": "The Meal",
"Age":  "2 Weeks",
"Gender": "Soup",
"Size": "500ml",
}
```

1. Write code to print the keys and the values next to each other
    - It should look kind of like this (make sure you have at least 1 space between the key and the value on each line):
    ```python
    key_a    value_a
    key_b    value_b
    key_c    value_c
    ```
    - Hint: Use loops!
   
### 3. MEET Partner
 *Define* a variable called `partner_dict`.
    - `partner_dict` should be a dictionary of questions and answers about another MEET student.
    - Using `input()` and `while` loops, write code that prints out each question, and asks the reader for an answer. The code should keep running until the reader gets all of the answers right!
    - Example of how it should look like:
    ```python
    Lill = {"When did Lill graduate from meet?" : "Summer 2021", "How old is Lill?" : 19}
        
    ### The terminal should look like:
    Question: When did Lill graduate from meet?
    Answer: Summer 2018 # User input
    Wrong Answer!
    
    Question: When did Lill graduate from meet?
    Answer: Summer 2021 # User input
    Correct Answer!
    
    Question: How old is Lill?
    Answer: 19
    Correct Answer!
    You win!
    ```


