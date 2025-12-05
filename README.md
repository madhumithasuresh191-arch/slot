# Ex03 Time Table
## Date:29-11-2025
## Ref no: 25014660

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
~~~
<<html>
    <head>
        <title>Slot Timetable</title>
    </head>
    <body>
        <center>
            <img src="/static/logo.png" height="100" width="540">
        </center>
        <br>
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
            <caption><b>SLOT TIME TABLE - S Madhumitha (25014660)</b></caption>
            <tr align="center">
                <th bgcolor="pink">Day/Time</th>
                <th bgcolor="pink">Monday</th>
                <th bgcolor="pink">Tuesday</th>
                <th bgcolor="pink">Wednesday</th>
                <th bgcolor="pink">Thursday</th>
                <th bgcolor="pink">Friday</th>
                <th bgcolor="pink">Saturday</th>
            </tr>
            <tr align="center">
                <th bgcolor="pink">8-10</th>
                <td >FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>COMMUNICATIVE ENGLISH</td>
                <td>FREE SLOT</td>
                <td>FUNDAMENTALS OF C PROGRAMMING</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center">
            <th bgcolor="pink">10-12</th>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>FREE SLOT</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            </tr>
            <tr>
                <th bgcolor="pink">12-1</th>
                <td colspan="5" align="center">L U N C H</td>
            </tr>
            <tr align="center">
            <th bgcolor="pink">1-3</th>
            <td>FREE SLOT</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>COMMUNICATIVE ENGLISH</td>
            </tr>
            <tr align="center">
            <th bgcolor="pink">3-5</th>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
            <td>FUNDAMENTALS OF WEB APPLICATIONS</td>
            <td>FREE SLOT</td>
            </tr>
         </table>
         <br>
         <table align="center"  cellspacing="2" cellpadding="4" border="2">
          <tr align="center">
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Code</th>
          </tr>
          <tr> 
          <td align="center">1.</td> 
          <td align="center">19AI414</td>
          <td> Fundamentals of Web Application Development (FWAD)</td>
          </tr>
          <tr> 
          <td align="center">2.</td> 
          <td align="center">19AI302</td>
          <td> Fundamentals of C Programming (C Program)</td>
          </tr>
          <tr> 
          <td align="center">3.</td>
~~~

## Output
<img width="1907" height="959" alt="Screenshot 2025-12-05 110053" src="https://github.com/user-attachments/assets/83086e4a-9594-46ee-b4a3-551a2b3be36f" />


<img width="1920" height="1020" alt="Screenshot 2025-11-28 162351" src="https://github.com/user-attachments/assets/92a91077-60f0-46eb-88b2-dab2865c36de" />

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
