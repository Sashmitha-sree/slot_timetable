# Ex03 Time Table
## Date:17-11-2024

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
'''
<html>
    <head>

    </head>
    <body align="center">
        <img src="/static/logo.png" width="500">
        <table border="2" cellpadding="10" align="center">
            <tr>
                <th bgcolor="#153E7E">TIME</th>
                <th bgcolor="#3B9C9C">MONDAY</th>
                <th bgcolor="#3B9C9C">TUESDAY</th>
                <th bgcolor="#3B9C9C">WEDNESDAY</th>
                <th bgcolor="#3B9C9C">THURSDAY</th>
                <th bgcolor="#3B9C9C">FRIDAY</th>
                <th bgcolor="#3B9C9C">SATURDAY</th>
            </tr>
            <tr>
                <th bgcolor="#AFDCEC">8am-10am</th>
                <th bgcolor="#87AFC7">-</th>
                <th bgcolor="#E3E4FA">POC</th>
                <TH bgcolor="#FDEEF4">FOCP</TH>
                <TH bgcolor="#87AFC7">-</TH>
                <TH bgcolor="#87AFC7">-</TH>
                <TH bgcolor="#C38EC7">DE</TH>
            </tr>
            <TR>
                <TH bgcolor="#AFDCEC">10am-12pm</TH>
                <th bgcolor="#EBDDE2">FWAD</th>
                <TH bgcolor="#BDEDFF">DS</TH>
                <TH bgcolor="#EBDDE2">FWAD</TH>
                <TH bgcolor="#50EBEC">CE</TH>
                <TH bgcolor="#C38EC7">DE</TH>
                <TH bgcolor="#E0FFFF">CDS</TH>
            </TR>
            <TR aria-colspan="7">
                <TH bgcolor="#AFDCEC">12pm-1pm</TH>
                <TH colspan="6" bgcolor="#153E7E">LUNCH</TH>
            </TR>
            <tr>
                <th bgcolor="#AFDCEC">1pm-3pm</th>
                <th bgcolor="#FDEEF4">FOCP</th>
                <TH bgcolor="#50EBEC">CE</TH>
                <TH bgcolor="#D2B9D3">MENTOR MEET</TH>
                <TH bgcolor="#E3E4FA">POC</TH>
                <TH bgcolor="#BDEDFF">DS</TH>
                <TH bgcolor="#EBDDE2">FWAD</TH>
            </tr>
        </table>
        <br>
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="5">
            <tr align="center">
                <th>sno</th>
                <th>subject code</th>
                <th>subject name</th>
            </tr>
            <tr align="center">
                <th>1.</th>
                <th>19AI414</th>
                <th>fundamentals of web application</th>
                
            </tr>
            <tr align="center">
                <th>2.</th>
                <th>19CY205</th>
                <th>principles of chemistry in engineering</th>

            </tr>
            <tr align="center">
                <th>3.</th>
                <th>19AI403</th>
                <th>introduction to data science</th>
            </tr>
            <tr align="center">
                <th>4.</th>
                <th>19AI304</th>
                <th>fundamental of c programming</th>
            </tr>
            <tr align="center">
                <th>5.</th>
                <th>19EE404</th>
                <th>digital electronics</th>
            </tr>
            <tr align="center">
                <th>6.</th>
                <th>19EN101</th>
                <th>communicative english</th>
            </tr>
            <tr align="center">
                <th>7.</th>
                <th>19EY708</th>
                <th>career development</th>
                
            </tr>
        </table>
    </body>
</html>
'''


## OUTPUT
![alt text](<Screenshot (8).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
