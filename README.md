# Ex03 Time Table
## Date:09.04.2025

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

### PROGRAM

<!DOCTYPE html>
<html>
<head>
    <title>Slot Time Table - Hareni N(212224040096)</title>
</head>
<body>
    <IMG SRC="logo.png"HEIGHT="100"WIDTH="500"BORDER=6>
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - Hareni N(212224040096)</h3>

    <table border="1">
        <tr BGCOLOR="YELLOW">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">8-10</td>
            <td></td>
            <td>FREE SLOT</td>
            <td></td>
            <td>PHY</td>
            <td>CHE</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">10-12</td>
            <td></td>
            <td>FWAD</td>
            <td></td>
            <td>PHY</td>
            <td>CHE</td>
        </tr>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">12-1</td>
            <td COLSPAN=5 ALIGN="CENTER">LUNCH</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">1-3</td>
            <td>FREE SLOT</td>
            <td>MAT</td>
            <td>MAT</td>
            <td>SS</td>
            <td></td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">3-5</td>
            <td>FREE SLOT</td>
            <td>GER</td>
            <td>CHE</td>
            <td>FWAD</td>
            <td></td>
        </tr>
    </table>

    <h3>Subjects</h3>
    <table border="1">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19EN612</td>
            <td>German Basic (GER)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19PH206</td>
            <td>Physics for Information Technology (PHY)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19CY205</td>
            <td>Principles of Chemistry in Engineering (CHE)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19MA201</td>
            <td>Calculus and Matrix Algebra (MAT)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19EY701</td>
            <td>Soft Skills (SS)</td>
        </tr>
    </table>
</body>
</html>

## OUTPUT

![alt text](image.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
