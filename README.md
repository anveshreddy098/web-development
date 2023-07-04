<!DOCTYPE html>
<html>
    <title>Student Registration Form</title>
    <head>
        <style>
            body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background-image: url('pic.jpg');
      background-position: center;
      background-repeat: no-repeat;
      background-size: cover;
    } 
    h2{
        text-align: center;
    }
    .container {
      max-width: 400px;
      margin: 0 auto;
    }
    label {
      
      font-weight: bold;
    }
    button {
      background-color: #4caf4c;
      color: rgba(255, 255, 255, 0);
      padding: 10px 20px;
      border: none;
      cursor: pointer;
      width: 100%;
    }
        </style>
    </head>
    <body>
        <div class="container">

            <h2><u>STUDENT REGISTRATION FORM</u></h2>
            <label for="name">NAME:</label>
            <input type="text" id="name"></br></br>
            <label for="AGE">AGE:</label>
            <input type="text" id="age"></br></br>
            <label for="dob">DATE OF BIRTH:</label>
            <input type="date" id="dob"></br></br>
            <label for="gender">GENDER:</label>&nbsp;&nbsp;&nbsp;
            <label for="male">MALE:</label>
            <input type="radio" id="male" name="gender" value="male">&nbsp;&nbsp;&nbsp;&nbsp;
            <label for="female">FEMALE:</label>
            <input type="radio" id="female" name="gender" value="female"></br></br>
            <label for="address">ADDRESS:</label> <br>
            <textarea cols="40" rows="5" value="address">
            </textarea><br><br>
            <label for="phn">PHONE NUMBER:</label>
            <input type="text" size="3">
            <input type="text" id="phn" size="10"><br><br>
            <button type="submit"><a href="secondpage.html">REGISTER</a></button>
          

        </div>

    </body>

</html>
