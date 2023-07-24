# Functions Lab

## Objective: 
In this lab, you will learn how to start writing working **functions**, as well as use **inputs & outputs** a lot!


[![](https://thumbs.gfycat.com/SevereUnnaturalAlbino-size_restricted.gif)]()

> Before we start, navigate to the Repl.it assignment associated with this lab in the Teams tab!


## Instructions:

<!-- 

### 1) Excited @MEET!
1. *Define* a new function and call it `excited`, it should take 1 argument which is `name`.

2. The function should **return**: `[name] is super excited to be at MEET!`

3. Let a neighbor try it out!
    - You can print the result of the function to see it work like this:
    ```python
    print(excited("Maggie"))
    ```
    -->
### 1) GO HOME!

1. *Define* a new function and call it `go_home`, it should take 1 argument which is `name`.

2. The function should **return**: `"[name] go home!"`
    
3. Add an argument to the function called `hours`, and update the function to **return**: `"[name] go home! But come back after [hours] hours."`

3. Test our your code!
    - You can print the result of the function to see it work like this:
    ```python
    print(go_home("Vivien", 6))
    ```


### 2) Restaurant Tip Calculator!

1. Define a new function and call it `tip_calc()`. It should take 2 arguments:
    - `bill` - The table's bill.
    - `percentage` - the percentage you'd like to tip (if you want to tip 10%, `percentage` should be `10`)

2. The function should calculate and print how much you should tip based on the bill & percentage!
    - For example, if the bill was `250`, and you want to tip `10%`, you could call `tip_calc(250, 10, 5)`, and you should print `Tip: 25`.
    - How would you calculate that ?
    - Let's try to add it to the function!

3. Add another print statement in your function that prints the total amount you need to pay.
    - The total is the tip, plus the original bill.
    - In our example above, if you call `tip_calc(250, 10, 5)` you should print `Total: 275`.

4. Add a new argument to the function `tip_calc()` called `people`
    -  `people` - the number of people sitting at your table.
    

6. In your function, return the amount each person needs to pay if you split the total equally.
    - This is the total amount, divided by the number of people.
    - In our example above, if you call `tip_calc(250, 10, 5)` it should return `55`.

    

[![](https://thumbs.gfycat.com/ImpeccableInnocentHoiho-size_restricted.gif)]()

### Wrapping up:
- Please show your work to an Instructor or TA!
- When you're done, make sure to submit the lab with the Submit button on the top right.

<!-- 
## Wrapping up:

Run the test.
- If it passes:
    - You can go on to try the bonus problems at the bottom of the lab. Be sure you don't change any of the code you already wrote!
    - When you're done, make sure to submit the lab with the `Submit` button on the top right.
- If it fails:
    - Review the lab to see if you missed any steps. You need to follow the steps _exactly_ to pass.
    - If you have questions, ask a classmate, or call over an Instructor or TA
-->

## Bonus Problems:
[![](https://camo.githubusercontent.com/2f9feb41e6febba197c32171bba0924fe0b0123a/687474703a2f2f312e62702e626c6f6773706f742e636f6d2f2d4844492d58694c697264382f546f614a736568535930492f414141414141414142736f2f5848584f555f71444b336b2f73313630302f506172726f742b46756e6e792b50696374757265735f312e6a7067)]()

Parrots love to mimic their human companions. In this part you'll write some parrot functions that accept a word or phrase as an **argument**, and repeat it back to you with some change!

Write the following functions according to each one's description:

1. Happy Parrot - This parrot is happy as heck. It accepts a `phrase` as its argument and it says how happy it is about that phrase!  
    - Example: `happy_parrot("the meal")` would return `"I am so happy about the meal!"`

2. Math Parrot - Create a function that accepts **two numbers** as arguments and adds them together!
    - Example: `math_parrot(2, 3)` would return `"2 plus 3 is 5!"`

3. Reverse Parrot - This parrot repeats words in reverse.
    - Example: `reverse_parrot("hello")` would return `"hello reversed in olleh!"`

4. Favorites Parrot - Tell this parrot about your three favorite things and it will return "I love [thing] too!" for each of them.
    - Example: `favorites_parrot("bikes","cars","carrots")` would return 
    
```
"I love bikes too!"
"I love cars too!"
"I love carrots too!"
```

5. Now let's pretend you are a wizard and you want to place a spell on each of the parrots so that they speak with letter cases swapped. How would you do that? 

6. The spell has been broken and everyone is speaking normally again. The parrots are really excited about it though - make them shout in all caps!


