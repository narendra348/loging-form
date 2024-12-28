<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <pre>
        <h1>APPLICATION FORM</h1>
    </pre>
    <form action="submit.php" method="post">
        <label for="first name">firstname</label>
<input type="text" id="firstname" name="firstname" placeholder="enter fname" required>
<br><br>
<label for="dob">dob</label>
<input type="password" id="dob" name="dob" placeholder="d/mm/y" required>
<br><br>
<select name="gender">
<option value="male">male</option>
    <option value="female">female</option>
</select>
<label for="positio available">position available</label>
<input type="radio" name="position available" value="junior developer">junior developer
<input type="radio" name="position available" value="mid level-developer">mid level-developer
<input type="radio" name="position available" value="senior deveioper">senior developer
<br>
<label for="prog lang">programming languages</label>
<input type="radio" name="prog lang" value="java">java
<input type="radio" name="prog lang" value="javascript">javascript 
<input type="radio" name="prog lang" value="python">python<br>
<label for="password">password</label> 
<input type="password" id="password" name="password" required>
<br>
<label for="cofirm password">confirm password</label>
<input type="password" id="password" name="password" required>


    </form>
</body>
</html>
