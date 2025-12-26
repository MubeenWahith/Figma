# Ex08 Event Registration Web Application
## Date: 26/12/2025

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
~~~
home page 

index.html 

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-mini">
      <img class="rectangle" src="img/rectangle-3.svg" />
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <img class="image" src="img/image-4.png" />
      <img class="img" src="img/image-5.png" />
      <p class="text-wrapper">HACKATHON EVENT DAY - 2</p>
      <img class="image-2" src="img/image-7.png" />
      <img class="image-3" src="img/image-8.png" />
      <img class="rectangle-2" src="img/rectangle-4.svg" />
      <div class="div">CLICK HERE</div>
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.iphone-mini {
  background-color: #ffffff;
  width: 100%;
  min-width: 375px;
  min-height: 812px;
  position: relative;
}

.iphone-mini .rectangle {
  position: absolute;
  top: 241px;
  left: 72px;
  width: 232px;
  height: 42px;
}

.iphone-mini .text-on-a-path {
  position: absolute;
  top: 233px;
  left: 19px;
  width: 242px;
  height: 39px;
}

.iphone-mini .image {
  top: 26px;
  left: 16px;
  width: 343px;
  height: 69px;
  aspect-ratio: 4.97;
  position: absolute;
  object-fit: cover;
}

.iphone-mini .img {
  top: 202px;
  left: 28px;
  width: 107px;
  height: 107px;
  aspect-ratio: 1;
  position: absolute;
  object-fit: cover;
}

.iphone-mini .text-wrapper {
  position: absolute;
  top: 256px;
  left: 104px;
  width: 168px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #683d00;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-mini .image-2 {
  top: 576px;
  left: 0;
  width: 356px;
  height: 225px;
  aspect-ratio: 1.58;
  position: absolute;
  object-fit: cover;
}

.iphone-mini .image-3 {
  top: 301px;
  left: 251px;
  width: 105px;
  height: 105px;
  aspect-ratio: 1;
  position: absolute;
  object-fit: cover;
}

.iphone-mini .rectangle-2 {
  position: absolute;
  top: 477px;
  left: 78px;
  width: 200px;
  height: 27px;
}

