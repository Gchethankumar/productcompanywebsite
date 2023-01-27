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
### Home.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Marvels Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="/static/img/logo.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"> </div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="/static/img/comic.jpg" alt="Marvel" />
          <div class="contenttext">
            Marvel Comics, American media and entertainment company that was 
            widely regarded as one of the “big two” publishers in the comic industry. 
            Its parent company, Marvel Entertainment, is a wholly owned subsidiary of the Disney Company.
            Its headquarters are in New York City.
            <br />
            Marvel Comics differentiated itself from DC Comics 
            in the 20th century by introducing human, fallible superheroes 
            with unlikely or unexpected origin stories. Also unlike DC, 
            Marvel told stories that were set in real-life locations, such as New York City.
            However, fans and critics note that the two companies have historically imitated 
            characters and qualities of each other’s comics.
            <ul>
              <li>Their Focus On Superheroes Have Created Iconic Tales</li>
              <li>Marvel Revolutionized Anti-Heroes</li>
              <li>Marvel's Does Reformed Villains Better Than Anyone Else</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2022 Marvels Private Limited, Developed by G.Chethan kumar.
      </div>
    </div>
  </body>
</html>

```
### Product.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Marvels Private Limited.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="/static/img/logo.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"> </div>
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
                  <img src="/static/img/tshirt.jpeg" alt="product image">
                  </div>
                  <div class="itemname">Marvel T-shirt</div>
                  <div class="itemprice">Price: Rs.40,00.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/earpods.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Earpods</div>
                  <div class="itemprice">Price: Rs.6,999.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/bottle.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Water Bottle</div>
                  <div class="itemprice">Price: Rs.1,699.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2022 Marvels Private Limited, Developed by G.Chethan kumar.
      </div>
    </div>
  </body>
</html>

```
### layout.css
```
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #ffffff;
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
  background-image: url("/static/img/banner.jpg");
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
  background-color: #ff7300;
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
  color: #d18316;
}

.menuitem a {
  text-decoration: none;
  color: #000000;
}

.content {
  display: block;
  width: 100%;
  background-color: #25e2c2;
  background-image: url("/static/img/back.jpg");
  background-position: 100%;
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
  background-color: #07c500;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #ffffff;
}

```
## OUTPUT:

### Home Page:

![Screenshot_20230127_094251](https://user-images.githubusercontent.com/118348224/215137944-f3594f08-48b2-42c9-8b51-477d12018677.png)

### Product Page:

![Screenshot_20230127_094305](https://user-images.githubusercontent.com/118348224/215138047-6a197012-1c2d-4129-b119-c74a68643341.png)

### Validator:

![Screenshot_20230127_093253](https://user-images.githubusercontent.com/118348224/215138144-b5f04691-6dee-4ecb-9a55-150537b3ea7d.png)

## Result:

Thus a website is designed for the software product company and the HTML, CSS code are validated.
