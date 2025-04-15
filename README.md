# Ex03 Time Table
# Date:15.04.2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<html>
<title>title</title>
<body>
<img src="logo.png" height="100" width="540">
  <table border="6" cellspacing="4" cellpadding="4">
      <caption>MY TIME TABLE</caption>

          <tr>
            <th bgcolor="sky blue" align="center">day/time</th>
            <th bgcolor="sky blue" align="center">8:9 am</th>
            <th bgcolor="sky blue" align="center">9:10 am</th>
            <th bgcolor="sky blue" align="center">10:11 am</th>
            <th bgcolor="sky blue" align="center">11:12 am</th>
            <th bgcolor="sky blue" align="center">12:1 pm</th>
            <th bgcolor="sky blue" align="center">1:2 pm</th>
            <th bgcolor="sky blue" align="center">2:3 pm</th>
            <th bgcolor="sky blue" align="center">3:4 pm</th>
            <th bgcolor="sky blue" align="center">4:5 pm</th>
         </tr>

          <tr>
            <th bgcolor="sky blue" align="center" bgcolor="orange">MONDAY</th>
            <td colspan="2" align="center" bgcolor="orange">Communicative English</td> 
            <td colspan="2" align="center" bgcolor="orange">free</td>
            <td align="center" bgcolor="orange">LUNCH</td>
            <td colspan="2" align="center" bgcolor="orange">Maths</td>
            <th colspan="2" align="center" bgcolor="orange">free</th>                   
            </tr>

          <tr>
            <th bgcolor="sky blue" align="center" >TUESDAY</th>
            <th colspan="2" align="center" bgcolor="orange">Communicative English</th>
    <th colspan="2" align="center" bgcolor="orange">Maths</th>
    <td align="center" bgcolor="orange">LUNCH</td>
            <th colspan="2" align="center" bgcolor="orange">free</th>
    <th colspan="2" align="center" bgcolour="orange">physics</th>
            </tr>

          <tr>
            <th bgcolor="sky blue" align="center">WEDNESDAY</th>
            <td colspan="2" align="center" bgcolor="orange">web application</td>
            <td colspan="2" align="center" bgcolor="orange">Chemistry</td>                    
            <td align="center" bgcolor="orange">LUNCH</td>
            <td colspan="2" align="center" bgcolor="orange">free</td>                    
            <th colspan="2" align="center" bgcolor="orange">Softskill</th>                    
         </tr>

          <tr>
            <th bgcolor="sky blue" align="center">THURSDAY</th>
            <td colspan="2" align="center" bgcolor="orange">Chemistry</td>
            <td colspan="2" align="center" bgcolor="orange">web application</td>                    
            <td align="center" bgcolor="orange">LUNCH</td>
            <td colspan="2" align="center" bgcolor="orange">physics</td>                    
            <th colspan="2" align="center" bgcolor="orange">python</th>                    
         </tr>

            <tr>
            <th bgcolor="sky blue" align="center">FRIDAY</th>
            <th colspan="2" align="center" bgcolor="orange">free</th>                    
            <th colspan="2" align="center" bgcolor="orange">free</th>
            <td align="center" bgcolor="orange">LUNCH</td>
            <td colspan="2" align="center" bgcolor="orange">web application</td>                    
            <td colspan="2" align="center" bgcolor="orange">python</td>
            </tr>

  </table>
  <table border="4" cellspacing="4" cellpadding="4">

/<caption>SUBJECT AND THEIR RESPECTIVE SUBJECT CODES </caption>
             <tr>
            <th align="center" bgcolor="blue">S.NO</th>
            <th align="center" bgcolor="blue">Subject Code</th>
            <th align="center" bgcolor="blue">Subject Name</th>
            </tr>

             <tr>
            <td align="center" bgcolor="blue">1.</td>
            <td align="center" bgcolor="yellow">19AI414</td>
            <td align="center" bgcolor="gold">Fundamentals Of Web Application Development (web application)</td>
            </tr>

             <tr>
            <th align="center" bgcolor="blue">2.</th>
            <td align="center" bgcolor="yellow">19AI301</th>
            <td align="center" bgcolor="gold">Python Programming (python)</th>
            </tr>

             <tr>
            <th align="center" bgcolor="blue">3.</th>
            <td align="center" bgcolor="yellow">19CY205</th>
            <td align="center" bgcolor="gold">Chemistry </th>
    </tr>

     <tr>
            <th align="center" bgcolor=" blue">4.</th>
            <td align="center" bgcolor="yellow">19EY701</th>
            <td align="center" bgcolor="gold"> Soft Skills </th>
            </tr>

             <tr>
            <th align="center" bgcolor="blue">5.</th>
            <td align="center" bgcolor="yellow">19EN101</th>
            <td align="center" bgcolor="gold">Communicative English</th>
            </tr>

             <tr>
            <th align="center" bgcolor="blue">6.</th>
            <td align="center" bgcolor="yellow">19PH214</th>
            <td align="center" bgcolor="gold">Physics For Qantum Computing (physics)</th>
            </tr>

     <tr>
    <th align="center" bgcolor="blue">7.</th>
            <td align="center" bgcolor="yellow">19MA201</th>
            <td align="center" bgcolor="gold">Calculus and Matrix Algebra</tb>
            </tr>

  </table>    
 </body>
```
# OUTPUT
![SLOT TIME TABLE](https://github.com/user-attachments/assets/e7dc9af3-43c7-42a8-ae92-59a4d422c89e)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
