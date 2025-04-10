# Ex03 Time Table
## Date:10/04/2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Semester Timetable</title>
    <style>
        
        th, td {
            border: 2px solid white;
            padding: 8px;
            
        }
        th{
            background-color: black;
            
        }
        
        td{
            background-color:white;
        }
    </style>
</head>
<body>
    <center>
    <img src="app3/static/logo.png" height="100" width="540"><br><br>

    <caption><b>SLOT TIMETABLE-SANTHOSH KUMAR P(24900711)</b></caption>
</center>
    <table border="5" align="center" cellpadding="4" bgcolor="black" width="540">
        <tr align="center">
            <th style="background-color: grey;">Day/Time</th>
            <th style="background-color: grey;">Monday</th>
            <th style="background-color: grey;">Tuesday</th>
            <th style="background-color: grey;">Wednesday</th>
            <th style="background-color: grey;">Thursday</th>
            <th style="background-color: grey;">Friday</th>
            <th style="background-color: grey;">Saturday</th>
        </tr>
        <tr align="center">
            <td style="background-color:grey">8-10</td>
            <td>Free Slot</td>
            <td>UI/UX</td>
            <td>Free Slot</td>
            <td>UI/UX</td>
            <td>Free Slot</td>
            <td>Free Slot</td>
        </tr>
        <tr align="center">
            <td style="background-color: grey">10-12</td>
            <td>Fundamentals of C programming</td>
            <td>Physics</td>
            <td>Fundamentals of web Application Development</td>
            <td>Engineering Design and Modeling</td>
            <td>Digital Electronics</td>
            <td>Funamentals of C programming</td>
        </tr>
        <tr align="center">
            <td style="background-color:grey">12-1</td>
            <td>LUNCH</td>
        </tr>
        <tr align="center">
            <td style="background-color:grey">1-3</td>
            <td>Engineering Design and Modeling</td>
            <td>Probability and queuing Model</td>
            <td>Mentor Meet</td>
            <td>Physics</td>
            <td>Probability and queuing Model</td>
            <td>Free Slot</td>
        </tr>
        <tr align="center">
            <td style="background-color:grey">3-5</td>
            <td>Free Slot</td>
            <td>Free Slot</td>
            <td>Digital Electronics</td>
            <td>Free Slot</td>
            <td>Fundamentals of web Application Development</td>
            <td>EVS</td>
        </tr>
    </table>
   <br><br>
        <table border="5" align="center" cellpadding="4" bgcolor="black" width="540">
            <tr align="center">
                <th style="color: white;">S.No</th>
                <th style="color: white;">Subject Code</th>
                <th style="color: white;">Subject Name</th>
            </tr>
            <tr align="center">
                <td>1</td>
                <td>19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
                </tr>
                <tr align="center">
                    <td>2</td>
                    <td>19CS549</td>
                    <td>UI/UX DESIGN</td>
                </tr>
                <tr align="center">
                    <td>3</td>
                    <td>19PH814</td>
                    <td>PHYSICS FOR QUANTUM COMPUTING</td>
                </tr>
                <tr align="center">
                    <td>4</td>
                    <td>19AI301</td>
                    <td>FUNDAMENTALS OF C PROGRAMMING</td>
                </tr>
                <tr align="center">
                    <td>5</td>
                    <td>19MA222</td>
                    <td>PROBABILITY AND QUEUING MODELS</td>
                </tr>
                <tr align="center">
                    <td>6</td>
                    <td>19AAI302</td>
                    <td>ENGINEERING DESIGN AND MODELING</td>
                </tr>
                <tr align="center">
                    <td>7</td>
                    <td>19CY801</td>
                    <td>EVS</td>
                </tr>
                <tr align="center">
                    <td>8</td>
                    <td>19EE404</td>
                    <td>DIGITAL ELECTRONICS</td>
                </tr>
                

        </table>
    
</body>
</html> 

```


## OUTPUT
![alt text](<Web03/static/Screenshot 2025-04-10 235732.png>)
![alt text](<Web03/static/Screenshot 2025-04-10 235744.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
