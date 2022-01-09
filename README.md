<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Arial;}

/* Style the tab */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
}

/* Style the buttons inside the tab */
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-size: 17px;
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #ddd;
}

/* Create an active/current tablink class */
.tab button.active {
  background-color: #ccc;
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}
</style>
</head>
<body>

<h1 align="center"> Sreehan's HEADER website </h1>
<center> <script>
  function myFunction() {
    document.getElementById("demo").innerHTML = "The word 'HEADER' means headquarter and + website which is equal to headquarter website. This means that this website is my headquarter website. got it?";
  }
  </script>
<p id="demo">Click the button if you don't understand what is the meaning of 'HEADER'.</p>
<button type="button" onclick="myFunction()">Clear your doubt!</button> </center>
<br>
<br>

<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'Home')">Home</button>
  <button class="tablinks" onclick="openCity(event, 'Contact')">Contact</button>
  <button class="tablinks" onclick="openCity(event, 'Websites')">Webistes</button>
</div>

<div id="Home" class="tabcontent">
  <h3>Home</h3>
  <p>Hi, I'm SREEHAN!! Thanks for Visiting my HEADER website.
     I hope all of you are healthy, me you ask? Well I am all fine as usually! If you want to ask me some other questions, go to Contact tab and chat in a form or through e-mail. </p>
</div>

<div id="Contact" class="tabcontent">
  <h3>Contact</h3>
  <p>Want to chat with me through e-mail,ok then👍</p> 
  <center> <a class="btn" href="mailto:asreehan@outlook.com">CONTACT ME</a> </center>
  Else directly chat with me in forms
  <h2> <center> If you get anything on the iframe like "404 File not found" this, then click "form" below
<iframe src="demo_iframe.htm" name="iframe_a" height="500px" width="100%" title="Iframe Example"></iframe>

<p><a href="https://sreehanadgopula.github.io/Form/" target="iframe_a">Form</a></p>
</div>

<div id="Websites" class="tabcontent">
  <h3>Websites</h3>
  <p>I made 7 websites! So want to see them, ok, down there are<br>
  <a class="btn" href="https://sreehanadgopula.github.io/Sreehan-s-website/">Sreehan's website</a></p><a class="btn" href="https://sreehanadgopula.github.io/clock/">clock </a><br> <a class="btn" href="https://sreehanadgopula.github.io/How-to-hack-any-game/">How to hack any game</a><br>
  <a class="btn" href="https://sreehanadgopula.github.io/Coding/" >Coding </a><br>
  <a class="btn" href="https://sreehanadgopula.github.io/Form/">Form </a><br>
  <a class="btn" href="https://sreehanadgopula.github.io/SPACE/">Space </a><br>
  <a class="btn" href="https://sreehanadgopula.github.io/Game/">Game </a><br>
  <h2 align="center"> Thanks visiting my website, Bye and have a great day! </h2> 
</div>
<h3> <center> Click the tabs on top to see it's descripcion </center> </h3>

<script>
function openCity(evt, cityName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}
</script>
   

