This is vaibhav,
This is an illustration for creating the portfolio with HTML5 and CSS.
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Complete Responsive Personal Portfolio Website HTML CSS Javascript </title>
    <link rel="stylesheet" href="CSS/style.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
</head>
<body>
    <header class="header">
        <a href="#" class="logo">Vaibhav</a>

        <div class="bx bx-menu" id="menu-icon"></div>

        <nav class="navbar">
            <a href="#home" class="active">Home</a>
            <a href="#about">About</a>
            <a href="#education">Education</a>
            <a href="#skills">Skills</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    
<section class="home" id="home">
    <div class="home-content">
     <h1>Hi, I'm <span>Vaibhav Mishra</span></h1> 
     <div class="text-animate">
        <h3>Web Developer</h3>
     </div>
     <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Qui ex facere non quidem nulla provident maiores eum doloremque dignissimos, aliquid in. Dolore itaque sequi consequatur eaque ad quaerat accusamus veniam.</p>  
    
     <div class="btn-box">
        <a href="#" class="btn">Hire Me</a>
        <a href="#" class="btn">Let's Talk</a>
     </div>
   </div>

    <div class="home-sci">
      <a href="#"><i class='bx bxl-facebook' ></i>></a>
      <a href="#"><i class='bx bxl-twitter' ></i></a>
      <a href="#"><i class='bx bxl-linkedin' ></i></a>
   </div>

   <div class="home-imghover"></div> 

</section>

<section class="about" id="about">
    <h2 class="heading">About <span>Me</span></h2>

    <div class="about-img">
     <img src="Image/self.png" alt="">
     <span class="circle-spin"></span>
   </div>

   <div class="about-content">
    <h3>Web Developer</h3>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque maxime commodi qui voluptate, ipsam eligendi optio a odit alias saepe, deleniti, sit enim. Ipsum delectus laudantium illum a quo libero.</p>

     <div class="btn-box btns">
        <a href="#" class="btn">Read More</a>
     </div>
   </div>

</section>

<section class="education">
    <h2 class="heading">My <span>Journey</span></h2>

    <div class="education-row">
        <div class="education-column">
            <h3 class="title">Education</h3>

            <div class="education-box">
                <div class="education-content">
                    <div class="content">
                        <div class="year"><i class='bx bx-calendar' ></i>2022-2025</div>
                        <h3>Graduation B.Tech in Computer Science</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. At mollitia excepturi quos in ab quod accusamus officiis quis? Sunt repellendus incidunt numquam nemo id minus aut dicta ut repellat sapiente.</p>
                    </div>
                </div>

                <div class="education-content">
                    <div class="content">
                        <div class="year"><i class='bx bx-calendar' ></i>2020-2022</div>
                        <h3>Diploma in Electrical </h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. At mollitia excepturi quos in ab quod accusamus officiis quis? Sunt repellendus incidunt numquam nemo id minus aut dicta ut repellat sapiente.</p>
                    </div>
                </div>

                <div class="education-content">
                    <div class="content">
                        <div class="year"><i class='bx bx-calendar' ></i>2017-2018</div>
                        <h3>Intermediate Education </h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. At mollitia excepturi quos in ab quod accusamus officiis quis? Sunt repellendus incidunt numquam nemo id minus aut dicta ut repellat sapiente.</p>
                    </div>
                </div>

                <div class="education-content">
                    <div class="content">
                        <div class="year"><i class='bx bx-calendar' ></i>2015-2016</div>
                        <h3>Matric Education</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. At mollitia excepturi quos in ab quod accusamus officiis quis? Sunt repellendus incidunt numquam nemo id minus aut dicta ut repellat sapiente.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<section class="skills" id="skills">
    <h2 class="heading">My <span>Skills</span></h2>
    <div class="skills-row">
        <div class="skills column">
            <h3 class="title">Coding Skills</h3>

            <div class="skills-box">
                <div class="skills-content">
                    <div class="progress">
                        <h3>HTML <span>80%</span></h3>
                        <div class="bar"><span></span></div>
                    </div>
                    <div class="progress">
                        <h3>CSS <span>80%</span></h3>
                        <div class="bar"><span></span></div>
                    </div>
                    <div class="progress">
                        <h3>Javascript<span>60%</span></h3>
                        <div class="bar"><span></span></div>
                    </div>
                    <div class="progress">
                        <h3>Python <span>70%</span></h3>
                        <div class="bar"><span></span></div>
                    </div>
                </div>
            </div>
        </div>
        <div class="skills column">
            <h3 class="title">Professional Skills</h3>

            <div class="skills-box">
                <div class="skills-content">
                    <div class="progress">
                        <h3>Web Development <span>70%</span></h3>
                        <div class="bar"><span></span></div>
                    </div>
                    <div class="progress">
                        <h3>Java Core <span>75%</span></h3>
                        <div class="bar"><span></span></div>
                    </div>
                    <div class="progress">
                        <h3>Database <span>90%</span></h3>
                        <div class="bar"><span></span></div>
                    </div>
                    <div class="progress">
                        <h3>Cloud Developer <span>70%</span></h3>
                        <div class="bar"><span></span></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

</body>
</html>
