<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TeeGee TechBro Portfolio</title>
    <link rel="stylesheet" href="tee.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.1/font/bootstrap-icons.css">
</head>

<body>

    <h1>TeeGee TechBro</h1>
    <nav id="mynav" class="navbar">
        <a href="projects.html">My Projects and Skills</a>
        <a href="about.html">About Me</a>
    </nav>

    <div class="doit">
        <img src="pic20.jpg" alt="coding tags" class="do">
        <img src="pic21.jpg" alt="coding tags" class="it">
        <a class="stay" onclick="prev()"><p><b><</b></p></a>
        <img class="pic" id="slider" src="pic9.jpg" alt="TeeGee TechBro ">
        <a class="move" onclick="next()"><p><b>></b></p></a>
        <img src="pic22.jpg" alt="coding tags" class="yh">
    </div>
    <script>
        var images = ["pic9.jpg", "pic4.jpg", "pic6.jpg", "pic3.jpg", "pic2.jpg"];
        var num = 0;

        function next() {
            var slider = document.getElementById("slider");
            num++;
            if (num >= images.length) {
                num = 0;
            }
            slider.src = images[num];
        }

        function prev() {
            var slider = document.getElementById("slider");
            num--;
            if (num <
                0) {
                num = images.length - 1;
            }
            slider.src = images[num];
        }
    </script>
    <h2>
        To achieve something great in life, you have to wait for a longer period of time. Like they say," NOTHING GOOD COMES EASY ". Peace.
    </h2>

    <div class="all ">
        <div class="bot ">
            <img class="pic14 " src="pic14.jpg " alt="FRONT-END DEVELOPERS ">
        </div>
        <div class=" both ">
            <img class="pic13 " src="pic13.jpg " alt="BACK-END DEVELOPERS ">
        </div>
        <div class="both ">
            <img class="pic10 " src="pic10.jpg " alt="FULL-STACK DEVELOPERS ">
        </div>
    </div>


    <div class="together ">
        <h2
            <i>FRONT-END DEVELOPERS</i>
        </h2>
        <h2>
            <i>BACK-END DEVELOPERS</i>
        </h2>
        <h2>
            <i>FULL-STACK DEVELOPER</i>
        </h2>
    </div>

    <aside>
        <h1>
            CONTACT OR HIRE ME
        </h1>
        <div class="contact ">
            <br><br>
            <a href="https://www.facebook.com/profile.php?id=100086218393511 "><i class="bi bi-facebook "></i></a>
            <a href="https://twitter.com/teegeeofafrica"><i class="bi bi-twitter "></i></a>
            <a href="https://www.instagram.com/therealteegeeofafrica/"><i class="bi bi-instagram "></i></a>
            <a href="https://www.linkedin.com/in/thankgod-uzochukwu"><i class="bi bi-linkedin "></i></a>
            <a href="https://tiktok.com/@therealteegeeofafrica"><i class="bi bi-tiktok "></i></a>
        </div>
        <div class="get ">
            <div class="app ">
                <h3>
                    <i>ANDRIOD APP</i>
                </h3>
                <h3>
                    <i>IOS APP</i>
                </h3>
            </div>
            <div class="hey ">
                <img class=" pic30 " src=" pic30.jpg " alt="ANDRIOD APP ">
                <img class="pic25 " src="pic25.jpg " alt="IOS APP ">
            </div>
        </div>

    <footer>
        <p class="foot ">
            &copy; TEEGEE TECHBRO. All Rights Reserved &#9776;
        </p>
    </footer>
