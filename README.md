# nipun-12
html project
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nipun Fitness lub</title>
</head>
<link href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2&family=Poppins:wght@400;500;600;700&display=swap"
    rel="stylesheet">

<style>
    /* CSS Reset */
    body {
        font-family: 'Baloo Bhai 2', cursive;
        color: white;
        margin: 0px;
        padding: 0px;
        background-image: url("bg.jpg");
        background-size:125%;
        background-repeat:no-repeat;
        
    }

    .left {
        display: inline-block;
        
        position: absolute;
        left: 60px;
        top: 20px;

    }

    .left img {
        width: 136px;
        filter: invert(100%)
    }

    .left div {
        line-height: 19px;
        font-size: 26px;
        text-align: centre;
    }

    .mid {
        display: block;
        width: 36%;
        margin: 12px auto;
        

    }

    .right {
        position: absolute;
        right: 34px;
        top: 20px;
        display: inline-block;
        

    }

    .navbar {
        display: inline-block;
    }

    .navbar li {
        color: cyan;
        display: inline-block;
        font-size: 25px;
    }

    .navbar li a {
        color: cyan;
        text-decoration: none;
        padding: 34px 23px;
    }

    .navbar li a:hover,
    .navbar li a.activa {
        text-decoration: underline;
    }

    .btn {
        font-family: 'Baloo Bhai 2', cursive;
        margin: 0px 9px;
        background-color: black;
        color: white;
        padding: 4px 14px;
        border: 2px solid grey;
        border-radius: 10px;
        font-size: 20px;
        cursor: pointer;
    }

    .btn:hover {
        background-color: rgb(red, green, blue);
    }

    .container {
        
        margin: 2px 2px;
        padding: 2px 2px;
        width: 33%;
        border-radius: 2px;
    }

    .form-group input {
        font-family: 'Baloo Bhai 2', cursive;
        text-align: centre;
        display: block;
        width: 80%;
        padding: 9px;
        border: 2px solid black;
        margin: 3px auto;
        font-size: 25px;
        border-radius: 8px
    }

    .container h1 {
        text-align: centre;
    }

    .container buttom {
        display: black;
        width: 74%;
        margin: 20px auto;
    }
</style>

<body>
    <header class="header">
        <!--left box for navbar-->
        <div class="left">
            <background-image: url(gym.jpg) alt="" <div> Nipun Fitness club
        </div>
        </div>
        <!--mid box for navbar -->
        <div class="mid">
            <ul class="navbar">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#">About us</a></li>
                <li><a href="#">Fitness Calculator</a></li>
                <li><a href="#">ContactUS</a></li>
            </ul>
            
        </div>
        <!--right box for buttom-->
        <div class="right">
            <button class="btn">Call Us Now</button>
            <button class="btn">Email Us</button>

        </div>
    </header>
    <div class="container">
        
        <h1>Join the Best GYM of Delhi Now</h1>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your name" </div>
                <div class="form-group">
                    <input type="text" name="" placeholder="Enter your Age" </div>
                    <div class="form-group">
                        <input type="text" name="" placeholder="Enter your Gender" </div>
                        <div class="form-group">
                            <input type="text" name="" placeholder="Enter your Locality" </div>

                        <button class="btn">submit</button>
                        <form action="https://google.com">
                            
                            <input type="submit" value="search us on google" />
                             

                        </form>
                        <a href="https://www.w3schools.com">Visit our site</a>
        </form>
    </div>

</body>

</html>
