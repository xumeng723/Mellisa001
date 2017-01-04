# Mellisa001
<!DOCTYPE html>
<html>
<head>
<style> 
#myDIV {
    width: 500px;
    height: 500px;
    background-color: lightblue;
}
</style>
</head>
<body>

<p>Click the "Try it" button to set the display property of the DIV element to "none":</p>

<button onclick="myFunction('none')">隐藏</button>
<button onclick="myFunction('block')">出现</button>

<div id="myDIV">
This is my DIV element.
</div>

<p><b>Note:</b> The element will not take up any space when the display property set to "none".</p>

<script>
function myFunction(zzz) {
    document.getElementById("myDIV").style.display =zzz;
}
</script>

</body>
</html>
