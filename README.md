# Admission of Covid-19 patients Form Using HTML:-

###HTML Code:-

<!-- saved from url=(0074)file:///C:/Users/smitr/OneDrive/Documents/WEB%20DESIGNING/EXPERT_FORM.html -->
<html><head><meta http-equiv="Content-Type" content="text/html; charset=windows-1252"></head><body bgcolor="orange"><font face="algerian" size="14" color="black">  
<title>Admission Form</title></font>  
<font color="red" width="800"><center><u><h1>R.G.KAR MEDICAL COLLEGE AND HOSPITAL</h1></u></center></font>  
<p align="center"><font face="Times" new="" roman="" size="14" color="orange">  
</font></p><center><font face="Times" new="" roman="" size="14" color="orange"><b><u><marquee behavior="alternate" scrollamount="5" bgcolor="blue">Admission Of COVID-19 Patients</marquee></u></b></font></center><br><br>
    

<form>
<b><u>PERSONAL DETAILS:</u></b>
<br><br>

<label for="fname">First Name: </label>  
<input type="text" id="fname" placeholder="first name" name="fname"><br><br>

<label for="mname">Middle Name: </label>  
<input type="text" id="mname" placeholder="middle name" name="mname"><br><br>  
    
<label for="lname">Last Name: </label>  
<input type="text" id="lname" placeholder="last name" name="lname"><br><br> 

<label for="dob">Date of Birth: </label>  
<input type="date" id="d.o.b" placeholder="date of birth" name="d.o.b."><br><br>
 
<label for="email">Email ID: </label>  
<input type="text" id="email" placeholder="email" name="email"><br><br>

<label for="ph_no.">Phone no. </label>  
<input type="numeric" id="ph_no." placeholder="phone no" name="ph_no.">

<label for="em_no.">Emergency no. </label>  
<input type="numeric" id="em_no." placeholder="emergency no" name="em_no."><br><br>

Gender<br><input type="radio" name="gender" value="male"> Male
                        <input type="radio" name="gender" value="female"> Female<br><br>

<b><u>ADDRESS:</u></b><br>
Present Address: <textarea rows="3" cols="50"> </textarea><br><br><br>
Permanent Address: <textarea rows="3" cols="50"> </textarea><br><br><br>

<label for="pcode">Pin Code: </label>  
<input type="text" id="pcode" name="pcode">
<br><br>


<b>COVID-19 Test Done In The Past 14 Days?</b><br>
<input type="radio" name="yesno" value="Yes"> Yes
<input type="radio" name="yesno" value="No"> No <br><br>

<b>Have the patient travelled abroad?</b><br>
<input type="radio" name="yesno" value="Yes"> Yes
<input type="radio" name="yesno" value="No"> No <br><br>


<b>Symptoms of Patient: </b><br>
<input type="checkbox" name="symptoms" value="fever">Fever<br>
<input type="checkbox" name="symptoms" value="lossofsmell">Loss Of Smell<br>
<input type="checkbox" name="symptoms" value="lossoftaste">Loss of Taste<br>
<input type="checkbox" name="symptoms" value="bodypain">Body Pain<br>
<input type="checkbox" name="symptoms" value="headache">Headache<br>
<input type="checkbox" name="symptoms" value="breathlessness">Breathlessness<br>
<input type="checkbox" name="symptoms" value="others">Others<br><br>


<b>Select State</b>
<select class="States">
<option value="select state">Select State</option>
<option value="West Bengal">West Bengal</option>
<option value="Maharashtra">Maharashtra</option>
<option value="Uttar Pradesh">Uttar Pradesh </option>
<option value="Madhya Pradesh">Madhya Pradesh</option>
<option value="Delhi">Delhi</option>
</select><br><br>


<b>Nationality</b>
<select class="nationality">
<option value="nationality">Select Nationality</option>
<option value="nationality">Indian</option>
</select><br><br>

<label for="Aadhar_no."><b>Aadhar Card no:</b> </label>  
<input type="numeric" id="Aadhar_no." placeholder="aadhar no" name="aadhar_no."><br><br>




<b><u>PHYSICIAN INFORMATION:</u></b><br><br>

<label for="name">Name Of Physician: </label>  
<input type="text" id="name" name="name">

<label for="phone">Phone:</label>  
<input type="text" id="phone" name="phone"><br><br>

 Address: <textarea rows="5" cols="50"> </textarea><br><br>


<b>Passport Size photo of patient:</b>
<input type="file" name="filetoupload" id="filetoupload"><br>
<br>

<b>Covid Positive Test Report</b>
<input type="file" name="filetoupload" id="filetoupload">
<br><br>

<input type="submit" value="Submit">
<input type="reset" value="Reset">





</form></body></html>
