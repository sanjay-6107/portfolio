<!DOCTYPE html>
<html>

<head>
  <title>Second Page</title>
</head>

<body>

<h1>Information Page</h1>

<h2 id="result"></h2>

<script>

let params = new URLSearchParams(window.location.search);

let firstname = params.get("firstname");
let lastname = params.get("lastname");
let fname = params.get("fname");
let rnumber = params.get("rnumber");
let email = params.get("email");
let number = params.get("number");

document.getElementById("result").innerHTML =
"First Name: " + firstname + "<br><br>" +
"Last Name: " + lastname + "<br><br>" +
"Father Name: " + fname + "<br><br>" +
"Roll Number: " + rnumber + "<br><br>" +
"Email: " + email + "<br><br>" +
"Phone Number: " + number;

</script>

</body>
</html>
