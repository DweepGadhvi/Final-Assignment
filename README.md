<!DOCTYPE html>
<html lang="en">
<head>
<title>Page Title</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}
html{
    background-color:rgb(255, 99, 71);
  color:dark rgb(255,255,255);
}
/* Style the body */
body {
  font-family:'Times New Roman', Times, serif;
  margin: 0;
 background-color:rgb(255, 99, 71);
  color:dark rgb(255,255,255);
}

/* Header/logo Title */
.header {
  padding: 80px;
  text-align: center;
  background: #A1BDA4;
  color: white;
}

/* Increase the font size of the heading */
.header h1 {
  font-size: 40px;
}

/* Style the top navigation bar */
.navbar {
  overflow: hidden;
  background-color: rgb(255, 255, 255);

}

/* Style the navigation bar links */
.navbar a {
  float: left;
  display: block;
  color: rgb(128, 128, 0);
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

/* Right-aligned link */
.navbar a.right {
  float: center
  ;
}

/* Change color on hover */
.navbar a:hover {
  background-color:rgb(196, 160, 196);
  color:rgb(130, 38, 217);
}

/* Column container */
.row {  
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
  background-color: pink;
}

/* Create two unequal columns that sits next to each other */
/* Sidebar/left column */
.side {
  -ms-flex: 30%; /* IE10 */
  flex: 30%;
  background-color: #BA7B7D;
  padding: 10px;
  font: size 100px;
}

/* Main column */
.main {   
  -ms-flex: 70%; /* IE10 */
  flex: 70%;
  background-color: rgb(255, 255, 255);
  padding: 20px;
  background-color: rgb(161, 189, 164);
}

/* Fake image, just for this example */
.fakeimg {
  background-color: rgb(161, 189, 164);
  width: 100%;
  padding: 20px;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background:rgb(186, 123, 125);
}
/* CSS for form */
form {
    margin-top: 20px;
    }
    label {
    display: block;
    margin-bottom: 2px;
}

/* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 700px) {
  .row {   
    flex-direction: column;
  }
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 400px) {
  .navbar a {
    float: none;
    width: 100%;
  }
}
</style>
</head>
<body>

<div class="header">
  <h1>Red Swan Pizza</h1>
  <p>Pizza varities</p>
</div>

<div class="navbar">
  <a href="#" class="menu">MENU</a>
  <a href="#" class="contact">Contact Us</a>
  <a href="#" class="about">About Us</a>
  <a href="#" class="right">Work With Us</a>
</div>

<div class="row">
  <div class="side">
    <h2>About us</h2>
    <h5>WE located in the Brampton region </h5>
    <div class="img" style="height:200px;">
            <img src="Images/Red-Swan-Pizza__shop.jpg" alt="our branch" width="300" height="200">
    </div>
    <p>Red Swan is a pizza store located all across Canada. We believe in our core value systems which are Taste, Service and Quality. These are non-negotiable and will not be compromised in Red Swan Pizza. Customer satisfaction is utmost priority for us and we are always open to hear what our customer has to say.</p>
    <h3></h3>
    
    <div class="fakeimg" ><img src="Images/three-cheese Pizza.jpg" width="200" height="200"></div><br>
    <div class="fakeimg" ><img src="Images/spicy-paneer Pizza.jpg" width="200" height="200"></div><br>
    <div class="fakeimg" ><img src="Images/spicy-ginger-cilantro Pizza.jpg" width="200" height="200"></div>
    <form><h7>Contact List</h7>
        <div><label for="input1">Your name:</label>
        <input type="text" id="input1" name="Your name"><br>
      
        <label for="input2">Your email:</label>
        <input type="text" id="input2" name="Your email"><br>
      
        <label for="input3">Your message:</label>
        <input type="text" id="input3" name="your message"><br>
      
        <input type="submit" value="Submit">
        <input type="cancel" value="cancel"></div>
      </form>
  </div>
 
  <div class="main">
   
    <img src="Images/another branch.jpg" alt="Another branch" width="250" height="250">
    
    <h2>MENU</h2>
    <h3>Veg Options</h3>
    <img src="Images/italian-supreme veg pizza.jpg" width="300" height="300">
    <p>Italian Supreme Pizza<br>
      
        <div>
    <h2>Non-Veg Option</h3>
    <img src="Images/pepperoni Pizza.jpg" width="300" height="300">
    <p> Pepperoni pizza<br>
  
</div>
<div class="footer">
  <h2>First Location</h2>
    <p><iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d11525.629931282192!2d-79.6697448!3d43.7643996!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x882b3d94256d8225%3A0xb50e5616aaa1e0e1!2sRed%20Swan%20Pizza!5e0!3m2!1sen!2sca!4v1701818159287!5m2!1sen!2sca" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe></p>

    <h2>Second Location</h2>
    <p><iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d11521.020821324617!2d-79.4711967!3d43.7883172!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x882b2f967b22ab37%3A0x3c7df4537834bd60!2sRed%20Swan%20Pizza!5e0!3m2!1sen!2sca!4v1701819968682!5m2!1sen!2sca" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe></p>
</div>

</body>
</html>
