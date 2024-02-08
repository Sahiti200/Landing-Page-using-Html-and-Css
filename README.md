# Landing-Page-using-Html-and-Css
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Glass-Effect | New Trend | 2024-2025 | PRAROZ</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css">
</head>
<body>
    <div class="glass-effect">
    <nav>
        <h1 class=""logo>PLAN-A</h1>
        <ul>
            <li><a href="#">HOME</a></li>
            <li><a href="#">ABOUT</a></li>
            <li><a href="#">SERVICE</a></li>
            <li><a href="#">CONTACT</a></li>
        </ul>
        <img src="img2.png" alt="profile">
    </nav> 
    <div class="info">
        <h2>TRAVEL BEFORE YOU RUN OUT OF <br> TIME.</h2>
        <h4>A WORLD IS A BOOK AND THOSE WHO <br> DO NOT TRAVEL READ ONLY <br> A PAGE.</h4>
                <p>--------------YOUR CHOICE--------------</p>
                <button type="button">BOOK NOW</button>
   
    <div class="icons">
        <p>------15% OFF------</p>
        <ul>
            <li><i class="fab fa-facebook-square"></i></li>
            <li><i class="fab fa-instagram"></i></li>
            <li><i class="fab fa-twitter"></i></li>

        </ul>
    </div>
</div>

    </div>
</body>
</html> 








CSS
body{
    background-image: url(img.png);
    background-position: center;
    background-size: cover;
    height: 95vh;
    display: flex;
    align-items: center;
    justify-content: center;
    backdrop-filter: blur(3px);
}
.glass-effect{
    background-image: url(img.png);
    background-position: center;
    background-size: cover;
    margin: 0;
    padding: 0;
    font-family: cursive;
    width: 920px;
    height: 530px;
    background: radial-gradient(rgba(255, 255, 255, 0.6));
    border-radius: 20px; 
    box-shadow: 5px 10px 20px rgba(0, 0, 0, 0.6);
}
.logo{
    color: #0000;
    font-size: 35px;
    float: left;
    cursor: pointer;
}
nav{
    display: flex;
    align-items: center;
    padding: 10px 5%;
}
nav ul{
    flex: 1;
    text-align: right;
}
nav ul li{
    list-style: none;
    display: inline-block;
    margin: 0 20px;
}
nav ul li a{
    text-decoration: none; 
    color: #000;
    transition: 0.2s;
}

nav ul li a:hover{
    color: #fff;
}
img{
    width: 30px;
    height: 30px;
    border-radius: 50%;
    cursor: pointer;
}
.info{
    margin-left: 30px;
    padding: 18px;
}
p{
    color: #fff;
}
button{
    cursor: pointer;
    text-decoration: none;
    padding: 6px 16px;
    font-size: 18px;
    color: #fff;
    background-color: #000;
    border: 0;
    outline: 0;
    font-family: cursive;
    border-radius: 5px;
    transition: 0.2s;
}
button:hover{
    background-color: #fff;
    color: #000;
}
.icons{
    display: flex;
}
.icons ul{
    flex: 1;
    text-align: right;
}
.icons ul li{
    list-style: none;
    display: inline-block;
    margin: 0 20px;
    padding: 0 20px;
}
.icons ul li i{
    text-decoration: none;
    color: #fff;
    font-size: 18px;
    cursor: pointer;
}
