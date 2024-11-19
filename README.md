<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Marvel Heroes Hub</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header -->
  <header class="header">
    <h1>Marvel Heroes Hub</h1>
    <nav>
      <ul class="menu">
        <li><a href="#heroes-index">The Hero's Index</a></li>
        <li><a href="#marvel-media">Marvel Media</a></li>
        <li><a href="#events-timelines">Events & Timelines</a></li>
        <li><a href="#fan-zone">Fan Zone</a></li>
        <li><a href="#news-features">News & Features</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Banner -->
  <section class="banner">
    <h2>Welcome to the Ultimate Marvel Database!</h2>
    <p>Explore your favorite heroes, iconic villains, and epic storylines!</p>
  </section>

  <!-- Sections -->
  <section id="heroes-index" class="content-section">
    <h2>The Hero's Index</h2>
    <p>Discover detailed profiles of Marvel’s legendary heroes, villains, and teams.</p>
    <a href="#">Explore More</a>
  </section>

  <section id="marvel-media" class="content-section">
    <h2>Marvel Media</h2>
    <p>Stay updated on MCU movies, TV shows, comics, and video games!</p>
    <a href="#">Read Articles</a>
  </section>

  <section id="events-timelines" class="content-section">
    <h2>Events & Timelines</h2>
    <p>Dive into Marvel’s iconic storylines, crossover events, and multiverse timelines.</p>
    <a href="#">View Timelines</a>
  </section>

  <section id="fan-zone" class="content-section">
    <h2>Fan Zone</h2>
    <p>Join the community with quizzes, polls, and fan art showcases!</p>
    <a href="#">Get Involved</a>
  </section>

  <section id="news-features" class="content-section">
    <h2>News & Features</h2>
    <p>Catch up on the latest Marvel updates, theories, and editorials!</p>
    <a href="#">Read News</a>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <p>&copy; 2024 Marvel Heroes Hub. All Rights Reserved.</p>
  </footer>
</body>
</html>
/* General Styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f9;
  color: #333;
  line-height: 1.6;
}

h1, h2 {
  color: #d32f2f;
}

a {
  color: #d32f2f;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

/* Header Styles */
.header {
  background-color: #333;
  color: #fff;
  padding: 1rem 0;
  text-align: center;
}

.header h1 {
  margin: 0;
}

.menu {
  list-style: none;
  padding: 0;
  display: flex;
  justify-content: center;
  gap: 2rem;
  margin-top: 1rem;
}

.menu li {
  display: inline;
}

.menu a {
  color: #fff;
  font-weight: bold;
}

/* Banner Styles */
.banner {
  text-align: center;
  padding: 2rem;
  background: linear-gradient(135deg, #d32f2f, #f57c00);
  color: #fff;
}

.banner h2 {
  margin: 0 0 1rem;
}

.banner p {
  font-size: 1.2rem;
}

/* Section Styles */
.content-section {
  padding: 2rem;
  text-align: center;
  margin: 2rem auto;
  max-width: 800px;
  background: #fff;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
}

.content-section h2 {
  margin-bottom: 1rem;
}

.content-section a {
  display: inline-block;
  margin-top: 1rem;
  padding: 0.5rem 1rem;
  background-color: #d32f2f;
  color: #fff;
  border-radius: 5px;
  font-weight: bold;
}

.content-section a:hover {
  background-color: #b71c1c;
}

/* Footer Styles */
.footer {
  text-align: center;
  background-color: #333;
  color: #fff;
  padding: 1rem;
  position: relative;
}
