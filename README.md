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

### CSS:
~~~
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: black;
  color: black;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px grey;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("https://www.pngmagic.com/product_images/light-blue-background-hd.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: black;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: grey;
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
  color: #004445;
}

.menuitem a {
  text-decoration: none;
  color: white;
}

.content {
  display: block;
  width: 100%;
  background-image:url("https://i.pinimg.com/originals/9f/c3/48/9fc348296d65884f53a7d82ca54afa13.jpg");
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
  color: green;
  background-repeat: no-repeat;
  background-size: 100% 100%;

}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
  color: green;
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
  color: brown;
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
  color: brown;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
  color: brown;
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
  background-color: grey;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: white;
}
~~~

### Home Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>TopCO Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">TopCO Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/logo.png" alt="logo" />
          <div class="contenttext">
            We TopCO pvt.ltd provide many original products for low prices than than the original prices.
            We are the best to provide you many products to make your work easy. 
            <br />
            All the products are verified and original. All the products will be shipped to your home or 
            college or office within 3 days all over India and will be shipped in 5 days for Overseas.
            <ul>
              <li>All Original Products</li>
              <li>Easy to buy</li>
              <li>Can Cancel before 3 days</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 TopCO Private Limited, Developed by Dhivya Shri.
      </div>
    </div>
  </body>
</html>
~~~

### Product Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>TopCO Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">TopCO Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"> <a href="/static/products.html">Products</a> </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://rukminim1.flixcart.com/image/832/832/kj7gwi80/gamingconsole/t/v/v/cfi-1008a01r-825-sony-no-original-imafytxe7twjskbx.jpeg?q=70"  alt="product image">
                  </div>
                  <div class="itemname">PlayStation 5</div>
                  <div class="itemprice">Price: Rs.49,999 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://rukminim1.flixcart.com/image/832/832/ktketu80/mobile/c/g/4/iphone-13-pro-max-mlll3hn-a-apple-original-imag6vpg3r7dyvhm.jpeg?q=70"  alt="product image">
                  </div>
                  <div class="itemname">Iphone 13 Pro Max</div>
                  <div class="itemprice">Price: Rs.1,59,900 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://rukminim1.flixcart.com/image/832/832/kg8avm80/mobile/r/h/z/apple-iphone-12-dummyapplefsn-original-imafwg8dqgncgbcb.jpeg?q=70" alt="product image">
                </div>
                <div class="itemname">Iphone 12</div>
                <div class="itemprice">Price: Rs.51,990 </div>
              </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://rukminim1.flixcart.com/image/832/832/kjvrdzk0/mobile/y/n/z/samsung-galaxy-s21-ultra-sm-g998bzsginu-original-imafzchbfk4zg9ga.jpeg?q=70"  alt="product image">
              </div>
              <div class="itemname">Samsung S21 Ultra</div>
              <div class="itemprice">Price: Rs.1,05,990 </div>
            </div>
            <div class="productitem"> 
            <div class="itemimage">
            <img src="https://rukminim1.flixcart.com/image/832/832/k6mibgw0/mobile/j/z/b/samsung-galaxy-s20-ultra-sm-g988bzapinu-original-imafpfkb6mkgyegk.jpeg?q=70"  alt="product image">
            </div>
            <div class="itemname">Samsung S20 Ultra</div>
            <div class="itemprice">Price: Rs.97,889 </div>
            </div>
          <div class="productitem"> 
          <div class="itemimage">
          <img src="https://rukminim1.flixcart.com/image/832/832/ksnjp8w0/mobile/b/t/k/galaxy-z-fold3-5g-sm-f926bzkdinu-samsung-original-imag662a7zgxn2fv.jpeg?q=70"  alt="product image">
          </div>
          <div class="itemname">Samsung Z Fold 3</div>
          <div class="itemprice">Price: Rs.1,57,999 </div>
          </div>
          <div class="productitem"> 
          <div class="itemimage">
          <img src="https://rukminim1.flixcart.com/image/832/832/ksnjp8w0/mobile/w/u/8/galaxy-z-flip3-5g-sm-f711bzeeinu-samsung-original-imag662adrayy6cg.jpeg?q=70"  alt="product image">
          </div>
          <div class="itemname">Samsung Flip 3</div>
          <div class="itemprice">Price: Rs.84,999</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://rukminim1.flixcart.com/image/832/832/kqjtd3k0/screen-guard/screen-guard/g/s/0/apple-macbook-pro-m1-somtone-original-imag4jhqaxbprrgx.jpeg?q=70"  alt="product image">
          </div>
          <div class="itemname">Macbook Pro</div>
          <div class="itemprice">Price: Rs.1,12,999 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://rukminim1.flixcart.com/image/832/832/khdqnbk0/computer/5/d/e/apple-original-imafxfyqkdfxqjab.jpeg?q=70"  alt="product image">
          </div>
          <div class="itemname">Macbook Air</div>
          <div class="itemprice">Price: Rs.1,09,999 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://rukminim1.flixcart.com/image/832/832/kpinwy80/headphone/r/1/q/mwp22hn-a-apple-original-imag3qe9eqkfhmg8.jpeg?q=70"  alt="product image">
          </div>
          <div class="itemname">Airpods Pro</div>
          <div class="itemprice">Price: Rs.24,999 </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="https://rukminim1.flixcart.com/image/832/832/kigbjbk0-0/headphone/n/z/m/mgyl3hn-a-apple-original-imafy8wb7tuduaf2.jpeg?q=70"  alt="product image">
        </div>
        <div class="itemname">Airpods Max</div>
        <div class="itemprice">Price: Rs.59,999 </div>
      </div>
      <div class="productitem"> 
      <div class="itemimage">
      <img src="https://rukminim1.flixcart.com/image/832/832/kp036vk0/headphone/d/d/2/galaxy-ear-buds-pro-samsung-original-imag3c9egbuzfzbd.jpeg?q=70"  alt="product image">
      </div>
      <div class="itemname">Samsung Galaxy Buds Pro</div>
      <div class="itemprice">Price: Rs.16,999 </div>
      </div>
      </div>
          </div>        
        </div>
      <div class="footer">
        Copyright &#169; 2021 TopCO Private Limited, Developed by Dhivya Shri.
      </div>
    </div>
  </body>
