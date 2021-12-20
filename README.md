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
### Home Page:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Rockstar Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/download.png" type="image/x-icon" />
  </head> 
  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/People.html">People</a></div>
        <div class="menuitem"><a href="/static/Contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>

          <div class="slider">
            <div class="slides">
              <input type="radio" id="radio1" name="radios">
              <input type="radio" id="radio2" name="radios">
              <input type="radio" id="radio3" name="radios">
              <div class="slide first">
                  <img src="./img/rdr.png">                
              </div>
              <div class="slide">
                <img src="./img/gta5.png">                
            </div>
            <div class="slide">
              <img src="./img/gta4.png">                
            <div class="auto">
              <div class="auto1"></div>
              <div class="auto2"></div>
              <div class="auto3"></div>

            </div>
        
             </div>
             <div class="manual">
               <label for="radio1"class="manuals"></label>
               <label for="radio2"class="manuals"></label>
               <label for="radio3"class="manuals"></label>
             </div>
            </div>

          </div>
          <div class="contenttext">
            <b>The Rockstar Games label was founded in 1998 to create the most innovative and progressive interactive entertainment. It is a wholly owned subsidiary of Take-Two Interactive Software, Inc.</b>

            <br>       <b>     Rockstar Games welcomes input from the gaming community. However, any submissions to Rockstar Games of any nature whatsoever, whether through this site or otherwise, and whether via electronic or other mean, become the sole and exclusive property of Rockstar Games, which shall have full right, title and interest thereto, including under copyright, in all media now existing or hereafter created, and without any obligation to account or make any payment to the submitter for any use thereof. No purported reservation of rights incorporated in or accompanying any submission shall have any force or effect. By making a submission to Rockstar Games, you hereby agree to all of the foregoing.</b> </br>
             <br><b>You buy the rockstar games in our website in products.</b> </br>
          
          </div>
      </div>

      <div class="footer">
        Copyright &#169; 2021 Rockstar Private Limited, Developed by Nithiswar
         s
      </div>
      <div><h2><marquee>Thank For Visiting Our Page</marquee</h2></div>

    </div>
  </body>
</html>


### products page:
  
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Rockstar Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/download.png" type="image/x-icon" />
  </head>
  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/People.html">People</a></div>
        <div class="menuitem"><a href="/static/Contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>LASTEST Games</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/rdr.png" alt="product image">
                  </div>
                  <div class="itemname">Red Dead Redemption 2
                  </div>                
                  <div class="itemprice">price:$3,999 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/gta5.png"  alt="product image">
                  </div>
                  <div class="itemname">Grand Theft Auto V
                  </div>
                  <div class="itemprice">price:$2,999 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/gta4.png"  alt="product image">
                </div>
                <div class="itemname">Grand Theft Auto IV
                </div>
                <div class="itemprice">price:$999 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/rdr1.png" alt="product image">
              </div>
              <div class="itemname">Red Dead Redemption 
              </div>                
              <div class="itemprice">price:$2,499 </div>
          </div>
          <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/gta3.png"  alt="product image">
              </div>
              <div class="itemname">Grand Theft Auto III
              </div>
              <div class="itemprice">price:$499 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/gtasa.png"  alt="product image">
            </div>
            <div class="itemname">Grand Theft Auto :San Andreas
            </div>
            <div class="itemprice">price:$999 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/gtavc.png" alt="product image">
          </div>
          <div class="itemname">Grand Theft Auto :Vice City
          </div>                
          <div class="itemprice">price:$399 </div>
      </div>
      <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/bully.png"  alt="product image">
          </div>
          <div class="itemname">Bully
          </div>
          <div class="itemprice">price:$999 </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/gtalcs.png"  alt="product image">
        </div>
        <div class="itemname">Grand Theft Auto :Liberty City Stories
        </div>
        <div class="itemprice">price:$999 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/rdo.png" alt="product image">
      </div>
      <div class="itemname">Red Dead Online
      </div>                
      <div class="itemprice">price:$2,999 </div>
  </div>
  <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/mh2.png"  alt="product image">
      </div>
      <div class="itemname">Man Hunt 2
      </div>
      <div class="itemprice">price:$2,599 </div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="/static/img/mp3.png"  alt="product image">
    </div>
    <div class="itemname">Max Payne 3

    </div>
    <div class="itemprice">price:$1,999 </div>
</div>
            
            </div>
          </div>
          </div> 
          <div class="footer">
            Copyright &#169; 2021 Rockstar Private Limited, Developed by Nithiswar
             s
          </div>
          <div><h2><marquee>Thank For Visiting Our Page</marquee</h2></div>    
      </div>
      

    </div>
    
  </body>
</html>

