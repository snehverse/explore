<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sneha's Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header -->
  <header>
    <h1>Sneha</h1>
    <p>Writer | Advertising & PR Enthusiast</p>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#blog">Blog</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Home Section -->
  <section id="home">
    <h2>Welcome!</h2>
    <p>Hi, I'm Sneha. A passionate storyteller, aspiring writer, and a future leader in Advertising and PR.</p>
    <button onclick="location.href='#portfolio'">View My Work</button>
  </section>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>
      I'm Sneha, a bachelor's student in Advertising & PR. I love weaving words to craft compelling narratives, and I aspire to join creative teams that make an impact.
    </p>
    <p>Skills: Writing, PR Campaigns, Content Creation, Digital Marketing.</p>
    <p>Fun Fact: When I'm not writing, I’m exploring new cuisines and dreaming about working at Zomato’s marketing team.</p>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio">
    <h2>Portfolio</h2>
    <div class="project">
      <h3>Project 1: Writing Sample</h3>
      <p>A short story about finding joy in small things. <a href="#">Read More</a></p>
    </div>
    <div class="project">
      <h3>Project 2: PR Campaign</h3>
      <p>Details about a mock campaign for a brand. <a href="#">View Project</a></p>
    </div>
  </section>

  <!-- Blog Section -->
  <section id="blog">
    <h2>Blog</h2>
    <article>
      <h3>My Journey in Advertising</h3>
      <p>Reflections on my university projects and future goals. <a href="#">Read More</a></p>
    </article>
    <article>
      <h3>Top 5 Campaigns That Inspire Me</h3>
      <p>A breakdown of campaigns that shaped my vision in PR. <a href="#">Read More</a></p>
    </article>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      <label for="message">Message:</label>
      <textarea id="message" name="message" rows="4" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Sneha. All rights reserved.</p>
    <div class="socials">
      <a href="#">LinkedIn</a> | <a href="#">Instagram</a> | <a href="#">Twitter</a>
    </div>
  </footer>
</body>
</html>
