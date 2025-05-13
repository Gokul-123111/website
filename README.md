# Ex.07 Restaurant Website
# Date:
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:

index.html
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FOODIEE BUDDIEE - Home</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        header {
            background-color: #333;
            color: white;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header .logo img {
            width: 50px;
            height: 50px;
            margin-right: 10px;
            vertical-align: middle;
        }

        header h1 {
            display: inline-block;
            margin: 0;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            gap: 15px;
        }

        nav ul li {
            display: inline;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
            padding: 5px 10px;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        nav ul li a:hover {
            background-color: #555;
        }

        .banner {
            background-color: #f4f4f4;
            padding: 20px;
            margin-bottom: 20px;
        }

        .features {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 20px;
        }

        .card {
            width: 300px;
            border: 1px solid #ddd;
            border-radius: 10px;
            padding: 15px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .card img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            margin-bottom: 10px;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 10px;
            margin-top: 20px;
        }

        .footer-logo {
            width: 50px;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">
            <img src="food14.jpg" alt="FOODOS CHEAP THRILLS">
            <h1>FOODIEE BUDDIEE</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="admin.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="banner">
        <h2>25% discount This Weekend</h2>
        <p>SERVICE OF APPETIZING FOODS AT ITS EARLIEST</p>
    </section>

    <section class="features">
        <div class="card">
            <h3>Our New Menu</h3>
            <p>jalapeno poppers</p>
            <img src="food13.jpg" alt="New Menu">
            <p>Your cravings called—we answered.</p>
            <a href="menu.html">See our new menu</a>
        </div>
        <div class="card">
            <h3>Book a table</h3>
            <img src="food4.jpg" alt="Book a Table">
            <p>The table’s waiting. Are you?</p>
            <a href="#">Book your table now</a>
        </div>
        <div class="card">
            <h3>Opening Hours</h3>
            <img src="food7.jpg" alt="Chef">
            <p>Mon - Fri: 3pm - 10pm<br>Sat: 12pm - 12am<br>Sun: 4pm - 8pm</p>
        </div>
    </section>

    <footer>
        
        <p>Designed and Developed by Gokul S(212224240044)</p>
    </footer>
</body>
</html>
```

menu.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - FOODIEE BUDIEE</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>FOODIEE BUDIEE</h1>
    </header>
    <main class="menu">
        <h2>Our Menu</h2>
        <div class="menu-grid">
            <div class="menu-item">
                <img src="food1.jpg" alt="Tomato Soup">
                <h4>MOKO CHOCOLATE SHAKE</h4>
                <p>With herbs and fresh cream</p>
            </div>
            <div class="menu-item">
                <img src="food2.jpg" alt="Mushroom Tikka">
                <h4>BHEL POORI</h4>
                <p>Indian classic</p>
            </div>
            <div class="menu-item">
                <img src="food3.jpg" alt="Jalapeno Poppers">
                <h4>JALAPENO POPPERS</h4>
                <p>Special menu</p>
            </div>
            <div class="menu-item">
                <img src="food4.jpg" alt="Crispy Baby Corn Roast">
                <h4>CRISPY BABY CORN ROAST</h4>
                <p>Fresh & crunchy</p>
            </div>
            <div class="menu-item">
                <img src="food5.jpg" alt="Dum Aloo Biriyani">
                <h4>Aloo puloo</h4>
                <p>Indian cuisine</p>
            </div>
            <div class="menu-item">
                <img src="food6.jpg" alt="Chinese Hakka Noodles">
                <h4>CHINESE HAKKA PAKODA</h4>
                <p>Chinese classic</p>
            </div>
            <div class="menu-item">
                <img src="food7.jpg" alt="Schezwan Fried Rice">
                <h4>SCHEZWAN BURGER</h4>
                <p>Chinese cuisine</p>
            </div>
            <div class="menu-item">
                <img src="food8.jpg" alt="Baked Spaghetti">
                <h4>CHEESE CAKE</h4>
                <p>Cheese-loaded</p>
            </div>
            <div class="menu-item">
                <img src="food9.jpg" alt="Hot Mocha Chocolate">
                <h4>HOT MOCHA CHOCOLATE</h4>
                <p>With maple</p>
            </div>
        </div>
    </main>
    <footer>
        <p>&copy; FOODIE BUDDIEE BY GOKUL</p>
    </footer>
</body>
</html>
```

admin.html
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - FOODOS CHEAP THRILLS</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>FOODOS CHEAP THRILLS</header>
    <main class="admin">
        <h2>Meet Our Team</h2>
        <div class="admin-grid">
            <div class="admin-card">
                <img src="chef1.jpeg" alt="Sanjay Ramasamy">
                <h4>SANJAY RAMASAMY</h4>
                <p>Head Chef</p>
            </div>
            <div class="admin-card">
                <img src="chef2.jpeg" alt="Stella Mary">
                <h4>STELLA MARY</h4>
                <p>Restaurant Manager</p>
            </div>
            <div class="admin-card">
                <img src="chef3.jpeg" alt="Amanda">
                <h4>AMANDA</h4>
                <p>Pastry Chef</p>
            </div>
            <div class="admin-card">
                <img src="chef4.jpeg" alt="Jamesmith">
                <h4>JAMESMITH</h4>
                <p>Marketing Head</p>
            </div>
            <div class="admin-card">
                <img src="chef6.jpeg" alt="Chef Dhamu">
                <h4>CHEF DHAMU</h4>
                <p>THALAIVAR OF CHEF</p>
            </div>
        </div>
    </main>
    <footer>
        <img src="logo.png" alt="FOODIEE BUDDIEE" class="footer-logo">
        <p>Developed by Gokul S (212224240044)</p>
    </footer>
</body>
</html>
```

contact.html

```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - FOODIEE BUDIEE</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>FOODIEE BUDIEE</header>
    <main class="contact">
        <h2>Contact Us</h2>
        <p><strong>Address:</strong> 3rd Face,2nd cross st, J.P. NAGAR, BENGALURU, India</p>
        <p><strong>Phone:</strong> +91 6380445678</p>
        <p><strong>Email:</strong> contact@FOODIEE BUDDIEE.com</p>
    </main>
    <footer>
        <img src="food14.jpg" alt="FOODIEE BUDDIEE" class="footer-logo">
        Developed by Gokul S (212224240044)
    </footer>
</body>
</html>
```
# OUTPUT:

index.html

![Screenshot 2025-05-13 083636](https://github.com/user-attachments/assets/4dd534cb-4466-4192-840c-134250e9beaa)

menu.html

![Screenshot 2025-05-09 142027](https://github.com/user-attachments/assets/8c80604b-b220-4023-bb38-6dc355ff9340)
![Screenshot 2025-05-09 142039](https://github.com/user-attachments/assets/a2076275-f9a2-4fa9-b182-30624301d1a5)

admin.html

![Screenshot 2025-05-13 082842](https://github.com/user-attachments/assets/bc1c58b8-c124-456b-9367-f352820e0e0f)

contact.html

![Screenshot 2025-05-09 143535](https://github.com/user-attachments/assets/a1eccc0e-5cb5-4518-9b07-cbf9c23acc67)



# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
