# Ex.07 Software Product Company Website
## Date:

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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
main.html
```
<html>
<title>MULTI TECH</title>
<style>
    body{
        background:url("C:\\Users\\91755\\Pictures\\bg.jpg") ;
        background-size: cover;
        
    }

    h1{
        color: aliceblue;
    }
    h2{
        color: aliceblue;
    }
    h3{
        color:bisque;
        text-align: center;
    }

/* the main window options*/
.styled form {
            margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:aliceblue; /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#ffffff; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); /* Adjust the color as needed */
}

.login{
    margin-top: -100;
    margin-left: 1100;
    margin-right: 100;    
    background:url(123.jpg);

    scroll-padding-left: 5px;
    border:2px solid white;
}
.login input[type="button"] {
    padding: 10px 20px; /*  button size */
    background-color: #3498db;
    color: #ffffff;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.login input[type="button"]:hover {
    color:#000;
    background-color:rgb(204, 32, 204);
}
.login input[type="submit"]{
    padding: 10px 15px; /*  button size */
    background-color:#4234db;
    color: #ffffff;
    border-radius: 10px;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.login input[type="submit"]:hover {
    color:#000;
    background-color:chocolate;
}
.login input[type="text"] { 
    padding: 10px; /* Add padding for better appearance */
    transition: background-color 0.3s; /* Add transition for a smooth effect */
        /* Set initial background color */
        background-color: #ffffff;
}
.login input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:slateblue; /* Adjust the color as needed */
}
.join{
    padding: 10px 20px; /*  button size */
    background-color: #3498db;
    color: #ffffff;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.join:hover {
    color: aquamarine;
    background-color: #4234db;
}

</style>
<body >
    <form class="styled ">
        <div class=>
            <a href="mainpage.html">
                <input type="button" value="HOME">
            </a>
            <a href="products.html">
                <input type="button" value="OUR PRODUCTS">
            </a>

            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>

    <h1>WELCOME TO MULTI TECH</h1>
    <h2>INTERNATIONAL  COMPANY</h2>
    <h2>PRODUCTS</h2>
    <a href="sign.html">
        <input type="button" value="JOIN US" class="join">
    </a>  
    
    <h3>"The best way to predict the future is to invent it." </h3>

         <center>
        <div class="login">
            <div class="login-box">
            <p style="color: aliceblue;">DONT HAVE AN ACCOUNT</p>
            <a href="sign.html">
                <input type="button" value="SIGN IN"><br><br>
            </a>  
            <p style="color: aliceblue;">LOGIN</p>
            <input type="text" value="Username or email" ><br><br>
            <input type="text" value="Password"><br><br>
            <a href="products.html">
                <input type="submit" value="SUBMIT"><br><br>
            </a>  
        </div>
        </div>
    </center>

</body>
<footer style="background-color:rgb(255, 183, 0);margin-top: 180; border: none;">
    <P style="color:#ffffff; ;"align="center">Designed and Devoloped by KISHORE.B (212222110020) </P>
</footer>
</html>
```
product.html
```
<html>
    <title>OUR PRODUCTS</title>
    <style>  
    body{
        background:url("C:\\Users\\91755\\Pictures\\bg.jpg");
        background-size:contain;
    } 
    h1{
        color: aliceblue;
    }  
    .styled form {
            margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:aliceblue; /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#ffffff; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); /* Adjust the color as needed */
}
</style>
    
    <body>
        <form class="styled ">
            <div class=>
                <a href="mainpage.html">
                    <input type="button" value="HOME">
                </a>
                <a href="products.html">
                    <input type="button" value="OUR PRODUCTS">
                </a>
                <a href="about.html">
                    <input type="button" value="ABOUT US">
                </a>
                <a href="sign.html">
                    <input type="button" value="SIGN IN">
                </a>
                <a href="contact.html">
                    <input type="button" value="CONTACT">
                </a>  
                <input type="text">
                <input type="submit"value="SEARCH">  
            </div>
        </form>
        
        <center>
            <h1 >OUR TECH MASSIVE PROJECTS</h1>
        <img src="C:\Users\91755\Pictures\it.jpg" height="500" width="800">
    </center>
    </body>
    <footer style="background-color:black;margin-top: 100; border: none;">
        <P style="color:#ffffff; ;"align="center">Designed and Devoloped by KISHORE (212222110020)</P>
    </footer>
</html>
```
contact.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Contact Us</title>
    <style>
        b{
            color:cornflowerblue
        }
        p {
            color: aliceblue;
        }

        body {
            background:url("C:\\Users\\91755\\Pictures\\bg.jpg");
        }

        .yourinfo {
            background:url(bg.jpg);
            border:5px solid rgb(210, 186, 186);
            margin-right: 800px ;
            
            margin-top: 200px; /* Adjusted margin-top */
            padding: 10px; /* Added padding for better spacing */
        }
        .yourinfo input[type="text"] {
            width: 500px;
            transition: background-color 0.3s; 
        }
        .yourinfo input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color: #2278c3; /* Adjust the color as needed */
}

        .buttons {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #3498db;
            color: #ffffff;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s, color 0.3s;
        }

        .buttons:hover {
            color: aqua;
            background-color: #4234db;
        }
        .styled form {
            display: flex;
            justify-content: space-evenly;
        }
        .styled form {
            margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:aliceblue; /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#ffffff; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); /* Adjust the color as needed */
}
    
