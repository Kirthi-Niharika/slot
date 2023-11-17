# Ex03 Time Table

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

## CODE
```
<html>
<head>
<title>Project Exhibition Schedule</title>
</head>
<body bgcolor="white">
<center><img src="saveetha.png"></center>
<h3><center>SLOT TIME TABLE - T KIRTHI NIHARIKA (21500327)<center></h3>
<TABLE BORDER="5" width="600" cellspacing="5" cellpadding="5" Align="center" bgcolor="cyan"> 
<TR bgcolor="yellow" > 
	<TH ><h3><b> Day/Time </b></h3></TH> 
	<TH ><h3><b>Monday</b></h3></TH>
	<TH><h3><b>Tuesday</b></h3></TH>
	<TH ><h3><b>Wednesday</b></h3></TH>
	<TH ><h3><b>Thursday</b></h3></TH>
	<TH ><h3><b>Friday</b><h3></TH>
</TR>   
<TR Align="center" > 
	<TD bgcolor="yellow">8-10</TD>
	<TD colspan="3">FREE SLOT</TD> 
	<TD >PHY</TD>
	<TD >CHEM</TD>
</TR>
<TR Align="center">
	<TD bgcolor="yellow">10-12</TD> 
	<TD >GER</TD>
	<TD >FREE SLOT</TD>
	<TD >FWAD</TD>
	<TD >FWAD</TD>
	<TD  >PHY</TD>
</TR>
<TR Align="center">
	<TD bgcolor="yellow">12-1</TD> 
	<TD colspan="5" > L U N C H</TD>

</TR>
<TR Align="center">
	<TD bgcolor="yellow">1-3</TD> 
	<TD colspan="2">FREE SLOT</TD>
	<TD >MAT</TD>
	<TD >MAT</TD>
	<TD>SS</TD>
</TR>
<TR Align="center">
	<TD bgcolor="yellow">3-5</TD> 
	<TD colspan="2">FREE SLOT</TD>
	<TD >GER</TD>
	<TD >CHE</TD>
	<TD>FWAD</TD>
</TR>
</TABLE>
<br>
<TABLE BORDER="5" width="600" cellspacing="5" cellpadding="5" Align="center" bgcolor="white"> 
<TR > 
	<TH ><h3><b> S.No. </b></h3></TH> 
	<TH ><h3><b>Subject Code</b></h3></TH>
	<TH ><h3><b>Subject Name</b></h3></TH>
</TR>   
<TR  > 
	<TD ><center>1.</center></TD>
	<TD ><center>19AI414</center></TD> 
	<TD >Fundamentals of Web Application Development (FWAD)</TD>
</TR>
<TR>
	<TD><center>2.</center></TD> 
	<TD ><center>19EN612</center></TD>
	<TD >German Basic(GER)</TD>

</TR>
<TR>
	<TD ><center>3.</center></TD> 
	<TD ><center>19PH206</center></TD>
	<TD >Physics for Information Technology(PHY)</TD>
</TR>
<TR>
	<TD ><center>4.</center></TD> 
	<TD ><center>19CY205</center></TD>
	<TD >Principles of Chemistry in Engineering (CHE)</TD>
</TR>
<TR>
	<TD><center>5.</center></TD> 
	<TD ><center>19MA201</center></TD>
	<TD >Calculus and Matrix Algebra(MAT)</TD>
</TR>
<TR>
	<TD><center>6.</center></TD> 
	<TD ><center>19EY701</center></TD>
	<TD >Soft Skills(SS)</TD>
</TR>
</TABLE>
</body>
<style>
h3 {text-align: center;}

</style>
```

## OUTPUT
<img width="960" alt="exp3" src="https://github.com/Kirthi-Niharika/slot/assets/114135005/4c13a81a-1ba1-416a-adb0-e8055bf1c60d">

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
