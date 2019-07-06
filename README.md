# git-cookin
:shallow_pan_of_food::man_cook::woman_cook::dash:

## Why 

A repository dedicated to preserving the best flavors of 
[potluck club](#git-cookin "known aliases GOT potluck, Naptime potluck"),
for likely eventual transformation into physical book form henceforth referred to as a cookbook.

## Ingredients

* Every recipe herein must have been cooked for some potluck by a `primary chef`
* Every recipe must have an awesome name 
* Every recipe shall be made to look consistently awesome, to do so we shall implement a common theme and template recipes using `LaTeX` 
* Not every recipe in this pot will have the luck 
to be included in the final binding, as such we will discuss some (probably multiple) filters

## Steps

1. dump recipe text into tex file
1. identify important sections
   * title
   * author
     * this shouldn't need an example...
   * tags
     * `e.g.` : kosher, meat, dairy, vegetarian, vegan, allergen, dessert, main, side, vegetable, cuisine of origin ...  
   * ingredients
     * with quantities or ranges 
   * steps
     * stylistically lets veer towards many smaller steps in list form
   * estimated servings?
   * estimated time (total, elapsed, active)
   * commentary and [flavor text](#git-cookin "not neccessarily about the actual flavor")
   * required equipment (desired, necessary)
   * date first brought to potluck (or `BGC` if before git-cookin) and the theme of that day if applicable
   * source of inspiration / credit?
1. organize accordingly and check the tex compiles

--- 

## discussion of further requirements
* must be able to compile individual recipes with minimal hassle
* must have full list of dependencies to build recipes on their own
* must figure out how to register approval -- what sort of criteria are important to get  
  * do we need some other database / table that records what people think of each recipe
  * or just a chef + approver system (codeowners?) to get things in to the master cookbook
* may want to standardize on a set of units that are approved and those that are verboten as well as standard aliases in the latex 
  + cups
  + liters
  + Tablespoons
  + Teaspoons
  - ~~pinches~~
  - ~~to taste~~
  - ~~pecs~~
  + lbs
  + grams
  * 
* how to reference other recipes from recipes
* support for multiple page recipes, 
* \# of columns to use in the style
  + 1
  - ~~2~~
* how to organize the compilations 
* naming conventions -- how do we make a fun hyperlinked index 
* what sort of ways do we want to look up recipes in the final product?
* what sorts of files / builds should be more public -- ie how to share to others outside of potluck with a link for read? or 
* assume that this repository could be public at any time
* standards for how we cite inspiration 
* how do we want to support scaling recipes
* how do we best refer to units in pre list and in steps
* terminology [disambiguation](#git-cookin "c.f. flask")
