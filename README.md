# Projects

## **PPDS - Activity 1 - Data Features**

This Google Colab assignment demonstrates a data feature combining data from a recipe API (Edamam Recipes) and fruit API (FruityVice). This feature will help people find recipes that contain their desired fruit ingredients.


### **API Access:**


Recipe API: https://developer.edamam.com/edamam-docs-recipe-api

-Developer account required (limit of 10 requests per minute)

-Keys Used:

App ID - 757c083c


App Key - 2d327a070018d370d2ff3eb8c5732da0

Fruit API: https://www.fruityvice.com/doc/index.html

-No special authorization required



### **API Selection**


-The recipe API was selected for its vast array of recipes to provide multiple selections per fruit.

-The fruit API included various types of fruits, including less common ones, which made it ideal.



### **Features:**


-Recipes are sorted into URL, label (Name), ingredients, and image.

-The original code produced a random fruit each time the code is run from the fruit API. The updated code includes optionality over which fruit to search.

-Displays all of the recipes from the recipe API that align with the selected fruit in the format of a Pandas DataFrame.



### **Use Instructions**


-Run the code to get your desired fruit's accompanying recipes and information. 



### **Process & Implementation**

-In order to access the Edamam recipe API, account creation is required. Next, we broke down the recipes into the relevant parts mentioned in the features section. Following this, we processed the FruityVice API to provide a random fruit from its list each time it's run or the opportunity to input a specific fruit. Throughout our process, we created code for exceptions and errors. 

### **Execution**

For custom searches replace the "fruit" in the params variable code with your desired fruit.

For a random fruit:

params = {"type": "public", "app_id": *APP ID*,"app_key":*API KEY*,"q":fruit} 

For a custom fruit:

params = {"type": "public", "app_id": *APP ID*,"app_key":*API KEY*,"q":custom fruit}


