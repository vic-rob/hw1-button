<!DOCTYPE html>
<html>
<head>
<style>
.button {
    background-color: #4CAF50;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}
h2 {
	font-family: arial;
}
p {
	font-family: verdana;    
}
</style>
</head>
<body>
<h2>Magic Button</h2>

<button class="button"onclick="myFunction()">Click me to change the text color!</button>

<p id="demo">Califragilisticoespiralidoso.</p>

<script>
function myFunction() {
    document.getElementById("demo").style.color = "blue";
}
</script>


</body>
</html>
