# Ex03 Time Table
## Date: 04-10-2024

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
<html>
    <head>
        <title>class schedule</title>
        
        <style>
            td{
                font-family:system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
                color : hsl(347, 82%, 4%);
                background-color : rgb(233, 11, 211)
            }
        </style>
    </head>
    <body background="https://png.pngtree.com/thumb_back/fh260/background/20231110/pngtree-abstract-light-colored-paint-texture-background-wallpaper-image_13802780.png">
        <center><img src="https://www.saveetha.ac.in/images/WEB_LOGO-01.png" height="75" width="500"></center>
        <b><p align="center" font size="20">SLOT TIME TABLE (Padmavathi M)</p></b>
        
        <table align="center" border="3"cellspacing="2" cellpadding="5" width="1500" >
            <tr bgcolor="yellow">
                <th>Day/Time</th>
                <th>8-10</th>
                <th>10-12</th>
                <th>12-1</th>
                <th>1-3</th>
                <th>3-5</th>
            </tr>
            <tr>
                <th bgcolor="yellow">Monday</th>

                <td>Fundamentals of C programming</td>
                <td>Free</td>
                <td rowspan="6" align="center">Lunch</td>
                <td>Free</td>
                <td>Fundamentals of Web Application</td>
            </tr>
            <tr>
                <th bgcolor="yellow">Tuesday</th>
                <td>Computer Networks</td>
                <td>Introduction to Machine Learning</td>
                
                <td>Free</td>
                <td>-</td>
                
            </tr>
            <tr>
                <th bgcolor="yellow">Wednesday</th>
                <td>Logics and Combinatorics</td>
                <td>Free</td>
                
                <td>Free</td>
                <td>Fundamentals of C programming</td>
            </tr>
            <tr>
                <th bgcolor="yellow">Thursday</th>
                <td>Introduction to Machine Learning</td>
                <td>Fundamentals of Web Application Development</td>
                
                <td>Software Engineering</td>
                <td>-</td>
            </tr>
            <tr>
                <th bgcolor="yellow">Friday</th>
                <td>Logics and Combinatorics</td>
                <td>Software Engineering</td>
                
                <td>Free</td>
                <td>-</td>
            </tr>
            <tr>
                <th bgcolor="yellow">Saturday</th>
                <td>Fundamentals of Web Application Development</td>
                <td>Quantitative Ability II</td>
                
                <td>Computer Networks</td>
                <td>-</td>
            </tr>
        </table>
        <br>
        <table align="center" border="3" cellspacing="1" cellpadding="5" height="5" width="700">
            <tr bgcolor="yellow">
                <th>S.NO</th>
                <th>Subject code</th>
                <th>Subject course</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI304</td>
                <td>Fundamentals of C programming</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AI410</td>
                <td>Introduction to Machine Learning</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19CS406</td>
                <td>Computer Networds</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19CS408</td>
                <td>Software Engineering</td>
            </tr>
            <tr>
                <td>6</td>
                <td>19EY710</td>
                <td>Quantitative Ability I</td>
            </tr>
            <tr>
                <td>7</td>
                <td>19MA206</td>
                <td>Logics and Combinatorics</td>
            </tr>
            
        </table>
    </body>
</html>
```
## OUTPUT
![Screenshot 2024-10-04 180658](https://github.com/user-attachments/assets/1250df87-3be2-435f-95a3-be82fd32637b)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
