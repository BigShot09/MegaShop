# MegaShop
Megashop website

<!DOCTYPE html>
<html>
    <head>
        <title>MegaShop</title>
        <link rel="stylesheet" href="megashop.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
    </head>
    <body>
        
        <div class="styling-head">
            <p> Mega Shop<p>
        </div>

        <div class="button-holder">
            <ul>
                <li>Currency $</li>
                <li>My Account</li>
                <li>My Wallet</li>
                <li><a href="contact-us.html">Contact us</a></li>
                <li><a href="checkout.html">Checkout</a></li>
                <li><a href="log-in.html">Log in</a></li>
            </ul>
        </div>

        <div class="search-holder">
            <input class="search-bar" type="text" placeholder="Search">
        </div>

        <div class="menu-holder">
            <button class="menu-home"><a href="mega-shop.html">HOME</a></button>
            <button class="menu"><a href="shop.html">SHOP</a></button>
            <button class="menu"><a href="blog.html">BLOG</a></button>
            <button 
                class="menu" onclick="document.location='http://127.0.0.1:5500/practice.html'" ta> FAQ
            </button>
            <button class="menu"><a href="about-us.html">ABOUT US</a></button>
            <button class="menu"> <a href="contact-us.html">CONTACT US</a></button>
        </div>
        </div>

        <div class="faq-holder">
            <p class="faq"> FAQ</p>
        </div>

        <div class="second-search-holder">
            <input class="second-search" type="text" placeholder="Type to search">
        </div>

        <div class="paragraph">
            <p>
                why can't i cancel or get a refun fo my order on 'the Big Billcon day"? <button>+</button>
            </p>

            <p>
                What is 'My Account'? How do i update my information <button class="details">+</button>
            </p>
            
        </div>

     <div class="dropdown">
        <button>+</button>
        <div class="content">
            <p></p>
        </div>
     </div>       

       


    </body>
</html>

body {
    margin-left: 70px;
}

h1 {
    color: red;

}
    .styling-head {
    font-family: Arial, Helvetica, sans-serif;
    font-weight: 500;
    font-style: normal;
    font-size: 40px;
    color: rgb(201, 171, 5);
    cursor: pointer;
    display: inline-block;
  }
    
  .button-holder {
    display: inline-block;
    margin-left: 750px;
    margin-right: 0;
    background-color: rgb(235, 86, 32);
    
  }

  li {
    display: inline-block;
    padding: 10px 15px;
    font-weight: bold;
    transition: 1s;
    background-color: rgb(235, 86, 32);
    color: white;
    cursor: pointer;
    
  }
  li a{
    text-decoration: none;
    color: white;
  }

  li:hover {
    font-size: 23px;
    text-decoration: underline;

  }
  .buttons {
    font-size: 10px;
    margin-top: 0;
    color: white;
    background-color: rgb(235, 86, 32);
    border: none;
    padding-top: 15px;
    padding-bottom: 15px;
    padding-left: 12px;
    padding-right: 12px;
    transition: 0.5s;
    cursor: pointer;
    border-radius: 3px;
    margin-right: 0;
    
  }
  .search-holder {
    text-align: center;
    
   
  }

  .search-bar {
    padding-top: 12px;
    
    padding-bottom: 12px;
    padding-left: 18px;
    padding-right: 70px;
    border-radius: 3px;
    width: 250px;
    box-shadow: 3px 5px 10px rgba(0, 0, 0, 0.2);

  }
  .menu-holder {
    margin-top:  15px;
    margin-right: 0;
    margin-left: 0;
    
    border-top-style: solid;
    border-top-width: 4px;
    border-top-color: rgb(235, 86, 32);

  }
  .menu-home {
    background-color: rgb(235, 86, 32);
    color: white;
    border-top-color: rgb(235, 86, 32);
    font-size: 18px;
    padding: 20px;
    width: 160px;
    border-top-width: 5px;
    border-bottom: none;
    border-left: none;
    border-right: none;
  }
  .menu:hover {
    background-color: rgb(235, 86, 32);
    color: white;
    font-weight: 500;
  }
  a {
    text-decoration: none;
    color: black;
    font-weight: bold;
  }


  .menu {
    margin-left: 0;
    margin-right: 0;
    font-size: 18px;
    font-weight: bold;
    padding: 20px;
    transition: 1s;
    border: none;
    cursor: pointer;
    width: 160px;
  }
  .paragraph {
    display: block;
  }
  .paragraph button {
    border: none;
    background-color: red;
    font-size: 20px;
    font-weight: bold;
    margin-left: 250px;
    cursor: pointer;
    
  }
  .paragraph .details {
    background-color: blueviolet;

  }
  

  p {
    font-size: 20px;
    font-family: Arial, Helvetica, sans-serif;
    margin-top: 35px;
    margin-bottom: 45px;
    display: inline-block;
  }
  .faq-holder {
    display: inline-block;
    padding-right: 700px;
    font-weight: bold;
    border-bottom-style: solid;
    border-bottom-width: 10px;
    border-bottom-color: rgb(235, 86, 32);
    
    border-width: 3px;
  }
  
    

  .sign {
    font-weight: bold;
    margin-left: 100px;
    cursor: pointer;
  }

  .second-search-holder {
    display: inline-block;
    margin-left: 300px;
  }
  .second-search {
    padding: 10px;
    width: 210px;
  }

  <!DOCTYPE html>
