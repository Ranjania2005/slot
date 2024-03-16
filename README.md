# Ex03 Time Table
## Date:16.03.2024

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
<title>MY TIME TABLE</title>
</head>
<body>
<img src="logo.png" height="200" width="1200" align="centre">
</center>
<table align="center" border="4" cellspacing="5" cellpadding="10" height="100" width="100">
<caption><B>SLOT TIME TABLE -RANJANI A (23012505)</B></caption>
<tr align="center">
<th bgcolor="green">Day/Time</th>
<th bgcolor="green">Monday</th>
<th bgcolor="green">Tuesday</th>
<th bgcolor="green">Wedday</th>
<th bgcolor="green">Thursday</th>
<th bgcolor="green">Friday</th>
<th bgcolor="green">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="green">8-10</th>
<td bgcolor="cyan">Free slot</td>
<td bgcolor="pink">Chem</td>
<td bgcolor="pink">Adv c</td>
<td bgcolor="pink">Japanese</td>
<td bgcolor="pink">Web App</td>
<td bgcolor="pink">Chem</td>
</tr>
<tr>
<th bgcolor="green">10-12</th>
<td bgcolor="cyan">Free slot</td>
<td bgcolor="pink">OS</td>
<td bgcolor="cyan">Free slot</td>
<td bgcolor="pink">OS</td>
<td bgcolor="pink">Creative Skills</td>
<td bgcolor="cyan">Free slot</td>
</tr>
<tr>
<th bgcolor="green">12-1</th>
<td colspan="6" align="center" bgcolor="cyan">LUNCH</td>
</tr>
<tr>
<th bgcolor="green">1-3</th>
<td bgcolor="cyan">Free slot</td>
<td bgcolor="pink">Web App</td>
<td bgcolor="cyan">Free slot</td>
<td bgcolor="pink">Web App</td>
<td bgcolor="cyan">Free slot</td>
<td bgcolor="pink">Japanese</td>
</tr>
<tr>
<th bgcolor="green">3-5</th>
<td colspan="2" align="center" bgcolor="cyan">Free slot</td>
<td bgcolor="pink">Japanese</td>
<td colspan="2" align="center" bgcolor="cyan">Free slot</td>
<td bgcolor="pink">Adv c</td>
</tr>
<tr>
<th bgcolor="green">5-7</th>
<td bgcolor="cyan">Free slot</td>
<td colspan="5" align="center" bgcolor="pink">Python</td>

</tr>
</table>
    </body>
<body>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19CY205</td>
<td>Principles of Chemistry in Engineering(chem)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development(Web App)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI305</td>
<td>Advanced C Programming(Adv c)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19AI301C</td>
<td>Python anf Linear Algebra(Python)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19CS405</td>
<td>Operating System(OS)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EY702</td>
<td>Creative Skills for Communication(Creative Skills)</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19EN615C</td>
<td>Japanese Basic and Advanced(Japaneses)</td>
</tr>
</table>
</body>
</html>
```


## OUTPUT
![alt text](image.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
