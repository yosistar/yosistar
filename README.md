<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Yosi Star | Pranks & Entertainment</title>

<!-- Google Font -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Poppins', sans-serif;
  background: #0d0d0d;
  color: white;
}

/* NAVBAR */
header {
  display: flex;
  justify-content: space-between;
  padding: 15px 40px;
  background: rgba(0,0,0,0.8);
  position: sticky;
  top: 0;
  z-index: 1000;
}

.logo {
  font-weight: 600;
  font-size: 22px;
  color: #ff0055;
}

nav a {
  margin-left: 20px;
  text-decoration: none;
  color: white;
  transition: 0.3s;
}

nav a:hover {
  color: #ff0055;
}

/* HERO */
.hero {
  height: 90vh;
  background: linear-gradient(135deg, #ff0055, #ff5500);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.hero h1 {
  font-size: 50px;
}

.hero p {
  margin-top: 10px;
  font-size: 18px;
}

.btn {
  margin-top: 20px;
  padding: 12px 25px;
  border: none;
  background: black;
  color: white;
  cursor: pointer;
  border-radius: 25px;
  transition: 0.3s;
}

.btn:hover {
  background: white;
  color: black;
}

/* SECTION */
section {
  padding: 60px 40px;
  text-align: center;
}

/* VIDEO GRID */
.video-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
  margin-top: 30px;
}

.video-card {
  background: #1a1a1a;
  border-radius: 15px;
  overflow: hidden;
  transition: 0.3s;
}

.video-card:hover {
  transform: scale(1.05);
}

iframe {
  width: 100%;
  height: 200px;
}

/* SUPPORT */
.support {
  background: linear-gradient(135deg, #111, #222);
}

/* FOOTER */
footer {
  background: black;
  padding: 20px;
  text-align: center;
  font-size: 14px;
}
</style>
</head>

<body>

<!-- NAVBAR -->
<header>
  <div class="logo">Yosi Star 😂</div>
  <nav>
    <a href="#home">Home</a>
    <a href="#videos">Videos</a>
    <a href="#about">About</a>
    <a href="#support">Support</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<!-- HERO -->
<section class="hero" id="home">
  <h1>Crazy Pranks & Real Reactions 😂🔥</h1>
  <p>Welcome to the funniest place on the internet</p>
  <button class="btn" onclick="scrollToVideos()">Watch Now</button>
</section>

<!-- VIDEOS -->
<section id="videos">
  <h2>🔥 Latest Videos</h2>

  <div class="video-grid">
    <div class="video-card">
      <iframe src="https://www.youtube.com/embed/VIDEO_ID"></iframe>
    </div>

    <div class="video-card">
      <iframe src="https://www.youtube.com/embed/VIDEO_ID"></iframe>
    </div>

    <div class="video-card">
      <iframe src="https://www.youtube.com/embed/VIDEO_ID"></iframe>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section id="about">
  <h2>About Me</h2>
  <p>
    I'm Yosi — I create fun, crazy, and entertaining prank videos.
    My mission is simple: make people laugh and enjoy life 😄
  </p>
</section>

<!-- SUPPORT -->
<section class="support" id="support">
  <h2>Support Me ❤️</h2>
  <p>Help me create better content and more crazy videos!</p>
  <button class="btn">Buy Me a Coffee ☕</button>
</section>

<!-- CONTACT -->
<section id="contact">
  <h2>Contact</h2>
  <p>Email: your@email.com</p>
  <p>YouTube: @Yosistar15</p>
</section>

<footer>
  © 2026 Yosi Star | Built for entertainment 🔥
</footer>

<script>
function scrollToVideos() {
  document.getElementById("videos").scrollIntoView({ behavior: "smooth" });
}
</script>

</body>
</html>
