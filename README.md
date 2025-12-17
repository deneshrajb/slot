# Ex02 Time Table
## Date: 17/12/2025

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
    <title>Document</title>
</head>
<body>
    <center>
        <img src="logo.png" alt="no image" height="150" width="800">
    </center>
        <table align="center" border="3" cellpadding="5" cellspacing="2">
        <tr>
            <th bgcolor="cyan">Day/Time</th>
            <th bgcolor="cyan">Monday</th>
            <th bgcolor="cyan">Tuesday</th>
            <th bgcolor="cyan">Wednesday</th>
            <th bgcolor="cyan">Thursday</th>
            <th bgcolor="cyan">Friday</th>
        </tr>
        <tr>
            <th bgcolor="cyan">8-10</th>
            <td bgcolor="lightpink">Free Slot</td>
            <td bgcolor="lightpink">Free Slot</td>
            <td bgcolor="lightpink">Free Slot</td>
            <td bgcolor="lightgreen">Web Application</td>
            <td bgcolor="lightgreen">Data Science</td>
        </tr>
        <tr>
            <th bgcolor="cyan">10-12</th>
            <td bgcolor="lightgreen">Web Application</td>
            <td bgcolor="lightpink">Free Slot</td>
            <td bgcolor="lightgreen">Data Science</td>
            <td bgcolor="lightgreen">Data Science</td>
            <td bgcolor="lightpink">Free Slot</td>
        </tr>
        <tr>
            <th bgcolor="cyan">12-1</th>
            <td bgcolor="yellow" colspan="5" align="center">LUNCH</td>
        </tr>
        <tr>
            <th bgcolor="cyan">1-3</th>
            <td bgcolor="lightpink">Free Slot</td>
            <td bgcolor="lightgreen">Data Science</td>
            <td bgcolor="lightgreen">Mentor Meet</td>
            <td bgcolor="lightgreen">Data Science</td>
            <td bgcolor="lightgreen">Web Application</td>
        </tr>
        <tr>
            <th bgcolor="cyan">3-5</th>
            <td bgcolor="lightpink">Free Slot</td>
            <td bgcolor="lightpink">Free Slot</td>
            <td bgcolor="lightgreen">Web Application</td>
            <td bgcolor="lightpink">Free Slot</td>
            <td bgcolor="lightgreen">Web Application</td>
        </tr>
        <table border="7" cellpadding="7" cellspacing="2" align="center">
       <table border="7" cellpadding="7" cellspacing="2" align="center">
         <tr>
           <th><h4>S.NO</h4></th>    
           <th><h4>SUBJECT CODE </h4></th>
           <th><h4>SUBJECT NAME </h4></th>
         </tr>
         <tr>
            <th>1.</th>
            <td>19AI414</td>
            <td>WEB APPLICATION  </td>
         </tr>
         <tr>
             <th>2.</th>
             <td>19AI403</td>
             <td>INTRODUCTION TO DATA SCIENCE </td>
          </tr> 

</body>
</html>
```
## OUTPUT
![alt text](<Screenshot 2025-12-17 191854.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
