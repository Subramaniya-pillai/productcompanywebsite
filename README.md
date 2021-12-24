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
HOME PAGE:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/Contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/down1.png" alt="Building" />
          <div class="contenttext">
            Turbo Energy Private Limited (TEL) was incorporated in the year 1982 as a joint venture company between Brakes India Private Limited, Sundaram Finance Limited and BorgWarner Turbo Systems.
            <br />
            TEL is a pioneer and the largest manufacturer of turbochargers in India. With over 60% market share, the company achieved a gross sales turnover of INR 12,768 million in FY20-21.

The Engineering R&D centre which was established in 1985, is recognized by the Department of Scientific and Industrial Research, Government of India. The Centre designs and develops components, applicate turbochargers, conducts simulation, testing and validation in-house.

TEL has four manufacturing locations with the capacity to produce 1.8 million turbochargers and 5 million turbocharger components per year. TEL is the most backward integrated turbocharger manufacturer ensuring consistent quality and reliable supply.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by SUBRAMANIYA PILLAI.B
      </div>
    </div>
  </body>
</html>
```


PRODUCT PAGE:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/Contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>TURBO CHARGER TECHNOLOGIES</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro1.png" alt="product image">
                  </div>
                  <div class="itemname">REGULATED TWO STAGE</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro2.png"  alt="product image">
                  </div>
                  <div class="itemname">VARIABLE TURBINE GEOMENTRY</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/pro3.png"  alt="product image">
                </div>
                <div class="itemname">GASOLINE WG</div>
                <div class="itemprice">Price: Rs.10,000.00 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/pro4.png"  alt="product image">
              </div>
              <div class="itemname">GASOLINE VTG</div>
              <div class="itemprice">Price: Rs.10,000.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/pro5.png"  alt="product image">
            </div>
            <div class="itemname">WASTE GATE</div>
            <div class="itemprice">Price: Rs.10,000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/pro6.png"  alt="product image">
          </div>
          <div class="itemname">NON WASTE GATE</div>
          <div class="itemprice">Price: Rs.10,000.00 </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/pro7.png"  alt="product image">
        </div>
        <div class="itemname">E BOOSTER</div>
        <div class="itemprice">Price: Rs.10,000.00 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/pro8.png"  alt="product image">
      </div>
      <div class="itemname">TC FOR SMALL ENGINES</div>
      <div class="itemprice">Price: Rs.10,000.00 </div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="/static/img/pro9.png"  alt="product image">
    </div>
    <div class="itemname">WATER COOLED TURBO CHARGER</div>
    <div class="itemprice">Price: Rs.10,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/pro20.png"  alt="product image">
  </div>
  <div class="itemname">water cooled bearings</div>
  <div class="itemprice">Price: Rs.10,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/pro21.png"  alt="product image">
  </div>
  <div class="itemname">TWIN SCROLL TURBO</div>
  <div class="itemprice">Price: Rs.10,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/pro22.png"  alt="product image">
  </div>
  <div class="itemname">MONO SCROLL TURBO</div>
  <div class="itemprice">Price: Rs.10,000.00 </div>
</div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by SUBRAMANIYA PILLAI.B
      </div>
    </div>
  </body>
</html>
```
PEOPLE PAGE:
```
<head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/Contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>OUR TEAM MEMBERS</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro11.png" alt="product image">
                  </div>
                  <div class="itemname">BOOMINATHAN.S</div>
                  <div class="itemprice">CEO </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro19.png"  alt="product image">
                  </div>
                  <div class="itemname">NAVEEN</div>
                  <div class="itemprice">GENERAL MANAGER </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/pro13.png"  alt="product image">
                </div>
                <div class="itemname">SIVA</div>
                <div class="itemprice">TEAM LEADER </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/pro14.png"  alt="product image">
              </div>
              <div class="itemname">GOKUL ANAND</div>
              <div class="itemprice">PRODUCTION MANAGER</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/pro15.png"  alt="product image">
            </div>
            <div class="itemname">KATHIR KUMAR</div>
            <div class="itemprice">PLAN EXECUTOR</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/pro16.png"  alt="product image">
            </div>
            <div class="itemname">SASIDHAR</div>
            <div class="itemprice">MOP CLEANER</div>
          </div>

          

          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by SUBRAMANIYA PILLAI.B
      </div>
    </div>
  </body>
</html>
```
CONTACTS PAGE:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>TURBO ENERGY PRIVATE LIMITED</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/pro18.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/Contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>For Further Details:</h1>
          <img src="/static/img/pro26.png" alt="BUILDING">
          <div class="contenttext">
            ADDRESS
Registered Office
Turbo Energy Private Limited,
67 Chamiers Road, Chennai- 600028

CIN
U40107TN19IOTWOI239363

PLANT ADDRESS
            <br>
            Contact NO: 9600191888
            <br>
            Landline: 911 8375 6789
            <br>
            Our Email: marketing@turboenergy.co.in
         </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 PACIFIC TECHNOLOGIES PVT LTD, Developed by SUBRAMANIYA PILLAI.B
      </div>
    </div>
  </body>
</html>
```


## OUTPUT:

### Home Page:

![output](./images/homepage.png)

### productpage:
![output](./images/product.png)

### People's page:
![output](./images/peoplepage.png)

### Contact's page:
![output](./images/contactpage.png)



## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
