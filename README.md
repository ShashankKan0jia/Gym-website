# Gym-website
This is a gym website, that I have made for my HTML project.
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Gold Fitness</title>
</head>
<link href="https://fonts.googleapis.com/css?family=Baloo+Bhai&display=swap" rel="stylesheet">
<link rel="stylesheet" href="css/style.css">
<style>
    /* CSS Reset */
    body {
        font-family: 'Baloo Bhai', cursive;
        color: rgb(249, 245, 245);
        margin: 0px;
        padding: 0px;
        background: url('img/bg.jpg');
    }

    .left {
        display: inline-block;
        /* border: 2px solid red; */
        position: absolute;
        left: 10px;
        top: 10px;
    }

    .left img {
        width: 136px;
        filter: invert(100%);
    }

    .left div {
        line-height: 19px;
        font-size: 26px;
        text-align: center;
    }

    .mid {
        display: block;
        width: 65%;
        margin: 10px auto;
        /* border: 2px solid green; */
    }

    .right {
        position: absolute;
        right: -15px;
        top: 0px;
        display: inline-block;
        /* border: 2px solid yellow; */
    }

    .navbar {
        display: inline-block;
    }

    .navbar li {
        display: inline-block;
        font-size: 25px;
    }

    .navbar li a {
        color: white;
        text-decoration: none;
        padding: 34px 23px;

    }

    .navbar li a:hover,
    .navbar li a.active {
        text-decoration: underline;
        color: grey;

    }

    .btn {
        font-family: 'Baloo Bhai', cursive;
        margin: 20px 15px;
        background-color: black;
        color: white;
        padding: 4px 14px;
        border: 2px solid grey;
        border-radius: 10px;
        font-size: 20px;
        cursor: pointer;
    }

    .btn:hover {
        background-color: rgb(31, 30, 30);
    }

    .container {
        border: 2px solid white;
        margin: 106px 80px;
        padding: 75px;
        width: 33%;
        border-radius: 28px;
    }

    .form-group input {
        font-family: 'Baloo Bhai', cursive;
        text-align: center;
        display: block;
        width: 400px;
        padding: 1px;
        border: 10px solid black;
        margin: 20px auto;
        font-size: 25px;
        border-radius: 8px;
    }

    .container h1 {
        text-align: center;
    }

    .container button {
        display: block;
        width: 74%;
        margin: 20px auto;
    }

    /* this is container 2 */
    .container2 {
        border: 2px solid white;
        margin: -600px 800px;
        padding: 75px;
        width: 33%;
        border-radius: 28px;
        font-size: 30px;
    }
</style>

<body>
    <header class="header">
        <!-- Left box for logo -->
        <div class="left">
            <img src="img/gym.png" alt="">
            <div>Gold Fitness</div>
        </div>
        <!-- Mid box for navbar -->
        <div class="mid">
            <ul class="navbar">
                <li><a href="#" class="active">Register</a></li>
                <li><a href="#">Training</a></li>
                <li><a href="#">Timetable</a></li>
                <li><a href="https://drive.google.com/drive/folders/14qKMEo9xMpoAu_A5YypwRjq4gCKzxWVN" target="_blank">Gallery</a></li>
                <li><a href="about.html" target="_blank">About</a></li>
            </ul>
        </div>

        <!-- Right box for buttons -->
        <div class="right">
            <button class="btn">Insta.</button>
            <button class="btn">FB</button>
        </div>
    </header>
    <div class="container">
        <h1>Become a member now!!</h1>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Name">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Age">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Gender">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Phone Number">
            </div>
            <button class="btn">Submit</button>
        </form>
    </div>
    <div class="container2">
        Basic facility : ₹5000 /month                                     Standard Facility : ₹7000 / month                                         Premium Facility : ₹10,000 / month

    </div>
</body>

</html>
