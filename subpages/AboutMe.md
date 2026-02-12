<html>
  <head>
  <title>Brandon F's about me section</title>
  <meta name="description" content="Brandon F's about me section with a breif introduction">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="../styles.css">
</head>
  
  
<body>
  
nav>
  <a href="../index.html">Home</a>
  <a href="AboutMe.html">About</a>
  <a href="experience.html">Experience</a>
  <a href="hobbies.html">Hobbies</a>
  <a href="projects.html">Projects</a>
</nav>
  
<div class="container">
  <h1>About me</h1>
  <div class="row">
    <div class="column">
      <img src="/aman.jpg" width="200" height="350">
    </div>
    <div class= "column">
      <p>Hello, I'm Brandon F. Im a 23 yr old coder and developer. I enjoy building applications, learning new technologies, and solving complex problems through code.</p>
      <p>On the other pages you can find my hobbies, experiences, and projects. You can click on the top in order to return to the menu</p>
    </div>
  </div>

  <h2>Contact Me</h2>
  
  <form onsubmit= "Function()">
    <label for="email">Type your email here:</label><br>
    <input type="email" id="email" name="email" required><br>
    <input type="submit" value = "Submit">
  </form>
</div>

<footer>
    2026 Brandon F
</footer>

<script>
function Function() {
  alert("The form was submitted successfully");
}
</script>
</body>
</html>