.company{

margin-left: 900px;
margin-top: -330px;
background:url(bg5.jpg);

scroll-padding-left: 5px;
border:2px solid white;
}
.message textarea {
        background-color: white; /* Set the default background color */
        color: black; /* Set the default text color */
    }

    /* Styles for the text area when it is in focus */
.message    textarea:focus {
        background-color: cadetblue; /* Set the background color when in focus */
        color: white; /* Set the text color when in focus */
    }
    </style>
</head>
<body>
    <form class="styled">
        <div>
            <a href="mainpage.html">
                <input type="button" value="HOME">
            </a>
            <a href="products.html">
                <input type="button" value="OUR PRODUCTS">
            </a>
            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>
            <input type="text" >
            <input type="submit" value="SEARCH">
        </div>
    </form>
    <div class="yourinfo">
        <center>
        <p>Contact Information</p>
        <div>            
            <input type="text" maxlength="100" placeholder="Your Name"><br><br>
            <input type="text" maxlength="100" placeholder="Your Email"><br><br>
            <div class="message">
            <textarea rows="5" cols="65" placeholder="Your Message"></textarea><br><br>
        </div>
            <input type="button" value="SUBMIT" class="buttons">
        
        </center>
        </div>
    </div>
    <div class="company">
        <center>
        <h3 style="color: aliceblue;">COMPANY CONTACT INFORMATION</h3>
       <p> <b >Address</b></p>
        <p >4/335 VEERAMAMUNIVAR STREET</p>
        <p >MUGAPPAIR EAST</p>
        <p >CHENNAI-600037</p>
        <b >Email:</b>
        <p >KISHORE@GMAIL.COM</p>
        <b >Phone</b>
        <p >7396248743</p>
    </center>
    </div>
</body>
<footer style="background-color:black;margin-top: 150px; border: none;">
    <P style="color:#ffffff ;"align="center">Designed and Devoloped by KISHORE (212222110020) </P>
</footer>
</html>
```
about.html
```

<html>
<title>about us</title>
<style>
    p{
        color:rgb(255, 0, 0);
    }
    body{
        background:url("C:\\Users\\91755\\Pictures\\bg.jpg");
        background-size: cover;
    }
    .styled form {
            margin-top:20px;
            display:flex;
            justify-content:space-between
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:aliceblue; /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#ffffff; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); /* Adjust the color as needed */
}
.photos{
    display:flex;
    justify-content: space-around;
    margin-top: 200px;
}
.names{
    display:flex;
    justify-content: space-around;

}
.position {
    display: flex;
    justify-content: space-around;
    margin-left: 10px;
    border-image:5px;
    border-image: antiquewhite;
}

</style>
<body>
    <form class="styled ">
        <div class=>
            <a href="mainpage.html">
                <input type="button" value="HOME">
            </a>
            <a href="products.html">
                <input type="button" value="OUR PRODUCTS">
            </a>
            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>
    <div class="photos">
    <img src="C:\Users\91755\Pictures\WhatsApp Image 2024-05-01 at 11.06.37_6edbf742.jpg" height="200" width="180">
    <img src="C:\Users\91755\Pictures\KARTHI.jpg" height="200" width="200">
    <img src="C:\Users\91755\Pictures\NANDHA.jpg" height="200" width="200">
    <img src="C:\Users\91755\Pictures\ROHIT.jpg" height="200" width="200">
    <img src="C:\Users\91755\Pictures\BARATH.jpg" height="200" width="200">
