# html-ABC-college


There should be an appropriate description of the college on the home page.
# AIM:
Design a website for a College. There should be at least 15 web-pages present in the web-site.
## index.html:
```
<!DOCTYPE html>
<head>
    <title>Saveetha engineering college</title>
    <meta charset=""UTF-8>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <body>
    <img src="/Users/admin/Desktop/MFS/WEB_LOGO-01 (1).png" alt="logo" align=""top" width="100%">
    <style>
        body{background-color: rgb(215, 242, 250);}
        p{
            font-size: 34px;
            font-weight: bold;
            font-style:normal;}
            h1{
                font-size: "30px";
                font-weight: 700;
                font-style: normal;
                justify-content: center;
            }
            h2{
                font-size: 20px;
                justify-content: center;
    
            }
        </style>
        </head>
        <center>
    <p >WELCOME TO SEC !!</p>
    <h1>ABOUT</h1>
    <h2>Welcome to SEC - Saveetha Engineering College (Autonomous), a distinguished institution established in 2001 under the visionary leadership of Dr. N. M. Veeraiyan— a committed medical professional and philanthropist par excellence. With over 35 years of unwavering commitment to excellence in education, our college has emerged as the forefront of engineering education and research.</h2>
</center>
<center>
<a href="/Users/admin/Desktop/MFS/ex 2.1/academics.html">Academics</a><br>
<a href="/Users/admin/Desktop/MFS/ex 2.1/courses.html"> Click here! For Courses we provide</a><br>
<a href="/Users/admin/Desktop/MFS/ex 2.1/admission.html">Admission</a>
</center>
    </body>
</HTML>
```
## courses.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <style>
        body{
            background-color: rgb(213, 209, 157);
            
        }
        p{
            font-size: large;
            font-weight: 800;
        }
        h1{
            font-size: medium;
        font-weight: 600;
        }
    </style>
    <center>
    <p>Computer science</p>
    <img src="/Users/admin/Desktop/MFS/download.jpeg" width="40%">
    <P>Mathematics</P>
    <img src="/Users/admin/Desktop/MFS/image-20160927-14593-1rf92dt.avif" width="40%">
    <p>English</p>
    <img src="/Users/admin/Desktop/MFS/images.jpeg" width="40%">
    <p>economics</p>
    <img src="/Users/admin/Desktop/MFS/images (1).jpeg" width="40%">
    </center>
</body>
</html>
```
## academics.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <style>
        BODY{
            background-color: antiquewhite;
            
        }
        p{
            font-size: x-large;
            font-weight: bolder;
            
        }
        h1{
            font-size: large;
            font-weight: 800;
            justify-content: center;
            font-family: Arial, Helvetica, sans-serif;
        }
        h2{
            font-size: small;
            font-weight: 600;
            
        }
    </style>
    <CENTER>
    <p>LIFE AT SAVEETHA</p>
    <IMG SRC="/Users/admin/Desktop/MFS/DSC_0096.jpg" width="35%" border="10px">
</CENTER>
<h1>The Teaching and Learning Method :</h1>
<h2>All academic information including daily lecture notes and important questions are updated on Website to be accessed by student from anywhere before they come to the class. As per the teaching and learning method, each of the departments focuses on continuous assessment of students throughout the semester and year through continuous internal accessment exams, assignments, model exams etc. The department continuously tracks the course coverage by the faculty, and plans for any extra classes to complete the portions in time. Students’ attendance and their marks in each are being updated daily in the college website for the parents view.</h2>
<a href="/Users/admin/Desktop/MFS/ex 2.1/courses.html"> Click Here! For courses we provide</a>
</body>
</html>
```
## admission.html
```
<html>
    <head> 
    <title>
    Registration Page
    </title>
    <style>
      body {
        background-color: rgb(247, 245, 242);
      }
    </style>
    </head>
    <body>
        <img src="/Users/admin/Desktop/MFS/WEB_LOGO-01 (1).png" alt="logo" align="top" width="100%">
    <br>
    <br>
    <form>
    
    <label> Firstname </label>       
    <input type="text" name="firstname" size="15"/> <br> <br>
    <label> Middlename: </label>   
    <input type="text" name="middlename" size="15"/> <br> <br>
    <label> Lastname: </label>       
    <input type="text" name="lastname" size="15"/> <br> <br>
    
    <label> 
    Course :
    </label> 
    <select name="course">
    <option value="Course">Course</option>
    <option value="Computer Science Engineering">cse</option>
    <option value="Electronics and Electrical Engineering">eee</option>
    <option value="Electronics and Communication Engineering">ece</option>
    <option value="BME">bme</option>
    <option value="Civil">civil</option>
    <option value="Mech">Mech</option>
    </select>
    
    <br>
    <br>
    <label> 
    Gender :
    </label><br>
    <input type="radio" name="gender" value="male"/> Male <br>
    <input type="radio" name="gender" value="female"/> Female <br>
    <input type="radio" name="gender" value="other"/> Other
    <br>
    <br>
    
    <label> 
    Phone :
    </label>
    <input type="text" name="country_code"  value="+91" size="2"/> 
    <input type="text" name="phone" size="10"/> <br> <br>
    Address
    <br>
    <textarea cols="80" rows="5" name="address"></textarea>
    <br>
    <br>
    <input type="submit" value="Register">
    </form>
    </body>
</html>
```
## OUTPUT:

![Screenshot 2024-07-04 at 9 34 09 AM](https://github.com/gowriganeshns/html-ABC-college/assets/161415847/6389b047-7ee0-43b2-86a5-203466bc949c)
![Screenshot 2024-07-04 at 9 34 18 AM](https://github.com/gowriganeshns/html-ABC-college/assets/161415847/2c6a7fb8-14e4-4fae-8fd5-54ffc06db198)
![Screenshot 2024-07-04 at 9 34 27 AM](https://github.com/gowriganeshns/html-ABC-college/assets/161415847/eed83939-2371-46ac-be64-fced6f5e52dc)
![Screenshot 2024-07-04 at 9 34 37 AM](https://github.com/gowriganeshns/html-ABC-college/assets/161415847/042704f3-4bcd-4dc8-876e-d3ed26e21809)
![Screenshot 2024-07-04 at 9 34 45 AM](https://github.com/gowriganeshns/html-ABC-college/assets/161415847/ae489186-c32b-4e22-acc7-bb606be63d45)
![Screenshot 2024-07-04 at 9 34 59 AM](https://github.com/gowriganeshns/html-ABC-college/assets/161415847/2726f1c8-90b7-4a89-88c9-3d27a69c40ee)
