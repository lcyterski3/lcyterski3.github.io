<!DOCTYPE html>
<html>
<title>Cyterski Personal Site</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<body class="w3-content" style="max-width:1300px">

<!-- First Grid: Logo & About -->
<div class="w3-row">
  <div class="w3-half w3-black w3-container w3-center" style="height:700px">
    <div class="w3-padding-64">
      <h1>Logan Cyterski</h1>
    </div>
    <div class="w3-padding-64">
      <a href="#" class="w3-button w3-black w3-block w3-hover-blue-grey w3-padding-16">Home</a>
      <a href="#work" class="w3-button w3-black w3-block w3-hover-teal w3-padding-16">My Hobbies</a>
      <a href="#contact" class="w3-button w3-black w3-block w3-hover-brown w3-padding-16">Contact Me</a>
    </div>
  </div>
  <div class="w3-half w3-blue-grey w3-container" style="height:700px">
    <div class="w3-padding-64 w3-center">
      <h1>About Me</h1>
      <img src="me2.png" class="w3-margin w3-circle" alt="Me" style="width: 70%">
      <div class="w3-left-align w3-padding-large">
        <p>I'm Logan, a third-year Computational Media major at Georgia Tech.</p>
      </div>
    </div>
  </div>
</div>

<!-- Second Grid: Work & Resume -->
<div class="w3-row">
  <div class="w3-half w3-white w3-center" style="min-height:900px" id="work">
    <div class="w3-padding-64">
      <h2>My Favorite Shows</h2>
    </div>
    <div class="w3-row">
      <div class="w3-half">
        <img src="GoT.jpg" style="width:100%">
      </div>
      <div class="w3-half">
        <img src="Eva.jpg" style="width:100%">
      </div>
    </div>
    <div class="w3-row w3-hide-small">
      <div class="w3-half">
        <img src="fmab.png" style="width:100%">
      </div>
      <div class="w3-half">
        <img src="odd.jpg" style="width:100%">
      </div>
    </div><br>
  </div>
  <div class="w3-half w3-indigo w3-container" style="min-height:900px">
    <div class="w3-padding-64 w3-center">
      <h2>My Favorite Games</h2>
      <div class="w3-container w3-responsive">
        <div class="w3-row">
          <div class="w3-half">
            <img src="baba.jpg" style="width:100%">
          </div>
          <div class="w3-half">
            <img src="civ.jpg" style="width:100%">
          </div>
        </div>
        <div class="w3-row w3-hide-small">
          <div class="w3-half">
            <img src="sky.png" style="width:100%">
          </div>
          <div class="w3-half">
            <img src="ff.jpg" style="width:100%">
          </div>
        </div><br>
      </div>
    </div>
  </div>
</div>
        
<!-- Third Grid: Swing By & Contact -->
<div class="w3-row" id="contact">
  <div class="w3-half w3-dark-grey w3-container w3-center" style="height:700px">
    <div class="w3-padding-64">
      <h1>Socials</h1>
    </div>
    <div class="w3-padding-64">
      <p>Snap: logandecy</p>
      <p>Insta: logandorancyterski</p>
    </div>
  </div>
  <div class="w3-half w3-teal w3-container" style="height:700px">
    <div class="w3-padding-64 w3-padding-large">
      <h1>Contact Me</h1>
      <form class="w3-container w3-card w3-padding-32 w3-white" action="/action_page.php" target="_blank">
        <div class="w3-section">
          <label>Name</label>
          <input class="w3-input" style="width:100%;" type="text" required name="Name">
        </div>
        <div class="w3-section">
          <label>Email</label>
          <input class="w3-input" style="width:100%;" type="text" required name="Email">
        </div>
        <div class="w3-section">
          <label>Message</label>
          <input class="w3-input" style="width:100%;" type="text" required name="Message">
        </div>
        <button type="submit" class="w3-button w3-teal w3-right">Send</button>
      </form>
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="w3-container w3-black w3-padding-16">
  <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank">w3.css</a></p>
</footer>

</body>
</html>

