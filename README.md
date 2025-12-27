# Ex08 Event Registration Web Application
## Date:27/12/2025

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
```
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
    <div class="iphone-plus">
      <img class="saveetha-eng-logo" src="img/saveetha-eng-logo-1.png" />
      <img class="saveetha-logo" src="img/saveetha-logo-1.png" />
      <img class="screenshot" src="img/screenshot-2025-12-19-112413-1.png" />
      <img class="img" src="img/screenshot-2025-12-19-111616-1.png" />
      <img class="screenshot-2" src="img/screenshot-2025-12-19-113358-1.png" />
    </div>
  </body>
</html>

global.css
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

styles.css 
.iphone-plus {
  background-color: #ffffff;
  width: 100%;
  min-width: 430px;
  min-height: 932px;
  display: flex;
  flex-direction: column;
}

.iphone-plus .saveetha-eng-logo {
  margin-left: 15px;
  width: 400px;
  height: 80px;
  margin-top: 44px;
  aspect-ratio: 5.01;
  object-fit: cover;
}

.iphone-plus .saveetha-logo {
  margin-left: 98px;
  width: 233px;
  height: 233px;
  margin-top: 40px;
  aspect-ratio: 1;
  object-fit: cover;
}

.iphone-plus .screenshot {
  margin-left: 82px;
  width: 274px;
  height: 63px;
  margin-top: 48px;
  aspect-ratio: 4.35;
  object-fit: cover;
}

.iphone-plus .img {
  margin-left: 118px;
  width: 177px;
  height: 66px;
  margin-top: 50px;
  aspect-ratio: 2.68;
  object-fit: cover;
}

.iphone-plus .screenshot-2 {
  margin-left: 33px;
  width: 348px;
  height: 73px;
  margin-top: 75px;
  aspect-ratio: 4.77;
  object-fit: cover;
}

2.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-plus">
      <img class="image" src="img/image-1.png" />
      <p class="element-hack-hustle-no">
        1 . Hack hustle <br /><br />2 . No code rush <br /><br />3 . Frontend Fusion <br /><br />4 . Logic creator
        <br /><br />5 . Tech quest <br /><br />6 . Logicloom
      </p>
    </div>
  </body>
</html>

2.css

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

2styles.css

.iphone-plus {
  background-color: #ffffff;
  width: 100%;
  min-width: 430px;
  min-height: 932px;
  display: flex;
  flex-direction: column;
  gap: 78px;
}

.iphone-plus .image {
  margin-left: 45px;
  width: 339px;
  height: 76px;
  margin-top: 23px;
  aspect-ratio: 4.45;
  object-fit: cover;
}

.iphone-plus .element-hack-hustle-no {
  margin-left: 53px;
  width: 331px;
  height: 638px;
  font-family: "Inria Serif-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

3.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-plus">
      <div class="text-wrapper">Registration Details :</div>
      <p class="element-NAME-CONTACT">
        1 . NAME :<br /><br />2 . CONTACT :<br /><br />3 . GMAIL :<br /><br />4 . GENDER :<br /><br />5 . AGE :<br /><br />6
        . REF NO :<br /><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SIGN
        <br /><br /><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;THANK YOU !!!
      </p>
    </div>
  </body>
</html>

3.css

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

3styles.css

.iphone-plus {
  background-color: #ffffff;
  width: 100%;
  min-width: 430px;
  min-height: 932px;
  display: flex;
  flex-direction: column;
  gap: 35px;
}

.iphone-plus .text-wrapper {
  margin-left: 28px;
  width: 374px;
  height: 102px;
  margin-top: 34px;
  font-family: "Inria Serif-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-plus .element-NAME-CONTACT {
  margin-left: 35px;
  width: 367px;
  height: 673px;
  font-family: "Inria Serif-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

```


## OUTPUT:
![alt text](<Screenshot (63).png>)


## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
