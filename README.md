# Ex.07 Restaurant Website
# Date:12/12/2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RESTAURANT</title>
    <link rel="stylesheet" href="mohan.css">
    
     <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
     <style>
        *{
    margin: 0;
    padding: 0;
}
body{
    filter: brightness(0.7);
}
body img{
    width: 100%;
    height: 800px;
}
#logo{
    width: 202px;
    height: 202px;
    top: 40px;
    left: 10px;
    position: absolute;
    filter: brightness(1.1);
    cursor: pointer;
}
.nav-list{
    position: absolute;
    top: 45PX;
    left: 50%;
    transform: translateX(10%);
    overflow: hidden;
}
.nav-list a{
    display: inline-block;
    margin: 0 10px;
    font-family: MS  sans-serif;
    text-decoration: none;
    font-size: 18px;
    font-weight: bold;
    color: white;
}
.nav-list a:hover{
    color: #ff6931;
}
#welcome{
    text-align: center;
    font-size: 23px;
    font-family: montserrat semibold;
    margin-top: -500px;
    color: white;
}
#lorem{
    font-size: 20px;
    color: white;
    font-family: leelawdee UI;
    text-align: center;
}
.search-bar{
    margin-left: 640px;

}
#search{
    width: 290px;
    height: 30px;
    border-radius: 5px;
}
.submit{
    height: 40px;
    width: 70px;
    margin-left: 100px;
    cursor: pointer;
    background-color: #ff6931;
    border-radius: 10px;
    border: 2px solid white;
}
.submit:hover{
    background-color: white;
    border: 2px solid #ff6931;
}
.order{
    border: 2px solid #ff6931;
    width: 150px;
    height: 50px;
    margin-left: 700px;
    cursor: pointer;
    background-color: white;
    border-radius: 10px;
    opacity: 0.9;
}
#now{
    font-size: 20px;
    font-family: mingl iu_10scs-EXtB;
    padding-top: 10px;
    text-align: center;
}
.order:hover{
    background-color: #ff6931;
    border: 2px solid white;
}
.navbar ul{
    list-style-type: none;
    background-color: hsl(0, 0%, 25%);
    padding: opx;
    margin: 0px;
    overflow: hidden;
}
.navbar a{
    color: white;
    text-decoration: none;
    padding: 15px;
    display: block;
    text-align: center;
}
.navbar a:hover{
    background-color: #ff6931;
}
.navbar li{
    float: left;
}
     </style>
</head>
<body>
    <div class="background image ">
        <img src="restaraunt.avif" alt="">
        <img id="logo" src="logo.png">
        <div class="nav-list">
           <nav class="navbar">
            <ul>
           <Li> <a href="mohan.html">HOME</a></Li>
           <Li>  <a href="menu.html">MENU</a></Li>
           <Li> <a href="aboutus.html">ABOUT US</a></Li>
           <Li> <a href="contact.html">CONTACT US</a></Li>
            </ul>
    </nav> 

        
        </div>
        <p id="welcome">welcome to our restaurant</p><br>
        <p id="lorem">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Porro<br> recusandae ut rem blanditiis odio et consequatur delectus, expedita <br> error dicta quod exercitationem animi dolorum<br> ratione impedit voluptatibus, optio molestiae unde!</p>
        <br>
        <form class="search-bar">
            <input type="text" placeholder="search..." id="search"><br>
            <button type="submit" class="submit">submit</button>
        </form>
        <br><br><br><br><br><br>
        <div class="order">
            <p id="now">order now</p>
        </div>
    </div>
    
</body>
</html>
```
### menu.html
```
<style>
    #menu{
        padding: 25px 0 25px 0;

    }
    #selection{
        padding: 25px 0 25px 0;
        text-align: center;
        font-size: 2rem;
        font-family: Verdana;
    }
    #menu_row{
        display: flex;
        padding: 0 100px 0 100px;
        

    }
    #menu_col{
        box-shadow: 2px 2px 2px #bbb;
        border: 1px solid #bbb;
        background-color: #fff;
        margin: 10px;
        padding: 10px;
        flex: 1;
    }
    #menu_col h2{
        background-color: red;
        color: #fff;
        text-align: center;
        padding: 5px;
        font-family: cursive;
    }
    #image{
        width: 150px;
        height: 150px;
        border-radius: 50%;
        padding: 5px;
        border: 2px solid orange;
    }
    #image img{
        width: 100%;
        height: 100%;
        border-radius: 50%;
        object-fit: cover;
    }
    .box{
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: center;
        margin: 5px;
    }

