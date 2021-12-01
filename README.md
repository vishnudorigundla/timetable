# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
~~~<!DOCTYPE html>
<html>

   <head>
      <title>TIME TABLE</title>
   </head>
	
   <body>
      <table border = "8" cellspacing="3" bordercolor="BLUE" bgcolor="GREY">
      <img src="logo.png">
         <tr>
            <th colspan="8">TIME TABLE</th>
         </tr>
         <tr>
                <th colspan="2">Reference number:</th>
                <th colspan="2" align="left">21005311</th>
                <th colspan="2">Name:<th>
                <th colspan="2" align="left">D Vishnuvardhan Reddy</th>
        <tr>
            <th>DAYS</th>
            <th>1</th>
            <th>2</th>
            <th>3</th>
            <th>4</th>
            <th>5</th>
            <th>6</th>
            <th>7</th>
            
            
        </tr>
        
      <tr>
             <td>MONDAY</td>
             <td colspan="2">Fundamentals of web technology</td>
             <td colspan="2">Linear algebra laboratory</td>
	        <th rowspan="1">LUNCH BREAK</th>
             <td colspan="2">Mathematics for artificial intelligence</td>
         </tr>
             <td>TUESDAY</td>
             <td colspan="2">Soft skills</td>
             <td colspan="2">Engineering design and modelling</td>
             <th rowspan="1">LUNCH BREAK</th>
             <td colspan="2">Engineering mechanics and product development</td>
        </tr>
  
  	     <td>WEDNESDAY</td>
             <th colspan="2">Free period</th>
             <td colspan="2">MAthematics for artificial intelligence</td>
             <th rowspan="1">LUNCH BREAK</th>
             <td colspan="2">Fundamentals of web technology</td>
         </tr>
	     <td>THURSDAY</td>
             <td colspan="2">Engineering mechanics and product development</td>
             <td colspan="2">Python Programming</td>
             <td colspan="1">Mentoring</td>
             <td colspan="2">Engineering design and modelling</td>
         </tr>  
	     <td>FRIDAY</td>
             <td colspan="2">Environmental science</td>
             <td colspan="2">Python programming</td>
             <th rowspan="1">LUNCH BREAK</th>
             <td colspan="2">Web technology Laboratory</td>
          </tr>  
	     <td>SATURDAY</td>
             <td colspan="7" align="center">HOLIDAY</td> 
          </tr>  
	     <td>SUNDAY</td>
             <td colspan="7" align = "center">HOLIDAY</td>           
      </table>
   </body>
</html>
</html>


~~~
# OUPUT
![OUTPUT](/IMAGES/img9.png)
# RESULT:
Thus the program to create the simple time table using html is created sucessfully.
