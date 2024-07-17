# Lists Lab

## Objective: 
In this lab, you will learn how to start writing AND using **lists**, to start and get a sense on where and when to use them!

<img src="lists.gif" width="400">


> Before we start, navigate to Repl.it and `+ Create Repl` with the title `Lists - Your Name`

## Instructions:

### 1) Warm Up!
1. *Create* a new list and call it `classmates`, and include all of the classmates you see around you in that list!
    - Example: `classmates = ["Paulina", "Mustafa", "Firas"]`

2. Add your name to the list, using the `append()` function, then print out the list!
<img src="https://media2.giphy.com/media/26tk0T3cxwc4yFvK8/source.gif" align="right" hspace="10" width="300">

3. Check with a neighbor to make sure your list is correct!

### 2) Parking Valet!

You're working as a valet tonight at the **"Magic Palace"**! But, since you're a clever programmer, you decide to write a program that does your work for the night!  

1. *Define* a new list and call it `parked_cars`.
    - It should start as an empty list!

2. *Define* a new variable `car`, which uses `input()` to take a string as the name of the car.

3. Write code to append the `car` to the `parked_cars` list!
    - And print `"Parked [car] in the garage!"`
    - [car] = the value of your `car` variable

4. Repeat this process 2 more times so you end up with 3 cars in your list.

5. *Define* a new variable called `car_to_remove` using the `input()` function.

6. In your code, you should check to see **if** the car_to_remove is in the garage. In case your chosen car is not there: You should reply with `"Your car is not in the garage!"`

7. Else, now that you know that the car is in the `parked_cars` list, your code should remove the `car_to_remove` from `parked_cars` list!
    - And print `"[car_to_remove] is out of the garage and ready for use!"`

8. Finally, print how many cars are parked in the garage (using one of the list functions).


### 3) Netflix!

<img src="https://nofilmschool.com/media-library/film-netlifx.gif?id=34069820&width=210" hspace="10" width="400">

Sometimes it's hard to keep up with your **Netflix *movie queue***. Sometimes, all you need is a Friday night to binge watch Friends.

We're going to use lists to manipulate our own movie queue.

1. Write a new list variable called `movie_queue` - that includes your favourite movies and/or tv shows!
    - For example: `movie_queue = ["Minions", "Fast & Furious 1", "Harry Potter"]`

2. Write code that prints the first movie in the list.

3. Let's say you watched the first movie - Write code that deletes the first movie and prints the updated list. 


### Wrapping up:
- Please show your work to an Instructor or TA!
- When you're done, click on the submission link: https://forms.gle/QAbq9t31RAyH7iio7
- Copy your replit lab url, and paste it in the right place in the survey.
- Submit the survey!

<!-- 

Run the test.
- If it passes:
    - When you're done, make sure to submit the lab with the `Submit` button on the top right.
- If it fails:
    - Review the lab to see if you missed any steps. You need to follow the steps _exactly_ to pass.
    - If you have questions, ask a classmate, or call over an Instructor or TA!
-->
[![](https://camo.githubusercontent.com/2f9feb41e6febba197c32171bba0924fe0b0123a/687474703a2f2f312e62702e626c6f6773706f742e636f6d2f2d4844492d58694c697264382f546f614a736568535930492f414141414141414142736f2f5848584f555f71444b336b2f73313630302f506172726f742b46756e6e792b50696374757265735f312e6a7067)]()

-->
## Bonus Problems:

### Netflix Plus
Take your code from part 3 and add the following to it:
1. Turns out you watched movie 2 (second movie), ask the user for a new movie and replace it with movie 2. 

2. What if the user entered a movie that already exists in your movie list?
   - Check if the user's movie is **in** the movie list. If it is, print: "Sorry, the movie already exists." If not, add the movie to the list.
