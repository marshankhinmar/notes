thank u Collin
20.3.2024
```
Variables are Containers for Storing Data
JavaScript Variables can be declared in 4 ways:

Automatically
Using var
Using let
Using const
When to Use var, let, or const?
1. Always declare variables

2. Always use const if the value should not be changed

3. Always use const if the type should not be changed (Arrays and Objects)

4. Only use let if you can't use const

5. Only use var if you MUST support old browsers.
JavaScript Code Blocks
JavaScript statements can be grouped together in code blocks, inside curly brackets {...}.

22/3/2024
<ul>

    <li> Home </li>
    <li> Product </li>
    <li> Shopping</li>
    <li> Contact NO.</li>
</ul>

<ol>

    <li> Home </li>
    <li> Product </li>
    <li> Shopping</li>
    <li> Contact NO.</li>
</ol>

<p>

    This is just testing for <span style="color:aquamarine"> span </span>.

<img src ="a yuu ma.jpg " width= "500px" height="500px"

<h3> List of citizens or sinners in Myanmar</h3>
    
    <form action="/" method="get">

        <div>

            <label for=" Username">User Name:</label>
            <input type=" text" name="Username" Id="user" required placeholer="Enter Your Name....">

        </div>


        <div>

            <label for=" pwd"> Password:</label>
            <input type="password" name="pwd" Id="user" required placeholder="Enter your secret, Lol">


        </div>
        <div>
            <button type="ResetButton"> Reset</button>
            <button type="submitButton"> login</button>

        </div>
    

    </form>

23/3/2024

<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>Marshan Survey Form</title>
</head>

<body>
    <h1> Survey Form</h1>
    <form>

        <div>
        <label for="Firstname">First Name: </label>
        <input type="text" name="Firstname" id="Firstname">
       </div>

       <div>

        <label for="Lastname">Last Name: </label>
        <input type="text" name="Lastname" id="Lastname"> 

       </div>

       <div>

        <label for="email">Email</label>
        <input type="text" name="email" id="email">

       </div>
       <div>

        <label for="birthdate">Date of Birth</label>
        <input type="date" name="birthdate" id="birthdate">

       </div>

       <h3>Gender</h3>
       <div>
        <label for="male">Male</label>
        <input type="radio" id="male" name="gender" value=" male">
        <label for="female">Female</label>
        <input type="radio" id="female" name="gender" value=" female">
        <label for="other">Other</label>
        <input type="radio" id="other" name="gender" value=" other">

       </div>


       <div>
            <select>
                <option value="html">Html</option>
                <option value="Css">Css</option>
                <option value="js">Javescript</option>
                <option value="c#">C#</option>

            </select>

        <div>
            <h2>Favourite Progamming Languages</h2>
            <label for="html">Html</label>
            <input type="checkbox" id="html" name="html" value="html">
            <label for="python">Python</label>
            <input type="checkbox" id="python" name="python" value="python">
            <label for="C++">C++</label>
            <input type="checkbox" id="C++" name="C++" value="C++">

        </div>

        <div>
            
            <button type="submit" name="Submityoursurvey" id="submityoursurvery"> Submit</button>

        </div>
    </form>
</body>
</html>




23/3/2024 (Revision)

<!DOCTYPE html>
<html lang="en">
<head>
   
    <title>Marshan Personal Space</title>
</head>
<body>

    <h1> Marshan Khin Mar Oo</h1>

    <p> This is kind of my portfolio or smth like that.</p>
    
    <p> i am trying my best for <strong> my self production</strong> and i want to <em>destroy</em> my old bad habbits into a skill of a specific career so that I will be a better person for my mom.</p>

    <a href="www.google.com"> Go to Google</a>

    <ul>
        <li> Home</li>
        <li> Products</li>
        <li> Price</li>
        <li> Payment type</li>

    </ul>

    <ol>

        <li> Home</li>
        <li> Products</li>
        <li> Price</li>
        <li> Payment type</li>

    </ol>

    <p>
        I've never thought <span style=" color: red"> these languages </span> will be interesting.

    </p>

    <img src="stu'slove.jpg" width="38 px" height="37 px">

</body>
</html>

<p> So here is another section</p>
<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>Login Form</title>
</head>
<body>
 <form>
    <div>
         <label for="Username">Username</label>
        <input type="text" name=" Username" id="Username" Required placeholder="Enter your name here">
    </div>

    <div>
        <label for="email">Email</label>
       <input type="text" name="email" id="email">
   </div>

   <div>
    <label for="birthday">Date of Birth</label>
   <input type="date" name=" birthday" id="birthday">
   </div>

   <div>
    <label for="pwd">Password</label>
   <input type="text" name=" password" id="pwd" required placeholder="Enter Your Password">
   </div>
   
   <div>
    <button type="Reset" name=" Resetbutton">Reset</Button>
    <button type="Submit" name="loginbutton"> Login</button>
   </div>

   <h2> Choose your Gender</h2>

   <div>

    <label for="male"> Male</label>
    <input type="radio" id="male" name="gender" value="male">

    <label for="female"> Female</label>
    <input type="radio" id="female" name="gender" value="female">

    <label for="other"> Others</label>
    <input type="radio" id="other" name="gender" value="other">

   </div>

   <div>

    <Select>

        <Option value="html">Html</Option>
        <Option value="css"> Css</Option>
        <Option value="js">Javascript</Option>
        <Option value="Python"> Python</Option>

    </Select>
   </div>


 
   <div>
   <button type="Submit" name="submityoursurvey" id="submityoursurvey">Submit your survery</button>
   </div>


 </form>
    
</body>
</html>



24/3/2024

<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>Marshan Login Form(upgrade)</title>

    <link rel="stylesheet" href="style.css">

</head>

<body>

    <div class= "container-box">
    <h1> Login Form</h1>

     <form>
    <div>

        <label for="user"> Username</label>
        <input type="text" name="username" id="user" placeholder="Enter your name here">
    </div>

    <div>
        <label for="pwd">Password</label>
        <input type="password" name="pwd" id="pwd" placeholder="At least 8 characters">


    </div>
    
    <div class="button-container">

        <button type=" Login">Login</button>
        <button type="submit">Submit</button>

    </div>

    </form>

    </div>

    <p class="footer-text"> Do not have acoount? Please <a href="register.html"> Register Here</a>.</p>


</body>
</html>

The Next part is as below. ************************

body{
    background-color: gray;
    font-family: sans-serif;
    font-size: 20px;
}

.container-box{

    width: 360px;
    height:100%;
    margin:auto;
    color:antiquewhite;
    background: linear-gradient(135deg, black, red);
    border-radius: 10px;
}

    h1{

        text-align: center;
        padding-top: 20px;
        font-size: 25px;
        padding-bottom: 20px;
        border: none;
        border-bottom: 1px solid white;
    }

    form{

        width: 300px;
        margin-left: 23px;
    }


    form input{
         
        width: 100%;
        padding: 7px;
        border: 1px;
        border-radius: 5px;
        margin-bottom: 10px;

    }

    .button-container{

        display: flex;
        padding-top: 20px;
        padding-bottom: 20px;
    }

     button{
        text-align: center;
        background: linear-gradient(135deg, red, black);
        border: 1px solid white;
        padding: 5px;
        margin: 5px;
        border-radius: 5px;
        color: white;
        width: 150px;
        cursor: pointer;
    }
        button:hover{
            background:linear-gradient(-135deg, red, black)
        }

    .footer-text{
        color:white;
        width:360px;
        margin: auto;
        text-align: center;
    }

    a:hover{
        color: pink;
    }


The purpose of code blocks is to define statements to be executed together.

One place you will find statements grouped together in blocks, is in JavaScript functions:


```