<html>
    <head>
        <title>MegaShop</title>
        <link rel="stylesheet" href="contact-us.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
       
    </head>
    <body>
        
        <div class="styling-head">
            <p> Mega Shop<p>
        </div>

        <div class="button-holder">
            <ul>
                <li>Currency $</li>
                <li>My Account</li>
                <li>My Wallet</li>
                <li><a href="contact-us.html">Contact us</a></li>
                <li><a href="checkout.html">Checkout</a></li>
                <li><a href="log-in.html">Log in</a></li>
            </ul>
        </div>

        <div class="search-holder">
            <input class="search-bar" type="text" placeholder="Search">
            
        </div>

        <div class="menu-holder">
            <button class="menu-home"><a href="mega-shop.html">HOME</a></button>
            <button class="menu"><a href="shop.html">SHOP</a></button>
            <button class="menu"><a href="blog.html">BLOG</a></button>
            <button class="menu"><a href="FAQ.html"> FAQ</a></button>
            <button class="menu"><a href="about-us.html">ABOUT US</a></button>
            <button class="menu"> <a href="contact-us.html">CONTACT US</a></button>
        </div>

        <div class="champ">
            <div class="compare">
                <p>COMPARE PRODUCTS</p><hr>
                
                 <p class="item"> You have no items to compare</p>
                
            </div>
            
            <div class="contact">
                <p>Contact Us</p>
                <p class="info">Contact information</p>
            </div>
        </div>

        <div class="poll">
            <p>COMMUNITY POLL</p>

            <p class="fav">WHAT IS YOUR FAVOURITE COLOR</p>
            <hr>
            <input class="color" type="checkbox" >Green <br>
            <input class="color" type="checkbox" >Red<br>
            <input class="color" type="checkbox" >Black<br>
            <input class="color" type="checkbox" >Magenta
            <hr>
            <button class="vote"> Vote</button>
        </div>
        
        <div class="information">
            Name<span class="important">*</span><br><input type="text">
            Email<span class="important">*</span><input type="text">
            <br>
            Telephone<span class="important">*</span><br><input type="number">
            <br>
            Comment<span class="important">*</span><br><input class="comment"type="text">
        </div>
        
       
       
        


    </body>
</html>

