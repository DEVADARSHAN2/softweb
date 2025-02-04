# Ex.07 Software Product Company Website
## Date:01/11/23

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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
# home.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Webpage Design</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">VirtuTech Solutions</h2>
            </div>

            <div class="menu">
                <ul>
                    <li><a href="home.html">HOME</a></li>
                    <li><a href="people.html">PEOPLES</a></li>
                    <li><a href="product.html">PRODUCTS</a></li>
                    <li><a href="contact.html">CONTACT</a></li>
                </ul>
            </div>

            <div class="search">
                <input class="srch" type="search" name="" placeholder="Enter To Search">
                <a href="#"> <button class="btn">Search</button></a>
            </div>

        </div> 
        <div class="content">
            <h1>A Software Agency shaping <br><span>ideas into</span> <br>Products</h1>
            <p class="par"><b>"People who are really serious about software <br>should make their own hardware" - Alan Kay. 
                </b></p>

                <button class="cn"><a href="#">JOIN US</a></button>

                <div class="form">
                    <h2>Login Here</h2>
                    <input type="email" name="email" placeholder="Username or Email">
                    <input type="password" name="" placeholder="Password">
                    <button class="btnn"><a href="#">Login</a></button>

                    <p class="link">Don't have an account<br>
                    <a href="#">Sign up </a> here</a></p>
                    <p class="liw">Log in with</p>

                    <div class="icons">
                        <a href="#"><ion-icon name="logo-facebook"></ion-icon></a>
                        <a href="#"><ion-icon name="logo-instagram"></ion-icon></a>
                        <a href="#"><ion-icon name="logo-twitter"></ion-icon></a>
                        <a href="#"><ion-icon name="logo-google"></ion-icon></a>
        
                    </div>

                </div>
                    </div>
                </div>
        </div>
    </div>
    <script src="https://unpkg.com/ionicons@5.4.0/dist/ionicons.js"></script>
</body>
</html>
~~~

# people.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="peo.css">
    <title>People</title>
</head>
<body>

    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">VirtuTech Solutions</h2>
            </div>

            <div class="menu">
                <ul>
                    <li><a href="home.html">HOME</a></li>
                    <li><a href="people.html">PEOPLES</a></li>
                    <li><a href="product.html">PRODUCTS</a></li>
                    <li><a href="contact.html">CONTACT</a></li>
                </ul>
            </div>

            <div class="search">
                <input class="srch" type="search" name="" placeholder="Enter To Search">
                <a href="#"> <button class="btn">Search</button></a>
            </div>

        </div> 
    <div class="centered-content">
        <div class="people-grid">
            <div class="person">
                <div class="circle-box">
                    <img src="person1.png" alt="Person 1">
                </div>
                <h3>Sundar Pichai</h3>
                <p>CEO</p>
            </div>
            <div class="person">
                <div class="circle-box">
                    <img src="person2.png" alt="Person 2">
                </div>
                <h3>Eleanor Bolton</h3>
                <p>CEO,Co-Founder</p>
            </div>
            <div class="person">
                <div class="circle-box">
                    <img src="person3.png" alt="Person 3">
                </div>
                <h3>Caspian Shields</h3>
                <p>CTO,Co-Founder</p>
            </div>
            <div class="person">
                <div class="circle-box">
                    <img src="person4.png" alt="Person 4">
                </div>
                <h3>Marek Goodman</h3>
                <p>CFO</p>
            </div>
            <div class="person">
                <div class="circle-box">
                    <img src="person5.png" alt="Person 5">
                </div>
                <h3>Lisa WhiteHouse</h3>
                <p>CMO</p>
            </div>
            <div class="person">
                <div class="circle-box">
                    <img src="person6.png" alt="Person 6">
                </div>
                <h3>Buster Mckenize</h3>
                <p>COO</p>
            </div>
        </div>
    </div>
</body>
</html>
~~~

# product.html
~~~
product.html

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Webpage Design</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .product-image {
            text-align: center;
        }

        .product-image img {
            max-width: 100%;
            max-height: 100%;
        }
    </style>
</head>
<body>
    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">VirtuTech Solutions</h2>
            </div>

            <div class="menu">
                <ul>
                    <li><a href="home.html">HOME</a></li>
                    <li><a href="people.html">PEOPLES</a></li>
                    <li><a href="product.html">PRODUCTS</a></li>
                    <li><a href="contact.html">CONTACT</a></li>
                </ul>
            </div>

            <div class="search">
                <input class="srch" type="search" name="" placeholder="Enter To Search">
                <a href="#"><button class="btn">Search</button></a>
            </div>
        </div> 

        <div class="product-image">
            <img src="image.jpeg" alt="Product Name" width="800" height="600">
        </div>
    </div>
</body>
</html>
~~~

