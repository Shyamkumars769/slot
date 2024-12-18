# Ex03 Time Table
## Date: 16-11-2024

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
<body>
    <img src="logo.png" width="1000px" height="150px">
<table border="2" cellpading="5">
    <caption>Time Table SHYAM KUMAR-24001160</caption>
<tr bgcolor="cyan">
    <th>Time</th>
    <th>Monday</th>
    <th>Tuesday</th>
    <th>Wednesday</th>
    <th>Thursday</th>
    <th>Friday</th>
    <th>Saturday</th>
</tr>
<tr>
    <td>8:00 AM - 10:00AM</td>
    <td></td>
    <td bgcolor="yellow">Web</td>
    <td></td>
    <td bgcolor="yellow">Humanities</td>
    <td></td>
    <td></td>
</tr>
<tr>
    <td>10:00 AM - 12:00 PM</td>
    <td bgcolor="yellow">Math</td>
    <td></td>
    <td bgcolor="yellow">Chem</td>
    <td bgcolor="yellow">CDS</td>
    <td bgcolor="yellow">Chem</td>
    <td bgcolor="yellow">C</td>
</tr>
<tr>
    <td>12:00 PM - 1:00 PM</td>
    <td colspan="7" bgcolor="lightgrey" align="center"><strong>Lunch</strong></td>
</tr>
<tr>
    <td>1:00 PM - 3:00 PM</td>
    <td bgcolor="yellow">C</td>
    <td bgcolor="yellow">Math</td>
    <td bgcolor="yellow">Mentor</td>
    <td bgcolor="yellow">Digital</td>
    <td bgcolor="yellow">Web</td>
    <td bgcolor="yellow">Web</td>
</tr>
<tr>
    <td>3:00 PM - 5:00PM</td>
    <td></td>
    <td bgcolor="yellow">Digital</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
</tr>
</table>
<head>
    <title>Course Details</title>
</head>
<body>
    <table border="2" cellpadding="5">
        <caption>Course Details</caption>
        <tr bgcolor="lightgrey">
            <th>S.No</th>
            <th>Course Code</th>
            <th>Course Name</th>
        </tr>
        <tbody>
            <tr>
                <td>1</td>
                <td>19MA201</td>
                <td>Calculus and Matrix Algebra</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19CY205</td>
                <td>Principles of Chemistry</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AI304</td>
                <td>Fundamentals of C Programming</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19EE404</td>
                <td>Digital Electronics</td>
            </tr>
            <tr>
                <td>5</td>
                <td>SH7801</td>
                <td>Human Values</td>
            </tr>
            <tr>
                <td>6</td>
                <td>19EY708</td>
                <td>Career Development Skills</td>
            </tr>
            <tr>
                <td>7</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Applications</td>
            </tr>
            <tr>
                <td>8</td>
                <td>ECA-M SCOFT</td>
                <td>Mentor Meet</td>
            </tr>
        </tbody>
    </table>

```
## OUTPUT

![alt text](<Screenshot (6).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
