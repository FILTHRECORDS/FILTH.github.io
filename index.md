<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Filth</title>
  <style>
  * {
  box-sizing: border-box;
}

body {
  width: 100%;
  height: 1500px;
  background-image: url('https://live.staticflickr.com/65535/50946464071_10f374a41a_h.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  margin:0;
}

.topnav {
  background-color: black;
  overflow: hidden;
}


.topnav a {
  float: left;
  color: white;
  text-align: center;
  padding: 25px 25px;
  text-decoration: none;
  font-size: 25px;
}

.topnav a:hover {
  background-color: gray;
  color: white;
}

.dropdown {
  float: right;
  overflow: hidden;
}

.dropdown .dropbtn {
  color: white;
  background-color:black;
  text-align: center;
  padding: 25px 25px;
  text-decoration: none;
  font-size: 25px;
}

.topnav a:hover, .dropdown:hover .dropbtn {
  background-color:gray;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 25px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  float: none;
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content a:hover {
  background-color: gray;
}

.dropdown:hover .dropdown-content {
  display: block;
}

.topnav.responsive a {
  float: none;
  display: block;
  text-align: left;
}

</style>
<header>
<div class="topnav" id="myTopnav">
<a href="index.html">HOME</a>
<a href="merchandise.html">MERCH</a>
<div class="dropdown">
  <button class="dropbtn">ROSTER</button>
    <div class="dropdown-content">
      <a href="https://dogdied.bandcamp.com/">Dogdied</a>
      <a href="https://goodbyeheretic.bandcamp.com/releases">Goodbye Heretic</a>
      <a href="https://intjthreat.bandcamp.com/track/what-to-avoid-when-making-a-dating-profile">INTJ threat</a>
      <a href="https://kiroku.bandcamp.com/album/storm-heaven-ep">Kiroku</a>
      <a href="https://wormhero.bandcamp.com/">Worm Hero</a>
      <a href="https://yanguro.bandcamp.com/">Yangire</a>
      <a href="https://elat0nic.bandcamp.com/">€L@T0NiC</a>
    </div>
</div>
</div>
</header>
</body>
</html>
