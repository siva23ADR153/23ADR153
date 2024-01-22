<html>
<head>
<title>Form</title>
</head>
<style>
body{background: linear-gradient(yellow,green,orange);}
</style>
<body>
<font color="violet">R</font> 
<font color="indigo">E</font>
<font color="blue">G</font>
<font color="green">I</font>
<font color="red">S</font>
<font color="black">T</font>
<font color="violet">R</font>
<font color="orange">A</font>
<font color="brown">T</font>
<font color="violet">I</font>
<font color="green">O</font>
<font color="violet">N</font>
<font color="red">--</font>
<font color="blue">F</font>
<font color="red">O</font>
<font color="green">R</font>
<font color="blue">M</font>
<form>
<label for="NAME">First name:</label>
<input type="text" placeholder="Enter first name" id="name" name="name" required/><br><br>
<label for="NAME">Last name:</label>
<input type="text" placeholder="Enter last name" id="name" name="name" required/><br><br>
<label for="DOB">DOB:</label>
<input type="date" placeholder="Enter your dob" id="dob" name="dob" required/><br><br>
<label for="number">Mobile No:</label>
<input type="tel" placeholder="Enter mobile no" id="number" name="number" required/><br><br>
<p>Gender</p>
<input type="radio" id="GENDER" name="GENDER" value="male"/>MALE
<input type="radio" id="GENDER" name="GENDER" value="female"/>FEMALE
<input type="radio" id="GENDER" name="GENDER" value="Others"/>OTHERS<br>
<label for="mail">Email:</label>
<input type="email" placeholder="@gmail.com"id="mail" name="user_email" required/><br><br>
<label for="nationality">Nationality:</label>
<input type="text" placeholder="Your nationality" id="nationality" name="nationality" required/><br><br>
<label for="course">Course:</label>
<select id="course" name="course">
<option>course</option>
<option value="tamil">Tamil</option>
<option value="english">English</option>
<option value="MODE">MODE</option>
<option value="physics">Physics</option>
<option value="eit">EIT</option>
<option value="cp">CP</option>
</select><br><br>	
<p>Select Course</p>
<input type="checkbox" id="vehicle1" name="course1" required>
<label for="course1">Problem solving using python</label><br>
<input type="checkbox" id="vehicle2" name="course2" required>
<label for="course">UI Design</label><br>
<input type="checkbox" id="vehicle3" name="course3" required>
<label for="course">Data Analysis</label><br>
<label for="PASSWORD">Password:</label>
<input type="password" id="password" name="password" required/><br><br>
<label for="PASSWORD">Confirm password:</label>
<input type="password" id="password" name="password" required/><br><br>
<label for="address">Adderss:</label>
<textarea id="msg" id="address" name="address" required></textarea><br><br>
<input type="submit" bgcolor="red" value="submit">
<input type="reset" value="reset">
</form>
</body>
</html>	
