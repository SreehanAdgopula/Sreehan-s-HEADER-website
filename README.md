<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}

/* Set height of body and the document to 100% */
body, html {
  height: 100%;
  margin: 0;
  font-family: Arial;
}

/* Style tab links */
.tablink {
  background-color: #555;
  color: white;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  font-size: 17px;
  width: 25%;
}

.tablink:hover {
  background-color: #777;
}

/* Style the tab content (and add height:100% for full page content) */
.tabcontent {
  color: white;
  display: none;
  padding: 100px 20px;
  height: 100%;
}

#Home {background-color: rgb(211, 0, 0);}
#Biolink {background-color: rgb(0, 255, 42);}
#Contact {background-color: rgb(5, 5, 131);}
</style>
</head>
<body>

    <h2> <center> Sreehan's HEADER website </center></h2>
    <center> <script>
        function myFunction() {
          document.getElementById("demo").innerHTML = "Hello Friend !!";
        }
        </script>
      <p id="demo">Click this button so that I can say something!</p>
      <button type="button" onclick="myFunction()">Try it</button> </center>
      

<button class="tablink" onclick="openPage('Home', this, 'red')">Home</button>
<button class="tablink" onclick="openPage('Biolink', this, 'green')" id="defaultOpen">Biolink</button>


<div id="Home" class="tabcontent">
  <h3>Home</h3>
  <p>Hi, I'm SREEHAN!! Thanks for Visiting my HEADER website. I hope all of you are healthy, me you ask? Well I am all fine as usually! If you want to ask me some other questions, go to down and chat in a form or through e-mail.</p>
  <center> chat with me here! </center>
            <a class="btn" href="mailto:asreehan@outlook.com">CONTACT ME</a><br>
            Else directly chat with me in forms
            <center> <iframe src="demo_iframe.htm" name="iframe_a" height="500px" width="100%" title="Iframe Example"></iframe>
              
            <p><a href="https://sreehanadgopula.github.io/Form/" target="iframe_a">Form</a></p> </center>
</div>

<div id="Biolink" class="tabcontent">
  <h3>Biolink</h3>
  <p>See all of my websites here👇
      <br>
      <a class="btn" href="https://bio.link/sreehanadigopula" target="_blank">My Bio link</a><br>
      <a class="btn" href="https://sreehanadgopula.github.io/Sreehan-s-website/" target="_blank">Sreehan's website</a><br>
      <a class="btn" href="https://sreehanadgopula.github.io/How-to-hack-any-game/" target="_blank">How to hack any game</a><br>
      <a class="btn" href="https://sreehanadgopula.github.io/SPACE/" target="_blank">space</a><br>
    
<script>
function openPage(pageName,elmnt,color) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].style.backgroundColor = "";
  }
  document.getElementById(pageName).style.display = "block";
  elmnt.style.backgroundColor = color;
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>
