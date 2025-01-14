<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dream Cookbook</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600&display=swap" rel="stylesheet">
    <style>
        /* Global styling */
        body {
            background-color: #f9f9f9;
            font-family: Arial, sans-serif;
            color: #333;
            margin: 0;
            padding: 0;
        }

        /* Header styling */
        h1 {
            font-size: 2.5em;
            color: #ff66b2;
            background-color: #333;
            text-align: center;
            padding: 20px 0;
            margin: 0;
        }

        h3 {
            color: #333;
            text-align: center;
            font-size: 1.2em;
            margin-top: 0;
            background-color: #f0f0f0;
            padding: 10px;
            font-weight: normal;
        }

        h2 {
            text-align: center;
            color: #333;
            background-color: #ff66b2;
            padding: 10px;
            border-radius: 5px;
            margin: 20px auto 10px auto;
        }

        /* Custom font styling for Grocery List header */
        h2.grocery-header {
            font-family: 'Poppins', sans-serif;
            font-weight: 600;
            color: #ff66b2;
            text-align: center;
            font-size: 2em;
            margin-bottom: 20px;
            padding: 10px;
            background-color: #fff;
            border: 2px solid #ff66b2;
            border-radius: 5px;
        }

        /* Table styling */
        .recipe-table, .meal-plan-table {
            width: 90%;
            border-collapse: collapse;
            margin: 20px auto;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            background-color: #fff;
        }

        th, td {
            border: 1px solid #ff66b2;
            padding: 12px;
            text-align: center;
        }

        th {
            background-color: #333;
            color: #fff;
            font-size: 1.1em;
        }

        tr:nth-child(even) {
            background-color: #f9f9f9;
        }

        /* Button styling */
        .video-button, .recipe-link-button {
            display: inline-block;
            background-color: #ff66b2;
            color: #fff;
            padding: 10px 20px;
            margin: 10px auto;
            text-align: center;
            border-radius: 5px;
            font-weight: bold;
            text-decoration: none;
            transition: background-color 0.3s ease, transform 0.2s ease;
            font-size: 1em;
        }

        .video-button:hover, .recipe-link-button:hover {
            background-color: #333;
            color: #ff66b2;
            transform: scale(1.05);
        }

        /* Recipe steps styling */
        .recipe-steps, .highlight, .grocery-list {
            width: 90%;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border: 2px solid #ff66b2;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        .highlight {
            background-color: #ff66b2;
            color: white;
            border-color: #ff66b2;
            text-align: center;
        }

        /* Animation for tables and highlights */
        .recipe-table, .meal-plan-table, .highlight {
            opacity: 0;
            animation: fadeIn 1.2s ease forwards;
        }

        @keyframes fadeIn {
            to {
                opacity: 1;
            }
        }

        /* Link styling */
        a {
            color: #ff66b2;
            font-weight: bold;
        }

        a:hover {
            color: #333;
        }

        /* Image styling */
        .recipe-image {
            width: 100%;
            height: auto;
            border-radius: 5px;
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <h1>Welcome to Angie's Dream Cookbook</h1>
    <h3>Discover recipes, meal ideas, and cooking tips to spice up your culinary adventures!</h3>

    <!-- Recipe Table -->
    <h2>Popular Recipes</h2>
    <table class="recipe-table">
        <tr>
            <th>Recipe</th>
            <th>Main Ingredient</th>
            <th>Preparation Time</th>
        </tr>
        <tr>
            <td><a href="#grilled-chicken-salad-recipe" class="recipe-link-button">Grilled Chicken Salad</a></td>
            <td>Chicken & Vegetables</td>
            <td>20 minutes</td>
        </tr>
        <tr>
            <td>Spaghetti Carbonara</td>
            <td>Pasta & Eggs</td>
            <td>30 minutes</td>
        </tr>
    </table>

    <!-- Recipe Steps -->
    <h2 id="grilled-chicken-salad-recipe">Grilled Chicken Salad Recipe</h2>
    <img src="c:\Users\ASHIN\Downloads\download.jpg" alt="Grilled Chicken Salad" class="recipe-image">
    <ol class="recipe-steps">
        <li>Gather Ingredients
            <ul>
                <li>1 chicken breast</li>
                <li>2 cups mixed greens</li>
                <li>1/2 cup cherry tomatoes, halved</li>
                <li>1/4 cup cucumber slices</li>
                <li>1/4 cup shredded carrots</li>
                <li>2 tbsp olive oil</li>
                <li>1 tbsp lemon juice</li>
                <li>Salt and pepper to taste</li>
            </ul>
        </li>
        <li>Marinate the Chicken
            <ol>
                <li>In a small bowl, mix 1 tbsp of olive oil, salt, and pepper.</li>
                <li>Coat the chicken breast with the mixture and let it marinate for 10-15 minutes.</li>
            </ol>
        </li>
        <li>Grill the Chicken
            <ol>
                <li>Heat a grill pan over medium heat and add a little olive oil.</li>
                <li>Place the chicken breast on the pan and grill each side for 5-7 minutes or until fully cooked.</li>
                <li>Remove from heat and let it cool slightly, then slice it into strips.</li>
            </ol>
        </li>
        <li>Prepare the Salad
            <ol>
                <li>In a large salad bowl, combine the mixed greens, cherry tomatoes, cucumbers, and carrots.</li>
                <li>Top with the grilled chicken slices.</li>
            </ol>
        </li>
        <li>Make the Dressing
            <ol>
                <li>In a small bowl, whisk together 1 tbsp olive oil, 1 tbsp lemon juice, salt, and pepper.</li>
            </ol>
        </li>
        <li>Toss and Serve
            <ol>
                <li>Drizzle the dressing over the salad and toss to coat evenly.</li>
                <li>Serve immediately and enjoy your healthy Grilled Chicken Salad!</li>
            </ol>
        </li>
    </ol>

    <!-- Weekly Meal Plan Table -->
    <h2>Weekly Meal Plan</h2>
    <table class="meal-plan-table">
        <tr>
            <th>Day</th>
            <td>Monday</td>
            <td>Tuesday</td>
            <td>Wednesday</td>
            <td>Thursday</td>
            <td>Friday</td>
        </tr>
        <tr>
            <th>Breakfast</th>
            <td>Oatmeal</td>
            <td>Scrambled Eggs</td>
            <td>Fruit Smoothie</td>
            <td>Pancakes</td>
            <td>Yogurt & Granola</td>
        </tr>
    </table>

    <!-- Grocery List -->
    <h2 class="grocery-header">Grocery List</h2>
    <img src="https://example.com/grocery-list.jpg" alt="Grocery List" class="recipe-image">
    <ul class="grocery-list">
        <li>Fruits and Vegetables
            <ul>
                <li>Apples</li>
                <li>Carrots</li>
                <li>Spinach</li>
            </ul>
        </li>
        <li>Dairy
            <ul>
                <li>Milk</li>
                <li>Yogurt</li>
                <li>Cheese</li>
            </ul>
        </li>

