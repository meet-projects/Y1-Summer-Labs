# Calculator Project - Y1 Summer 


> Before we start, navigate to the Repl.it assignment associated with this lab in the Teams tab!  



<img src="https://art.pixilart.com/2241c06cc44adc2.gif" align="right" width=300>

## Motivation:
- The purpose of this project is to combine and use all concepts we have learned in CS so far in Y1 Summer!  
- It is also your **first opportunity** to build an **application** using the **Input/Output** concept!

## User Experience (UX)
- This is your first experience in UX design! It's critical and very important you think about user experience.
- User experience is as important as writing your code!
    - Is your app enjoyable/intuitive/easy to use?
    - Why should users choose your calculator over any other calculator application?
    - What about your application that makes it extra useful/enjoyable and adds value to it?

- Building a great application requires **empathy**... put yourself in the shoes of the user while building it!

## Objectives:
1. The Basic 4: 
    - Create a calculator that processes at least the basic 4 symbols (Addition(+), Subtraction(-), Multiplication(*), and Division(/)) 
    - The calculator has to take as an **input** at least 2 numbers and 1 of the symbols in order to create an equation.
    - The input should be a one-line equation. for example `3 - 4` , instead of taking 3 separate inputs.
    - The calculator has to return the **value** of the **given equation**.
2. Exponents:
    - An exponent refers to the **number of times** a number is **multiplied** by *itself*.
        - For example, 2 to the 3rd (written like this: 2^3) means: 2 x 2 x 2 = 8.
    - The calculator has to process exponents as well.
        - For example, if the user writes `2**3`, it should return `8` as the result.
        - Remember that `2**3` means 2 to the power of 3 or 2^3.
3. Error Handling:
    - What happens when you write:
        - An invalid equation. (For example: `3 - 4 + `)
        - An unsupported symbol. (For example `,` or `@`)
        - Dividing by 0 (For example `5 / 0`)
        - What if I enter a random string. (For example: `Potato` or `New York City`). Hint: `isdigit()`

    - Handle all of these resulting errors.
    - Make sure to cover all similar gaps in your application, to make sure it's as **user friendly** as possible!
4. Menu:
    - Include a menu of operations/actions options that is displayed when your application starts running.
    - This menu should serve as instructions to the user, to know how to use your application!
5. Run Continuously:
    - The program must run **continuously** until the user decides to stop/exit the application.
    - Think about a **user friendly** way how this can be implemented. 


## Challenges: *(Extra)*
*You can pick any/all of these if you like!* In other words, you don't have to do them in order.  

1. Add the option to take more than two numbers! For example, computing an expression like 3 + 4 / 2 with three numbers, or being able to make an expression such as 3 + 4 with only two numbers. 
2. Take more than one symbol, and make sure that you calculate the right order of operations. 
3. Add a history of operations list/dictionary!


> Turtle is a Python library that enables users to create pictures and shapes by providing them with a virtual canvas. Here's MEET's [Introduction to Turtle](https://docs.google.com/presentation/d/12hUghofRqPTL3jsDazqqUrrr8-GfMe68-IFim9XTEDI/edit?usp=sharing) Lecture. You will need to learn Turtle for the rest of the challenges.
4. Show the calculator results using turtle! 
    - Something that looks like this:
    <img src="https://github.com/meet-projects/Y1-Summer-Labs/blob/master/TurtleResult.png" width=150>

## Go Crazy: *(Extra)*
1. Full Functional Graphics! (Turtle)
    - Something that looks like this:
    <img src="https://media.geeksforgeeks.org/wp-content/uploads/Screenshot-774.png" width=450>


## Submission
When you're done, make sure to submit the lab with the `Submit` button on the top right. 

Congrats on finishing your calculator!
