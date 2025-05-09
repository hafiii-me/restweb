# Ex.07 Restaurant Website
## Date : 09-05-2025
# NAME : MOHAMED HAFEEZ S
# REG NO : 212224040193
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
HTML 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Delish Dine</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <header>
    <h1>Delish Dine</h1>
    <nav>
      <a href="#menu">Menu</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome to Delish Dine</h2>
    <p>Where every bite is a delight</p>
  </section>

  <section id="menu" class="menu">
    <h2>Our Menu</h2>
    <div class="items">
      <div class="item">
        <img src="images/pizza.jpg" alt="Pizza" />
        <h3>Italian Pizza</h3>
        <p>Cheesy and delicious wood-fired pizza.</p>
      </div>
      <div class="item">
        <img src="images/burger.jpg" alt="Burger" />
        <h3>Classic Burger</h3>
        <p>Juicy beef burger with fresh veggies.</p>
      </div>
    </div>
  </section>

  <section id="services" class="services">
    <h2>Our Services</h2>
    <ul>
      <li>Dine-in Experience</li>
      <li>Online Ordering</li>
      <li>Event Catering</li>
    </ul>
  </section>

  <footer id="contact">
    <p>Contact us: +123 456 789 | delishdine@example.com</p>
  </footer>
</body>
</html>

   CSS

body {
  font-family: Arial, sans-serif;
  margin: 0;
  background-color: #fff8f0;
  color: #333;
}

header {
  background-color: #d84315;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  margin: 0 15px;
  color: white;
  text-decoration: none;
}

.hero {
  background-color: #ffe0b2;
  padding: 60px;
  text-align: center;
}

.menu, .services {
  padding: 40px 20px;
  text-align: center;
}

.items {
  display: flex;
  justify-content: center;
  gap: 30px;
  flex-wrap: wrap;
}

.item {
  background: white;
  border-radius: 10px;
  padding: 20px;
  max-width: 250px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

.item img {
  width: 100%;
  border-radius: 8px;
}

footer {
  background-color: #d84315;
  color: white;
  text-align: center;
  padding: 15px;
}


## OUTPUT:
![Screenshot 2025-05-09 134942](https://github.com/user-attachments/assets/cbc07dfb-4114-406c-abfc-37b970f66267)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
