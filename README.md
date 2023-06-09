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
### Main page
```
<!DOCTYPE html>
<html>
    <head>
        <title>Portfolio</title>
        <link rel="icon" href="./icon.png" type="icon" />
        <link href="./stylesheet.css" rel="stylesheet">
    </head>
    <body>
        <div style="background-image: url(./bg4.jpg); background-size: cover; border-left: 8px dotted #2F234B;">
        <div class="header">
            <div class="header_elements"><a href="./service.html" style="text-decoration: none; color:#2F234B">
                Portfolio
            </div></a>
            <div class="header_elements"><a href="./service.html" style="text-decoration: none; color:#2F234B;">
                Services
            </div></a>
            <div class="header_elements"><a href="./service.html" style="text-decoration: none; color:#2F234B;">
                Contact me
            </div></a>
        </div>
        <div class="content">
            <div class="content_elements" style="padding-top: 140px; padding-left: 100px;">
                <div style="font-size: 50px; color: #fdfdfd;">Hello there, Myself<br>
                <div style="font-size: 60px; color: #170a35;">PAVITHRA<br>
                    <div style="font-size: 20px; color: #2F234B;">AIML dept<br><br>
                    <div style="font-size: 18px; color: #380948;" >I have completed my BTech.AIML and very much interested in<br>
                    expanding my knowledge in this field. I Would like to keep myself updated<br>
                and i m very much interested in learning new things.</div>
                </div>
                </div>
                </div>
            </div>
            <div class="content_elements" style="padding-top: 100px; padding-left: 100px;">
                <div style="padding-left: 100px;">
                    <div class="photo">
                    </div>
                </div>
            </div>
        </div>
        <div class="content">
            <div class="content_elements">
                <div style="padding-left: 150px;">
                    <div class="hireme">
                        Hire Me
                    </div>
                </div>
            </div>
        </div>
    </body>
</html>
```
### Service page:
```
<!DOCTYPE html>
<html>
    <head>
        <title>Service</title>
        <link rel="icon" href="./icon.png" type="icon" />
        <link href="./styling.css" rel="stylesheet">
        <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bruno+Ace&family=Josefin+Sans:ital@1&family=Sigmar&display=swap" rel="stylesheet">
    </head>
    <body>
        <div class="header">
            <div style="align-content: center; font-size: 50px; color: rgb(5, 1, 50); font-family:  'Josefin Sans', sans-serif;
            font-family: 'Sigmar', cursive; padding-left: 650px; padding-bottom: 75px;">Profile</div>
        </div>
        <div class="serve">
            <div style="padding-top: 0px; display: flex;
            flex-direction: column;
            justify-content: space-around;"><div class="photos" style="background-image: url(./communication.jpg); background-size: cover;"></div>
            <div class="photos" style="background-image: url(./dedicated.jpg); background-size: cover;"></div>
            </div>

            <div class="serve_element">
                <div style="font-size: 35px; color: rgb(9, 19, 72); font-family: 'Bruno Ace', cursive;
                font-family: 'Josefin Sans', sans-serif;
                font-family: 'Sigmar', cursive;">Education:</div>
                <br>
                High School: Vivekanandha vidyalaiya junior college<br>
                UG: Saveetha ENgineering College<br>
                Course: BTech.AIML
            </div>
            <div class="serve_element"><div style="font-size: 35px; color: rgb(9, 19, 72); font-family: 'Bruno Ace', cursive;
                font-family: 'Josefin Sans', sans-serif;
                font-family: 'Sigmar', cursive;">Soft Skills:</div><br>
                <ul>
                    <li>Good communication skills</li>
                    <li>Good in team work</li>
                    <li>Easily adaptable</li>
                    <li>Good in balancing emotion</li>
                </ul>
            </div>
            <div style="padding-top: 0px; display: flex;
            flex-direction: column;
            justify-content: space-around;"><div class="photos" style="background-image: url(./teamwork.jpg); background-size: cover;"></div>
            <div class="photos" style="background-image: url(./hardwork.jpg); background-size: cover;"></div>
            </div>
        </div>
        <div class="serve" style="justify-content: space-between;">
            
            <div class="serve_element">
                <div style="font-size: 35px; color: rgb(9, 19, 72); font-family: 'Bruno Ace', cursive;
                font-family: 'Josefin Sans', sans-serif;
                font-family: 'Sigmar', cursive;">Technical Skills:</div><br>
                C<br>
                Java<br>
                python<br>
                Webtechnolgy(frontend)<br>
                Snap AR<br>
                Spark AR<br>
            </div>
            <div class="serve_element" ><div style="font-size: 35px; color: rgb(9, 19, 72); font-family: 'Bruno Ace', cursive;
                font-family: 'Josefin Sans', sans-serif;
                font-family: 'Sigmar', cursive;">Language:</div><br>
                <br>English
                <br>Telugu
                <br>Tamil
                <br>German
            </div>
            <div class="serve_element">
                <div class="text"><div style="font-size: 35px; color: rgb(9, 19, 72); font-family: 'Bruno Ace', cursive;
                    font-family: 'Josefin Sans', sans-serif;
                    font-family: 'Sigmar', cursive;"> Contact:</div>
                <div class="text" style="padding-top: 50px;">
                    <a href="pavithra0607gjm@gmail.com"><img src="https://icons-for-free.com/download-icon-google+mail+icon-1320192249286867468_512.png" style="width: 50px; height: 50px;"></a>
                </div>
                <div class="text">
                    <a href="https://github.com/gpavithra673"><img src="https://w7.pngwing.com/pngs/914/758/png-transparent-github-social-media-computer-icons-logo-android-github-logo-computer-wallpaper-banner-thumbnail.png" 
                        style="width: 50px; height: 50px;"></a>
                </div>
                <div class="text">
                    <a href="https://www.linkedin.com/in/pavithra-g-990442237/"><img src="https://assets.stickpng.com/images/6297a2f1e01809629f113598.png" 
                        style="width: 50px; height: 50px;"></a>
                </div>
            </div>
        </div>
    </body>
</html>
```
### CSS CODE:
```
*{
    font-family: 'Anuphan', sans-serif;
    font-family: 'Caveat', cursive;
    font-family: 'DynaPuff', cursive;
}
html{
    cursor: url(./cursor.png), auto;
}
body{
    margin: 0px;
}
.header{
    padding-top: 50px;
    padding-left: 1050px;
    display: flex;
    justify-content: flex-end;
    justify-content: space-between;
    padding-right: 15px;
}
.header_elements{

    display: inline-flex;
    font-size: 20px;
    font-weight: bold;
    border: 1px solid #2F234B;
    border-radius: 35px;
    padding: 10px;
    position: relative;
    background-color: #ffc3d4;
    color: #2F234B;
}
.header_elements:hover{
    animation: buttonup1 infinite;
    animation-duration: 0.6s;
    animation-direction:alternate;
    
}
@keyframes buttonup1 {
    from {top: 0px;}
    to {top: 10px;}
  }
.content{
    padding: 10px;
    display: flex;
}
.content_elements{
    display: inline-flex;
    padding: 10px;
    font-size: 25px;
}
.photo{
    padding: 50px;
    display: flex;
    width: 300px;
    height: 300px;
    border: 2px solid #2F234B;
    box-shadow: 50px 60px rgb(251, 202, 202);
    border-radius: 35px;
    animation: photocg 2s infinite;
    animation-direction: alternate;
    
}
@keyframes photocg{
     0% {
        background-image: url(./bg1.jpg);
        background-size: 400px 400px;
     }
     65% {
        background-image: url(./bg2.jpg);
        background-size: 400px 400px;
     }
     100% {
        background-image: url(./bg3.jpg);
        background-size: 400px 400px;
     }
}
.hireme{
    background-color: rgb(205, 249, 247);
    border: 2px solid #2F234B;
    border-radius: 20px;
    padding: 20px;
    font-size: 18px;
    font-weight: bold;
    color: #2F234B;
}
.hireme:hover{
    animation: button infinite;
    animation-duration: 0.6s;
    animation-direction:alternate;
    background-color: #2F234B;
    color:rgb(205, 249, 247);
}
@keyframes button{
    from {top: 0px;}
    to {top: 25px;}
 }
 .bg2{
    background-color: rgb(253, 181, 181);
    display: flex;
    height: 712px;
    width: 100vw;
    justify-content: space-evenly;
    border: 1px solid black;
 }
 .port{
    width: 100px;
    height:100px;
 }
 
.serve{
    display: flex;
    padding: 50px;
    justify-content: space-evenly;
}
.serve_element{
    height: 400px;
    width: 300px;
    font-size: 29px;
    font-weight: bold;
    font-family: Arial, Helvetica, sans-serif;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    border: 2px solid rgb(7, 7, 7);
    padding: 50px;
    border-radius: 25px;
    color: rgb(64, 15, 113);
    box-shadow: 10px -10px 0 -3px var(--background), 10px -10px var(--green),
        20px -20px 0 -3px var(--background), 20px -20px var(--yellow),
        30px -30px 0 -3px var(--background), 30px -30px var(--orange),
        40px -40px 0 -3px var(--background), 40px -40px var(--red);
}
.serve_element:hover {
    animation: shadow-wave 1s ease infinite;
  }
@keyframes shadow-wave {
    0% {
      border: 3px solid var(--primary);
      box-shadow: 10px -10px 0 -3px var(--background), 10px -10px var(--green),
        20px -20px 0 -3px var(--background), 20px -20px var(--yellow),
        30px -30px 0 -3px var(--background), 30px -30px var(--orange),
        40px -40px 0 -3px var(--background), 40px -40px var(--red);
    }
    20% {
      border: 3px solid var(--red);
      box-shadow: 10px -10px 0 -3px var(--background), 10px -10px var(--primary),
        20px -20px 0 -3px var(--background), 20px -20px var(--green),
        30px -30px 0 -3px var(--background), 30px -30px var(--yellow),
        40px -40px 0 -3px var(--background), 40px -40px var(--orange);
    }
    40% {
      border: 3px solid var(--orange);
      box-shadow: 10px -10px 0 -3px var(--background), 10px -10px var(--red),
        20px -20px 0 -3px var(--background), 20px -20px var(--primary),
        30px -30px 0 -3px var(--background), 30px -30px var(--green),
        40px -40px 0 -3px var(--background), 40px -40px var(--yellow);
    }
    60% {
      border: 3px solid var(--yellow);
      box-shadow: 10px -10px 0 -3px var(--background), 10px -10px var(--orange),
        20px -20px 0 -3px var(--background), 20px -20px var(--red),
        30px -30px 0 -3px var(--background), 30px -30px var(--primary),
        40px -40px 0 -3px var(--background), 40px -40px var(--green);
    }
    80% {
      border: 3px solid var(--green);
      box-shadow: 10px -10px 0 -3px var(--background), 10px -10px var(--yellow),
        20px -20px 0 -3px var(--background), 20px -20px var(--orange),
        30px -30px 0 -3px var(--background), 30px -30px var(--red),
        40px -40px 0 -3px var(--background), 40px -40px var(--primary);
    }
    100% {
      border: 3px solid var(--primary);
      box-shadow: 10px -10px 0 -3px var(--background), 10px -10px var(--green),
        20px -20px 0 -3px var(--background), 20px -20px var(--yellow),
        30px -30px 0 -3px var(--background), 30px -30px var(--orange),
        40px -40px 0 -3px var(--background), 40px -40px var(--red);
    }
    
  }
  :root {
    --primary: #d8d8ff;
    --secondary: #192824;
    --background: #0c0a50;
    --green: #20e1b1;
    --yellow: #ddf476;
    --orange: #e3c429;
    --red: #1c263d;
  } 
body{
    background-image: url(./bg5.jpg);
    background-size: cover;
    padding: 15px;
}
.photos{
  width: 200px;
  height: 100px;
  box-shadow: 7px 7px 5px rgb(66, 76, 76);
  border-radius: 100px;
}
```
## OUTPUT:
![Screenshot (59)](https://github.com/gpavithra673/Exp_01_Create_portfoli_using_html-css/assets/93427264/9137fc51-899a-4d52-8420-7924b31c2d80)

![image](https://github.com/gpavithra673/Exp_01_Create_portfoli_using_html-css/assets/93427264/32402ad8-3c00-4e5d-b031-f11abb05aa15)

## RESULT:

Thus, a Portfolio is created using HTML and CSS.
