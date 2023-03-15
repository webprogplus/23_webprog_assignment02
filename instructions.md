### Introduction

It's time to practice all of the HTML knowledge you have acquired. In this project, you are going to build a basic recipe website.

The website will consist of a main index page which will have links to a few recipes. The website won't look very pretty by the time you've finished. Not unless you're into [brutalist web design](https://brutalistwebsites.com/), that is.

But it's important to keep in mind that this project is just to build your HTML chops; we will revisit this project in the future to style it up with CSS.

#### Tips on When to Commit 
When you're building your project, you will probably end up doing several `git add` + `git commit` cycles before being ready to push it up to GitHub with `git push origin main`.

When writing code, it's considered best practice to commit early and often. Commit every time you have a meaningful change in the code. This will create a timeline of your progress and show that your finished code didn't appear out of nowhere.

After you have entered `git push origin main`, switch over to your browser and open your repository on GitHub. You should now see all the files you just pushed.

Okay, that's enough Git for the moment -- time to actually build stuff!

### Assignment

<div class="lesson-content__panel" markdown="1">

#### Iteration 1: Initial Structure

1.  Within the repository directory, create an `index.html` file.
2.  Fill it out with the usual boilerplate HTML and add an `h1` heading "PLUS Recipes" to the body.

#### Iteration 2:  Recipe Page

1.  Create a new directory and name it `recipes`.
2.  Create a new HTML file within the  `recipes` directory and name it after the recipe it will contain. For example `lasagna.html`. You should use the name of your favorite dish or search for recipes in the web.
3.  For now, just include an `h1` heading with the recipe's name as its content.
4.  Back in the `index.html` file, add a link to the recipe page you just created. Example: Under the `<h1>PLUS Recipes</h1>` heading, write out the link like so: `<a href="recipes/recipename.html">Recipe Title</a>`. The text of the link should again be the recipe name.

#### Iteration 3:  Recipe Page Content

Your new recipe page should have the following content:

1.  An image of the finished dish under the h1 heading that you added earlier. You can find images of the dish on Google or the [recipe site](https://www.allrecipes.com/) we linked to earlier.

2.  Under the image, it should have an appropriately sized "Description" heading followed by a paragraph or two describing the recipe.

3.  Under the description, add an "Ingredients" heading followed by an **unordered list** of the ingredients needed for the recipe.

4.  Finally, under the ingredients list, add a "Steps" heading followed by an **ordered list** of the steps needed for making the dish.

#### Iteration 4: Add More Recipes

1. Add two more recipes with identical page structures to the recipe page you've already created.
2. Don't forget to link to the new recipes on the index page. Also, consider putting all the links in an unordered list so they aren't all on one line. 

Example:

~~~html 
 <ul>
    <li><a href="recipes/yourrecipe1.html">Recipe Title 1</a></li>
    <li><a href="recipes/yourrecipe2.html">Recipe Title 2</a></li>
    <li><a href="recipes/yourrecipe3.html">Recipe Title 3</a></li>
  </ul>
~~~
  
Your links won't be flashy, but for now just focus on building them out.
</div>



These assignments were slightly adopted based on the content provided by:

**The Odin Project** • [https://www.theodinproject.com/](https://www.theodinproject.com/)

 [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
