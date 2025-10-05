# Ex.07 Restaurant Website
## Date:5-10-2025

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
~~~
home.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Little Lemon - Home</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <img src="logo.png" alt="Little Lemon Logo">
    <h1>Tasty Restaurant </h1>
  </header>

  <nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="people.html">administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <section class="banner">
    <h1>30% Off This Weekend</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. 
       Fusce dapibus vehicula ex at ultricies. Duis at varius ligula.</p>
  </section>

  <section class="container">
    <div class="card">
      <h2>Our New Menu</h2>
      <img src="menu.jpg" alt="New Menu">
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris.</p>
      <a href="menu.html">See our new menu</a>
    </div>

    <div class="card">
      <h2>pasta</h2>
      <img src="pasta.jpg" alt="Book a table">
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris.</p>
      <a href="contact.html">Book your table now</a>
    </div>

    <div class="card">
      <h2>Opening Hours</h2>
      <img src="chef.jpg" alt="Opening Hours">
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris.</p>
      <p>
        Mon - Fri: 2pm - 10pm <br>
        Sat: 2pm - 11pm <br>
        Sun: 2pm - 9pm
      </p>
    </div>
  </section>

  <footer>
    <p>Designed and Developed by <span style="color:red;">Evangeline Sophiya </span></p>
  </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - Little Lemon</title>
  <link rel="stylesheet" href="contact.css">
</head>
<body>
  <header>
    <h1>Tasty Restaurant</h1>
  </header>

  <nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="people.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <section class="contact-form">
    <h2>Contact Us</h2>
    <form>
      <label for="name">Your Name:</label>
      <input type="text" id="name" required>

      <label for="email">Your Email:</label>
      <input type="email" id="email" required>

      <label for="message">Message:</label>
      <textarea id="message" rows="5"></textarea>

      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>Designed and Developed by <span style="color:red;">Evangeline Sophiya</span></p>
  </footer>
</body>
</html>
menu.html

<!DOCTYPE html>
<html lang="en">
<head>
 <section class="container">
    <div class="card">
      <h2>Our New Menu</h2>
      <img src="menu.jpg" alt="New Menu">
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris.</p>
      <a href="menu.html">See our new menu</a>
    </div>
  <footer>
    <p>Designed and Developed by <span style="color:red;">Evangeline Sophiya </span></p>
  </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Team - Little Lemon</title>
  <link rel="stylesheet" href="people.css">
</head>
<body>
  <header>
    <h1>Tasty Restaurant</h1>
  </header>

  <nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="people.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <section class="people-container">
    <div class="person-card">
      <img src="manager.jpg" alt="Manager">
      <h3>Sophia</h3>
      <p>Restaurant Manager, making sure everything runs smoothly.</p>
    </div>
    <div class="person-card">
      <img src="waiter.jpg" alt="Waiter">
      <h3>John</h3>
      <p>Senior Waiter with a passion for excellent service.</p>
    </div>
  </section>

  <footer>
    <p>Designed and Developed by <span style="color:red;">Evangeline Sophiya</span></p>
  </footer>
</body>
</html>

~~~

## OUTPUT:
![alt text](<Screenshot 2025-10-05 152451.png>)
![alt text](<Screenshot 2025-10-05 152511.png>)

![alt text](<Screenshot 2025-10-05 153600.png>)
![alt text](<Screenshot 2025-10-05 153629.png>)
![alt text](<Screenshot 2025-10-05 153648.png>)
![alt text](<Screenshot 2025-10-05 154311.png>)




## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