</style>
<div id="menu">
    <h1 id="selection">Menu</h1>
    <div id="menu_row">
        <div id="menu_col">
            <h2>BREAKFAST</h2>
            <div class="box">
                <div id="image">
                    <img src="breakfast.jpeg" alt="">
                </div>
                <div>
                    <h3>tasty dish 01</h3>
                    <h4>10$</h4>
                </div>
            </div>
            <div class="box">
                <div id="image">
                    <img src="breakfast2.jpeg" alt="">
                </div>
                <div>
                    <h3>tasty dish 01</h3>
                    <h4>10$</h4>
                </div>
            </div>
            <div class="box">
                <div id="image">
                    <img src="breakfast3.jpeg" alt="">
                </div>
                <div>
                    <h3>tasty dish 01</h3>
                    <h4>10$</h4>
                </div>
            </div>
        </div>
        <div id="menu_col">
            <h2>LUNCH</h2>
            <div class="box">
                <div id="image">
                    <img src="lunch1.jpeg" alt="">
                </div>
                <div>
                    <h3>tasty dish 01</h3>
                    <h4>10$</h4>
                </div>
            </div>
            <div class="box">
                <div id="image">
                    <img src="lunch2.jpeg" alt="">
                </div>
                <div>
                    <h3>tasty dish 01</h3>
                    <h4>10$</h4>
                </div>
            </div>
            <div class="box">
                <div id="image">
                    <img src="lunch3.jpeg" alt="">
                </div>
                <div>
                    <h3>tasty dish 01</h3>
                    <h4>10$</h4>
                </div>
            </div>
        </div>
        <div id="menu_col">
            <h2>DINNER</h2>
            <div class="box">
                <div id="image">
                    <img src="dinner1.jpeg" alt="">
                </div>
                <div>
                    <h3>tasty dish 01</h3>
                    <h4>10$</h4>
                </div>
            </div>
            <div class="box">
                <div id="image">
                    <img src="dinner2.jpeg" alt="">
                </div>
                <div>
                    <h3>tasty dish 01</h3>
                    <h4>10$</h4>
                </div>
            </div>
            <div class="box">
                <div id="image">
                    <img src="dinner3.jpeg" alt="">
                </div>
                <div>
                    <h3>tasty dish 01</h3>
                    <h4>10$</h4>
                </div>
            </div>
        </div>
    </div>

</div>

```
### aboutus.html
```
<style>
    #about{
        padding: 25px 0 25px 0;
    }
    #about_row{
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
        padding: 0 100px 0 100px;
    }
    .about_col{
        flex: 1;

    }
    #about_img{
        width: 300px;
        height: 300px;
        border-radius: 50%;
        margin: auto
    }
    #about_img img{
        width: 300px;
        height: 300px;
        border-radius: 50%;
        object-fit: fill;
    }
    .about_col h1{
        text-align: center;
        font-family: cursive;

    }
    .about_col p{
        text-align: justify;
        font-weight: bold;

    }
</style>


<div id="about">
    <h1 id="section"></h1>
    <div id="about_row">
        <div class="about_col">
            <h1>ABOUT US</h1>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore quam cupiditate est alias quae nulla porro ex itaque sed rem! Incidunt, perspiciatis? Delectus, dolores nisi eius minus officiis harum a, eum excepturi voluptas repellat molestias distinctio? Facilis cupiditate quae quo, saepe ut dolorem perferendis minus distinctio, enim iure repellat voluptatum cumque ab beatae, possimus iusto sapiente autem quam sit unde rem provident labore dolorum. Perspiciatis est commodi soluta excepturi a explicabo! Accusantium iusto iure tempore voluptatum adipisci dolorem iste incidunt, omnis asperiores esse ipsam nam dolores facilis, provident cum, dignissimos aspernatur sapiente. Eum ad voluptatem provident fuga esse deleniti at.
            </p>
        </div>
        <div class="about_col">
            <div id="about_img">
                <img src="chef1.jpeg" alt="">
            </div>
        </div>
    </div>
</div>
```
### contactus.html
```
<style>
    h1{
        
        text-align: center;
        text-decoration: solid black;
    }
    .container{
        font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        color: white;
        background-color: rgba(151, 138, 138, 0.674);
        padding-top: 80px;
        padding-left: 80px;
        height: 400;
        width: 700px;
        margin-left: 5%;
        margin-right: 5%;
    }
</style>
<h1>CONTACT US</h1>

<div class="container">
    <h2>phone number  : 8148452728</h2>
    <h2>email id : krishnanrama93132@gmail.com</h2>
    <p>no.2 abc street, xyz nagar ,chennai </p>
</div>
```
# OUTPUT:
![img1](https://github.com/user-attachments/assets/c51e2d7f-6ac4-4020-9a21-9e7d23c6a0f6)
![img2](https://github.com/user-attachments/assets/4f662d3b-250f-4ed8-a04b-d2087ed47d6e)
![img3](https://github.com/user-attachments/assets/e6eb7e3a-8e39-44cf-8173-558573788906)
![img4](https://github.com/user-attachments/assets/f8937235-c606-4bf3-900a-9709594ae5b1)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
