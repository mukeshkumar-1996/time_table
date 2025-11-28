# Ex03 Time Table
# Date:28/11/2025
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
    <head>
        <title>SLOT TIME TABLE</title>
        <style>
        img{
            width: 1100px;;
            height:auto;
            display:block;
            margin-left: auto;
            margin-right: auto;
            margin-top: auto;
            margin-bottom: auto;
        } 
    table {
      width: 70%;
      margin: 2px auto;
      text-align: center;
      font-size: 16px;
      color: black;
      background-color: aqua;
      border-style: double;
      margin-top: auto; 
      margin-bottom:20px;
    }
    th, td {
      border: 1px solid black;
      padding: 6px;
      background-color: aqua;
    }
    sub{
         text-align: center;
         }  
         </style>
    </head>
    <body> 
        <div>
            <img src="https://github.com/dr-pvijayan/slot_timetable/blob/main/logo.png?raw=true">
        </div>
        <div>
               <p class="sub" style="text-align: center; font-size: xx-large;"> SLOT TIME TABLE-MUKESHKUMAR.V(25012063)</p>
        </div>
        <table >
         <tr>
                <th style="background-color: yellow;">Timings/Days</th>
                <th style="background-color: yellow;">Monday</th>
                <th style="background-color: yellow;">Tuesday</th>
                <th style="background-color: yellow;">Wednesday</th>
                <th style="background-color: yellow;">Thursday</th>
                <th style="background-color: yellow;">Friday</th>
                <th style="background-color: yellow;">Saturday</th>
             </tr>
             <tr>
                <td style="background-color: yellow;">8am to 10pm</td>
                <td style="background-color: aqua;" colspan="3" style="text-align: center;">Fwad</td>
                <td style="background-color: aqua;">Free Slot</td>
                <td style="background-color: aqua;">Data science</td>
                <td style="background-color: aqua;">Python</td>
             </tr>
             <tr>
                <td style="background-color: yellow;">10am to 12pm</td>
                <td style="background-color: aqua;" >Free</td>
                <td style="background-color: aqua;">Python</td>
                <td style="background-color: aqua;" colspan="2"style="text-align: center;">Data Science</td>
                <td style="background-color: aqua;" colspan="2" style="text-align: center;">Free Slot</td>
               </tr>
                <tr>
                <td style="background-color: yellow;">12pm to 1pm</td>
                <td style="background-color: aqua;" colspan="6"style="text-align: center;">Lunch</td>
               </tr>
               <tr>
                <td style="background-color: yellow;">1pm to 3pm</td>
                <td style="background-color: aqua;">Fwad</td>
                <td style="background-color: aqua;">Data Science</td>
                <td style="background-color: aqua;">Mentor Meet</td>
                <td style="background-color: aqua;">Data Science</td>
                <td style="background-color: aqua;">Fwad</td>
                <td style="background-color: aqua;">Free Slot</td>
             </tr>
             <tr>
                <td style="background-color: yellow;">3pm to 5pm</td>
                <td style="background-color: aqua;">Free Slot</td>
                <td style="background-color: aqua;" colspan="3"style="text-align: center;">python</td>
                <td style="background-color: aqua;" colspan="2"style="text-align: center;">Free Slot</td>
             </tr>
        </table >
        <div>
       <table>
         <tr>
                <th style="background-color:yellow;">S.no</th> 
                <th style="background-color:yellow;">Subject Code</th>
                <th style="background-color:yellow;">Subject name</th>
             </tr>
              <tr>
                <td style="background-color: yellow;">1 </td> 
                <td style="background-color: white;"> 19AI414</td>
                <td style="background-color: white;">Fundamentals of Web Application Development(fwad)</td>
             </tr>
              <tr>
                <td style="background-color: yellow;">2</td> 
                <td style="background-color: white;">19AI403</td>
                <td style="background-color: white;">Introduction of Data Science</td>
             </tr>
             <tr>
                <td style="background-color: yellow;">3</td> 
                <td style="background-color: white;">19AI301</td>
                <td style="background-color: white;">Python Programming</td>
             </tr>
             <tr>
               <td style="background-color: yellow;">4</td>
               <td style="background-color: white;">(ECM-M)</td>
               <td style="background-color: white;">Mentor Meet</td>
             </tr>
             </div>
        </table>
    </body>
</html>

```

# OUTPUT


![alt text](<Screenshot (17).png>)

# RESULT
The program for creating slot timetable using basic HTML tags !