body {
    margin-left: 100px;
    margin-right: 400px;
    
}


  
.styling-head {
    font-family: "Pacifico", system-ui;
    font-weight: 400;
    font-style: normal;
    font-size: 40px;
    color: rgb(201, 171, 5);
    cursor: pointer;
    display: inline-block;
  }
    
  .button-holder{
    display: inline-block;
    float: right;
    background-color: rgb(235, 86, 32);
    
  }

  li {
    display: inline-block;
    padding: 10px 15px;
    font-weight: bold;
    transition: 1s;
    background-color: rgb(235, 86, 32);
    color: white;
    cursor: pointer;
    
  }
  li a{
    text-decoration: none;
    color: white;
  }

  li:hover {
    font-size: 23px;
    text-decoration: underline;

  }
  .button {
    font-size: 10px;
    margin-top: 0;
    color: white;
    background-color: rgb(235, 86, 32);
    border: none;
    padding-top: 15px;
    padding-bottom: 15px;
    padding-left: 12px;
    padding-right: 12px;
    transition: 0.5s;
    cursor: pointer;
    border-radius: 3px;
    margin-right: 0;
    
  }
  .search-holder {
    text-align: center;
    margin-top: 15px;
    font-size: 20px;
    
  }

  form {
    margin-top: 20px;
  }

  .search-bar {
    margin-top: 15px;
    padding-top: 12px;
    padding-bottom: 12px;
    padding-left: 18px;
    padding-right: 70px;
    border-radius: 3px;
    width: 250px;
    box-shadow: 3px 5px 10px rgba(0, 0, 0, 0.2);

  }
  .menu-holder {
    margin-top:  15px;
    margin-right: 0;
    margin-left: 0;
    border-top-style: solid;
    border-top-width: 5px;
    border-top-color: rgb(235, 86, 32) ;

  }
  .menu-home {
    background-color: rgb(235, 86, 32);
    color: white;
    border-top-color: rgb(235, 86, 32);
    font-size: 18px;
    padding: 20px;
    width: 160px;
    border-top-width: 5px;
    border-bottom: none;
    border-left: none;
    border-right: none;
  }
  .menu:hover {
    background-color: rgb(235, 86, 32);
    color: white;
    font-weight: 500;
  }
  a {
    text-decoration: none;
    color: black;
    font-weight: bold;
  }


  .menu {
    margin-left: 0;
    margin-right: 0;
    font-size: 18px;
    font-weight: bold;
    padding: 20px;
    transition: 1s;
   border: none;
    width: 160px;
  }

  .compare {
    display: inline-block;
    border-style: solid;
    border-width: 1px;
    margin-top: 30px;
    width: 330px;
    height: 120px;
    margin-bottom: 0;
    
  }
  .compare p {
    background-color: rgb(214, 214, 214);
    padding: 13px;
    margin: 0;
  }
  .compare .item {
    background-color: white;
  }
  .contact {
    font-family: Arial, Helvetica, sans-serif;
    font-weight: bold;
    font-size: 20px;
    display: block;
    margin-top: 30px;
    padding-bottom: 80px;
    vertical-align: middle;
    margin-left: 180px;
  }
  .champ {
    display: grid;
    grid-template-columns: 200px 1fr;
    height: 180px;
  }

  .info {
    font-weight: normal;
    font-size: 15px;
    margin-top: 5px;
    padding: 7px;
    background-color: lightgrey;
    display: block;
  }

   .color {
    display: inline;
    
    
  }
  .poll {
    display: inline-block;
    width: 330px;
    border-style: solid;
    border-width: 1px;
    
    margin-right: 50px;
  }
  .poll p {
    padding-left: 8px;
    padding: 15px;
    font-family: Arial, Helvetica, sans-serif;
    background-color: rgb(214, 214, 214);
    margin: 0;
    font-size: 18px;
  }

  .poll .fav {
    
    font-size: 14px;
    background-color: white;
    padding: 12px;
    font-family: Arial, Helvetica, sans-serif;
  }

  .vote {
    background-color: rgb(235, 86, 32);
    color: white;
    font-size: 20px;
    padding: 5px 7px;
    float: right;
    border: none;
    margin-bottom: 12px;
    margin-right: 7%;
    font-family: Arial, Helvetica, sans-serif;
  }

  .information {
    display: inline-block;
    margin-top: 0;
    height: 200px;
    vertical-align: top;
    font-size: 20px;
    font-family: Arial, Helvetica, sans-serif;
    
  }

  .information input {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 25px;
    padding: 10px;
    margin-bottom: 6px;
  }
  
  .information .important {
    color: red;
  }
  .information .comment {
    width: 720px;
    height: 150px;
  }

  <!DOCTYPE html>
<html>
    <head>
        <title>MegaShop</title>
        <link rel="stylesheet" href="about-us.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
    </head>
    <body>
        
        <div class="styling-head">
            <p> Mega Shop<p>
        </div>

        <div class="button-holder">
            <ul>
                <li>Currency $</li>
                <li>My Account</li>
                <li>My Wallet</li>
                <li><a href="contact-us.html">Contact us</a></li>
                <li><a href="checkout.html">Checkout</a></li>
                <li><a href="log-in.html">Log in</a></li>
            </ul>
        </div>

        <div class="search-holder">
            <input class="search-bar" type="text" placeholder="Search">
            
        </div>

        <div class="menu-holder">
            <button class="menu-home">HOME</button>
            <button class="menu">SHOP</button>
            <button class="menu">BLOG</button>
            <button class="menu"> FAQ </button>
            <button class="menu">ABOUT US</button>
            <button class="menu"> CONTACT US</button>
        </div>

        <div class="about_us">
            <p> About Us</p>
        </div>
        
        <div class="second-search-holder">
            <input class="second-search" type="text" placeholder="Type to search">
            <hr>
            <p>125 * 125</p>
            <p>125 * 125</p>
            <p>125 * 125</p>
            <p>125 * 125</p>
        </div>

        <div class="site_info">
     <pre>
