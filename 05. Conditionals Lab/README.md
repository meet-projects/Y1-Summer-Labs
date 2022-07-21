# Conditionals Lab

## Objective: 
In this lab, you will learn how to start writing **conditions** using **conditionals** and make programs that can make decisions!



<img src="https://thumbs.gfycat.com/QualifiedAdolescentHind-size_restricted.gif">




> Before we start, make sure to create a new file in **Repl.it** and call it **"ConditionsLab"**!  
> And make sure to save it in **"Day 4"** Folder.  

## Instructions:

### 1) Homer Diet
<img src="https://s3.amazonaws.com/after-school-assets/homer.gif" width="300px" align="right" hspace="10"> Homer Simpson has decided to go on a diet and he needs your help to stay on track. You are going to make the tests pass and help him control his donut intake.   

1. *Define* a new function called `no_donuts` that takes in a **number of donuts** as an argument. 
    - If the **number of donuts** is *greater* than **zero**, then this function should **print** `"Get back on your diet!"` 
    - Otherwise it should **print** `"Good job, Homer!"`
    
- Homer's diet has been going well and we're going to cut him some slack. 
2. Write a new function called `less_donuts` that takes in a **number of donuts** as an argument
    - The function should tell Homer `"good job"` when he eats **less than *3 donuts***
    - And to `"slow down"` if he's eaten **exactly 3 donuts** 
    - And "`get back on your diet"` if he eats **more than 3 donuts**.

- We've decided to give Homer a little more control over his diet.  
3. Write a function called `some_donuts` that takes in **two arguments**, the **number of donuts** he has eaten, and a **maximum donut intake**. 
    - This method should tell Homer `"good job"` if he eats **less than half his maximum intake**
    - And `"get back on your diet"` when he **exceeds his maximum intake**.


### 2) GO HOME!, Unless...  

Remember the **"GO HOME"** function from before?
1. Write a new function called `goHome_unless`, it should take 1 argument - `name`.

2. Make it so the function prints `"[name], Go home!"`, unless the name is `"homer"`, he is allowed to stay!

3. Does it work if you put in these strings as the `name` argument?
    - `"homer"`
    - `"Homer"`
    - `"hoMEr"`
    
4. If it doesn't take the previous strings, update and fix your function so it accepts the name `"homer"` in any way written! 


### 3) Daily Routine Function

Homer's daily routine is:
- 8-9 Wake up
- 9-10 Brush teeth, then eat 10 donuts.
- 10-12 Run to the store and make sure you have enough donuts for lunch.
- 12-13 Donuts Lunch
- 13-15 Go to the park
- 15-19 TV Time!
- 19-20 Donuts Dinner!
- 20-24 Fall asleep while watching TV and eating donuts.

1. Write a new function called `whatToDo`, that takes 1 argument called `time`, it represents the hour.

2. Plan the function and make it so when you put in `time` while calling the function `whatToDo`, it would print Homer's task according to the daily routine plan of his!
    - For example: `whatToDo(12)` would return as an output: `Donuts Lunch`
    
3. Does it work properly? Test it out!
 
 
4. Now, ask a neighbor to write down his/her daily routine, and write a new function that does the same, but for the new routine!
    - Let your neighbor try it out!



[![](https://media.tenor.com/images/a1a7f2e6a0a7e99a019a8937af3935e7/tenor.gif)]()




##### Great job!
##### Call an Instructor/TA to check your completed tasks
 

If you have extra time, continue to the **Bonus Problems** *below*.  
If not, make sure your code is saved in **Repl.it**!







## Bonus Problems:

#### Leap Years*
<img src="https://s3.amazonaws.com/after-school-assets/leap.gif" align="right" hspace="10">

1. Write a new function that takes in **two arguments** for a `starting year` and an `ending year`, and then `print` all of the **leap years** *between them* (including the starting and ending years, if they are also leap years). 

    - Hint: Leap years are years **divisible by four** (like 1984 and 2004). However, years divisible by 100 are _not_ leap years (such as 1800 and 1900) unless they are ALSO divisible by 400 (like 1600 and 2000). 

Yes, it's all pretty confusing, but not as confusing as having July in the middle of the winter, which is what would eventually happen if we didn't have leap years!



##### Great job on completing the bonus problems section!  
###### Make sure your code is saved in Repl.it

