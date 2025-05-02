# Ex.07 Restaurant Website
## Date:02-05-2025

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
`````
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sara Delights</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #a03f76;
            color: white;
            padding: 15px;
            text-align: center;
        }

        header h1 {
            font-weight: 400;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
        }

        header nav ul li a:hover {
            color: rgb(251, 150, 110);
            font-weight: bold;
        }

        .container {
            width: 100%;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-around;
        }

        h2 {
            color: #3f45a0;
        }

        .menu-item {
            background-color: #fff;
            margin: 10px 0;
            padding: 15px;
            border-radius: 8px;
            display: flex;
            align-items: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .menu-item img {
            border-radius: 8px;
            margin-right: 15px;
            width: 100px;
            height: auto;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 5px 0;
        }

        ::-webkit-scrollbar {
            width: 0px;
        }
    </style>
</head>

<body>
    <header>
        <h1> Saara Delights </h1>
        <nav>
            <ul>
                <li><a href="food.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="container">
        <h2>Welcome to Our Restaurant</h2>
        <p>Faites l’expérience de la meilleure cuisine avec nous. Profitez de notre délicieux menu, de notre excellent service et d’une atmosphère chaleureuse.</p>
        <img src="./french.png" alt="Restaurant Banner" style="width: 30%; border-radius: 10px;">
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 Saara Delights| Designed by Saranya AV (24900084) </p>
        </div>
    </footer>
</body>

</html>

menu.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - SAARA DELIGHTS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f6f1;
            color: #333;
        }

        header {
            background-color: #3fa0a0;
            color: rgb(255, 255, 255);
            padding: 15px;
            text-align: center;
        }

        header h1 {
            font-weight: 400;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
            padding: 3px;
        }

        header nav ul li a:hover {
            color: rgb(251, 150, 110);
            font-weight: bold;
        }

        .menu-container {
            width: 80%;
            margin: 20px auto 70px auto;
            display: flex;
            justify-content: space-around;
            flex-wrap:wrap;
            overflow: scroll;
        }

        .menu-item {
            width: 30%;
            display: flex;
            align-items: center;
            margin-bottom: 20px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 8px;
            background-color: #fff;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .menu-item img {
            width: 100px;
            height: 100px;
            border-radius: 8px;
            margin-right: 15px;
        }

        .menu-item h3 {
            margin: 0;
            font-size: 1.2em;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 5px 0;
        }

        ::-webkit-scrollbar {
            width: 0px;
        }
    </style>
</head>

<body>
    <header>
        <h1>OUR MENU</h1>
        <nav>
            <ul>
                <li><a href="food.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <div class="menu-container">
        <div class="menu-item">
            <img src="./thai.png" alt="biryani">
            <div>
                <h3>THAI GREEN BIRIYANI</h3>
                <p>Fragrant jasmine rice cooked in Thai green curry with veggies or chicken.</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./nonveg.png" alt="NON VEG MEALS">
            <div>
                <h3>NON-VEG MEALS<h3>
                <p>Rice with chicken,mutton,fish gravy with rotti and chicken starters</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./naan.png" alt="Naan">
            <div>
                <h3>BUTTER CHICKEN LASAGNA</h3>
                <p>Layers of pasta,creamy makhani sauce, and pulled tandoori chicken. </p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./pasta.png " alt="chicken65">
            <div>
                <h3>PASTA 65</h3>
                <p>Spicy South Indian chicken or paneer 65 tossed with creamy Alfredo sauce. </p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./pav.png " alt="chickenlollipop">
            <div>
                <h3>SHAWARMA PAV BHAJI SLIDERS</h3>
                <p>Mini burgers with pav bhajo masala and shawarma-style fillings.</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./lemon.png" alt="butterchicken">
            <div>
                <h3>LEMON CHICKEN</h3>
                <p> Flavor full chicken rich in lemon and other secret spices</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./manchow.png" alt="mutton">
            <div>
                <h3>MANCHOW 2.0</h3>
                <p>A modern take on the Indo-Chinese favourite,served in a bowl with crispy noodles formed as a nest.</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./pesto.png" alt="prawnthokku">
            <div>
                <h3>PESTO KULCHA</h3>
                <p>Soft Kulcha with basil pesto filling.</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./naan.png" alt="crabsoup">
            <div>
                <h3>TRUFFLE BUTTER NAAN</h3>
                <p>Soft naan brushed with truffle-infused butter.</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./biscoff.png" alt="attukalsoup">
            <div>
                <h3>BISCOFF RASAMALAI TRUFFLE</h3>
                <p>Bite-sized rasmalai spheres rolled in Biscoff dust and saffron cream.</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./spl.png" alt="">
            <div>
                <h3>SAARA SPECIAL MOCKTAIL</h3>
                <p>A blend of kokum,lychee,mint,and soda.</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="./manjo.png" alt="jigarthanda">
            <div>
                <h3>MANGO CHILI MOJITO</h3>
                <p>Mango,mint,lemon and a spicy chili kick.</p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Designed by Saranya AV (24900084)</p>
    </footer>
</body>

</html>

administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - Saara Delights</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }

        header {
            background-color: #3f51b5;
            color: white;
            padding: 15px;
            text-align: center;
        }

        header h1 {
            font-weight: 400;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
        }

        header nav ul li a:hover {
            color: rgb(251, 150, 110);
            font-weight: bold;
        }

        .admin-container {
            width: 80%;
            margin: 20px auto;
            text-align: center;
        }

        .admin-card {
            display: inline-block;
            width: 200px;
            margin: 15px;
            padding: 15px;
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .admin-card img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 5px 0;
        }

        ::-webkit-scrollbar {
            width: 0px;
        }
    </style>
</head>
<body>
<header>
    <h1>ADMINISTRATION TEAM</h1>
    <nav>
        <ul>
            <li><a href="food.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="administration.html">Administration</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
    </nav>
</header>

<div class="admin-container">
    <div class="admin-card">
        <img src="./saara.png" alt="Dirtector">
        <h3> SAARA</h3>
        <p>Founder & Visionary Director</p>
    </div>
    <div class="admin-card">
        <img src="./gaggan.png" alt="Chef">
        <h3> GAGGAN ANAND </h3>
        <p>Head Chef</p>
    </div>
    <div class="admin-card">
        <img src="./vikhas.png" alt="Sous Chef">
        <h3>VIKAS KHANNA </h3>
        <p>General Manager</p>
    </div>
    <div class="admin-card">
        <img src="./ranveer.png" alt="Waiter">
        <h3>RANVEER BRAR</h3>
        <p>Executive Chef</p>
    </div>
    <div class="admin-card">
        <img src="./alain.png" alt="Bartender">
        <h3>ALAIN DUCASSE</h3>
        <p>Guest Experience Manager</p>
    </div>
    <div class="admin-card">
        <img src="./image.png" alt="Receptionist">
        <h3>PIERRE GAGNAIRE</h3>
        <p>HR Manager</p>
    </div>
</div>

<footer>
    <p>&copy; 2025  Designed by Saranya AV (24900084)</p>
</footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - SAARA DELIGHTS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #eaeaea;
            color: #333333;
        }

        header {
            background-color: #0b1cad;
            color: white;
            padding: 15px;
            text-align: center;
        }

        header h1 {
            font-weight: 400;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
        }

        header nav ul li a:hover {
            color: rgb(251, 110, 234);
            font-weight: bold;
        }

        .contact-container {
            width: 60%;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .contact-container h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        .contact-item {
            margin-bottom: 15px;
        }

        .contact-item label {
            font-weight: bold;
        }

        .contact-item p {
            margin: 5px 0;
        }

        footer {
            background-color: #333333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 5px 0;
        }

        ::-webkit-scrollbar {
            width: 0px;
        }
    </style>
</head>
<body>
<header>
    <h1>CONTACT US</h1>
    <nav>
        <ul>
            <li><a href="food.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="administration.html">Administration</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
    </nav>
</header>

<div class="contact-container">
    <h2>Get in Touch</h2>
    <div class="contact-item">
        <label>Email:</label>
        <p>info@SaaraDelights.com</p>
    </div>
    <div class="contact-item">
        <label>Phone:</label>
        <p>+9841345678</p>
    </div>
    <div class="contact-item">
        <label>Address:</label>
        <p>231 Cross Street,Sara City, Chennai, Tamilnadu</p>
    </div>
</div>

<footer>
    <p>&copy; 2025 Designed by Saranya AV (24900084)</p>
</footer>
</body>
</html>

`````



## OUTPUT:

![alt text](<Screenshot 2025-05-02 112136.png>) 
![alt text](<Screenshot 2025-05-02 112149.png>) 
![alt text](<Screenshot 2025-05-02 112202.png>) 
![alt text](<Screenshot 2025-05-02 112216.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
