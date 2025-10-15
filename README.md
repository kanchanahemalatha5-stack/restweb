# Ex.07 Restaurant Website
## Date:15-10-2025

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
rest.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MARRIOTT MANOR | Home</title>
    
    <link href="style1.css" rel="stylesheet">

</head>
<body>
  <header>
    <h1>MARRIOTT MANOR</h1>
        <nav>
            <a href="rest.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="contact.html">Contact</a>
            <a href="admin.html">Admin</a>
        </nav>
    </header>

    <div class="banner">
        <div class="banner-content">
            <h1>Modern Muse</h1>
            <p>Serving You the Finest Cuisine</p>
            <a href="#features">Discover More</a>
        </div>
    </div>

    <section id="features" class="features">
        <div class="feature">
            <img src="table.png" alt="High quality dishes">
            <h3>High Quality Dishes</h3>
            <p>Savor exquisite culinary creations, meticulously prepared with the finest ingredients and world-class expertise.</p>
        </div>
    </section>
    <footer align="center" id="copywrite">
                Designed and developed by Kanchana M(25016997) &copy 2025
     </footer>
    
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>MARRIOTT MANOR - Menu</title>
     <link href="style2.css" rel="stylesheet">
    
</head>
<body>

    <header>
        <div class="logo-container">
            <h1>MARRIOTT MANOR</h1>
        </div>
        <nav>
            <a href="rest.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="contact.html">Contact</a>
            <a href="admin.html">Admin</a>
        </nav>
    </header>

    <div class="menu-container">
        <h1>Our Menu</h1>
        <div class="menu-items">
            <div class="menu-item">
                <img src="chicken tagine.png" alt="Chicken tagine" />
                <div class="menu-details">
                    <h3>Chicken tagine</h3>
                    <p class="price">₹780/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="mutton chukka.png" alt="mutton chukka" />
                <div class="menu-details">
                    <h3>Mutton chukka</h3>
                    <p class="price">₹920/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="prawn biriyani.png" alt="prawn biriyani" />
                <div class="menu-details">
                    <h3>Prawn biriyani</h3>
                    <p class="price">₹880/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="fish fry.png" alt="fish fry" />
                <div class="menu-details">
                    <h3>Fish fry</h3>
                    <p class="price">₹350/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="crab curry.png" alt="crab curry" />
                <div class="menu-details">
                    <h3>Crab curry</h3>
                    <p class="price">₹650/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="indian frybread.png" alt="Indian frybread" />
                <div class="menu-details">
                    <h3>Indian frybread</h3>
                    <p class="price">₹1000/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="Mexican flat enchiladas.png" alt="Mexican flat enchiladas" />
                <div class="menu-details">
                    <h3>Mexican flat enchiladas</h3>
                    <p class="price">₹1350/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="Lobster rolls.png" alt=" Lobster rolls" />
                <div class="menu-details">
                    <h3> Lobster rolls</h3>
                    <p class="price">₹750/-</p>
                </div>
            </div>
        </div>
    </div>

   <footer align="center" id="copywrite">
                Designed and developed by Kanchana M(25016997) &copy 2025
            </footer>

</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MARRIOTT MANOR - Contact Us</title>
     <link href="style3.css" rel="stylesheet">
       
    
</head>
<body>

    <header>
        <h1>MARRIOTT MANOR</h1>
        <nav>
            <a href="rest.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="contact.html">Contact</a>
            <a href="admin.html">Administration</a>
        </nav>
    </header>

    <div class="contact-banner">
        <h1>Contact Us</h1>
    </div>

    <section class="contact-section">
        <div class="contact-details">
            <h2>Visit or Reach Out</h2>
            <p><strong>Address:</strong> Marriott Manor, Santa Monica, Los Angeles, USA</p>
            <p><strong>Phone:</strong> +1 212 555 4567</p>
            <p><strong>Email:</strong> marriottmanor@gmail.com</p>
            <p><strong>Hours:</strong> Mon-Sun: 9 AM - 12 AM</p>
        </div>

        <div class="contact-form">
            <h2>Send a Message</h2>
            <form action="#" method="post">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <footer align="center" id="copywrite">
                Designed and developed by Kanchana M(25016997) &copy 2025
            </footer>
</body>
</html>

admin.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MARRIOTT MANOR - Administration</title>
   <link href="style4.css" rel="stylesheet">

  
</head>

<body>
  <header>
    <h1>MARRIOTT MANOR</h1>
    <nav>
      <a href="rest.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="contact.html">Contact</a>
      <a href="admin.html">Administration</a>
    </nav>
  </header>

  <div class="admin-container">
    <h1>Meet Our Leadership Team</h1>
    <div class="admin-items">
      <div class="admin-item" data-aos="zoom-in">
        <img src="my pic.jpeg" alt="Portrait of CEO Kanchana" />
        <div class="admin-details">
          <h3>Kanchana</h3>
          <p>CEO of MARRIOTT MANOR</p>
        </div>
      </div>

      <div class="admin-item" data-aos="flip-left" data-aos-delay="100">
        <img src="shalini.png" alt="Portrait of Manager shalini" />
        <div class="admin-details">
          <h3>Shalini</h3>
          <p>Manager</p>
        </div>
      </div>

      <div class="admin-item" data-aos="flip-right" data-aos-delay="200">
        <img src="simran.png" alt="Portrait of Master Chef simran" />
        <div class="admin-details">
          <h3>Simran</h3>
          <p>Master Chef</p>
        </div>
      </div>

      <div class="admin-item" data-aos="fade-up-left" data-aos-delay="300">
        <img src="aishwarya.png" alt="Portrait of Assistant Managing Director Aishwarya" />
        <div class="admin-details">
          <h3> Aishwarya</h3>
          <p>Assistant Managing Director</p>
        </div>
      </div>
    </div>
  </div>

 <footer align="center" id="copywrite">
                Designed and developed by Kanchana M(25016997) &copy 2025
            </footer>

  <script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>
  <script>
    AOS.init({
      duration: 1000,
      once: true,
    });
  </script>
</body>
</html>


```

## OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2025-10-15 161828" src="https://github.com/user-attachments/assets/ff89bc7f-527b-40ea-9b7f-8949d47c5747" />

![alt text](<Screenshot 2025-10-15 161850.png>)
![alt text](<Screenshot 2025-10-15 161909.png>)
![alt text](<Screenshot 2025-10-15 161927.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