# contact.html
~~~
contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="cont.css">
    <title>Contact Us</title>
</head>
<body>
 <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">VirtuTech Solutions</h2>
            </div>

            <div class="menu">
                <ul>
                    <li><a href="home.html">HOME</a></li>
                    <li><a href="people.html">PEOPLES</a></li>
                    <li><a href="product.html">PRODUCTS</a></li>
                    <li><a href="contact.html">CONTACT</a></li>
                </ul>
            </div>

            <div class="search">
                <input class="srch" type="search" name="" placeholder="Enter To Search">
                <a href="#"> <button class="btn">Search</button></a>
            </div>

        </div> 
    <div class="container">
        <div class="contact-form">
            <h1>Contact Us</h1>
            <form action="submit_form.php" method="POST">
                <div class="form-group">
                    <input type="text" id="name" name="name" placeholder="Your Name" required>
                </div>
                <div class="form-group">
                    <input type="email" id="email" name="email" placeholder="Your Email" required>
                </div>
                <div class="form-group">
                    <textarea id="message" name="message" placeholder="Your Message" rows="5" required></textarea>
                </div>
                <button type="submit">Submit</button>
            </form>
        </div>
        <div class="contact-info">
            <h2>Contact Information</h2>
            <p><strong>Address:</strong> 123 Main Street,Tiruvallur,Chennai</p>
            <p><strong>Email:</strong> virtutech@gmail.com</p>
            <p><strong>Phone:</strong>044-0804</p>
        </div>
    </div>
</body>
</html>
~~~
# conT.html

~~~
cont.css
*{
    margin: 0;
    padding: 0;
}

.main{
    width: 100%;
    background: linear-gradient(to top, rgba(124, 70, 115, 0.5)50%,rgba(207, 21, 21, 0.5)50%), url(1.jpg);
    background-position: center;
    background-size: cover;
    height: 100vh;
}

.navbar{
    width: 1200px;
    height: 75px;
    margin: auto;
}

.icon{
    width: 200px;
    float: left;
    height: 70px;
}

.logo{
    color: #5500dd;
    font-size: 35px;
    font-family: Arial;
    padding-left: 20px;
    float: left;
    padding-top: 10px;
    margin-top: 5px
}

.menu{
    width: 400px;
    float: left;
    height: 70px;
}

ul{
    float: left;
    display: flex;
    justify-content: center;
    align-items: center;
}

ul li{
    list-style: none;
    margin-left: 62px;
    margin-top: 27px;
    font-size: 14px;
}

ul li a{
    text-decoration: none;
    color: #fff;
    font-family: Arial;
    font-weight: bold;
    transition: 0.4s ease-in-out;
}

ul li a:hover{
    color: #ff7200;
}

.search{
    width: 330px;
    float: left;
    margin-left: 270px;
}

.srch{
    font-family: 'Times New Roman';
    width: 200px;
    height: 40px;
    background: transparent;
    border: 1px solid #ff7200;
    margin-top: 13px;
    color: #fff;
    border-right: none;
    font-size: 16px;
    float: left;
    padding: 10px;
    border-bottom-left-radius: 5px;
    border-top-left-radius: 5px;
}
.btn{
    width: 100px;
    height: 40px;
    background: #ff7200;
    border: 2px solid #ff7200;
    margin-top: 13px;
    color: #fff;
    font-size: 15px;
    border-bottom-right-radius: 5px;
    border-bottom-right-radius: 5px;
    transition: 0.2s ease;
    cursor: pointer;
}
.btn:hover{
    color: #000;
}

.btn:focus{
    outline: none;
}

.srch:focus{
    outline: none;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    background-color: #fff;
    display: flex;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    text-align: center;
}

.contact-form, .contact-info {
    padding: 20px;
    flex: 1;
}

.contact-form {
    text-align: left;
}

h1 {
    color: #333;
}

h2 {
    color: #333;
}

.form-group {
    margin: 10px 0;
}

input[type="text"],
input[type="email"],
textarea {
    width: 100%;
    padding: 10px;
    margin: 5px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
}

button {
    background-color: #007BFF;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #0056b3;
}
~~~
## OUTPUT:
# home.html:
![image](https://github.com/Selvakumar525/softweb/assets/120643262/e5989efe-13d5-44c7-a39b-df6525ec0340)

# people.html:
![image](https://github.com/Selvakumar525/softweb/assets/120643262/ffebfa81-80be-4856-acc9-8847bf9cf265)

# product.html:
![image](https://github.com/Selvakumar525/softweb/assets/120643262/40ed9f57-60bd-4b3f-ad8e-aa1406d65b35)

# contact.html:
![image](https://github.com/Selvakumar525/softweb/assets/120643262/db76663e-197b-441a-98ae-7923bc826638)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
