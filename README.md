# Javascript-Form
Validating a Form Using Javascript

<!DOCTYPE html>
<html>
<body>

<form id = "fname" method="post" onsubmit="return validateForm ()" >
<input name="myName" type="text" ></input>
<input type="submit" value="submit"></input>
</form>
<script>
validateForm();

function validateForm(){
var x = document.forms["fname"]["myName"].value;
if(x==" "){
alert("required");
return false;
}
<script>


</body>
</html>
