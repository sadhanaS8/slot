# Ex04 Time Table
## Date:24/11/2026

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
    <title>Experiment 4</title>
</head>
<body>
    <img src="logo.png" width="750" height="180" >

<h1 align="center">
    SLOT TIME TABLE - SADHANA S (26014356)
</h1>

<table border="2" cellpadding="10" cellspacing="1" align="center" width="700" height="170">

    <tr bgcolor="baby pink" align="center">
        <th>Day/Time</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
        <th>Saturday</th>
    </tr>

    <tr bgcolor="pink" align="center">
        <td bgcolor="baby pink">8:00-10:00</td>
        <td></td>SOFTWARE ENGINEERING
        <td>PYTHON</td>
        <td>PYTHON</td>
        <td>MATHS</td>
        <td>FREE SLOT</td>
        <td>MATHS</td>
    </tr>

    <tr bgcolor="pink" align="center">
        <td bgcolor="baby pink">10:00-12:00</td>
        <td>FREE SLOT</td>
        <td>FWAD</td>
        <td>FREE SLOT</td>
        <td>SOFTWARE ENGINEERING </td>
        <td>FWAD</td>
        <td>DE</td>
    </tr>

    <tr bgcolor="pink" align="center">
        <td bgcolor="baby pink">12:00-01:00</td>
        <td colspan="6" align="center">LUNCH BREAK</td>
    </tr>

    <tr bgcolor="pink" align="center">
        <td bgcolor="baby pink">01:00-03:00</td>
        <td>FWAD</td>
        <td>DE</td>
        <td>FREE SLOT</td>
        <td>COMMUNICATIVE ENGLISH</td>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
    </tr>


    <tr bgcolor="pink" align="center">
        <td bgcolor="baby pink">03:00-05:00</td>
        <td>FREE SLOT</td>
        <td>COMMUNICATIVE ENGLISH </td>
        <td>CDS</td>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
        <td>PYTHON</td>
    </tr>

</table>

<h2> 




</h2>


<table border="2" cellpadding="10" cellspacing="3" align="center" width="700" height="170">
    <tr align="center">
        <th>S.No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
    </tr>
    <tr align="center">
        <td>1.</td>
        <td>19AI301</td>
        <td>Python Programming (PY)</td>
    </tr>
    <tr align="center">
        <td>2.</td>
        <td>19AI1414</td>
        <td>Fundamentals of Web Application Development (FWAD)</td>
    </tr>
    <tr align="center">
        <td>3.</td>
        <td>19MA201</td>
        <td>Calculus and Matrix Algebra (MAT)</td>
    </tr>
    <tr align="center">
        <td>4.</td>
        <td>19CS305</td>
        <td>Computer Architecture (CA)</td>
    </tr>
    <tr align="center">
        <td>5.</td>
        <td>19EY708</td>
        <td>Career Development Skills (CDS)</td>
    </tr> 
    <tr align="center">
        <td>6.</td>
        <td>19EN101</td>
        <td>COmmunicative English (CME)</td>
    </tr>
    <tr align="center">
        <td>7.</td>
        <td>19AI302</td>
        <td>Engineering Design and Modelling (EDM)1</td>
    </tr>        
</table>

</body>
</html>
```

## OUTPUT
![alt text](image-1.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
