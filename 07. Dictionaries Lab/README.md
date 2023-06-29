# Dictionaries Lab

## Objective: 
In this lab, you will learn how to start writing AND using **dictionaries**, and understand better on how we deal with data in computer science!



<img src="https://static.wixstatic.com/media/bb4cc9_7636144fdaa54a84a77b6c59d25dd6f8~mv2.gif" width="300" align="right">




> Before we start, navigate to the Repl.it assignment associated with this lab in the Teams tab! 

## Instructions:

### 1) Recipes Book!

1. Create a **dictionary** called `mac_and_cheese_recipe` that has the following data:  
    **Key** | **Value**          
    --- | ---   
    elbow pasta | 2 cups         
    butter | 1/2 stick      
    whole milk | 1 cup     
    shredded cheddar cheese | 3 cups    

  **All of the ingredients and amounts should be strings.**

2. Use `print` to print out the **amount of cheese** from `mac_and_cheese_recipe` that is needed!

3. Use `print` to print out the whole dictionary!

4. Now use `print` to print out just the ingredients without the amounts.

5. Next use `print` to print out just the amounts without the ingredients. 

     
### 2) Dictionaries in Dictionaries (Nested dictionaries)
```python
city_info = {		"new_york" : { "mayor" : "Bill DeBlasio",
							"population" : 8337000,
							"website" : "http://www.nyc.gov"
							},
			 "los_angeles" : { "mayor" : "Eric Garcetti",
							   "population" : 3884307,
							   "website" : "http://www.lacity.org"
							},
			 "miami" : { "mayor" : "Tomás Regalado",
					     "population" : 419777,
						 "website" : "http://www.miamigov.com"
					    },
			 "chicago" : { "mayor" : "Rahm Emanuel",
						   "population" : 2695598,
						   "website" : "http://www.cityofchicago.org/"
						}
		    }
```
1. The `city_info` dictionary above is a series of nested dictionaries. What do you think you get if you printed::
    - `city_info["los_angeles"]` ?
    - `city_info["chicago"]["mayor"]` ?
	
    Copy and paste the nested dictionaries into your Repl.it.
    **Print these lines of code to see if you're right!**

2. Write code to print each of these:
    - The population of New York
    - The website for Miami city government
    - The mayor of Los Angeles
    - A dictionary with all information on Chicago

> At this point your first 7 tests should pass!

### 3) Instagram Post

You are an engineer at **Instagram**, and your job is to organize the instagram post structure. We want to store them in a dictionary!

1. *Define* a new dictionary, call it `instagram_post`, It should have the following keys:
    **Key** | **Value**          
    --- | ---   
    image_link | A link to the image (`string`).         
    caption | I bet you know what a caption at Instagram means!      
    likes | should be an integer, counting the number of people who liked the post. You can set it to `0` to begin with.   
    comments | should be a `list` of strings of the comments.

<img src="https://gifimage.net/wp-content/uploads/2018/11/instagram-post-gif.gif" width="300" align="right">
    
2. Our post is super popular! Write code to add 1 like to our post.

3. Define a new variable, `comment`, containing a new comment to add to your dictionary.
    - It should look like `comment = "My new comment!"`
    - Write code to add `comment` to the `comments` list in the `instagram_post` dictionary.

4. *Define* a new variable, `new_caption`, containing a new caption for you post.
    - It should look like `new_caption = "My new caption!"`
    - Write code to update `caption` accordingly in the `instagram_post` dictionary.
    
5. Print out your updated `instagram_post` dictionary!

> All the test should pass at this point!


##### Great job!

### Wrapping up:
- Please show your work to an Instructor or TA!
- When you're done, make sure to submit the lab with the Submit button on the top right.

<!-- 

## Wrapping up:

Run the test.
- If it passes:
    - You can go on to try the challenges problems. Be sure you don't change any of the code you already wrote!
    - When you're done, make sure to submit the lab with the `Submit` button on the top right.
- If it fails:
    - Review the lab to see if you missed any steps. You need to follow the steps _exactly_ to pass.
    - If you have questions, ask a classmate, or call over an Instructor or TA!

-->
