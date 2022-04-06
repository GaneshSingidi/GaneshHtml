# GaneshHtml

<!DOCTYPE html>
<html>
<head>
<title>Forms</title>
<style>
legend
{ font-size: 20px; }
#abc {
width: 100%;
}
#abcd {
text-align: center;
}
#abcde
{ width: 100%; }
body { background:linear-gradient(45deg,cyan,violet,deeppink); }
</style>
</head>
<body>
<h1 align="center">Online Job Application Form</h1>
<div>
<form method="post" action="URL">
<fieldset>
<legend>Personal Information</legend>
<table>
<tr>
<td><label>First Name</label></td>
<td><input type="text" name=""></td>
<td><label>Middle Name</label></td>
<td><input type="text" name=""></td>
<td><label>Last Name</label></td>
<td><input type="text" name=""></td>
</tr>
<tr>
<td><label>Father's Name</label></td>
<td><input type="text" name=""></td>
<td><label>Mother's Name</label></td>
<td><input type="text" name=""></td>
</tr>
<tr>
<td><label>Current Address</label></td>
<td><textarea></textarea></td>
<td><label>Permanent Address</label></td>
<td><textarea></textarea></td>
</tr>
<tr>
<td><label>Phone Number</label></td>
</tr>
<tr>
<td><label>Landline Number</label></td>
<td><input type="text" name=""></td>
<td><label>Mobile Number</label></td>
<td><input type="text" name=""></td>
</tr>
<tr>
<td><label>Date of Birth</label></td>
<td><input type="Date" name=""></td>
<td><label>Place of Birth</label></td>
<td><input type="text" name=""></td>
</tr>
<tr>
<td colspan="1"><label>Select Gender</label></td>
<td><input type="radio" name="r1">Male</td>
<td><input type="radio" name="r1">Female</td>
</tr>
<tr>
<td><label>Highest Qualification</label></td>
<td><input type="text" name=""></td>
<td><label>Year of Passing</label></td>
<td><input type="month" name=""></td>
</tr>
<tr>
<td colspan="3"><label>Languages Known</label></td>
<td><input type="checkbox" name="r1">Telugu</td>
<td><input type="checkbox" name="r2">Hindi</td>
<td><input type="checkbox" name="r3">English</td>
</tr>
<tr>
<td colspan="3"><label>Select your Hobbies</label></td>
<td><input type="checkbox" name="r1">Eating</td>
<td><input type="checkbox" name="r2">Coding</td>
<td><input type="checkbox" name="r3">Sleeping</td>
</tr>
<tr>
<td><label>About Yourself</label></td>
<td><textarea></textarea></td>
</tr>
<tr>
<td><label>Nationality</label></td>
<td><select>
<option>American</option>
<option>Indian</option>
</select></td>
</tr>
<tr>
<td><label>Aadhar Card Number</label></td>
<td><input type="text" name=""></td>
<td><label>Pan Card Number</label></td>
<td><input type="text" name=""></td>
</tr>
</table>
</fieldset>
</form>
</div>
<hr>
<div>
<form>
<fieldset>
<legend>Education Details</legend>
<table id="abc">
<thead>
<tr>
<th>SNO</th>
<th>College/University</th>
<th>Degree</th>
<th>From Date</th>
<th>To Date</th>
</tr>
</thead>
<tbody id="abcd">
<tr>
<td>1</td>
<td><textarea></textarea></td>
<td><textarea></textarea></td>
<td><input type="month" name=""></td>
<td><input type="month" name=""></td>
</tr>
<tr>
<td>2</td>
<td><textarea></textarea></td>
<td><textarea></textarea></td>
<td><input type="month" name=""></td>
<td><input type="month" name=""></td>
</tr>
<tr>
<td>3</td>
<td><textarea></textarea></td>
<td><textarea></textarea></td>
<td><input type="month" name=""></td>
<td><input type="month" name=""></td>
</tr>
</tbody>
</table>
</fieldset>
</form>
</div>
<div>
<form>
<fieldset>
<legend>Other Details</legend>
<table id="abcde">
<tr>
<td><label>Job Type</label></td>
<td><input type="radio" name="r1">Permanent</td>
<td><input type="radio" name="r1">Contract</td>
<td><input type="radio" name="r1">Others</td>
</tr>
<tr>
<td><label>Date of joining</label></td>
<td><input type="Date" name=""></td>
<td><label>Time of joining</label></td>
<td><input type="time" name=""></td>
</tr>
<tr>
<td><label>Perferred Job Location</label></td>
<td><input type="radio" name="r1">Hyderabad</td>
<td><input type="radio" name="r1">Bangalore</td>
<td><input type="radio" name="r1">Other</td>
</tr>
<tr>
<td colspan="2"><label>Willing to Re-Locate?</label></td>
<td><input type="radio" name="r1">Yes</td>
<td><input type="radio" name="r1">No</td>
</tr>
<tr>
<td colspan="4"><input type="checkbox" name=""><span>Iam here declaring that all the above mentioned information is true as per my knowledge.</span></td>
</tr>
<tr>
<td></td>
<td><input type="submit" name=""></td>
<td><input type="reset" name=""></td>
</tr>
</table>
</fieldset>
</form>
</div>
</body>
</html

