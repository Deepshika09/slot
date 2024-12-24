# Ex03 Time Table
## Date:20.11.2024

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
        <table border="1" align="center" cellpadding="10">
            <caption align="center">SLOT TIMETABLE - DEEPSHIKA(24008389)</caption>
            <center>
                <img src="/static/logo.png" height="100" width="540">
            </center>

        <tr font bgcolor="lavender">
        <th>Day/Time</th>
        <TH>Monday</th>
        <th> Tuesday </th>
        <th>Wednesday</th>
        <th>Thurday</th>
        <th>Friday</th>
        <th>Saturday</th>
        </tr>
        <tr bgcolor="pink">
            <td bgcolor="lavender">8-10</td>
            <td colspan="2" align="center">FREE SLOT</td>
            <td>MATHS</td>
            <td>ENGLISH</td>
            <td colspan="2" align="center">FREE SLOT</td>


                
        </tr>
        <tr bgcolor="pink">
            <td bgcolor="lavender">10-12 </td>
            <td>ENGLISH</td>
            <td> EDM </td>
            <td>C PROGRAM</td>
            <td>MATHS</td>
            <td>C PROGRAM</td>
            <td>WEB</td>
            
            </tr>
            <tr bgcolor="skyblue">
            <td  bgcolor="lavender">12-1</td>
            <td colspan="10" align="center">L U N C H</td><br></br>

            </tr>
            <tr bgcolor="pink">
            <td bgcolor="lavender">1-3</td>
            <td>FREE SLOT</td>
            <td>WEB</td>
            <td>MENTOR MEET</td>
            <td>WEB</td>
            <td>EDM</td>
            <td>CHEMISTRY</td>
            

            </tr>
            <tr bgcolor="pink">
            <td bgcolor="lavender">3-5</td>
            <td colspan="2" align="center">FREE SLOT</td>
            <td>CHEMISTRY</td>
            <td>FREE SLOT</td>
            <td>CAREER</td>
            <td>FREE SLOT</td>
</tr>
</table>
<br></br>
<table align="center" cellpadding="6"cellspacing="3" border="2">
<tr>
    <th>S.NO</th>
    <th>Subject Code</th>
    <th>Subject Name</th>
    </tr>
    <tr>
        <td align="center">1.</td>
        <td align="center">19AI414</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
    </tr>
    <tr>
        <td align="center">1.</td>
        <td align="center">19AI302</td>
        <td>ENGINEERING DESIGN AND MODELLING</td> 
        </tr>
    <tr>
        <td align="center">3.</td>
        <td align="center">19EN101</td>
        <td>COMMUNICATIVE ENGLISH</td>
    </tr>
    <tr>
        <td align="center">4.</td>
        <td align="center">19MA201</td>
        <td>CALCULUS AND MATRIX ALGEBRA</td>
    </tr>
    <tr>
        <td align="center">5.</td>
        <td align="center">19AI304</td>
        <td>FUNDAMENTALSOF C PROGRAMMING</td>
    </tr>
    <tr>
        <td align="center">6.</td>
        <td align="center">19CY205</td>
        <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
    </tr>
    <tr>
        <td align="center">7.</td>
        <td align="center">19EY708</td>
        <td>CAREER DEVELOPMENT SKILLS</td>
    </tr>
        
        </table>
    </body>
</html>
```

## OUTPUT
![Screenshot 2024-11-16 213940](https://github.com/user-attachments/assets/5426142a-bae2-41de-88ae-1d047442398c)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
