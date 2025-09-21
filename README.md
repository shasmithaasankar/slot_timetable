# Ex03 Time Table
## Date: 21.09.2025

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
        <body>
            <center>
                <image src="/static/logo.png" height="100" width="540"></image>
            </center>

            <table border="1" cellpadding="10" align="center" bgcolor="#FFFACD">
                <caption><h2>Slot Time-Table</h2></caption>
                <tr><th>Day/Time</th><th>Monday</th><th>Tuesday</th><th>Wednesday</th><th>Thursday</th><th>Friday</th></tr>
                <tr><th>8-10</th><td>Web</td><td>CN</td><td>DBMS</td><td>FREESLOT</td><td>MATH</td></tr>
                <tr><th>10-12</th><td>Web</td><td>CN</td><td>DBMS</td><td>FREESLOT</td><td>GER</td></tr>
                <tr align="center"><th>12-1</th><td colspan="5">Lunch</td></tr>
                <tr><th>1-3</th><td>FREE SLOT</td><td>MAT</td><td>MAT</td><td>SS</td><td>FREESLOT</td></tr>
                <tr><th>3-5</th><td>FREE SLOT</td><td>GER</td><td>CHE</td><td>PHY</td><td>MATH</td></tr>
            </table>

        </body>
    </head>


</html>
```
## OUTPUT
![alt text](<Screenshot 2025-09-21 213039.png>)










## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
