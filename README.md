# html-forms
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EXAM FORM</title>
    <form action="">
        <h1> EXAM FORM LORD'S INSTIUTE OF ENGINEERING AND TECHNOLOGY (LIET)</h1>
        <h2>
            Student Information
        </h2>
        <p> *Name:  <input type="student name" id="  student name" required></p>
        <p> *Roll number : <input type="numner" id="number" required></p>
        <legend> *Gender </legend>
        <p> Male <input type="radio" name="Gender" id="Male" required></p>
        <p> Female  <input type="radio" name="Gender" id="Female"></p>
        <p>
            Date of Birth : * <input type="date" id="dob" required>
        </p>
        <p> *Branch : <select name=" selectBranch" id="Select Branch" required>
        <option value=""> Please Select Your Branch</option>
        <option value="Computer Science and Engineering(CSE)"> Computer Science Engineering (CSE)</option>
        <option value="Electronics and Communication Engineering (ECE)"> Electronics &  Communications Engineering(ECE)</option>
        <option value="Civil  Engineering(CE)"> Civil Engineering(CE)</option>
        <option value="Mechanical Engineering(ME)"> Mechanical Engineering (ME) </option>
        <option value="Electrical and Electronics Engineering (EEE)">Electrical and Electronics Engineering(EEE)</option>
        <option value= " Computer Science Statistics and Mathematics (CSM)">Computer Science Statistics and Mathematics (CSM)</option>
        <option value="Computer Science and  Design Engineering (CSD)"> Computer Science and  Design Engineering (CSD)</option>
        <option value="Computer Science & Engineering (Artifical Intelligence & Machine Learning)(CSEAIML)">Computer Science & Engineering (Artifical Intelligence & Machine Learning)(CSEAIML)</option>
        </select>
    </p>
    <P>  *College Email (or)  Personal Email: <input type="email" name="email" id="email"></P>
    <p> *Mobile Number : <input type="tel" name="mobile" id="Mobile No." required ></p>
    <fieldset><p> Address :<fieldset<textareaname="Address" id="Address" cols= "100" rows="60"></p></fieldset>
    <p>*<select name="Payment method" id="Payment method" required>
    <option value="select Payment Method "> Select paymet method</option>
    <option value="Cash"> Cash</option>
    <option value="Online  payment"> Online payment</option>
    <option value="Cheque/Dd"> Cheque / Dd</option>
    <option value="Card">Card</option>
</select></p> 
<p> Subjects : </p>
<textarea name="Subjects" id=" Subjects" cols="30" rows="10"></textarea>
<p> Photo </p>
<textarea name="Photo" id="Photo" cols="10" rows="9"></textarea>
<input type="Submit" name="Submit" id="Submit">
    </form>
</head>
<body>
    
</body>
</html>
