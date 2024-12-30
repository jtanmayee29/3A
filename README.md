# 3A
<!DOCTYPE html>  
<html lang="en">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Registration Form</title>  
    <link rel="stylesheet" href="styles.css">  
</head>  
<body>  
    <div class="container">  
        <h2>Register Here</h2>  
        <form action="submit_registration.php" method="post">  
            <label for="fname"><b>First Name</b></label>  
            <input type="text" id="fname" name="firstname" placeholder="Enter First Name" required>  
  
            <label for="lname"><b>Last Name</b></label>  
            <input type="text" id="lname" name="lastname" placeholder="Enter Last Name" required>  
  
            <label for="email"><b>Email</b></label>  
            <input type="email" id="email" name="email" placeholder="Enter Email" required>  
  
            <label for="psw"><b>Password</b></label>  
            <input type="password" id="psw" name="password" placeholder="Enter Password" required>  
  
            <label for="psw-repeat"><b>Repeat Password</b></label>  
            <input type="password" id="psw-repeat" name="psw-repeat" placeholder="Repeat Password" required>  
  
            <label for="mobile"><b>Contact</b></label>  
            <input type="text" id="mobile" name="mobile" maxlength="10" placeholder="Enter Contact Number" required>  
  
            <label for="gender"><b>Gender</b></label>  
            <select id="gender" name="gender" required>  
                <option value="male">Male</option>  
                <option value="female">Female</option>  
                <option value="other">Other</option>  
            </select>  
  
            <button type="submit">Register</button>  
        </form>  
    </div>  
</body>  
</html>  
