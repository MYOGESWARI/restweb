# Ex.07 Restaurant Website
## Date:17/12/2024

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
    <title>GOLDEN PLATE RESTAURANT </title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="LOGO.PNG" alt="GOLDEN PLATE Logo">
            <h1>GOLDEN PLATE RESTAURANT</h1>
        </div>
        <nav class="menu">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Book</a></li>
                <li><a href="#">About</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="banner" style="WhatsApp Image 2024-12-17 at 14.39.50_a919a90e.jpg,">
            <h2 class="offer-txt">30% Off This Weekend</h2>
            <p class = 'offer-txt'>Pan roasted brioche,Lobster bao,Chocolate cake,Manti dumplings,Blue crab meat balls</p>
        </section>
        <section class="features">
            <div class="feature">
                <h3>Our New Menu</h3>
                <img src="book a table.jpg" alt="Our New Menu">
                <p>Pan roasted brioche,Lobster bao,Chocolate cake,Manti dumplings,Blue crab meat balls</p>
            </div>
            <div class="feature">
                <h3>Book a table</h3>
                <img src="OUR MENU TIME.jpg" alt="Book a table">
                <p>Pan roasted brioche,Lobster bao,Chocolate cake,Manti dumplings,Blue crab meat balls</p>
            </div>
            <div class="feature">
                <h3>Opening Hours</h3>
                <img src="opening hours 2.jpg" class="hours" alt="Opening Hours">
                <p>Pan roasted brioche,Lobster bao,Chocolate cake,Manti dumplings,Blue crab meat balls</p>
                <ul>
                    Monday - Friday: 11:00 AM - 10:00 PM <br>
                    Saturday: 10:00 AM - 11:00 PM <br>
                    Sunday: 10:00 AM - 9:00 PM <br>
                </ul>
            </div>
        </section>
        <footer>
            <div class="logo">
                <img src="LOGO.PNG" class="footer" alt="GOLDEN PLATE logo">
                <p class="copy">&copy; Copyright GOLDEN RESTAURANT</p>
            </div>
        </footer>
    </main>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #b9fbe9;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: rgb(162, 211, 176);
    border-radius: 10px;
}

.menu{
    background-color: black;
    color: rgb(250, 4, 4);
    padding: 25px;
    border-radius: 30px;
}
.logo {
    display: flex;
    align-items: center;
}

.logo img {
    width: 90px;
    height: 90px;
    margin-right: 20px;
}

nav ul {
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin-right: 20px;
}

.footer{
    padding: 10px 10px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    font-weight: bold;
}

.offer-txt{
    color: rgb(156, 87, 235);
}
.hours{
    width: 300px;
    height: 80px;
}

.banner {
    text-align: center;
    background: url('c:\Users\admin\Downloads\background rest.avif') no-repeat center center/cover;
    padding: 60px 20px;
    color: #fff;
    border-radius: 10px;
    margin: 25px;
}

.banner h2 {
    font-size: 2.5em;
    margin: 0 0 20px;
}

.features {
    display: flex;
    justify-content: space-around;
    padding: 20px;
    background-color: rgb(162, 211, 176);
}

.feature {
    text-align: center;
    background-color: rgb(240, 202, 133);
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    flex: 1;
    margin: 0 10px;
}

.feature h3 {
    font-size: 1.5em;
    margin-bottom: 20px;
}

.feature img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
}

p {
    text-align: left;
}

ul {
    text-align: left;
}

.copy{
    margin-left: auto
}

.hyperlink{
    color: blue;
}

```
## OUTPUT:
![alt text](<yuva/restapp/static/Screenshot 2024-12-17 144612.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
