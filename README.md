<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            gap: 20px;
            background-color: #f8f8f8;
            padding: 20px;
        }
        .menu {
            width: 400px;
            height: 550px;
            padding: 20px;
            margin: 10px;
            border: 3px solid #333;
            border-radius: 10px;
            color: white;
            font-family: Arial, sans-serif;
            text-align: center;
            font-size: 18px;
            font-weight: bold;
        }
        .breakfast {
            background: url('https://github.com/Aidenrtz/Menu-Design/blob/main/Images/breakfast%20menu.jpg?raw=true') no-repeat center;
            background-size: cover;
        }
        .lunch {
            background: url('https://github.com/Aidenrtz/Menu-Design/blob/main/Images/lunch%20menu.jpg?raw=true') no-repeat center;
            background-size: cover;
        }
        .dinner {
            background: url('https://github.com/Aidenrtz/Menu-Design/blob/main/Images/dinner%20menu.jpg?raw=true') no-repeat center;
            background-size: cover;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        li {
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <div class="menu breakfast">
        <h2>Breakfast Menu</h2>
        <ul>
            <li>Pancakes & Syrup</li>
            <li>Scrambled Eggs</li>
            <li>Bacon & Sausage</li>
            <li>Orange Juice</li>
            <li>Hot Coffee</li>
        </ul>
    </div>
    <div class="menu lunch">
        <h2>Lunch Menu</h2>
        <ul>
            <li>Grilled Chicken Sandwich</li>
            <li>Caesar Salad</li>
            <li>French Fries</li>
            <li>Iced Tea</li>
            <li>Lemonade</li>
        </ul>
    </div>
    <div class="menu dinner">
        <h2>Dinner Menu</h2>
        <ul>
            <li>Steak & Mashed Potatoes</li>
            <li>Grilled Salmon</li>
            <li>Steamed Vegetables</li>
            <li>Red Wine</li>
            <li>Chocolate Cake</li>
        </ul>
    </div>
</body>
</html>