</html>
~~~

### People Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>TopCO Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">TopCO Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Council Members</h1>
          <div class="productitem"> 
          <div class="itemimage">
          <img src="http://t2.gstatic.com/licensed-image?q=tbn:ANd9GcS98QZPZ9v8G8Iv8bL3XPKjVAfUd6EMDcHptU3Nbap0dphboyQD6bs7Ki1utMdM"  alt="product image">
          </div>
          <div class="itemname">Tim Cook</div>
          <div class="itemprice">CEO</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://upload.wikimedia.org/wikipedia/commons/3/34/Elon_Musk_Royal_Society_%28crop2%29.jpg"  alt="product image">
          </div>
          <div class="itemname">Elon Musk</div>
          <div class="itemprice">MD</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://thumbor.forbes.com/thumbor/fit-in/416x416/filters%3Aformat%28jpg%29/https%3A%2F%2Fspecials-images.forbesimg.com%2Fimageserve%2F5babb7f1a7ea4342a948b79a%2F0x0.jpg%3Fbackground%3D000000%26cropX1%3D748%26cropX2%3D3075%26cropY1%3D1753%26cropY2%3D4082"  alt="product image">
          </div>
          <div class="itemname">Warren Buffett</div>
          <div class="itemprice">VP of Marketing</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://upload.wikimedia.org/wikipedia/commons/1/18/Mark_Zuckerberg_F8_2019_Keynote_%2832830578717%29_%28cropped%29.jpg"  alt="product image">
          </div>
          <div class="itemname">Mark Zucekrberg</div>
          <div class="itemprice">Cheif Architect</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="https://pbs.twimg.com/profile_images/669103856106668033/UF3cgUk4_400x400.jpg"  alt="product image">
        </div>
        <div class="itemname">Jeff Bezos</div>
        <div class="itemprice">Project Manager</div>
      </div>
      <div class="productitem"> 
      <div class="itemimage">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT2e7Bf6unlr5OvcEkyFTLrJcjs0bHsDS-VlbIkbDXVQXu0c7n-T0SuICk-egXXHJaky54&usqp=CAU"  alt="product image">
      </div>
      <div class="itemname">Bill Gates</div>
      <div class="itemprice">Technical Lead</div>
      </div>
      </div>
          </div>        
        </div>
      <div class="footer">
        Copyright &#169; 2021 TopCO Private Limited, Developed by Dhivya Shri.
      </div>
    </div>
  </body>
</html>
~~~

### Contact Us Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>TopCO Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">TopCO Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us</h1>
          <img src="./img/logo.png" alt="Logo" />
          <div class="contenttext">
            Email: topcopvtltd@gmail.com
            <br>
            Phone: +919256895098
            <br>
            Address: High Hills Road , Panja Gutta , Mumbai 400004

          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 TopCO Private Limited, Developed by Dhivya Shri.
      </div>
    </div>
  </body>
</html>
~~~

## OUTPUT:

### Home Page:

![output](./home.png)

### Product Page:

![output](./product1.png)
![output](./product2.png)

### People Page:

![output](./people.png)

### Contact Us Page:

![output](./contactus.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.

