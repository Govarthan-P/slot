# Ex04 Time Table
## Date:18.11.2026

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <head>
       <title>my slot</title> 
    </head>
    <body>
        <center><img src="logo.png" width="1500"></center>
        <table align="center" border="2" cellspacing="10" cellpadding="10" bgcolor="grey">
            <br><br>
        <caption><b>SLOT TIME TABLE-GOVARTHAN P(26014378)</b></caption>    
            <tr bgcolor="blue">
                <th bgcolor="green">Day/Time</th>
                <th>8:00-9:30</th>
                <th>9:45-11:15</th>
                <th>11:30-12:15</th>
                <th>1:15-2:30</th>
                <th>3:00-4:30</th>
            </tr>
            <tr>
                <th bgcolor="blue">Monday</th>
                <th bgcolor="yellow">Free</th>
                <th bgcolor="aqua">FWAD</th>
                <th bgcolor="black" style="color:aliceblue">Mentor Meet</th>
                <th bgcolor="yellow">Free</th>
                <th bgcolor="aqua">DE</th>
            </tr>
            <tr>
                <th bgcolor="blue">Tuesday</th>
                <th bgcolor="yellow">Free</th>
                <th bgcolor="aqua">CA</th>
                <th bgcolor="black" style="color:aliceblue">Mentor Meet</th>
                <th bgcolor="aqua">FWAD</th>
                <th bgcolor="aqua">Python</th>
            </tr>
            <tr>
                <th bgcolor="blue">Wednesday</th>
                <th bgcolor="aqua">FWAD</th>
                <th bgcolor="yellow">Free</th>
                <th bgcolor="black" style="color:aliceblue">Mentor Meet</th>
                <th bgcolor="yellow">Free</th>
                <th bgcolor="aqua">EDM</th>
            </tr>
            <tr>
                <th bgcolor="blue">Thursday</th>
                <th bgcolor="aqua">CA</th>
                <th bgcolor="aqua">Python</th>
                <th bgcolor="black" style="color:aliceblue">Mentor Meet</th>
                <th bgcolor="aqua">EDM</th>
                <th bgcolor="aqua">DE</th>
            </tr>
            <tr>
                <th bgcolor="blue">Friday</th>
                <th bgcolor="aqua">Stat</th>
                <th bgcolor="yellow">Free</th>
                <th bgcolor="black" style="color:aliceblue">Mentor Meet</th>
                <th bgcolor="yellow">Free</th>
                <th bgcolor="aqua">BEEE</th>
            </tr>
            <tr>
                <th bgcolor="blue">Saturday</th>
                <th bgcolor="aqua">Python</th>
                <th bgcolor="aqua">Stat</th>
                <th bgcolor="yellow">Free</th>
                <th bgcolor="yellow">Free</th>
                <th bgcolor="yellow">Free</th>
            </tr>
        </table>
        <br><br>
        <table align="center" border="2" cellspacing="10" cellpadding="5">
            <tr>
                <th>S.No:</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <th>1</th>
                <th>19AI414</th>
                <th>Fundamentals of Web Application Development(FWAD)</th>
            </tr>
            <tr>
                <th>2</th>
                <th>19EE404</th>
                <th>Digital Electronics(DE)</th>
            </tr>
            <tr>
                <th>3</th>
                <th>19CS305</th>
                <th>Computer Architecture(CA)</th>
            </tr>
            <tr>
                <th>4</th>
                <th>19AI301</th>
                <th>Python Programming(Python)</th>
            </tr>
            <tr>
                <th>5</th>
                <th>19AI302</th>
                <th>Engineering Design Modelling(EDM)</th>
            </tr>
            <tr>
                <th>6</th>
                <th>19MA211</th>
                <th>Statistics and Numerical Methods(Stat)</th>
            </tr>
            <tr>
                <th>7</th>
                <th>19EE305</th>
                <th>Basic Electrical,Electronics and Measurement Engineering(BEEE)</th>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (14).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
