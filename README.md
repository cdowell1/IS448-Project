# IS448-Project
Online Voter Registration

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
	<title> Voter Registration Application </title>
	<meta http-equiv="Content-Type" content="charset=UTF-8"/>
	<link rel="stylesheet" type="text/css" href="app_format.css"/>
</head>
<body>

<p class="heading"> <span class="large"> Voter Registration Application </span>
					<br/>
                    <span class="italic"> (*) Denotes Requied Field </span> </p>

<div class="background">
<form method="post" action="registration_form.php">
	<p>
		<span class="bold"> 1. Your Name </span>
		<br/>

		<label> *First Name: <input type="text" name="fname" size="25"/> </label>
		<br/>
		<br/>

		<label> Middle Initial: <input type="text" name="minitial" size="25"/> </label>
		<br/>
		<br/>

		<label> *Last Name: <input type="text" name="lname" size="25"/> </label>
		<br/>
		<br/>

		<span class="bold"> 2. *Eligibility </span>
		    <br/>
			If you answer "No" to either of the following questions, you cannot register to vote.
		<br/>
		<br/>
		
		<label> Are you a citizen of the U.S.? <br/>
							  <input type="radio" name="citizen" value="yes"/> Yes 
							  <input type="radio" name="citizen" value="no"/> No </label>
		<br/>
		<br/>	

		<label> Will you be 18 years or older on or before election day? <br/>
							  <input type="radio" name="eighteen" value="yes" /> Yes 
							  <input type="radio" name="eighteen" value="no" /> No </label>
		<br/>
		<br/>

	    <span class="bold"> 3. About You </span>
	    <br/>
		<label> *Date of Birth <span class="italic">(MM/DD/YYY)</span>: <input type="text" name="DOB"/> </label>
		<br/>
		<br/>
		<label> Sex: <br/> 
			<input type="radio" name="m"/> Male 
			<input type="radio" name="f"/> Female </label>
		<br/>
		<br/>

		<label> Race: <input type="text" name="race"/> </label>
		<br/>
		<br/>

		<label> Phone Number <span class="italic">(123-456-7890)</span>: <input type="text" name="phone"/> </label>
		<label> Email: <input type="text" name="email"/> </label>
		<br/>
		<br/>

		<span class="bold"> 4. Your Address </span>
		<br/>
		<label> *Address: <input type="text" name="addr" size="25"/> </label>
		<br/>
		<br/>
		<label> *City: <input type="text" name="city" size="15"/> </label>
		<label> *State:
					 <select>
					 	<option>    </option>
					 	<option> AL </option>
					 	<option> AK </option>
					 	<option> AZ </option>
					 	<option> AR </option>
					 	<option> CA </option>
					 	<option> CO </option>
					 	<option> CT </option>
					 	<option> DE </option>
					 	<option> FL </option>
					 	<option> GA </option>
					 	<option> HI </option>
					 	<option> ID </option>
					 	<option> IL </option>
					 	<option> IN </option>
					 	<option> IA </option>
					 	<option> KS </option>
					 	<option> KY </option>
					 	<option> LA </option>
					 	<option> ME </option>
					 	<option> MD </option>
					 	<option> MA </option>
					 	<option> MI </option>
					 	<option> MN </option>
					 	<option> MS </option>
					 	<option> MO </option>
					 	<option> MT </option>
					 	<option> NE </option>
					 	<option> NV </option>
					 	<option> NH </option>
					 	<option> NJ </option>
					 	<option> NM </option>
					 	<option> NY </option>
					 	<option> NC </option>
					 	<option> ND </option>
					 	<option> OH </option>
					 	<option> OK </option>
					 	<option> OR </option>
					 	<option> PA </option>
					 	<option> RI </option>
					 	<option> SC </option>
					 	<option> SD </option>
					 	<option> TN </option>
					 	<option> TX </option>
					 	<option> UT </option>
					 	<option> VT </option>
					 	<option> VA </option>
					 	<option> WA </option>
					 	<option> WV </option>
					 	<option> WI </option>
					 	<option> WY </option>
					 </select> </label>

		<label> *Zip: <input type="text" name="zip" size="10"/> </label>
		<br/>
		<br/>

		<label> County: <input type="text" name="county"/> </label>
		<br/>
		<br/>

		<span class="bold"> 5. Party Affiliation </span>
		<br/>
		<label> Affiliation: <select> 
								<option>  </option>
								<option> Democrat </option>
								<option> Republican </option>
								<option> Libertarian </option> 
							</select> </label>
		
	</p>

</form>
</div>
	<div class="heading">
	<p>
	<input type="submit" value="Submit"/>
	<input type="reset" value="Clear"/>
	</p>
    </div>



</body>
</html>
