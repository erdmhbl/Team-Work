<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clarusway Survey Form</title>
    <link rel="stylesheet" href="style.css">
    <style>
       
        #onay{
            width: 55px;
        }
        #h1{
            text-decoration: overline;
            font-size: 46px;
            margin-bottom: 1px;

        }

        #p1{
            margin-top: 1px;
        }
    </style>
</head>
<body>
    <div id="container">
    <form action="">
    <h1 id="h1">Clarusway Survey Form</h1>
    <p id="p1">Thank you for taking the time to help us improve the platform</p>

        <label for="Name">Name</label><br>
        <input type="text" name="Name" id="Name" placeholder="Enter your name"><br>
        <label for="surname">Surname</label><br>
        <input type="text" name="surname" id="surname" placeholder="Enter your Surname"><br>
        <label for="email">Email</label><br>
        <input type="email" name="email" id="email" placeholder="user@clarusway.com">
        <p>Which option bestdescribes your current role?</p>
        <select name="Current Role" id="current role">
            <option value="current role" selected>Select current role</option>
        </select>
        <p>Would you recommend Clarusway to a friend?</p>
        <input type="radio" name="recommend friend" id="Definitely, Yes" value="Definitely, Yes" checked>
        <label for="Definitely, Yes" >Definitely, Yes</label><br>
        <input type="radio" name="recommend friend" id="Maybe" value="Definitely, Yes">
        <label for="Maybe">Maybe</label><br>
        <input type="radio" name="recommend friend" id="Not sure" value="Definitely, Yes">
        <label for="Not sure">Not sure</label><br>
        <input type="radio" name="recommend friend" id="Definitely, No" value="Definitely, Yes">
        <label for="Definitely, No">Definitely, No</label>
        <p>What is your favotite feature of Clarusway?</p>
        <select name="favorite feature" id="feature">favorite feature
            <option value="favorite feature">Select an option</option>
        </select>
        <p>What would you like to see improved?(Check all that apply)</p>
        <input type="checkbox" name="front" id="front">
        <label for="front">Front-end Projects</label><br>
        <input type="checkbox" name="backend" id="back">
        <label for="back">Back-end Projects</label><br>
        <input type="checkbox" name="data" id="data">
        <label for="data">Data Science</label><br>
        <input type="checkbox" name="Additional Courses" id="Additional Courses">
        <label for="Additional Courses">Additional Courses</label><br><br>
        <label for="comments">Any comments or suggestions?</label><br>
        <textarea name="comments" id="comments" cols="15" rows="2" placeholder="Enter your comment here..Thanks for your idea.."></textarea>
        <input type="submit" value="Submit" id="onay">

    </form>
    </div>  
</body>
</html>
