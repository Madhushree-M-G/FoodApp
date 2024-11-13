# Food Recipe App

A front-end web application built with React that allows users to search for recipes, retrieve detailed recipe information, and get guidance on preparing dishes. The application fetches data from the **Spoonacular API** and uses **Postman API** to handle requests.

## Features

- **Search Recipes**: Search for a variety of recipes by keyword.
- **Recipe Details**: View ingredients, quantities, preparation instructions, and more.
- **Filter Options**: See if a recipe is vegetarian or non-vegetarian.
- **Price Information**: View price per serving for each recipe.
- **Instructions**: Get step-by-step instructions for making each recipe.

## Demo

![Home page](https://github.com/user-attachments/assets/50515de4-6527-4910-ab11-ef6db7eb55a6)
![Instructions](https://github.com/user-attachments/assets/e1a33e64-b677-4d19-88ea-abf7edd317a8)


## Installation

1. Clone the repository:
   git clone https://github.com/username/food-recipe-app.git
2. Navigate to the project directory
   cd food-recipe-app
3.install dependencies
  Obtain an API key from Spoonacular API.
  Create a .env file in the root directory and add your Spoonacular API key:
4. run the project
   

## Project Structure
  src
  ├── components     # Reusable components like RecipeList, RecipeCard, SearchBar, etc.
  ├── pages          # Pages like Home, RecipeDetail
  ├── services       # API calls and data handling
  ├── styles         # CSS or styled-components for styling
  └── App.js         # Main app component
  
## API Integration
  This project uses the Spoonacular API to fetch recipes and detailed information about each dish.
  
  Search Recipes: Fetches a list of recipes based on the user's search term.
  Recipe Details: Provides information such as ingredients, instructions, and dietary filters.
  Nutritional Information: Fetches nutritional info like price per serving and dietary compatibility.
  To handle API requests, Postman API was used for testing and debugging.

## Acknowledgments
  Spoonacular API for providing recipe data.
  Postman for testing API requests.
