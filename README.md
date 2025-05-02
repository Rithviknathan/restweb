# Ex.07 Restaurant Website


## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KFC </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ed0707;
            color: #27251f;
        }
        header {
            background-color: #da291c;
            padding: 20px;
            text-align: center;
        }
        .logo {
            color: #f1f0ec;
            font-size: 2.5em;
            font-weight: bold;
        }
        nav {
            background-color: #27251f;
            padding: 10px;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        nav li {
            margin: 0 15px;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .hero {
            background-image: url('mcdonalds-hero.jpg');
            background-size: cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
        }
        .slogan {
            font-size: 3em;
            text-shadow: 2px 2px 4px #000;
        }
        .menu-items {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .menu-item {
            background-color: white;
            border-radius: 10px;
            margin: 15px;
            padding: 20px;
            width: 250px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        footer {
            background-color: #27251f;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">KFC</div>
    </header>
    <nav>
        <ul>
            <li><a href="#">Menu</a></li>
            <li><a href="#">Deals</a></li>
            <li><a href="#">Locations</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
    <div class="hero">
        <div class="slogan">FRESH AND TENDER</div>
    </div>
    <div class="menu-items">
        <div class="menu-item">
            <h3>9 saver chicken pack</h3>
            <p>The one and only. 9 saver pack. serves two satisfied.</p>
        </div>
        <div class="menu-item">
            <h3>Rice Bowl</h3>
            <p>Made with indian touch, with our Fried Chicken or Smoky Grilled Chicken. </p>
        </div>
        <div class="menu-item">
            <h3>World Famous Fries</h3>
            <p>Golden on the outside, soft and fluffy on the inside. Our World Famous Fries® are a KFC's Classic.</p>
        </div>
    </div>
    <footer>
        <p>© 2024 KFC's. All Rights Reserved.</p>
    </footer>
</body>
</html>
```


## OUTPUT:
![Screenshot 2025-05-02 202303](https://github.com/user-attachments/assets/b5d5c260-c497-4e6a-bc29-6a1fdf84992b)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
