# Ex03 Time Table
## NAME: H. AARON
## Reference No: 23012368
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
<<html>
<head>
<title>slot Timetable</title>    
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="5" border="7" bgcolor="lavender">
<caption><b>SLOT TIME TABLE - H. AARON (23012368)</b></caption>
<tr align="center">
<th bgcolor="cream">Day/Time</th>
<th bgcolor="cream">Monday</th>
<th bgcolor="cream">Tuesday</th>
<th bgcolor="cream">Wednesday</th>
<th bgcolor="cream">Thursday</th>
<th bgcolor="cream">Friday</th>
</tr>
<tr align="center">
<th bgcolor="lavender">8-10</th>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>PRINCIPLES CHEMISTRY IN ENGINEERING</td>
<td>FREE SLOT</td>
<td>CALCULUS AND MATRIX ALGEBRA</td>
<td>PRINCIPLES CHEMISTRY IN ENGINEERING</td>
</tr>
<tr align="center">
<th bgcolor="lavender">10-12</th>
<td>FREE SLOT</td>
<td>CALCULUS AND MATRIX ALGEBRA</td>
<td>COMPUTER ARCHITECTURE</td>
<td>SOFT SKILLS</td>
<td>COMPUTER ARCHITECTURE</td>
</tr>
<tr>
<th bgcolor="lavender">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="lavender">1-3</th>
<td>PHYSICS FOR QUANTUM COMPUTING</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
</tr>
<tr align="center">
<th bgcolor="lavender">3-5</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>PHYSICS FOR QUANTUM COMPUTING</td>
</tr>
</table>
<br>
<table align="center" cellspacing="3" cellpadding="4" border="2">
<tr align="center">
<th>s. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19PH214</td>
<td>PHYSICS FOR QUANTUM COMPUTING</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19MA201</td>
<td>CALCULUS AND MATRIX ALGEBRA</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (FWAD)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS305</td>
<td>COMPUTER ARCHITECTURE</th>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EY701</td>
<td>SOFT SKILLS</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19CY205</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
</tr>
</table>
</body>
</html>
```

## OUTPUT
![Out1](<EXP 03-1.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
