<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <!-- Header Section -->
  <header>
    <h1>John Doe</h1>
    <p>Web Developer & Designer</p>
  </header>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm John Doe, a passionate web developer with a flair for creating beautiful and functional websites. Welcome to my portfolio!</p>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio">
    <h2>My Projects</h2>
    <div class="projects">
      <div class="project">
        <h3>Project Alpha</h3>
        <p>Description of Project Alpha. A great project that showcases HTML, CSS, and JavaScript skills.</p>
      </div>
      <div class="project">
        <h3>Project Beta</h3>
        <p>Description of Project Beta. A creative project focused on responsive design and user experience.</p>
      </div>
      <div class="project">
        <h3>Project Gamma</h3>
        <p>Description of Project Gamma. An innovative solution for e-commerce using modern frameworks.</p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <form action="https://formsubmit.co/your-email@example.com" method="POST">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

</body>
</html>
