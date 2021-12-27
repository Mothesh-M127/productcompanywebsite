# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

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

### Step 6:

Publish the website in the given URL.

## PROGRAM :
1. Home Page
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Atom workshop</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/m2.png" type="image/x-icon" />
  </head>

  <body>
    
    <div class="banner">ATOMWORKSHOP</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="./people.html">People</a></div>
        <div class="menuitem"><a href="./contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/walll.png" alt="walll" />
          <div class="contenttext">
            MIE conducts well-planned workshops on various topics – right from career guidance workshops for different streams to workshops on real issues that one comes across in their professional life. Conducted by experts, these workshops are a great way for students of professional courses to be better prepared and make better choices.

            Some of our Atom tracks are: 
            Career in Data Science and Analytics
            B2B Marketing
            Leadership Management and Decision Science
            Hedge Fund Walkthrough
            Investment Banking 
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Atom Workshop, Developed by Mothesh.
      </div>
    </div>
  </body>
</html> 
```
2. Product Page:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Atom Workshop</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/m2.png" type="image/x-icon"/>
  </head>

  <body>
    
    <div class="banner">ATOMWORKSHOP</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="img/m2.jpeg" alt="product image">
                  </div>
                  <div class="itemname">arduino Projects</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="img/images.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">robotics</div>
                  <div class="itemprice">Price: Rs.20,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="img/m4.jpeg"  alt="product image">
                </div>
                <div class="itemname">iot car</div>
                <div class="itemprice">Price: Rs.12,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="img/m5.jpeg"  alt="product image">
                </div>
                <div class="itemname">arduino robot</div>
                <div class="itemprice">Price: Rs.8,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="img/m6.jpeg"  alt="product image">
                </div>
                <div class="itemname">arduino robots</div>
                <div class="itemprice">Price: Rs.7,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="img/m7.jpeg"  alt="product image">
                </div>
                <div class="itemname">smart robot</div>
                <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="img/m8.jpeg"  alt="product image">
                </div>
                <div class="itemname">arduino robot</div>
                <div class="itemprice">Price: Rs.15,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="img/m9.jpeg" alt="product image">
                </div>
                <div class="itemname">iot robot</div>
                <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem">
                <div class="itemimage">
                <img src="img/m10.jpeg"  alt="product image">
                </div>
                <div class="itemname">robotics</div>
                <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem">
                <div class="itemimage">
                <img src="img/m11.jpeg"  alt="product image">
                </div>
                <div class="itemname">sensor dustbin</div>
                <div class="itemprice">Price: Rs.23,000.00 </div>
              </div>
              <div class="productitem">
                <div class="itemimage">
                <img src="img/m12.jpeg"  alt="product image">
                </div>
                <div class="itemname">panzer robot</div>
                <div class="itemprice">Price: Rs.15,000.00 </div>
              </div>

          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 ATOMWORKSHOP., Developed by Mothesh.
    </div>
  </body>
</html>
```
3. People Page:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Atom Workshop</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/m2.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">ATOMWORSHOP</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Team Members</h1>
          <div class="productitems">
            <div class="productitem"> 
                  <div class="itemimage">
                  <img src="img/stevechenlan.jpeg" alt="product imoage">
                  </div>
                  <div class="itemname">Steve chenlan</div>
                  <div class="itemprice"> Founder </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="img/mothi.jpeg" alt="product imoage">
                </div>
                <div class="itemname">Mothesh</div>
                <div class="itemprice"> Cheif Executive Officer</div>
            </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="img/rd.jpeg" alt="product imoage">
                  </div>
                  <div class="itemname">Joseph Cruel</div>
                  <div class="itemprice">Research Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="img/tim.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Tim Cook</div>
                  <div class="itemprice">Design Director </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="img/ste.jpeg" alt="product imoage">
                </div>
                <div class="itemname">Stefen salvatore</div>
                <div class="itemprice">Training Department Head </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="img/vic.jpeg" alt="product imoage">
              </div>
              <div class="itemname">Victoria Silva</div>
              <div class="itemprice">Web Organiser</div>
          </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 ATOMWORKSHOP., Developed by Mothesh.
      </div>
    </div>
  </body>
</html>
```
4. Contact Page:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Atom Workshop</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/m2.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">ATOMWORKSHOP</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/Contact.html">Contact Us</a></div>
      </div>
      <div class="content">
            <div class="productcontent">    
                <h1>CONTACT US</h1>
                <div class="productitems">
                    <div class="productitem"> 
                            <h2>INDIA</h2><br>
                        <div class="conadd">ATOMWORKSHOP<br>
                            <br>
                            CIN - L72200MH1995PLC091408, Marvel Edge,<br>
                            Office No.7010 C & D, 7th Floor, Viman Nagar,<br>
                            Pune 411014, Maharashtra, India<br></div>
                            <br>
                            <div class="connum">Mobile: +91 9710745354 </div><br>
                            <div class="conem">Email: mothesh1201@gmail.com</div>
                    </div>        
                </div>
        <div class="footer">
                    Copyright &#169; 2021 ATOMWORKSHOP., Developed by Mothesh.
        </div>
    </div>
        </body>
      </html>
```
5. CSS Worksheets:
```
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #422a17;
}

.banner {
  display: inline-block;
  width: 100px;
  height: 100px;
  text-align: left;
  font-family: colonna MT;
  font-size: 80px;
  background-image: url("./m2.png");
  background-position: left;
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 10px;
  padding-left: 100px;
  display: block;
  color: #127998;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #127998;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: whitesmoke;
}

.menuitem a {
  text-decoration: none;
  color: whitesmoke;
}

.content {
  display: block;
  width: 100%;
  background-color: #cffffd;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #127998;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: whitesmoke;
}
```
## OUTPUT:

### Home Page:

![homepage](https://user-images.githubusercontent.com/94170892/147434085-49018b5c-e910-41f3-b5cd-437f3bcb82b0.png)


### Product Page:

![product](https://user-images.githubusercontent.com/94170892/147434099-83aaaf78-7f20-4032-baa7-2d7b6ac4a098.png)

### People Page:

![people](https://user-images.githubusercontent.com/94170892/147434112-d1970fe9-f957-49a3-aa58-515e4106f3f6.png)

### Contact Us:
![contact](https://user-images.githubusercontent.com/94170892/147434126-fa4e2ab1-a525-4d00-8e34-bdf6323592da.png)


## Result:\

Thus a website is designed for the software product company and the HTML,CSS code are validated.
