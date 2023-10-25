<!DOCTYPE html>
<html>
    <head>
      <tittle></tittle>
      <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: rgb(243, 195, 233);
         }

         header {
            background-color: #383434;
            color: #e6dada;
            text-align: center;
            padding: 2rem 0;
            position:relative; /* Add this */
         }

         .header-content h1 {
            font-size: 2.5rem;
         }

         /* Add styles for the round profile picture */
         .profile-picture {
            width: 150px;
            height: 150px;
            border-radius: 75%;
            object-fit: cover;
            position: absolute;
            top: 75px;
            left: 75px;
         }

         nav {
            background-color: #333;
            color: #fff;
            text-align: center;
        }

        nav ul li {
            display: inline;
            margin: 0 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: #fff;
        }

        .section-content {
            background-color: #fff;
            padding: 2rem;
            margin: 1rem;
            border-radius: 20px;
            box-shadow: 0 0 10px rgba( 0, 0, 0,0.1);
        }

        .download-button {
            background-color: #333;
            color: #fff;
            padding: 0.5rem 1rem;
            text-decoration: none;
            border-radius: 20px;
            display: inline-block;
            margin-top: 10px;
        }

        .download-button:hover {
            background-color: #555;
        }

        footer {
            text-align: center;
            padding: 1rem;
            background-color: #333;
            color: #ffffff;
        }

        ul {
            list-style-type: cicle;
            padding-left: 21px;
        }
     </style>
</head>
<body>
    <header>
        <div class="header-content">
            <img src="praveen.img.jpg" alt="your profile-picture" class="profile-picture">
            <h1>PRAVEEN S</h1>
            <p>I LOVE CODING</p>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#my self">My Self</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#resume">Resume</a></li>
        </ul>
    </nav>

    <section id="about">
        <div class="section-content">
            <h2>About Me</h2>
            <p>Hi Guys! I am Praveen S and I am a Bsc Student </p>          
        </div>
    </section>

    <section id="education">
        <div class="section-content">
            <h2>Education</h2>
            <p>Annai Vailankanni Arts and Science collge-BSC(Computer Science) </p>
        </div>

    </section>

    <section id="skills">
        <div class="section-content">
            <h2>Skills</h2>
            <ul>
                <li>web designing</li>
                <li>Python</li>
                <li>programming</li>
            </ul>
        </div>

    </section>

    <section id="Resume">
        <center>
          <div class="section-content">
            <h2>Resume</h2>
            <embed src="Praveen resume.pdf" type="application/pdf" width="100%" height="500"/>
         </div>    
        </center>

    </section>
</body>
</html>