</div>

<div CLASS="names">
    <P>MR KISHORE</P>    
    <P>MR KARTHIKEYAN</P>    
    <P>MR NANDHA KUMAR</P>      
    <P>MR ROHIT JAIN</P>
    <P>MR BARATH</P>       
</div>

<DIV class="position">
    <p>FOUNDER</p>
    <p>CO-FOUNDER</p>
    <p>CEO</p>
    <p>DIRECTOR</p>
    <P>Exe-DIRECTOR</P>
</DIV>
</body>
<footer style="background-color:black;margin-top: 170; border: none;">
    <P style="color:#ffffff; ;"align="center">Designed and Devoloped bY KISHORE (212222110020) </P>
</footer>
</html>
```
sign.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Sign Up</title>
    <style>
        body {
            background:url("C:\\Users\\91755\\Pictures\\bg.jpg");
            background-size: cover;
            color: burlywood;
            font-family: Arial, sans-serif;
        }

        .form {
            margin: 0 auto;
            width: 300px;
            padding: 20px;
        }

        label {
            color: chocolate;
        }

        .purpose {
            color: aqua;
        }

        .buttons {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #3498db;
            color: #ffffff;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s, color 0.3s;
        }

        .buttons:hover {
            color: aqua;
            background-color: #4234db;
        }
        .styled form {
            margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:aliceblue; /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#ffffff; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:mediumaquamarine;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); /* Adjust the color as needed */
}
.text{
    transition: background-color 0.3s, color 0.3s;

}
.text :focus{
    background-color:skyblue;  
}
.full{
    background:url(bg2.jpg);
    padding: 10px;
    border:4px double white;
}
    </style>
</head>
<body>
    <form class="styled ">
        <div class=>
            <a href="mainpage.html">
                <input type="button" value="HOME">
            </a>
            <a href="products.html">
                <input type="button" value="OUR PRODUCTS">
            </a>
            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>
    <div class="form">
        <p align="margin-left">JOIN THE FAMILY OF TECH </p>
        <p align="left">DON'T HAVE AN ACCOUNT YET?</p>
        <div class="full">
        <div class="text">
           
        <label>Unique Username</label>
        <input type="text" value="username"><br><br>
        <label>Email</label>
        <input type="email" value="email"><br><br>
        </div>
        <label>DOB</label>
        <input type="date"><br><br>
        <label>Gender</label><br>
        <div class="purpose">
            <input type="radio" name="gender">Male<br>
            <input type="radio" name="gender">Female<br><br>
        </div>
        <label>Purpose</label><br>
        <div class="purpose">
            <input type="radio" name="purpose">Study<br>
            <input type="radio" name="purpose">Work<br>
            <input type="radio" name="purpose">Partnership<br><br>
        </div>
        <label>Click the checkbox to prove you are NOT A ROBOT </label>
        <input type="checkbox"><br><br>
        
            <input type="submit" value="CREATE ACCOUNT" class="buttons">
            <input type="submit" value="DOWNLOAD SOFTWARE"class="buttons">
        
    </div>
</div>
</body>
<footer style="background-color:black; margin-top: 45px ; border: none;">
    <P style="color:#ffffff ;"align="center">Designed and Devoloped by KISHORE (212222110020) </P>
</footer>
</html>
```
## OUTPUT:
![Screenshot 2024-05-08 190748](https://github.com/KSIHORE/softweb/assets/151484879/d1677bc2-d7e2-4131-bff5-6629d9f0b61b)
![Screenshot 2024-05-08 190817](https://github.com/KSIHORE/softweb/assets/151484879/51bcbcc4-e52c-46d1-848b-f9f6c7d8984b)
![Screenshot 2024-05-08 190924](https://github.com/KSIHORE/softweb/assets/151484879/5266c20b-68bc-4615-b589-71781e3ffda4)
![Screenshot 2024-05-08 191002](https://github.com/KSIHORE/softweb/assets/151484879/ecccd6be-2ec3-49c1-a7b6-e095199810e1)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
