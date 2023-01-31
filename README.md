# Random recipes
I constantly have the problem that I can't choose what to cook, so I decided to solve this problem and create a program that will select a random recipe based on my choices.

Steps:

1. Finding data. As a resource I used [this recipe site](https://harchi.info/recipes).
2. Web Scrapping. You can see my code in web_data.ipynb file. I used ***Selenium and Pandas*** libraries to get and deal with data in this step
3. Data manipulation. This is in manipulation_program.ipynb file. The data has been preprocessed with ***Pandas and regular expressions***.
4. Program. I decided that I want to add 2 filters:
    - type/time of dish (breakfast, salat...)
    - ingridients. You can choose from 1 to 3 different ingridients

     GUI is done with ***PySimpleGUI*** library. The code is in manipulation_program.ipynb.
     
In the future, I plan to add new recipes, organize a better filter by ingredients and add a photo of the dish to each recipe.  
 But even know I'm finding this program really useful.  

Unfortunately, I took the data from the Ukrainian site, so ***all the recipes are in Ukrainian***.
