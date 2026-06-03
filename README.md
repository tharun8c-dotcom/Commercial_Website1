# Ex02 Commercial Website
## Date:

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

```
HTML code:
<!DOCTYPE html>
<html>
<head>
    <title>Commercial Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Online Shopping Store</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Products</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </nav>

    <section class="container">

        <div class="card">
            <img src="laptopstopicpage-2048px-3685-2x1-1.webp" alt="Product 1">
            <h3>Laptop</h3>
            <p>High-performance laptop for work and study.</p>
            <button>Buy Now</button>
        </div>

        <div class="card">
            <img src="BEST-ANDROID-PHONES-2048px-9740.webp" alt="Product 2">
            <h3>Smartphone</h3/200>
            <p>Latest smartphone with advanced features.</p>
            <button>Buy Now</button>
        </div>

        <div class="card">
            <img src="bluetoothheadphones-2048px-0876.jpg" alt="Product 3">
            <h3>Headphones</h3>
            <p>Wireless headphones with excellent sound quality.</p>
            <button>Buy Now</button>
        </div>

    </section>

    <footer>
        <p>&copy; 2026 Online Shopping Store. All Rights Reserved.</p>
    </footer>

</body>
</html>

CSS code:
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

header{
    background:#090909;
    color:rgb(189, 58, 58);
    text-align:center;
    padding:20px;
}

nav{
    display:flex;
    justify-content:center;
    background:#e16969;
}

nav a{
    color:rgb(19, 131, 197);
    text-decoration:none;
    padding:15px 20px;
}

nav a:hover{
    background:#0d4daf24;
}

.container{
    display:flex;
    justify-content:space-around;
    flex-wrap:wrap;
    padding:20px;
}

.card{
    width:250px;
    border:1px solid #49053c;
    border-radius:10px;
    text-align:center;
    padding:15px;
    margin:10px;
    box-shadow:0 0 10px rgba(0,0,0,0.2);
}

.card img{
    width:100%;
    border-radius:10px;
}

button{
    background:#28a745;
    color:rgb(249, 168, 168);
    border:none;
    padding:10px 20px;
    margin-top:10px;
    cursor:pointer;
    border-radius:5px;
}

button:hover{
    background:#71a004;
}

footer{
    background:#02c171;
    color:rgb(44, 5, 5);
    text-align:center;
    padding:15px;
    margin-top:20px;
}
```


## OUTPUT

<img width="1913" height="967" alt="image" src="https://github.com/user-attachments/assets/cad723ce-03f7-4f8e-b024-8c8ab31298b4" />



## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
