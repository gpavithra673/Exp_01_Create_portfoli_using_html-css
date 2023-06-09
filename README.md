# EXP 01 - PORTFOLIO

## AIM:

To create a portfolio using HTML and CSS

## ALGORITHM:

1. Set up the basic structure of your HTML document.

2. Create a CSS file named "styles.css" and link it to your HTML document. This file will contain the CSS rules for styling your portfolio.

3. Design the layout of your portfolio using HTML elements such as < header >, < nav >, < section >, < article >, and < footer >. Use appropriate classes or IDs to style these elements later with CSS.

4. Add a header section to display your name or the title of your portfolio.

5. Add images or media to enhance your portfolio. You can use the <img> tag to display images and embed videos or other media using appropriate HTML tags.

6. Apply responsive design techniques to ensure your portfolio looks good on different devices and screen sizes. Use CSS media queries to adjust the layout and styling as needed.

7. Apply CSS styling to your portfolio elements by targeting their respective classes or IDs in the "styles.css" file. Customize the colors, fonts, spacing, and other visual properties to match your desired design.

## CODE:

### HTML CODE:

<!DOCTYPE html>
<html lang="en">
<head>
    <title>PORTFOLIO</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="topbanner.png" id="banner" style="height: 100%; width: 100%;">
        <p class="menubar m1">Details</p>
        <p class="menubar m2">Technical Skillsets</p>
        <p class="menubar m3">Soft Skills</p>
        <p class="menubar m4">Connect</p>
        <h1 id="name">Aashima Nazreen</h1>
        <h4 id="info">just another AI developer in the making.</h4>      
    </header>
    <div class="myinfo">
        <br><br><br><br><br><br>
        <div class="container">
            <img src="myinfor.jpg" id="study" style="padding: 50px; height: 80%;">
            <p id="title">ABOUT ME: </p>
            <p id="description">Student in Artificial Intelligence & Machine Learning. Fast learner <br>and quite adaptable to the work environment. Looking forward to <br>take part in IoT related projects. </p>
            <p id="title2">OBJECTIVE: </p>
            <p id="description2">To secure a responsible career within a respectable company, so that I am <br>able to fully utilize my training skills and make contributions for the success <br>of the company.</p>
        </div>
    </div>
    <div class="myinfo">
        <br><br><br><br><br><br>
        <div class="layer">
            <div class="box1 c1">
                <center>
                <br><br><br>
                <img src="codeblue.png" class="icon" style="height: 70px; width: 70px;">
                <p class="skill">CODING</p>
                </center>
            </div>
            <div class="box1 c2">
                <center>
                <br><br><br>
                <img src="machineblue.png" class="icon" style="height: 70px; width: 70px;">
                <p class="skill">CORE AREAS</p>
                </center>
            </div>
            <div class="box1 c3">
                <center>
                <br><br><br>
                <img src="webdblue.png" class="icon" style="height: 80px; width: 80px;">
                <p class="skill">WEB DESIGN</p>
                </center>
            </div>
            <div class="box1 c4">
                <center>
                <br><br><br>
                <img src="prodblue.png" class="icon" style="height: 70px; width: 70px;">
                <p class="skill">PRODUCT <BR> DEVELOPMENT</p>
                </center>
            </div>

            <div class="box2 c5">
                <center>
                <br><br>
                <p class="des">Well learned in programming languages like Python, Java and C Programming</p>
                </center>
            </div>
            <div class="box2 c6">
                <center>
                <br><br>
                <p class="des">Core areas of learning include Machine Learning, IoT, Data Science, Neural Networks, etc</p>
                </center>
            </div>
            <div class="box2 c7">
                <center>
                <br><br>
                <p class="des">Confident in Web Design & Development, UI/UX Designs and Wireframe Creations</p>
                </center>
            </div>
            <div class="box2 c8">
                <center>
                <br><br>
                <p class="des">Basic skills in Product Development including AutoCAD Fusion 360 & 3D Printing</p>
                </center>
            </div>
        </div>
    </div>
    <div class="myinfo">
        <br><br>
        <div class="containersoft">
            <img src="soft1.png" id="softskills" style="padding: 50px; height: 70%;">
            <p id="skillset">SOFT SKILLS:</p>
            <ul id="tasks">
                <li>Problem Solving Skills</li>
                <li>Time Management</li>
                <li>Creative</li>
                <li>Adaptability</li>
                <li>Inter Personal Skills</li>
                <li>Stress Management</li>
                <li>Critical Thinking</li>
            </ul>
        </div>
        <br><br><br><br><br><br>
        <div class="footer">
            <div class="frame">
                <p id="contact" style="padding-top: 20px;">Connect With Me:</p>
                <a href="https://github.com/Aashima02"><button class="button1" style="margin-left: 100px; margin-right: 100px;">GitHub </button></a>
                <a href="https://www.linkedin.com/in/aashima-nazreen-s-953074236/"><button class="button1" style="margin-left: 100px; margin-right: 100px;">LinkedIn</button></a>
                <a href="https://mail.google.com/mail/?view=cm&source=mailto&to=aashisayeed@gmail.com"><button class="button1" style="margin-left: 100px; margin-right: 100px;">Gmail</button></a>
            </div>
        </div>
    </div>
