
# ENDAVA  MENU!

**Endava Internship git challenge**

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRHzrKHnACL8XNZ0UdGaEvcki3My7y2FzwMgyjaEnNKB0AXNZaY)

## CONTEXT

To practice git knowledge a basic restaurant menu was created.
Every student created a recipe and used git commands for practice.
Individual recipes branches were created, in addition to a dev and master ones.
Menu was created using .txt files

## CONTENT

LICENSE: here you find the permissions and limitations of use the project's files
MENU.md: Here you find the restaurant's menu with all recipes and prices
.GITIGNORE: This file contains the ommited files for project
RECIPES: in this folder you can find all recipes instructions created for each of members

  			* Bayron_Recipe.txt: the bayron's recipe about Rice with milk
			* Gourmet Scramblet eggs with Lechona.txt: the oscar's recipe about scramblet eggs with lechona
			* Roasted milk.txt: the juan's recipe about roasted milk

## GIT REPO USE STRATEGY

This repository has followed a standard pattern of use. The main branch is called Master, and contains only the code which has been verified and tested. 
From the Master branch, derives the dev branch. It contains the work that has been done independently, and tested locally. 
This branch has the main purpose of merging the partially-working files from the independent branches, and testing whole-system functionality.
Finally, on the lowest level of branching hierarchy, comes the independent branches. They contain single-developer-feature work. This work may or may not run correctly.

The main branches (Master and Dev) are protected in the Github remote repository. For the Master branch it means that no pull request can be accepted unless it receives the approval from 3 contributors.
In the case of Dev branch, it only needs approval from 1 contributor. The protection also ensures no forcing can be applied to the repository.

All of the project is licensed under an MIT License.