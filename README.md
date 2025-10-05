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
people.html

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
contact.css
body {
  font-family: Arial, sans-serif;
  background-color: #fdfdfd;
  margin: 0;
  padding: 0;
}

header {
  text-align: center;
  padding: 20px;
}

nav {
  background-color: #333;
  display: flex;
  justify-content: center;
  padding: 10px 0;
}

nav a {
  color: white;
  text-decoration: none;
  padding: 10px 20px;
  font-weight: bold;
}

.contact-form {
  max-width: 600px;
  margin: 30px auto;
  background: #ffeedd;
  padding: 20px;
  border-radius: 10px;
}

.contact-form h2 {
  text-align: center;
}

.contact-form label {
  display: block;
  margin-top: 10px;
  font-weight: bold;
}

.contact-form input,
.contact-form textarea {
  width: 100%;
  padding: 8px;
  margin-top: 5px;
  border-radius: 5px;
  border: 1px solid #aaa;
}

.contact-form button {
  margin-top: 15px;
  padding: 10px 20px;
  background: #333;
  color: white;
  border: none;
  border-radius: 8px;
  cursor: pointer;
}

people.css
body {
  font-family: Arial, sans-serif;
  background-color: #fafafa;
  margin: 0;
  padding: 0;
}

header {
  text-align: center;
  padding: 20px;
}

nav {
  background-color: #333;
  display: flex;
  justify-content: center;
  padding: 10px 0;
}

nav a {
  color: white;
  text-decoration: none;
  padding: 10px 20px;
  font-weight: bold;
}

.people-container {
  display: flex;
  justify-content: space-around;
  margin: 20px;
  flex-wrap: wrap;
}

.person-card {
  background-color: #ffeedd;
  padding: 15px;
  margin: 10px;
  border-radius: 10px;
  width: 250px;
  text-align: center;
}

.person-card img {
  width: 100%;
  border-radius: 50%;
}
style.css

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f3f3f3;
}

header {
  text-align: center;
  padding: 20px;
}

header img {
  height: 80px;
}

header h1 {
  margin: 0;
  font-size: 28px;
  letter-spacing: 3px;
}

nav {
  background-color: #333;
  display: flex;
  justify-content: center;
  padding: 10px 0;
}

nav a {
  color: white;
  text-decoration: none;
  padding: 10px 20px;
  font-weight: bold;
}

nav a:hover {
  background-color: #555;
  border-radius: 5px;
}

.banner {
  background: url('pasta.jpg') no-repeat center center/cover;
  color: white;
  text-align: left;
  padding: 60px 30px;
  border-radius: 10px;
  margin: 20px;
}

.banner h1 {
  font-size: 2em;
  font-weight: bold;
}

.container {
  display: flex;
  justify-content: space-around;
  padding: 20px;
}

.card {
  background-color: #ffeedd;
  padding: 15px;
  margin: 10px;
  border-radius: 10px;
  width: 30%;
}

.card img {
  width: 100%;
  border-radius: 10px;
}

.card a {
  display: inline-block;
  margin-top: 10px;
  color: blue;
  font-weight: bold;
  text-decoration: none;
}

footer {
  text-align: center;
  padding: 20px;
  margin-top: 20px;
  border-top: 1px solid #ccc;
  font-size: 14px;
}


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
