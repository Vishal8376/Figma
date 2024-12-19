# Ex09 Event Registration Web Application
## Date:19/12/2024

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
HOMEPAGE
```
<div style="width: 100%; height: 100%; position: relative; background: rgba(141.94, 139.57, 139.57, 0.43)">
    <div style="width: 440px; height: 956px; left: 209px; top: 126px; position: absolute; background: #F8EFEF; border-radius: 63px; border: 10px black solid"></div>
    <img style="width: 440px; height: 956px; left: 209px; top: 126px; position: absolute; border-radius: 68px; border: 10px black solid" src="https://via.placeholder.com/440x956" />
    <div style="width: 286px; height: 67px; left: 280px; top: 855px; position: absolute; background: #DC080C"></div>
    <div style="width: 286px; height: 67px; left: 280px; top: 960px; position: absolute; background: #DC080C"></div>
    <div style="width: 220px; height: 67px; left: 311px; top: 855px; position: absolute; text-align: center; color: black; font-size: 50px; font-family: Inter; font-style: italic; font-weight: 600; word-wrap: break-word">LOGIN</div>
    <div style="left: 299px; top: 965px; position: absolute; text-align: center; color: black; font-size: 50px; font-family: Inter; font-style: italic; font-weight: 600; word-wrap: break-word">REGISTER</div>
    <img style="width: 361px; height: 72px; left: 249px; top: 166px; position: absolute" src="https://via.placeholder.com/361x72" />
</div>
```
EVENTS PAGE
```
<div style="width: 100%; height: 100%; position: relative; background: rgba(141.94, 139.57, 139.57, 0.43)">
    <img style="width: 440px; height: 956px; left: 209px; top: 126px; position: absolute; border-radius: 63px; border: 10px black solid" src="https://via.placeholder.com/440x956" />
    <div style="width: 260px; height: 79px; left: 299px; top: 327px; position: absolute; text-align: center"><span style="color: #DC080C; font-size: 30px; font-family: Inter; font-weight: 700; text-decoration: underline; word-wrap: break-word">SPORTS DAY EVENTS<br/></span><span style="color: #DC080C; font-size: 30px; font-family: Inter; font-style: italic; font-weight: 600; text-decoration: underline; word-wrap: break-word"><br/><br/></span></div>
    <div style="width: 199px; height: 341px; left: 330px; top: 467px; position: absolute; text-align: center; color: #F14343; font-size: 30px; font-family: Inter; font-weight: 600; word-wrap: break-word">CRICKET<br/>FOOTBALL<br/>VOLLEYBALL<br/>HOCKEY<br/>TENNIS<br/>BADMINTON</div>
</div>
```
REGISTRATION
```
<div style="width: 100%; height: 100%; position: relative; background: rgba(141.94, 139.57, 139.57, 0.43)">
    <img style="width: 440px; height: 956px; left: 209px; top: 133px; position: absolute; border-radius: 63px; border: 10px black solid" src="https://via.placeholder.com/440x956" />
    <img style="width: 361px; height: 72px; left: 249px; top: 181px; position: absolute" src="https://via.placeholder.com/361x72" />
    <div style="width: 256px; height: 42px; left: 249px; top: 345px; position: absolute; background: #FFFEFE"></div>
    <div style="width: 256px; height: 42px; left: 249px; top: 505px; position: absolute; background: #FFFEFE"></div>
    <div style="width: 256px; height: 42px; left: 249px; top: 431px; position: absolute; background: #FFFEFE"></div>
    <div style="width: 256px; height: 42px; left: 290px; top: 820px; position: absolute; background: linear-gradient(90deg, #5AF143 37%, #348B26 96%)"></div>
    <div style="width: 256px; height: 146.50px; left: 249px; top: 591px; position: absolute; background: #FFFEFE"></div>
    <div style="width: 252px; height: 28px; left: 220px; top: 289px; position: absolute; text-align: center; color: white; font-size: 25px; font-family: Inter; font-style: italic; font-weight: 600; text-decoration: underline; word-wrap: break-word">REGISTER HERE</div>
    <div style="width: 208px; height: 20px; left: 234px; top: 351px; position: absolute; text-align: center; color: rgba(0, 0, 0, 0.41); font-size: 25px; font-family: Inter; font-style: italic; font-weight: 600; word-wrap: break-word">FULL NAME</div>
    <div style="width: 214px; height: 21px; left: 212px; top: 442px; position: absolute; text-align: center; color: rgba(0, 0, 0, 0.41); font-size: 25px; font-family: Inter; font-style: italic; font-weight: 600; word-wrap: break-word">GENDER</div>
    <div style="width: 214px; height: 21px; left: 214px; top: 516px; position: absolute; text-align: center; color: rgba(0, 0, 0, 0.41); font-size: 25px; font-family: Inter; font-style: italic; font-weight: 600; word-wrap: break-word">PH.NO:</div>
    <div style="width: 214px; height: 21px; left: 213px; top: 599px; position: absolute; text-align: center; color: rgba(0, 0, 0, 0.41); font-size: 25px; font-family: Inter; font-style: italic; font-weight: 600; word-wrap: break-word">EMAIL</div>
    <div style="width: 214px; height: 21px; left: 204px; top: 703px; position: absolute; text-align: center; color: rgba(0, 0, 0, 0.41); font-size: 25px; font-family: Inter; font-style: italic; font-weight: 600; word-wrap: break-word">DEPT<br/></div>
    <div style="width: 210px; height: 36px; left: 312px; top: 826px; position: absolute; text-align: center; color: #FFFAFA; font-size: 25px; font-family: Inter; font-style: italic; font-weight: 600; word-wrap: break-word">SUBMIT</div>
</div>
```
CONTACT PAGE
```
<div style="width: 100%; height: 100%; position: relative; background: rgba(141.94, 139.57, 139.57, 0.43)">
    <img style="width: 440px; height: 956px; left: 209px; top: 126px; position: absolute; border-radius: 63px; border: 10px black solid" src="https://via.placeholder.com/440x956" />
    <img style="width: 361px; height: 72px; left: 241px; top: 161px; position: absolute" src="https://via.placeholder.com/361x72" />
    <div style="width: 336px; height: 303px; left: 253px; top: 726px; position: absolute; text-align: center"><span style="color: #030000; font-size: 30px; font-family: Inter; font-weight: 800; word-wrap: break-word">THANK YOU!<br/><br/></span><span style="color: #030000; font-size: 30px; font-family: Inter; font-weight: 500; word-wrap: break-word">WE ARE EAGERLY WAITING FOR YOUR PARTICIPATION IN THE SPORTS EVENT</span></div>
    <div style="width: 376px; height: 30px; left: 239px; top: 1018px; position: absolute; text-align: center; color: black; font-size: 12px; font-family: Inter; font-weight: 800; word-wrap: break-word">FOR ENQUIRIES,CONATACT<br/>@saveethaengineeringcollege@ac.saveetha.in</div>
</div>
```
## OUTPUT:
![alt text](<Screenshot 2024-12-19 202806.png>)
![alt text](<Screenshot 2024-12-19 202948.png>)
![alt text](<Screenshot 2024-12-19 203059.png>)
![alt text](<Screenshot 2024-12-19 203122.png>)
## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
