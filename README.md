<html>
<head>
  <link rel="stylesheet" href="my first css.css">
  
</head>

<body> 
  <form>
    <h2>∆ SBI Bank Account Opening Form</h2>
    <p> (Note- Fill all the details properly)</p>
    <fieldset>  <h3><u>~Personal details</u></h3>
     1.First name-
    <br> <input type="text" name="First name" required>
      <br>2.Last name-
    <br><input type="text" name="last name" required>
    <br> 3.Father name-
    <br>   <input type="text" name="Father name" required>
    <br>4.Mobile number-
    <br> <input type="tel" name="Mobile number" required>
    <br>5.Email-
      <br>  <input type="text" name="Email" required>
    <br>6.Select gender:
    <br>Male     -
        <input type="radio"  name="gender" value="Male" required>
    <br>Female -
    <input type="radio" name="gender" value="Female" required>
    <br>Custom -
    <input type="radio" name="gender"  value="Custom" required>
      <br>7.DOB -
      <input type="date" name="dob" required>
    <br>8.Enter Addhaar Card Number-
    <input type="tel" name="Addhhar Card Number" required>
    <br>9.Enter PAN Card number-
    <input type="tel" name="PAN Card Number" required>
    <br>10.Age-
    <br> <input type="tel" name="Age" required> years</fieldset>
    <fieldset>  <h3><u>~Domicile details</u></h3>
    <br>1.Permanent Address-
    <input type="text" name="Permanent address" required>
    <br>2.Name of City/Village-
    <input type="text" name="Name of City/Village" required>
    <br>3.Name of State-
    <br>  <input type="text" name="Name of State" required>
    <br>4.Citizenship-
    <br>  <input type="text"  name="Citizenship" required></fieldset>
    <fieldset> <u> <h3>~Additional details</h3></u>
    <br>Select religion :<br><select required>
      <option vlaue="None">None</option>
      <option value="Hindu">Hindu</option>
      <option value="Muslim">Muslim</option>
      <option value="Christian">Christian</option>
      <option value="jain">Jain</option>
      <option value="Budhhist">Budhhist</option>
      <option vlaue="Other">Other</option>
    </select>
    <br>Select Category :<br><select required>
      <option value="None">None</option>
      <option value="Open">Open</option>
      <option value="OBC">OBC</option>
      <option value="SC">SC</option>
      <option value="ST">ST</option>
    </select>
    <br>Qualification Details :<br><select required>
      <option value="None">None</option>
      <option value="Non graduate">Non graduate</option>
      <option value="Graduate">Graduate</option>
      <option value="Post Graduate"> Post Graduate</option>
    </select></fieldset>
    
 
    <br> <br> <input type="submit" 
 onclick="alert('You have successfully appiled for opening your new bank account. You will get your your passbook and atm card within 10 days . Thank you  ! team SBI...')"
      value="Submit">
    
    
    
    
  </form>
  
</body>
</html>