.iphone-mini .div {
  position: absolute;
  top: 477px;
  left: 120px;
  width: 152px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

~~~

~~~
second page 

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-mini">
      <div class="rectangle"></div>
      <div class="text-wrapper">EVENT LIST</div>
      <img class="img" src="img/rectangle-6.svg" />
      <img class="text-on-a-path" src="img/image.svg" />
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-2">AERO QUIZ</div>
      <img class="text-on-a-path-2" src="img/text-on-a-path.svg" />
      <div class="rectangle-4"></div>
      <div class="text-wrapper-3">SDG WINNERZ</div>
      <div class="text-wrapper-4">RENENERGY</div>
      <div class="text-wrapper-5">GRAVIUIZ</div>
      <img class="image" src="img/image-9.png" />
      <img class="rectangle-5" src="img/rectangle-12.svg" />
      <div class="text-wrapper-6">TO REGISTER</div>
      <div class="text-wrapper-7">chemfusion</div>
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.iphone-mini {
  background-color: #b63838;
  overflow: hidden;
  width: 100%;
  min-width: 375px;
  min-height: 812px;
  position: relative;
}

.iphone-mini .rectangle {
  position: absolute;
  top: 62px;
  left: 70px;
  width: 236px;
  height: 42px;
  background-color: #d9d9d9;
  border-radius: 464px;
}

.iphone-mini .text-wrapper {
  position: absolute;
  top: 71px;
  left: 130px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-mini .img {
  position: absolute;
  top: 143px;
  left: 44px;
  width: 287px;
  height: 39px;
}

.iphone-mini .text-on-a-path {
  position: absolute;
  top: 200px;
  left: -398px;
  width: 287px;
  height: 38px;
}

.iphone-mini .div {
  position: absolute;
  top: 298px;
  left: 44px;
  width: 287px;
  height: 37px;
  background-color: #d9d9d9;
}

.iphone-mini .rectangle-2 {
  position: absolute;
  top: 374px;
  left: 44px;
  width: 287px;
  height: 32px;
  background-color: #d9d9d9;
}

.iphone-mini .rectangle-3 {
  position: absolute;
  top: 445px;
  left: 44px;
  width: 287px;
  height: 32px;
  background-color: #d9d9d9;
}

.iphone-mini .text-wrapper-2 {
  position: absolute;
  top: 154px;
  left: 117px;
  width: 189px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-mini .text-on-a-path-2 {
  position: absolute;
  top: 200px;
  left: -398px;
  width: 287px;
  height: 39px;
}

.iphone-mini .rectangle-4 {
  position: absolute;
  top: 224px;
  left: 44px;
  width: 287px;
  height: 36px;
  background-color: #d9d9d9;
}

.iphone-mini .text-wrapper-3 {
  position: absolute;
  top: 235px;
  left: 103px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-mini .text-wrapper-4 {
  position: absolute;
  top: 374px;
  left: 117px;
  width: 140px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-mini .text-wrapper-5 {
  position: absolute;
  top: 446px;
  left: 126px;
  width: 240px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-mini .image {
  position: absolute;
  top: 599px;
  left: 0;
  width: 375px;
  height: 213px;
  aspect-ratio: 1.67;
  object-fit: cover;
}

.iphone-mini .rectangle-5 {
  position: absolute;
  top: 515px;
  left: 68px;
  width: 218px;
  height: 64px;
}

.iphone-mini .text-wrapper-6 {
  position: absolute;
  top: 537px;
  left: 117px;
  width: 133px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-mini .text-wrapper-7 {
  position: absolute;
  top: 302px;
  left: 117px;
  width: 338px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

~~~

~~~
last page

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-mini">
      <img class="image" src="img/image.png" />
      <div class="image-wrapper"><img class="img" src="img/image-10.png" /></div>
      <div class="rectangle"></div>
      <div class="text-wrapper">REGISTER</div>
      <img class="image-2" src="img/image-11.png" />
      <img class="image-3" src="img/image-12.png" />
      <div class="div">VENUE : SEC</div>
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}


style.css

.iphone-mini {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 375px;
  min-height: 812px;
  position: relative;
}

.iphone-mini .image {
  top: 0;
  left: 0;
  width: 375px;
  height: 212px;
  aspect-ratio: 1.69;
  position: absolute;
  object-fit: cover;
}

.iphone-mini .image-wrapper {
  position: absolute;
  top: 622px;
  left: -21px;
  width: 575px;
  height: 898px;
  display: flex;
  background-color: #ffffff;
  border-radius: 123px;
  overflow: hidden;
}

.iphone-mini .img {
  width: 375px;
  height: 190px;
  margin-left: 21px;
  aspect-ratio: 1.69;
  object-fit: cover;
}

.iphone-mini .rectangle {
  position: absolute;
  top: 375px;
  left: 47px;
  width: 247px;
  height: 54px;
  background-color: #d9d9d9;
}

.iphone-mini .text-wrapper {
  position: absolute;
  top: 391px;
  left: 108px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-mini .image-2 {
  top: 212px;
  left: 226px;
  width: 145px;
  height: 145px;
  aspect-ratio: 1;
  position: absolute;
  object-fit: cover;
}

.iphone-mini .image-3 {
  top: 498px;
  left: 251px;
  width: 124px;
  height: 124px;
  aspect-ratio: 1;
  position: absolute;
  object-fit: cover;
}

.iphone-mini .div {
  position: absolute;
  top: 588px;
  left: 84px;
  width: 193px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #5af8d8;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

~~~

## OUTPUT:
![alt text](<Screenshot (54).png>)
![alt text](<Screenshot (55).png>)
![alt text](<Screenshot (56).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
