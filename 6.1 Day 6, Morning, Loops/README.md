# Loops Lab

## Objective: 
In this lab, you will learn how to start writing and using **loops**! And apply a lot of previous topics we learned from before with loops! (Some good **input/output** examples as well!!)

<img src="https://www.system-concepts.com/wp-content/uploads/2020/02/excited-minions-gif-360x163.gif">




> Before we start, make sure to create a new folder in **Repl.it** and call it **"Day 6"**!  
> And create a new file and call it **"LoopsLab"**.  

## Instructions:

### 1) Deaf Grandma
<img src="https://s3.amazonaws.com/after-school-assets/deaf_grandma.jpg" width="400">

***This is a group/pair lab. Write out pseudo-code first!***

1. Write a `speak_to_grandma` function that accepts one argument:`text` -> what you want to say to her. 
    - Whatever you say to grandma (whatever you type in), she should respond with `HUH?!  SPEAK UP, SONNY!`
    - Unless you shout it (type in all capitals). If you shout, she can hear you (or at least she thinks so) and yells back, `NO, NOT SINCE 1938!`.


2. Too easy? To make your program really believable, have grandma shout a different year each time you run the program; maybe any year at random between 1930 and 1950. (Hint: There is a Python function that will generate random numbers.) 


3. Grandma decided she wants to keep talking to you and won't let you leave. Change your program so that it keeps running until you shout BYE. (Hint: You will probably want to use a `while loop` to keep the program running.)


4. Grandma really doesn't want you to leave! When you shout BYE, she pretends not to hear you. 
    - Change your program so that you have to shout BYE three times in a row before the program will end. 
    - Make sure to test your program: if you shout BYE three times, but not in a row, you should still be talking the function go o
### 2) Item Finder

Remember the **"Socks finder"** function from before? We'll make a similar function that finds items, but with loops!
1. Write a new function called `item_finder`, it should take 2 arguments:
    1. `item`
    2. `items_list`

2. Make the function go over each item in `items_list` until it finds the `item` you are searching for!
    - For example: if you wanted to find your old book from the messy closet, use `item_finder("old book",["laptop","teddy bear", "old clothes", "old book", "sunglasses", "guitar", "cookies"])`, and the function should find `"old book"`!
    - If it's not there, it should print `"Item not here"`

3. Let's squeeze in the runtime of our program and make it faster to finish running!
    - use `break` when finding the `item` and stop the loop.
    
4. Ask your partner to write 3 different **items lists** and asks you to find 1 `item`.
    - Write a function called `where_is_the_item`, that takes 3 `item lists` and an `item`, and it should tell you in which `item list` is the `item` located.
    - For example: If you wirte `where_is_the_item(kitchen,bedroom,diningroom,"cellphone")` it would print something like: `"The cellphone is in bedroom."`

### 3) Dictionary Printer!

1. *Define* a new function called `print_dict`, it should take 1 argument - `dict1`
    - It should print the keys and the values next to each other
    - For example:
    ```python
    dict1 = {"Name":"Loai","Age":20,Year:17}
    # The function should print:
    Name    Loai
    Age     20
    Year    17
    ```
    - Hint: Use loops!


[![](https://i.gifer.com/7tB1.gif)]()




##### Great job!
##### Call an Instructor/TA to check your completed tasks
 

If you have extra time, continue to the **Bonus Problems** *below*.  
If not, make sure your code is saved in **Repl.it**!







## Bonus Problems:

1. Complete previous incomplete labs. *(if any)*


##### Great job on completing the bonus problems section!  
###### Make sure your code is saved in Repl.it

