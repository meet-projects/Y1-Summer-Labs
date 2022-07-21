# Loops Lab

## Objective: 
In this lab, you will learn how to start writing and using **loops**! And apply a lot of previous topics we learned from before with loops! (Some good **input/output** examples as well!!)

<img src="https://www.system-concepts.com/wp-content/uploads/2020/02/excited-minions-gif-360x163.gif">



> Before we start, navigate to the Repl.it assignment associated with this lab in the Teams tab!


## Instructions:

### 1) Deaf Grandma
<img src="https://s3.amazonaws.com/after-school-assets/deaf_grandma.jpg" width="400">

***This is a group/pair lab. Write out pseudo-code first!***

1. We will now try to speak to grandma! *Define* a variable `text`, which uses **input()** to allow us to speak!
    - Whatever you say to grandma (whatever you type in), she should respond with `HUH?!  SPEAK UP, SONNY!`
    - Unless you shout it (type in all capitals). If you shout, she can hear you (or at least she thinks so) and yells back, `NO, NOT SINCE 1938!`.
        - **Hint:** Look up string methods to help you check for capitalization!


2. Too easy? To make your program really believable, have grandma shout a different year each time you run the program; maybe any year at random between 1930 and 1950. (**Hint**: There is a Python function that will generate random numbers.) 


3. Grandma decided she wants to keep talking to you and won't let you leave. Change your program so that it keeps running until you shout BYE. (Hint: You will probably want to use a `while loop` to keep the program running.)


4. Grandma really doesn't want you to leave! When you shout BYE, she pretends not to hear you. 
    - Change your program so that you have to shout BYE three times in a row before the program will end. 
    - Make sure to test your program: if you shout BYE three times, but not in a row, you should still be talking to the grandma.
### 2) Item Finder

We'll now write a code that finds items with loops!

1. *Define* a new variable, `item`, using `input()`, which represents an item you are looking for. Also *define* a variable `items_list`, which represents the list of all the items you have (you do not have to use `input()` for this, but you may if you like!)


2. Write code to go over each item in `items_list` until it finds the `item` you are searching for!
    - For example: if you wanted to find your old book from the messy closet, use `item_finder("old book",["laptop","teddy bear", "old clothes", "old book", "sunglasses", "guitar", "cookies"])`, and the code should find `"old book"`!
    - If the item is there, print `[item] is here`.
    - If it's not there, your code should print `[item] is not here`.

3. Let's squeeze in the runtime of our program and make it faster to finish running!
    - use `break` when finding the `item` and stop the loop.
    
4. Ask your partner to write 3 different **items lists** and asks you to find 1 `item`.
    - Write code that looks at the 3 `item lists` and an `item`, and it should tell you in which `item list` is the `item` located.

### 3) Dictionary Printer!

1. *Define* a new dictionary, `dict1`, in your code. Write code to print the keys and the values next to each other
    - For example:
    ```python
    dict1 = {"Name":"Loai","Age":20,Year:17}
    # The code should print:
    Name    Loai
    Age     20
    Year    17
    ```
    - Hint: Use loops!


[![](https://i.gifer.com/7tB1.gif)]()

##### Great job!

## Wrapping up:

Run the test.
- If it passes:
    - You can go on to try the bonus problems at the bottom of the lab. Be sure you don't change any of the code you already wrote!
    - When you're done, make sure to submit the lab with the `Submit` button on the top right.
- If it fails:
    - Review the lab to see if you missed any steps. You need to follow the steps _exactly_ to pass.
    - If you have questions, ask a classmate, or call over an Instructor or TA!





## Bonus Problems:

1. *Define* a variable called `partner_dict`.
    - `partner_dict` should be a dictionary of questions and answers about your partner.
    - Using `input()` and `while` loops, write code that prints out each question, and asks the reader for an answer. The code should keep running until the reader gets all of the answers right!
    - Example of how it should look like:
    ```python
    loai = {"When did loai graduate from meet?" : "Summer 2017", "How old is loai?" : 20}
        
    ### The terminal should look like:
    Question: When did loai graduate from meet?
    Answer: Summer 2016 # User input
    Wrong Answer!
    
    Question: When did loai graduate from meet?
    Answer: Summer 2017 # User input
    Correct Answer!
    
    Question: How old is loai?
    Answer: 20
    Correct Answer!
    You win!
    
    ```

2. Write code that prints how many questions we have in total, and print the number of the question with every question answered correctly!

3. Complete previous incomplete labs. *(if any)*


##### Great job on completing the bonus problems section!  
###### Make sure your code is saved in Repl.it