</body>
</html>


### CSS CODE:

body{
    margin: 0%;
}
header {
    height: 712px;
    width: 100vw;
    background: rgb(156, 115, 61);
    overflow: hidden;
}
#banner {
   object-fit: cover;
   opacity: 0.5;
}
.menubar{
    position: absolute;
    color: #ffffff;
    font-family: Garamond, serif;
    font-size:x-large;
    top: 0%;   
    font-weight: 300;
    cursor: pointer;
}
#name{
    position: absolute;
    top: 30%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: #ffffff;
    font-family: Garamond, serif;
    font-size: 610%;
}
#info{
    position: absolute;
    top: 45%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: #ffffff;
    font-family: 'Trebuchet MS', sans-serif;
    font-size: 200%;
}
.myinfo{
    height: 712px;
    width: 100vw;
    background: rgb(232, 223, 197);
}
.container{
    display: block;
    width: 70%;
    background-color: rgb(255, 255, 255);
    height: 70%;
    margin-left: auto;
    margin-right: auto;
    border-radius: 30px;
}
#study{
    border-radius: 80px;
}
#title{
    position: absolute;
    top: 130%;
    left: 43%;
    font-size: 23px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-weight: bold;
    color: #605e5e;
}
#description
{
    position: absolute;
    top: 137%;
    left: 43%;
    font-size: 20px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    color: rgb(134, 119, 79);
}
#title2{
    position: absolute;
    top: 150%;
    left: 43%;
    font-size: 23px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-weight: bold;
    color: #605e5e;
}
#description2
{
    position: absolute;
    top: 157%;
    left: 43%;
    font-size: 20px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    color: rgb(134, 119, 79);
}
.layer{
    display: block;
    width: 100%;
    background-color: #6f7ca3;
    top: 500%;
    height: 70%;
}
.box1{
    height: 50%;
    width: 20%;
    background-color: #ffffff;
}
.box2{
    height: 50%;
    width: 20%;
    background-color: #857f7f;
}
.c5:hover, .c6:hover, .c7:hover, .c8:hover {
    transition-duration: 0.1s;
    background-color: #6f7ca3;
}
.skill{
    color: #6f7ca3;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-weight:200;
    margin-left: 4%;
    font-size: x-large;
}
.des{
    color: #ffffff;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-weight:200;
    margin-left: 8%;
    margin-right: 8%;
    font-size: x-large;
}
.containersoft{
    display: block;
    width: 50%;
    background-color: #6f7ca3;
    height: 50%;
    margin-left: auto;
    margin-right: auto;
    border-radius: 30px;
}
#softskills{
    border-radius: 80px;
    margin-top: 2px;
}
#skillset{
    position: absolute;
    top: 317%;
    left: 50%;
    font-size: 30px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-weight: bold;
    color: #d1cece;
}
#tasks{
    position: absolute;
    top: 325%;
    left: 50%;
    font-size: 20px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-weight: 100;
    color: #d1cece;
}
.footer{
    display: block;
    width: 100%;
    background-color: #a29d9d;
    height: 100px;
    margin-top: 7%;
}
.frame{
    width: 1000px;
    margin-left: auto;
    margin-right: auto;
}
#contact{
    color: #ffffff;
    font-weight: bolder;
    font-size: 200%;
    padding-top: 0%;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.button1{
    top: 10%;
    padding: 15px;
    padding-left: 30px;
    padding-right: 30px;
    font-size: 20px;
    background-color:rgb(232, 223, 197);
    border-radius:50px;
    color: #777474;
    border:none;
    font-family: sans-serif;
    font-weight: bold;
    cursor: pointer;
    left: 100%;
} 
.button1:hover {
    transition-duration: 0.1s;
    background-color: rgb(255, 255, 255);
    border: 3px solid rgb(232, 223, 197);
}


## OUTPUT:
![Screenshot (59)](https://github.com/gpavithra673/Exp_01_Create_portfoli_using_html-css/assets/93427264/9137fc51-899a-4d52-8420-7924b31c2d80)

![image](https://github.com/gpavithra673/Exp_01_Create_portfoli_using_html-css/assets/93427264/32402ad8-3c00-4e5d-b031-f11abb05aa15)

## RESULT:

Thus, a Portfolio is created using HTML and CSS.
