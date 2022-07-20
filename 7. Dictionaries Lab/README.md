# Dictionaries Lab

## Objective: 
In this lab, you will learn how to start writing AND using **dictionaries**, and understand better on how we deal with data in computer science!



<img src="https://static.wixstatic.com/media/bb4cc9_7636144fdaa54a84a77b6c59d25dd6f8~mv2.gif" width="300" align="right">




> Before we start, make sure to create a new file in **Repl.it** and call it **"DictLab"**!  
> And make sure to save it in **"Day 5"** Folder.  

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

2. Write a function that **returns** (not print) your `mac_and_cheese_recipe` dictionary


3. Write function called `amount_of_cheese` that returns the **amount of cheese** from `mac_and_cheese_recipe` that is needed!

4. Use `print` to print out every ingredient and amount in the dictionary!

5. Now use `print` to print out just the ingredients without the amounts.

6. Next use `print` to print out just the amounts without the ingredients. 

7. Return the number of ingredients in the `mac_and_cheese_recipe` dictionary.
    - Create a function called `number_ingredients`, that handles this.
     
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
1. The `city_info` dictionary above is a series of nested dictionaries. What do I get returned if I ask for:
    - `city_info["los_angeles"]` ?
    - `city_info["chicago"]["mayor"]` ?

2. What code should I write to return each of these?:
    - The population of New York
    - The website for Miami city government
    - The mayor of Los Angeles
    - A dictionary with all information on Chicago

### 3) Instagram Post

Your an engineer at **Instagram**, the **App development manager** asks you to create better organized Instagram *post* data structure!
The manager thinks it's really messy and un-organized, and he wants the post data stored in **dictionaries**!


1. *Define* a new dictionary, call it `instagram_post`, It should have the following keys:
    **Key** | **Value**          
    --- | ---   
    image_link | A link to the image (`string`).         
    caption | I bet you know what a caption at Instagram means!      
    Likes | should be a `list` of names (strings) of the likers.     
    Comments | should be a `list` of strings of the comments.
    - Fill the content as you wish :)
<img src="https://gifimage.net/wp-content/uploads/2018/11/instagram-post-gif.gif" width="300" align="right">
    
2. *Define* a new function, call it `like_post`, It should have 1 argument - `name` (the name of the liker)
    - The function should add `name` to `Likes` in `instagram_post` dictionary.
    - Also `print`: `"[name] has liked your post."

3. *Define* a new function, call it `comment_post`, It should have 1 argument - `comment` (the string of a comment)
    - The function should add `comment` to `Comments` in `instagram_post` dictionary.
    - Also `print`: `"A follower has commented: [comment]"`
    
4. *Define* a new function, call it `edit_caption`, It should have 1 argument - `new_caption` (the string of a new caption)
    - The function should update `caption` accordingly in `instagram_post` dictionary.
    - Also `print`: `"Caption has been updated."`






##### Great job!
##### Call an Instructor/TA to check your completed tasks
 

If you have extra time, continue to the **Bonus Problems** *below*.  
If not, make sure your code is saved in **Repl.it**!







## Bonus Problems:

1. Complete the previous incomplete labs (if any).


##### Great job on completing the bonus problems section!  
###### Make sure your code is saved in Repl.it

