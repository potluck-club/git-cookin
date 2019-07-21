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
     * course: appetizer, main, dessert, side, drink, ...
     * classification: meat, dairy, vegetarian, vegan, kosher, ...
     * allergen: nuts (specify), shrimp, lentils, chickpeas, ...
     * cuisine: french, american, chinese, thai, ... 
     * other: no planned support 
   * ingredients
     * with quantities or ranges 
   * steps
     * stylistically lets veer towards many smaller steps in list form
   * estimated servings?
   * estimated time (total, elapsed, active)
   * commentary and [flavor text](#git-cookin "not neccessarily about the actual flavor")
   * required equipment (necessary, desired)
   * date first brought to potluck (or `BGC` if before git-cookin and date not available) and the theme of that day if applicable
   * source of inspiration / credit?
1. organize accordingly and check the tex compiles

--- 

## discussion of further requirements
* must be able to compile individual recipes with minimal hassle
  * everything will be kept within TeX where possible
  * functionality not available within TeX will be built into the bakefile using UNIX utilities
  * compilation of individual recipes or collections of recipes should be handled through the bakefile
  * the bakefile should be straightforward to use, with a clear and well-broken-down README (possibly within this README)
  * Keep It Simple, Stupid: for additional
    the requested feature is actually within scope of this project
* must have full list of dependencies to build recipes on their own
  * dependencies will be clearly listed for all relevant OSs
* must figure out how to register approval -- what sort of criteria are important to get 
  * do we need some other database / table that records what people think of each recipe
  * or just a chef + approver system (codeowners?) to get things in to the master cookbook
  * for starters recipes will be by request? -- in which case things are more or less pre-approved... however eventually?
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
* support for multiple page recipes, no support for multiple recipes on a page in stylefile
* \# of columns to use in the style
  + 1
  - ~~2~~
* how to organize the compilations 
* naming conventions -- how do we make a fun hyperlinked index 
* what sort of ways do we want to look up recipes in the final product?
  * hyperlinked index
  * hyperlinked glossary from recipes at a later date?
  * TOC arranged by chapter based on master bakefile
  * how does this change for sub-collections?
* what sorts of files / builds should be more public -- ie how to share to others outside of potluck with a link for read? --> stored individual recipe pdfs as well?
* assume this repository is public at all times
* standards for how we cite inspiration: themes, thoughts, and authors
* how do we want to support scaling recipes -- and unit conversion
  * no support for scaling
* how do we best refer to units in pre list and in steps
* terminology [disambiguation](#git-cookin "c.f. flask")