### people pages:
  
  
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Rockstar Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/download.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a>
        </div>
        <div class="menuitemselected"><a href="/static/People.html">People</a></div>

        <div class="menuitem"><a href="/static/Contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Board of Directors</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/nithish.png" alt="product image">
                  </div>
                  <div class="itemname">NITHISHWAR</div>
                  <div class="itemprice">Executive Chairman </div>
              </div>

              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/ashwin.png"  alt="image">
                </div>
                <div class="itemname">Ashwin</div>
                <div class="itemprice"> President and CEO </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/jeeva.png"  alt="image">
              </div>
              <div class="itemname">Jeeva</div>
              <div class="itemprice">Group President and COO</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/kirupa.png"  alt="image">
            </div>
            <div class="itemname">Kirupanandhan </div>
            <div class="itemprice">Senior vice president and general counsel</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/manoj.png"  alt="image">
          </div>
          <div class="itemname">Manoj kumar</div>
          <div class="itemprice">senior vice president : Internet Software and Services</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/sham.png"  alt="image">
        </div>
        <div class="itemname">Sham Rathan</div>
        <div class="itemprice">vice president and managing director :  Greater China</div>
    </div>
              </div>
              <div class="footer">
                Copyright &#169; 2021 Rockstar Private Limited, Developed by Nithiswar
                 s
              </div>    
              <div><h2><marquee>Thank For Visiting Our Page</marquee</h2></div>
          </div>
          </div>        
      </div>
      

    </div>
  </body>
</html>


### contact us page:
  
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Rockstar Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/download.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/People.html">People</a></div>
        <div class="menuitemselected"><a href="/static/Contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us</h1>
          <div class="contenttext">
           <b><br> Sales and Product Inquiries</br>
           <br> Rockstar Private Limited website is a convenient place to purchase Rockstar products and accessories</br>
           <br> You can buy online or call 1-866-922-8694---.<br/>
            You can get information about an order you placed on the DCT Online Store through the Order Status page.</br>
            If you prefer, you can also get order status or make changes by phone at 1-866-922-8694 ----.</br></b>
             <b> <br>Email: support@rockstargames.com</br>
              <br>Phone: 1-866-922-8694</br>
              <br>Address: Anna Nagar</br>
               <br>whatsapp contact details:</br>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/qrcode.png"  alt="image">
                </div>
                <div class="itemname"><b>for more details contact to this bot</b></div></b>
          </div>
        </div>
              </div>
              <div class="footer">
                Copyright &#169; 2021 Rockstar Private Limited, Developed by Nithiswar
                 s
              </div>
              <div><h2><marquee>Thank For Visiting Our Page</marquee</h2></div>

          </div>
          </div>        
      </div>
    </div>
  </body>
</html>


### layout css page:

* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #17421d;
  background: linear-gradient(75deg,blue,violet);
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/images.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #16d1ae;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #5bb045;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  text-transform: capitalize;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #16d1ae;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: wheat;
  min-height: 600px;
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



.contenttext {
  margin-top: 50px;
  text-align: center;
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
  background-color: #5bb045;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}
.slider{
  width: 400px;
  height: 300px;
  margin-left: 350px;
  border-radius: 10px;
  overflow: hidden;
}
.slides{
  width: 400px;
  height: 300px;
  display:flex;

}
.slides input{
  display: none;

}
.slide{
  width:400%;
  transition: 2s;

}
.slide img{
  width: 400px;
  height: 300px;
}
.manual{
  position: absolute;
  width: 400px;
  margin-top: -40px;
  display:flex;
  justify-content: center;
  margin-top: 320px;
}
.manuals{
  border: 2px solid red;
  padding: 5px;
  border-radius: 10px;
  cursor:pointer;
  transition: 2s;

}
.manuals:not(:last-child){
     margin-right: 40px;

}
.manuals:hover{
  background-color: red;
}
#radio1:checked ~ .first{
  margin-left: 0;
}
#radio2:checked ~ .first{
  margin-left: -400px;
}
#radio3:checked ~ .first{
  margin-left: -800px;
}

## Output:
### home page:
![image](https://user-images.githubusercontent.com/94164665/146777965-08b1ca8d-9386-4d13-a87c-3aeb5e76c036.png)

### product page:
![image](https://user-images.githubusercontent.com/94164665/146778067-4eeeddea-bd67-408a-bbab-7e00c201872c.png)

### people page:
![image](https://user-images.githubusercontent.com/94164665/146778004-8ff126a4-4774-4d9e-bf65-72ce6e348782.png)

### contact us page:


![image](https://user-images.githubusercontent.com/94164665/146778036-c450c912-267a-47e3-b18e-37290e56ad92.png)



## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
