# Ex03 Time Table
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
```
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="c:\Users\admin\Desktop\html\saveetha logo.jpeg" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIMETABLE - S.JAYA ABIRAMI (23004968)</b></caption>
<tr align="center">
	<th bgcolor="yellow">Day/Time</th>
	<th bgcolor="yellow">Monday</th>
	<th bgcolor="yellow">Tuesday</th>
	<th bgcolor="yellow">Wednesday</th>
	<th bgcolor="yellow">Thursday</th>
	<th bgcolor="yellow">Friday</th>
</tr>
<tr align="center">
	<th bgcolor="yellow">8-10</th>
	<td>Computer networks</td>
	<td>ComPUTER networks</td>
	<td>Web development</td>
	<td>Soft skills</td>
	<td>Logic and combinatorics</td>
</tr>
<tr align="center">
	<th bgcolor="yellow">10-12</th>
	<td>FREE</td>
	<td>Logic and combinatorics</td>
	<td>FREE</td>
	<td>Web development</td>
	<td>FREE</td>
</tr>
<tr>
	<th bgcolor="yellow">12-1</th>
	<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
	<th bgcolor="yellow">1-3</th>
	<td>Chemistry</td>
	<td>FREE</td>
	<td>Chemistry</td>
	<td>FREE</td>
	<td>Web development</td>
</tr>
<tr align="center">
	<th bgcolor="yellow">3-5</th>
	<td>FREE</td>
	<td>FREE</td>
	<td>fundamentals of C</Cap></td>
	<td>fundamentals of C</td>
	<td>FREE</td>
</tr>
</table>
</br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19MA206</td>
<td>logic and combinatorics</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI414</td>
<td>Web development</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS406</td>
<td>Computer networks</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CY205</td>
<td>Chemistry</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EY701</td>
<td>Soft skills</td>
</tr>
</table>
</body>
</html>
```
## OUTPUT
![Screenshot 2024-04-04 085436](https://github.com/JayaAbirami/slot/assets/151487010/3e7b5ae3-ccb1-4a37-92a3-ef9f4a911f85)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