Its's nice of you to take your time to get to know us better. Here are some things about us that we thought you might like to know.
MegaShop went line in 2014 with the objective of making books easily available to anyone who had internet access. Today
we're present across various categories including movies, music, games, mobiles, cameras, computers, healthcare and 
personal products, home appliances and electronics, stationery, perfumes, toys, apparals, shoes - and still counting! Be it our
path-breaking services like Cash on Delivery a 30-day replament policy. EMI options, free shopping - and of course the great
prices that we offer, everything we do revolves around our obsession with providing our customers a memorable online
shopping experience. Then there's our dedicated Megashop delivery partners who work round the clock to personally make 
sure the packages reach on time. so it's no surprise that we're a favourite online shopping destination.  
     </pre>


        </div>
    </body>
</html>

body {
    margin-left: 70px;
    margin-right: 100px;
    
}
.styling-head {
    font-family: Arial, Helvetica, sans-serif;
    font-weight: 400;
    font-style: normal;
    font-size: 40px;
    color: rgb(201, 171, 5);
    cursor: pointer;
    display: inline-block;
}

.button-holder{
    display: inline-block;
    float: right;
    background-color: rgb(235, 86, 32);
    
  }

  li {
    display: inline-block;
    padding: 10px 15px;
    font-weight: bold;
    transition: 1s;
    background-color: rgb(235, 86, 32);
    color: white;
    cursor: pointer;
    
  }
  li a{
    text-decoration: none;
    color: white;
  }

  li:hover {
    font-size: 24px;
    text-decoration: underline;

  }
  .button {
    font-size: 22px;
    margin-top: 0;
    color: white;
    background-color: rgb(235, 86, 32);
    border: none;
    padding-top: 15px;
    padding-bottom: 15px;
    padding-left: 12px;
    padding-right: 12px;
    transition: 0.5s;
    cursor: pointer;
    border-radius: 3px;
    margin-right: 0;
    
  }
  .search-holder {
    text-align: center;
    margin-top: 15px;
    font-size: 20px;
    
  }

  form {
    margin-top: 20px;
  }

  .search-bar {
    margin-top: 15px;
    padding-top: 12px;
    padding-bottom: 12px;
    padding-left: 18px;
    padding-right: 70px;
    border-radius: 3px;
    width: 250px;
    box-shadow: 3px 5px 10px rgba(0, 0, 0, 0.2);
    border: none;

  }
  .menu-holder {
    margin-top:  15px;
    margin-right: 0;
    margin-left: 0;
    border-top-style: solid;
    border-top-width: 5px;
    border-top-color: rgb(235, 86, 32) ;

  }
  .menu-home {
    background-color: rgb(235, 86, 32);
    color: white;
    border-top-color: rgb(235, 86, 32);
    font-size: 18px;
    padding: 20px;
    width: 160px;
    border-top-width: 5px;
    border-bottom: none;
    border-left: none;
    border-right: none;
  }
  .menu:hover {
    background-color: rgb(235, 86, 32);
    color: white;
    font-weight: 500;
  }
  a {
    text-decoration: none;
    color: black;
    font-weight: bold;
  }


  .menu {
    margin-left: 0;
    margin-right: 0;
    font-size: 18px;
    font-weight: bold;
    padding: 20px;
    transition: 1s;
   border: none;
    width: 160px;
  }
  .about_us {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 20px;
    font-weight: bold;
    margin-top: 30px;
    border-bottom-style: solid;
    border-bottom-color:rgb(235, 86, 32);
    display: inline-block;
    margin-bottom: 15px;
    width: 790px;
    margin-right: 30px;
  }

  .second-search-holder {
    display: inline-block;
    margin-left: 45px;
    width: 100px;
    vertical-align: top;
  }

  .second-search-holder p {
    color: black;
    margin-bottom: 2px;
    margin-left: 6px;
    padding: 40px;
    width: 70px;
    display: inline-block;
    border-style: solid ;

  }
  hr{
    width: 315px;
    margin-bottom: 27px;
  }
  .second-search {
    
    padding: 6px;
    width: 300px;
    margin-top: 30px;
    margin-bottom: 26px;
  }
  pre {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 14px;
    width: 780px;
    margin-right: 45px;
    display: inline-block;
    
  }

  .site_info {
    display: inline-block;
  }
