<!DOCTYPE html>
<html lang=en>

<head>
<title > Manar </title>
<link rel="stylesheet" href ="style.css">
</head>

<body>

<h1  title="11924470" onclick="name()"> 
Manar Eyad Harb
 </h1>
<p class="p1" title="no background " > 
Summary about work => dont have any work background.
<br>
<p class="p1" title="Education" id="p1" >
 I studied elementary & middle in UAE <br>
* elementary at Palestine school<br>
* middle at AL Khalil school .<br>
And now the university in Palestine <br>
* at An-Najah National University.<br>
</p><hr>
<p class ="p2" title = "student " >
No work Experience .<br>
</p></p><hr>
<h2>
Hobbies:
</h2>
<p class="p3"> 
1. drow <br>
2. playing music<br>
3. horse riding<br>
</p><hr>
<a href= " https://www.facebook.com/profile.php?id=100008553314628 ">
FACEBOOK linked 
</a><br>
<img src="never stop.jpg"  width ="500"   height = "600" >
<button type='button' class="B" onclick="myFunction()" >Print My CV</button>
<script>
    function myFunction() 
    {
        window.print();
    }
    function name()
    {
     alert("Welcome, please let me know if you have any questions");
    }

    document.getElementById("p1").onmouseover = function() {mouseOver()};
document.getElementById("p1").onmouseout = function() {mouseOut()};

function mouseOver() {
  document.getElementById("p1").style.color = "red";
}

function mouseOut() {
  document.getElementById("p1").style.color = "black";
}

</script>
</body>
</html>
