<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sushma - Developer Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="" stylesheet">

    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            background-color: rgb(0, 0, 33);
            color: white;
            font-family: 'Poppins', sans-serif;
        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: rgb(18, 18, 62);
        }

        nav ul {
            display: flex;
            justify-content: center;
        }

        nav ul li {
            list-style: none;
            color: white;
        }

        nav ul li {
            text-decoration: none;
            margin: 0 23px;
        }

        nav ul li a:hover {
            color: rgb(153, 153, 226);
            font-size: 1.02rem;
        }

        main hr {
            border: 0;
            background:#946db3;
            height:1.2px;
            margin:60px 84px;
        }

        .left {
            font-size: 1.2rem;
        }

        .firstSection {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 130px 0;
        }

        .firstSection>div {
            width: 30%;

        }

        .leftSection {
            font-size: 2.5rem;

        }
        .leftSection .buttons{
            padding: 50px 0;
        }
        .leftSection .btn{
           padding: 12px;
           background: #1e2167;
           color:white;
           border: 1px solid white;
           border-radius:5px;
           font-size:18px;
           cursor: pointer;


        }
        .rightSection img {
            width: 80%;

        }

        .purple {
            color: rgb(127, 44, 204);

        }

        .text-gray{
            color:gray
        }

        #element {
            color: blueviolet
        }

        .secondSection {
            max-width: 80vw;
            margin: auto;
            height:80vh;
        }

        .secondSection h1{
            font-size: 1.9rem;
        }

        .secondSection .box {
            background: white;
            width:77vw;
            height:2px;
            margin:56px 0;
            display:flex;
        }

        .secondSection .vertical{
            height: 93px;
            width: 1px;
            background-color: white;
            margin: 0 120px;
        }
        .image-top{
            width:23px;
            position:relative;
            top: -32px;
            left: -9px;
        }
        .vertical-title{
            position: relative;
            top:75px;
            width:150px;
            font-size: 14px;

        }

        .vertical-desc{
            position: relative;
            top:75px;
            width:150px;
            font-size: 9px;
        }
        footer{
            background-color: #19192c;
        }
        .footer{
           display:flex; 
           padding:23px 122px;
           justify-content: space-evenly;
        }
        .footer ul{
            list-style: none;
        }

        .footer > div{
            width:223px;
        }
        footer .footer-rights{
            text-align: center;
            color:gray;
            padding: 12px 0;
        }
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="left">Sushma's Portfolio</div>
            <div class="right"></div>
            <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/">About</a></li>
                <li><a href="/">Services</a></li>
                <li><a href="/">Projects</a></li>
                <li><a href="/">Contact Me</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="firstSection">
            <div class="leftSection">
                Hi, My name is <span class="purple">Sushma</span>
                <div>and I am a Passionate</div>

                <span id="element"></span>
                <div class="buttons">
                    <button class="btn">Download Resume</button>
                    <button class="btn">Visit Github</button>
                </div>
            </div>
            <div class="rightSection">
                <img src="developer.png" alt="" </div>
        </section>
        <hr>
        <section class="secondSection">
            <span class="text-gray">What I have done so far</span>
            <h1>Work Experience</h1>

           <div class="box">
            <div class="vertical">
                <img class="image-top" src="dv.png" alt="">
                <div class="vertical-title">
                    Android Developer (Intern 2024)
                </div>
                <div class="vertical-desc">
                    As an Android Developer Intern, 
                    I designed and build mobile applications for the Android platform.
                </div>
            </div>
            <div class="vertical">
                <img class="image-top" src="ev.png" alt="">
                <div class="vertical-title">
                    Electronics Industrial Trainee(NSIC)
                    </div>
                <div class="vertical-desc">
                    Gained hands-on experience in ece applications,
                    including circuit design, embedded systems, and industrial processes.
                </div>
            </div>
            
         
            
        </section>
    </main>
    <footer>
        <div class="footer">
            <div class="footer-first">
                <h3>Sushma's Developer Portfolio</h3>
            </div>
            <div class="footer-second">
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>Contact</li>
                </ul>
            </div>
           
        </div>
        <div class="footer-rights">
            Copyright@ sushmasportfolio.com | All rights reserved
        </div>
    </footer>
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
            strings: ['Web Developer', 'Electronics Engineer', 'Video Editor'],
            typeSpeed: 50
        });
    </script>
</body>

</html>
