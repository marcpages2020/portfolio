<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8"/>
        <meta name="description" content="Personal Portfolio"/>
        <meta name="keywords" conent="Game,Developer,Portfolio,Programmer"/>
        <meta name="author" content="Marc Pagès Francesch"/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <title>Marc Pagès Francesch | Game Developer</title>
        <link rel="stylesheet" href="style.css"/>
        <link href='https://fonts.googleapis.com/css?family=Carter One' rel='stylesheet'>
    </head>

<body style="background-color: #333;">

    <!--Banner-->
    <div class="blurred-banner-image"></div>
    <div class="banner">
        <!-- Big beginning-->
        <h1 style="font-size: 4vw; font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif">Marc Pagès Francesch</h1>
        <h2 style="font-size: 3vw; font-family: Verdana, Geneva, Tahoma, sans-serif;">Game Developer</h2>
    </div>

    <!--Navbar-->
    <div id="navbar">
        <a href="#AboutMe">About Me</a>
        <a href="#Projects">Projects</a>
        <a href="#Contact">Contact</a>
    </div>

    <!--About Me-->
    <div id="AboutMe">
    <h2 class="white-header">About Me</h2>
    <div class="row">
        <div class="col-7" style="padding-left: 2.5%;"> 
            <p class="paragraph" style="padding-bottom: 5%;">
                Born in Reus on 28th of June of 2000. Due to my passion for video games and my interest in computer science and graphics I started my video game development degree in CITM in Terrassa. 
                I like doing sport, travelling, cooking, reading and learning all kind of things, from history to science. Trying to improve a little bit every day is my main goal!
                I'm proficient in C and C++ and quite comfortable scripting in HTML. <br>
                I can use 3D software such as 3Ds Max and Maya but the one I'm most used to is Blender. I'm quite experienced in Adobe Photoshop, Illustrator and Premiere. <br>
            </p>
            <a href="documents/Marc Pagès Francesch.pdf" class="cv-button"><b>CV</b></a>
        </div>
        <div class="col-4" > 
            <img src="/photos/personal_pic3.png" alt="Personal Picture" style="width: 100%">
        </div>
    </div>

    </div>
    
    <!--Projects-->
    <div  id="Projects" class="light-section">
        <h2 class="white-header">Projects</h2>
        <div class="row">
            <div class="col-4 container" onClick="openUrlInNewTab('https://kalima-entertainment.github.io/Fallout_Strategy/index.html');">
                <img src="photos/fallout-strategy.png" alt="Fallout Strategy">
                <div class="overlay">
                    <div class="text">Fallout Strategy</div>
                  </div>
            </div>
            <div class="col-4 container" onClick="openUrlInNewTab('https://marcpages2020.github.io/Samurai-Shodown/');">
                <img src="photos/samurai_shodown.png" alt="Samurai Shodown">
                <div class="overlay">
                    <div class="text">Samurai Shodown</div>
                  </div>
            </div>
            <div class="col-4 container" onClick="openUrlInNewTab('https://windfog-studios.github.io/The-Little-Explorer/');">
                <img src="photos/the_little_explorer.png" alt="The Little Explorer">
                <div class="overlay">
                    <div class="text">The Little Explorer</div>
                  </div>
            </div>
        </div>
    </div>

    <!--Contact-->
    <div id="Contact" style="background-color: whitesmoke;">
        <h2 class="black-header" style="padding-top: 2vw; padding-bottom: 1vw; margin: auto;">Contact</h2>
        <div style="padding-left: 39%;">
            <a href="https://github.com/marcpages2020"><img src="icons/github.png" alt="github" style="width: 7vw;"></a>
            <a href="https://www.linkedin.com/in/marc-pagès-francesch-7206b3186/"><img src="icons/linkedin.png" alt="github" style="width: 7vw;"></a>
            <a href="https://twitter.com/MarcPF22?s=08"><img src="icons/twitter.png" alt="github" style="width: 7vw;"></a>
        </div>
        <h2 style="text-align: center; padding-top: 2vw; padding-bottom: 1vw; font-size: 1.5vw;">marcpages13@gmail.com</h2>

     <!--Recognition-->
    <div style="text-align: center; background-color: whitesmoke; padding-bottom: 1vw;">Icons made by <a href="https://www.flaticon.com/authors/freepik" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>
    </div>

    <!--scripting-->
    <script>
        window.onscroll = function() {stickyNavbar()};
        var navbar = document.getElementById("navbar");
        var sticky = navbar.offsetTop;

        function stickyNavbar(){
            if (window.pageYOffset >= sticky){
                navbar.classList.add("sticky")
            }else{
                navbar.classList.remove("sticky");
            }
        } 

    function openUrlInNewTab(url){
        window.open(url, "_blank");
    }
    </script>

</body>
</html>