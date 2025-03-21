# surya
Html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ice Cream Delights</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #e4fafc;
        }
        .logo {
            margin-top: 20px;
        }
        h1 {
            font-size: 48px;
            color: #d81b60;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            text-decoration: none;
            color: #fff;
            background: #e91e63;
            padding: 10px 20px;
            border-radius: 5px;
            margin: 0 10px;
        }
        nav a:hover {
            background: #c2185b;
        }
        .description {
            font-size: 20px;
            line-height: 1.6;
            color: #444;
            margin: 20px auto;
            max-width: 800px;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .flavours {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin: 20px 0;
        }
        .flavours img {
            width: 30%;
            border-radius: 10px;
        }
        .videos {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 20px 0;
        }
        .videos video {
            width: 45%;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <div class="logo">
        <img src="ice-cream-logo.jpg" alt="Ice Cream Logo">
    </div>

    <h1>ICE CREAM DELIGHTS</h1>
    
    <nav>
        <a href="Home.html">Home</a>
        <a href="About.html">About</a>
        <a href="Services.html">Services</a>
    </nav>
    
    <div class="description">
        <p>Ice cream is a frozen dessert typically made from milk or cream that has been flavored with a sweetener, either sugar or an alternative, and a spice, such as cocoa or vanilla, or with fruit, such as strawberries or peaches. Food coloring is sometimes added in addition to stabilizers. The mixture is cooled below the freezing point of water.</p>
    </div>

    <hr>
    
    <h1>The Flavours Of Core Ice</h1>
    <div class="flavours">
        <img src="The-Baked-Bear-15.jpg" alt="Flavor 1">
        <img src="OIP (2).jpg" alt="Flavor 2">
        <img src="ice-cream.webp" alt="Flavor 3">
    </div>
    
    <hr>
    
    <h1>Our Services</h1>
    <div class="videos">
        <video src="ice cream viedo.mp4" controls></video>
    </div>
</body>
</html>

