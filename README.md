# Ex.07 Restaurant Website
## Date: 11-12-2024.

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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
```
website.html

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Website</title>
    <link rel="stylesheet" href="C:\Users\naush\OneDrive\Desktop\style.css">
</head>
<body>
    <section id="Home">
        <nav>
            <div class="logo">
                <img class="image" src="C:\Users\naush\OneDrive\Desktop\fl2.jpg", width="10%"style="display:block;margin-left: auto;margin-right: auto;background-blend-mode: lighten;background-color: inherit;"/>
            </div>

            <ul>
                <li><button class="btn" type="button" onclick="location.href='website.html'">Home</a></li>
                <li><button class="btn" type="button" onclick="location.href='About.html'">About</a></li>
                <li><button class="btn" type="button" onclick="location.href='menu.html'">Menu</a></li>
            </ul>
        </nav>
    

        <div class="main" id="Home" >
            <div class="main_text">
                <h1 style="font-family:'Times New Roman', Times, serif">  Flavors Of India</h1>
                <h1 style="color:burlywood;left:300px;text-align: center;">.</h1>
                <h2>   Savour The Flavor...</h2>
                <h2>   ...Love The Experience</h2>
                <h1 style="color:burlywood;left:300px;text-align: center;">.</h1>
                <h3  style="font-family:cursive;font-style:italic">   North Indian, South Indian, Oriental, continental,Mexican,Italian,Chinese,Desserts,Beverages</h3>
            </div>
            <div class="main_image">
                <img src="C:\Users\naush\OneDrive\Desktop\de\flavours of india.jpeg">
            </div>

        </div>     
          
    </section>
    
    
</body>
</html>

style.css

*{
    margin:0;
    padding: 0;
    box-sizing: border-box;
    background-;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
html{
    scroll-behavior: smooth;
}

section{
    width: 100%;
    height:100vh;
}

section nav{
    display:flex;
    justify-content:space-around;
    align-items:center;
    position:fixed;
    right:0;
    left:0;
    style="background-color:brown;"
    background:url("C:\Users\naush\OneDrive\Desktop\fl1.jpg");
    box-shadow: 0 0 10px rgba(0,0,0,0.5);
    z-index:1000;
}

section nav .logo img{
    width:100px;
    cursor:pointer;
    margin:7px 0;
}

section nav ul{
    list-style:none;
}

section nav ul li{
    display:inline-block;
    margin:0 15px;

}

.btn{
    padding:15px 30px;
    border:none;
    outline:none;
    color:rgb(235, 177, 101);
    cursor:pointer;
    position:relative;
    z-index:0;
    border-radius:12px;
    font-family:Arial, Helvetica, sans-serif
    transition:0.1s;
}

.btn::after{
    content:"";
    z-index:-1;
    position:absolute;
    width:100%;
    height:100%;
    background-color:rgb(29, 0, 0);
    left:0;
    top:0;
    border-radius: 10px;
    display: block;
    transition: 0.2 linear;
}

.btn:hover::after{
    width:100%;
}

.btn:hover{
    color:rgb(214, 142, 54);
}



section .main{
    display: flex;
    align-items: center;
    justify-content: space-around;
    position: relative;
    top:115px;
}

section .main .main_text h1{
    font-size: 70px;
    position: relative;
    color:rgb(39, 2, 2);
    left:40px;
}

section .main .main_text h2{
    font-size:50px;
    position: relative;
    color:rgb(170, 115, 13);
    left:70px;
    
}

section .main .main_text h3{
    font-size:20px;
    position: relative;
    color:rgb(170, 115, 13);
    left:70px
}

section .main .main_image{
    max-width: 50%;
    margin:30px auto;

}

section .main .main_image img{
    width: 100%;
    height:auto;
    margin:30px auto;

}

section .about{
    display: flex;
    flex-wrap: wrap;
    align-items:center;
    justify-content: center;
    position: relative;
    top:115px;
    padding: 20px;
    overflow:hidden;
}


section .about .about_image{
    max-width:100%;
    text-align: start;

}

section .about .about_image img{
    width:100%;
    height:auto;
   
}

section .about .about_text{
    flex:1;
    max-width:100%;
    padding:65px;
    text-align:center;
    overflow: hidden;

}

section .about .about_text h1{
    font-size: 70px;
    flex:1;
    position:relative;
    color:rgb(170, 115, 13);
    min-width: 300px;
    padding:20px;
    text-align: center;
    
}


section .about .about_text h3,p{
    font-size:30px;
    position: relative;
    color:rgb(104, 44, 16);
    font-family:'Courier New', Courier, monospace;
    margin-bottom:20px;
}

style1.css

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
html{
    scroll-behavior: smooth;
}

section{
    width: 100%;
    height:100vh;
}

section nav{
    display:flex;
    justify-content:space-around;
    align-items:center;
    position:fixed;
    right:0;
    left:0;
    style="background-color:brown;"
    background:url("C:\Users\naush\OneDrive\Desktop\fl1.jpg");
    box-shadow: 0 0 10px rgba(0,0,0,0.5);
    z-index:1000;
}

section nav .logo img{
    width:100px;
    cursor:pointer;
    margin:7px 0;
}

section nav ul{
    list-style:none;
}

section nav ul li{
    display:inline-block;
    margin:0 15px;

}

.btn{
    padding:15px 30px;
    border:none;
    outline:none;
    color:rgb(235, 177, 101);
    cursor:pointer;
    position:relative;
    z-index:0;
    border-radius:12px;
    font-family:Arial, Helvetica, sans-serif
    transition:0.1s;
}

.btn::after{
    content:"";
    z-index:-1;
    position:absolute;
    width:100%;
    height:100%;
    background-color:rgb(29, 0, 0);
    left:0;
    top:0;
    border-radius: 10px;
    display: block;
    transition: 0.2 linear;
}

.btn:hover::after{
    width:100%;
}

.btn:hover{
    color:rgb(214, 142, 54);
}


section .about{
    display: flex;
    flex-wrap:wrap;
    align-items:center;
    justify-content: center;
    position: relative;
    top:115px;
    background-image: url(restbg.png);
    background-repeat: no-repeat;
    background-size:cover;
}

section .about .about_image{
    max-width:100%;
    text-align:start;
    margin:30px auto;
}

section .about .about_image img{
    width:100%;
    height:auto;
     margin:30px auto;

}

section .about .about_text{
    flex:1;
    max-width:100%;
    padding:65px;
    text-align:center;
    overflow:hidden;
}

section .about .about_text h1{
    font-size: 70px;
    flex:1;
    position: relative;
    color:rgb(170, 115, 13);
    min-width:300px;
    padding:20px;
    text-align:center;
    
}

section .about .about_text h3,p{
    font-size:30px;
    position: relative;
    color:rgb(104, 44, 16);
    font-family:'Courier New', Courier, monospace;
    margin-bottom: 20px;
}

style2.css

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
html{
    scroll-behavior: smooth;
}

section{
    width: 100%;
    height:100vh;
}

section nav{
    display:flex;
    justify-content:space-around;
    align-items:center;
    position:fixed;
    right:0;
    left:0;
    background-color:brown;
    background:url("C:\Users\naush\OneDrive\Desktop\fl1.jpg");
    box-shadow: 0 0 10px rgba(0,0,0,0.5);
    z-index:1000;
}

section nav .logo img{
    width:100px;
    cursor:pointer;
    margin:7px 0;
}

section nav ul{
    list-style:none;
}

section nav ul li{
    display:inline-block;
    margin:0 15px;

}

.btn{
    padding:15px 30px;
    border:none;
    outline:none;
    color:rgb(235, 177, 101);
    cursor:pointer;
    position:relative;
    z-index:0;
    border-radius:12px;
    font-family:Arial, Helvetica, sans-serif
    transition:0.1s;
}

.btn::after{
    content:"";
    z-index:-1;
    position:absolute;
    width:100%;
    height:100%;
    background-color:rgb(29, 0, 0);
    left:0;
    top:0;
    border-radius: 10px;
    display: block;
    transition: 0.2 linear;
}

.btn:hover::after{
    width:100%;
}

.btn:hover{
    color:rgb(214, 142, 54);
}

section .menu{
    display: flex;
    align-items: center;
    justify-content: space-around;
    position: relative;
    top:115px;
    padding:0 10px 30px 10px;
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(350px,1fr));
    grid-gap:20px 40px;
}
section .menu .heading{
    color:brown;
    margin: bottom 30px;
    padding:30px 0;
    grid-column:1/-1;
    text-align:center;
}
section .menu .food-items{
    display:grid;
    position:relative;
    grid-template-rows:auto 1fr;
    border-radius:15px;
    box-shadow:0 0 15px rgba(0,0,0,0.5);
    transition:.2s ease-in-out;
}

section .menu .food-items img{
    position:relative;
    width:100%;
    height:280px;
    border-radius:15px 15px 0 0;
    cursor:pointer;
    margin:30px auto;


}
section .menu .heading h1{
    grid-column:1/-1;
    text-align:center
}
section .menu .food-items .details{
    padding:20px 10px;
    display:grid;
    grid-template-rows:auto 1fr 50px;
    grid-row-gap:15px;
}

about.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Website</title>
    <link rel="stylesheet" href="C:\Users\naush\OneDrive\Desktop\style1.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body >
    <section id="Home">
        <nav>
            <div class="logo">
                <img class="image" src= "C:\Users\naush\OneDrive\Desktop\fl2.jpg"width="10%"style="display:block;margin-left: auto;margin-right: auto;background-blend-mode: lighten;background-color: inherit;"/>
            </div>

            <ul>
                <li><button class="btn" type="button" onclick="location.href='website.html'">Home</a></li>
                <li><button class="btn" type="button" onclick="location.href='About.html'">About</a></li>
                <li><button class="btn" type="button" onclick="location.href='menu.html'">Menu</a></li>
         
            </ul>
        </nav>
        <div class="main" >
            <div class="main_image">
                <img src="C:\Users\naush\OneDrive\Desktop\de\food1.jpeg">
                 

            </div>


            <div class="main_text">
                <h1 style="font-family:'Courier New', Courier, monospace;font-style:italic;color:  rgb(39, 2, 2)">About Us...</h1>
                <h3>Service options: Has all you can eat · Serves vegan dishes · Good for kids birthday</h3>
                
                <h3>Address:1st Floor Above Dominoe's E Block CitY center Chennai-600023</h3>
                <h3>Phone: 098436 32323</h3>
                <h3>Hours:11.AM-11.30PM</h3>
                <h3>Reservations: zomato.com</h3>
                <h3>From Flavors Of India
                    " a pure veg multicuisine restaurant situated in kilpauk area of Chennai City, Tamil Nadu."</h3>
            </div>

        </div>

        </div>
        </section>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Website</title>
    <link rel="stylesheet" href="C:\Users\naush\OneDrive\Desktop\style2.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body >
    <section id="Home">
        <nav>
            <div class="logo">
                <img class="image" src="C:\Users\naush\OneDrive\Desktop\fl2.jpg", width="10%"style="display:block;margin-left: auto;margin-right: auto;background-blend-mode: lighten;background-color: inherit;"/>
            </div>

            <ul>
                <li><button class="btn" type="button" onclick="location.href='website.html'">Home</a></li>
                <li><button class="btn" type="button" onclick="location.href='About.html'">About</a></li>
                <li><button class="btn" type="button" onclick="location.href='menu.html'">Menu</a></li>
                
            </ul>
        </nav>
        <div class="menu">
            <div class="heading">
                <h1>RESTAURANT FOOD</h1> 
                <h3>&mdash;MENU&mdash;</h3>
            </div>
            <div class="food-items">
                <img src="C:\Users\naush\OneDrive\Desktop\de\mutton gravy.jpeg"/>
                <div class="detals">
                    <div class="detailed-sub">
                        <h5>mutton gravy</h5>
                    </div>
                    <p>cubes of mutton and gravy. Traditionally it's grilled in a tandoor </p>
                    
                </div>
            </div>
        
            <div class="food-items">
                <img src="C:\Users\naush\OneDrive\Desktop\de\pulav.jpeg"/>
                <div class="detals">
                    <div class="detailed-sub">
                        <h5>Veg pulav</h5>
                    </div>
                    <p>a vegetarian Indo-Chinese dish in which shredded vegetables and rice are cooked in a tasty way </p>
                    
                </div>
            </div>
        
            <div class="food-items">
                <img src="C:\Users\naush\OneDrive\Desktop\de\briyani.webp"/>
                <div class="detals">
                    <div class="detailed-sub">
                        <h5>Veg briyani</h5>
                    </div>
                    <p>made in a traditional ariabian way with lots of masala and mutton . its also made with love.</p>
                    
                </div>
            </div>
        
            <div class="food-items">
                <img src="C:\Users\naush\OneDrive\Desktop\de\chicken.webp"/>
                <div class="detals">
                    <div class="detailed-sub">
                        <h5>Veg chicken lolypop</h5>
                    </div>
                    <p>a healthy Chinese inspired dish where chicken is fried until its crisp</p>
                    
                </div>
            </div>
        
            <div class="food-items">
                <img src="C:\Users\naush\OneDrive\Desktop\de\naan.jpeg"/>
                <div class="detals">
                    <div class="detailed-sub">
                        <h5>Naan</h5>
                    </div>
                    <p>a leavened, oven-baked flatbread that is a staple of South and Central Asian cuisine </p>
                    
                </div>
            </div>
        
            <div class="food-items">
                <img src="C:\Users\naush\OneDrive\Desktop\de\soup.jpeg"/>
                <div class="detals">
                    <div class="detailed-sub">
                        <h5>soup</h5>
                    </div>
                    <p>this hot and sour soup with make ur mind go crazy with flavours </p>
                   
                </div>
            </div>
        
            <div class="food-items">
                <img src="C:\Users\naush\OneDrive\Desktop\de\salad.jpg"/>
                <div class="detals">
                    <div class="detailed-sub">
                        <h5>salad</h5>
                    </div>
                    <p> with fresh veggies and mayo this sadal is perfect for a healthy life</p>
                    
                </div>
            </div>
        
            <div class="food-items">
                <img src="C:\Users\naush\OneDrive\Desktop\de\icecream.jpeg"/>
                <div class="detals">
                    <div class="detailed-sub">
                        <h5>Falooda</h5>
                    </div>
                    <p>a cold, layered dessert or snack that originated in Persia and is popular in India, Pakistan, and the Middle East </p>
                    
                </div>
            </div>
        
        
            <div class="food-items">
                <img src="C:\Users\naush\OneDrive\Desktop\de\fish.webp"/>
                <div class="detals">
                    <div class="detailed-sub">
                        <h5>fish</h5>
                    </div>
                    <p>this fish fry is made with lot of spices and its fresh from the ocean</p>
                    
                </div>
            </div>
</body>
</html>
```
 

## OUTPUT:
![alt text](<Screenshot (179).png>)

![alt text](<Screenshot (180).png>)
![alt text](<Screenshot (181).png>)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
