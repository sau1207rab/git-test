
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Dash Groceries</title>
    <link rel="stylesheet" href="CSS/stylesheet.css">
  </head>
  <body>
    <div class="nav-wrapper">
      <nav>
        <ul class="nav-list">
          <li class="nav-item"><a href="index.html">Home</a></li>
          <li><a href="#">Login</a></li>
          <li><a href="#">Order Online</a></li>
          <li><a href="#">About Us</a></li>
        </ul>
      </nav>
    </div>

<div class="image-holder">
  <img class="background-img" src="images\bg-image.png" width="100%" alt="Bg Img">
  <h1 id="caption-1">GROCERY SHOPPING DONE ONLINE</h1>

</div>

<h1 id="pop-cat">POPULAR CATEGORIES</h1>
<hr width="1300">

<div class="featured-wrapper">

 <div class="product-container">
    <p class="cat-text">Dairy Products</p>
    <img src="images\dairy.jpg" alt="Dairy" width="400">
    <div class="btn-container">
      <button class="view-more-btn" type="button" name="button">VIEW MORE</button>
    </div>
 </div>


 <div class="product-container">
    <p class="cat-text">Cold Meat</p>
    <img src="images\cold-meat.jpg" alt="Dairy" width="400">
    <div class="btn-container">
      <button class="view-more-btn" type="button" name="button">VIEW MORE</button>
    </div>
 </div>

  <div class="product-container">
    <p class="cat-text">Fruits and Veg</p>
    <img src="images\fruit-veg.jpg" alt="Dairy" width="400">
    <div class="btn-container">
      <button class="view-more-btn" type="button" name="button">VIEW MORE</button>
    </div>
  </div>

 </div>


<div id="social-media-container" background-color="#00000">
    <div id="facebook-icon-container" background-color=>
      <img src="images/icons/facebook-icon.png">
    </div>

    <div id="instagram-icon-container" href="instagram.com/saurabh.kushwh">
      <img src="images/icons/instagram-icon.png">
    </div>

    <div id="twitter-icon-container">
      <img src="images/icons/twitter-icon.png">
    </div>
</div>

<br>

<div class="form-container">
  <div id="form-head-container">
    <img id="email-icon" src="images/email-icon.png">
    <p id="contact-us-label">Contact Us</p>
  </div>

  <form action="">
    <label class="form-item" for="fname">First Name</label>
    <input type="text" id="fname" name="firstname" placeholder="Your name">
      <br><br>

    <label class="form-item" for="lname">Last Name</label>
    <input type="text" id="lname" name="lastname" placeholder="Your last name">
    <br><br>

    <label class="form-item" for="subject">Subject</label>
    <textarea id="subject" name="subject" placeholder="How can we help?"></textarea>
    <br><br>
    <input type="submit" id="submit-btn" value="submit">

  </form>

</div>

 </body>
</html>
