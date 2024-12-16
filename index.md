<!DOCTYPE html>
<head>
    <meta name="viewport" content="width=device-width, intitial-scale=1.0">
    <title>Wuschdie Website</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.6.0/css/fontawesome.min.css">
</head>

<body>
<section class="header">
    <nav>
        <a href="index.html"><img src="images/"></a>
        <div class="nav-links" id="navLinks">
            <i class="fa fa-times" onclick="hideMenu()"></i>
            <ul>
                <li><a href="index.html" style="color: #CFB997;">HOME</a></li>
                <li><a href="geschichte.html">GESCHICHTE</a></li>
                <li><a href="gutscheine.html">GUTSCHEINE</a></li>
                <li><a href="bilder.html">BILDER</a></li>
            </ul>
        </div>
        <i class="fa fa-bars" onclick="showMenu()"></i>
    </nav>

<div class="text-box">
    <h1>Für meinen Schatz</h1>
    <p>
        ♥ Ich liebe dich so sehr ♥
    </p>
    <a href="Liebesbrief.html" class="hero-btn">Liebesbrief...</a>

<div class="footer">
    <p>Made with ♡ by Mac Schatz</p>
</div>

</section>

<!-----------JavaScript Toggle Menu------------>
<script>

    var navLinks = document.getElementById("navLinks");

    function showMenu(){
        navLinks.style.right = "0";
    }
    function hideMenu(){
        navLinks.style.right = "-200px";
    }

</script>

</body>

</html>
