# gym-project
this is my first project on web dev
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>www.ashimfitness.com</title>
</head>
<!-- <link rel="stylesheet" href="style.css"> -->
<style>
    body {
        margin: 0px;
        padding: 0px;
        background: url('img/gym7.jpg.jpg');
        color: white;
        background-size: 1200px 1000px;
    }

    .left {

        display: inline-block;
        position: absolute;
        left: 20px;
        top: 5px;
    }

    .left img {
        width: 56px;
        filter: invert(100%);
    }

    .left div {
        line-height: 20px;
        font-size: 20px;
        text-align: center;
        font-style: inherit;
    }

    .mid {

        display: block;
        width: 50%;
        margin: 5px auto;


    }

    .right {

        display: inline-block;
        position: absolute;
        right: 34px;
        top: 20px;
    }

    .navbar {
        display: inline-block;
    }

    .navbar li {
        display: inline-block;
        font-size: 23px;
    }

    .navbar li a {
        color: white;
        text-decoration: none;
        padding: 60px 23px;
    }

    .navbar li a:hover,
    .navbar li a:active {
        text-decoration: underline;
        color: gray;
    }

    .btn {
        margin: 0px 9px;
        background-color: rgb(63, 62, 62);
        color: white;
        padding: 4px 14px;
        border: 2px solid gray;
        border-radius: 10px;
        font-size: 15px;
        cursor: pointer;
    }

    .btn:hover {
        background-color: rgb(192, 186, 186);
    }

    .container {

        margin: 160px 80px;
        padding: 75px;
        width: 33%;
        border-radius: 28px;
    }

    .form-group input {
        text-align: center;
        display: block;
        width: 504px;
        padding: 1px;
        border: 2px solid black;
        margin: 11px auto;
        font-size: 25px;
        border-radius: 8px;

    }

    .container h1 {
        text-align: center;
    }

    .container button {
        display: block;
        width: 102%;
        margin: 20px auto;

    }
</style>


<body>
    <header class="header">
        <!-- left box for logo -->
        <div class="left">
            <div class="left">
                <img src="img/logo3-removebg-preview.png" alt="">
                <div>Fitness</div>
            </div>

        </div>
        <!-- mid box for nav bar -->
        <div class="mid">
            <ul class="navbar">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#">About us</a></li>
                <li><a href="#">Fitness calculator</a></li>
                <li><a href="#">Contact us</a></li>
            </ul>
        </div>
        <!-- right box for buttons -->
        <div class="right">
            <button class="btn">Call Us</button><button class="btn">Email</button>
        </div>
    </header>
    <div class="container">
        <h1>Join the best gym of Kamakhyaguri now to get 33% off !</h1>
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
                <input type="text" name="" placeholder="Enter your Address">
            </div>
            <button class="btn">Submit</button>
        </form>
    </div>



</body>

</html>
