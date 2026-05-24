# Ex02 Time Table
## Date:

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
```html
<!DOCTYPE html>
<html>
<head>
    <title>SLOT TIMETABLE</title>
</head>
<body>

<center>
    <img src="logo.png" height="100" width="500" alt="Logo">
</center>

<h2>SLOT TIMETABLE - SARANRAJ R (212225040383)</h2>

<table border="1" cellpadding="8" cellspacing="0">

    <tr>
        <th>Day / Time</th>
        <th>8 - 10</th>
        <th>10 - 12</th>
        <th>1 - 3</th>
        <th>3 - 5</th>
    </tr>

    <tr>
        <td>MONDAY</td>
        <td>FWAD</td>
        <td>CDS</td>
        <td>OS</td>
        <td>ML</td>
    </tr>

    <tr>
        <td>TUESDAY</td>
        <td>FREE</td>
        <td>FREE</td>
        <td>FREE</td>
        <td>FREE</td>
    </tr>

    <tr>
        <td>WEDNESDAY</td>
        <td>FREE</td>
        <td>ML</td>
        <td>MENTOR MEET</td>
        <td>ML</td>
    </tr>

    <tr>
        <td>THURSDAY</td>
        <td>FWAD</td>
        <td>FWAD</td>
        <td>OS</td>
        <td>OS</td>
    </tr>

    <tr>
        <td>FRIDAY</td>
        <td>FWAD</td>
        <td>CDS</td>
        <td>ML</td>
        <td>OS</td>
    </tr>

    <tr>
        <td>SATURDAY</td>
        <td>FREE</td>
        <td>FREE</td>
        <td>FREE</td>
        <td>FREE</td>
    </tr>

</table>

<br><br>

<table border="2" cellpadding="5" cellspacing="2" align="center">

    <tr align="center">
        <th>S. No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
    </tr>

    <tr>
        <td align="center">1</td>
        <td align="center">19AI414</td>
        <td>Fundamentals of Web Application Development (FWAD)</td>
    </tr>

    <tr>
        <td align="center">2</td>
        <td align="center">19AI405</td>
        <td>Operating Systems</td>
    </tr>

    <tr>
        <td align="center">3</td>
        <td align="center">19EY401</td>
        <td>Career Development Skills</td>
    </tr>

    <tr>
        <td align="center">4</td>
        <td align="center">19AI415</td>
        <td>Machine Learning</td>

</table>

</body>
</html>
```

## OUTPUT
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/a5782c10-60aa-4fbf-b38b-4c972c42d1f1" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
