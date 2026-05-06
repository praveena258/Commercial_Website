# Ex02 Commercial Website
## Date:06.05.26

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Commercial Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- HEADER -->
    <header>
        <div class="logo">The Art Vault</div>
        <nav>
            <a href="#home">Home</a>
            <a href="#products">Products</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
            <a href="#account">Account</a>
        </nav>
    </header>
    <section id="home" class="home">
        <h1>Welcome to The Art Vault</h1>
        <p>Your one-stop solution for amazing room decor</p>
    </section>

    <!-- PRODUCTS SECTION -->
    <section id="products" class="products">
        <h2>Our Arts</h2>
        <div class="product-container">
            <div class="card">
                <img src="image.jpg">
                <h2>Van gogh</h2>
                <p>$20</p>
            </div>
            <div class="card">
                <img src="new.jpg">
                <h2>mystery eye</h2>
                <p>$30</p>
            </div>
            <div class="card">
                <img src="neww.jpg">
                <h2>silent land</h2>
                <p>$40</p>
            </div>
        </div>
    </section>

    <!-- ABOUT SECTION -->
    <section id="about" class="about">
        <h2>About Us</h2>
        <p>At Art Vault, we believe that art is not just decoration—it is a form of expression, emotion, and creativity. Our store brings together unique handmade artworks, modern designs, and creative pieces that add life to any space.</p>
    </section>

    <!-- CONTACT SECTION -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Email: support@myshop.com</p>
    </section>

    <!-- ACCOUNT SECTION -->
    <section id="account" class="account">
        <h2>User Account</h2>
        <button>Login</button>
        <button>Register</button>
    </section>

    <!-- FOOTER -->
    <footer>
        <p>© 2026 MyShop | Follow us:</p>
        <div class="social">
            <a href="#">Facebook</a>
            <a href="#">Instagram</a>
            <a href="#">Twitter</a>
        </div>
    </footer>

</body>
</html>
```
css
```
/* GLOBAL STYLES */
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #24605a;
}

/* HEADER */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #000000;
    color: white;
    padding: 15px;
}

nav a {
    color: white;
    margin: 10px;
    text-decoration: none;
}

nav a:hover {
    color: yellow;
}

/* HOME */
.home {
    text-align: center;
    padding: 50px;
    background: rgb(3, 39, 51);
    color: #ffffff;
}

/* PRODUCTS */
.products {
    padding: 40px;
    text-align: center;
}

.product-container {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;

}

.card {
    background:rgb(3, 39, 51);
    padding: 20px;
    margin: 30px;
    width: 400px;
    transition: 0.3s;
    color: #ffffff;
    height: 700px;
}
.card img {
    width: 100%;      
    height: 600px;     
    object-fit: cover;  
    border-radius: 5px; 
}

.card:hover {
    transform: scale(1.05);
}
.card p{
    font-size:150%;
}

/* ABOUT, CONTACT, ACCOUNT */
.about, .contact, .account {
    padding: 40px;
    text-align: center;
    font-size: 150%;
}
.about p{
 font-size: 250%;
} 

/* ACCOUNT BUTTONS */
.account button {
    padding: 10px 20px;
    margin: 10px;
    border: none;
    background: #10132e;
    color: white;
    cursor: pointer;
}

.account button:hover {
    background: orange;
}

/* FOOTER */
footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 20px;
}

.social a {
    color: white;
    margin: 10px;
    text-decoration: none;
}

.social a:hover {
    color: rgb(1, 0, 66);
}
```
## OUTPUT
<img width="1919" height="980" alt="image" src="https://github.com/user-attachments/assets/5539a3c7-5f2c-4a79-a3c7-bfa81de21dca" />
<img width="1919" height="877" alt="image" src="https://github.com/user-attachments/assets/dbb4e41d-0fbb-40a1-ab7d-f55d35da4b33" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
