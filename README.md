# Recipe Manager WPF

This Recipe Manager WPF application allows users to add, filter, and manage recipes. Each recipe can include multiple ingredients and steps. Users can also scale the ingredients by a factor and reset them to their original quantities.

## Features

- Add new recipes with ingredients and steps.
- Display recipe details including ingredient names, quantities, units, and calories.
- Filter recipes by ingredient, food group, or maximum calories.
- Scale recipe ingredients by a factor of 0.5 or 2.
- Reset recipes to their original state.
- Clear filters to display all recipes.

## Prerequisites

- [.NET Framework](https://dotnet.microsoft.com/download/dotnet-framework) (version 4.7.2 or later)
- [Visual Studio](https://visualstudio.microsoft.com/) (2019 or later) with WPF development tools installed.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/recipe-manager-wpf.git
   cd recipe-manager-wpf

   Adding a Recipe
Click the "Add Recipe" button in the main window.
Enter the recipe name.
Add ingredients by entering the ingredient name, quantity, unit, calories, and food group, then click "Add".
Add steps by entering the step description and clicking "Add".
Once all ingredients and steps are added, click "Save Recipe" to save the recipe.
Viewing and Filtering Recipes
The list of recipes is displayed on the main window.
Select a recipe to view its details including name, ingredients, and steps.
To filter recipes, enter the filter text and select the filter type (Ingredient, Food Group, or Max Calories), then click the "Filter" button.
To clear the filter and display all recipes, click the "Clear Filter" button.
Scaling and Resetting Recipes
To scale the ingredients of a selected recipe by a factor of 0.5 or 2, click the respective button.
To reset the ingredients of a selected recipe to their original quantities, click the "Reset" button.
