<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AbbasStack</title>
  
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
   
</head>
<header >
    <div class="one">
<body background="img.jpg.webp"></body>
    

   
   <div class="para">
    <p>Transform your testing process with:
        <a href="#"> Real Device Cloud, Company-wide Licences</a>
        &
        <a href="#">Accessibility Testing</a>
    </p>
</div>
    <div class="secondheader">
         <img src="logo.svg" alt="abbas" class="images" >
        <div>
<ul class="underlist">
         <li class="lin"><button class="navi" style="border: none;"><b>Products</b> </button></li>
        <li class="lin"><button class="navi" style="border: none;"><b> Developers</b></button></li>
        <li class="lin"><a href="#" class="navi"> <b>Live For Team</a></li>
        <li class="lin"><a href="#" class="navi">Pricing</a></li>
        <li class="lin"><a href="#" class="navi">Sign In</a></li>
        <li class="lin"><button class="freetrial">FREE TRIAL</b></button></li>
        <li class="lin"><button class="navi" style="border: none;"><i class="fa-solid fa-magnifying-glass"></i></button></li>
    </ul> </div>
    
    </div>
    <div class="heading">
        <p class="test">Test Websites on Real <br> Devices & Browsers <br> Effortlesly</p>
        <p class="heading-para">Test your website on real browsers & android devices for accurate test <br>results under real user conditions</p>
        <button class="Get-Started-Free"><b>Get Started Free</b></button>
        <button class="Contact-Sales"><b>Contact Sales</b></button>
    </div>
</div>
</header>
</body>
</html>

css  part -:
*{
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
}
.body{ 
   display: flex;
   position: fixed;
margin: 100%;
   width: 100%;
}
.para{
width: 100%;
color: white;
    background-color: #004f80;
    padding: 30px;
    text-align: center;
    font-size: 20px;
    
}
.abbas{
    padding-top: 0px;
display: inline-block;
}

.secondheader{
display: flex ;
padding: 8px;
width: 100%;
background-color: hsl(209, 44%, 14%);
position: fixed;
padding-left: 30px;
}
.images{
    font-size: 50px;
    padding-top: 30px;
    height: 65px;
    width: 200px;
}
.underlist{
    float: right;
    padding-left: 560px;

}
.lin{
    display: inline-block;
}


.para a{
    color: white;
}
.navi{
    font-size: 20px;
background-color: transparent;;
color: white;
padding: 25px;
font-weight: 800%;
font-family:serif;
text-align: center;
text-decoration: none;
padding-left: 20px;
}
.navi:hover{
    color: blue;
    cursor: pointer;
}

.freetrial{
    background-color: transparent;
color: white;

font-size: 18px;
font-family:serif;
border-radius: 5px;
padding: 10px 10px;
width: 140px;
}
.freetrial:hover{
background-color: blue;
cursor: pointer;
transition: 05.s;
}
.test{
    padding-top: 110px;
}
.heading{
    width: 100%;
    color: white;
    font-size: 65px;
    padding: 90px;
    padding-right: 454px;
font-family:sans-serif;
}
.heading-para{
    font-size: 24px;
    padding-top: 30px;
    width: 100%;
   
    }

   .Get-Started-Free{
    color: white;
background-color: #0e8aff;
font-size: 17px;
border: none;
border-radius: 5px;
padding: 15px 25px;
   
}
.Get-Started-Free:hover{
    color: white;
   background-color: red;
    cursor: pointer;
    transition: 0.5s;
    font-size:36%;
    
}

   .Contact-Sales{
    background-color: transparent;
    color: white;
    border-radius: 5px;
    padding: 15px 25px;
    font-size: 17px;
}
    .Contact-Sales:hover{
        background-color: rgb(255, 255, 255);
        color: rgb(240, 0, 0);
        transition: 0.5s;
         cursor: pointer;
         font-size:36%;
      }
    
    .chevron{font-size: 15px;
}
