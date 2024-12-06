
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Graphic Design Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="container">
      <h1>Welcome to My Graphic Design Portfolio</h1>
      <nav>
        <ul>
          <li><a href="#about">About Me "I am a creative and passionate graphic designer with a strong eye for detail, specializing in branding, digital illustration, and UI/UX design. I strive to create designs that not only look visually appealing but also connect with the audience and tell a compelling story."</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I am a passionate graphic designer with a focus on modern, clean, and creative designs. I specialize in branding, digital art, and UI/UX design.</p>
  </section>

  <section id="projects">
    <h2>My Projects</h2>
    <div class="gallery">
      <div class="project">
        <img src="images/design1.jpg" alt="Design 1">
        <h3>Project 1</h3>
        <p>Description of the design project.</p>
      </div>
      <div class="project">
        <img src="images/design2.jpg" alt="Design 2">
        <h3>Project 2</h3>
        <p>Description of the design project.</p>
      </div>
      <div class="project">
        <img src="images/design3.jpg" alt="Design 3">
        <h3>Project 3</h3>
        <p>Description of the design project.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>If you'd like to work with me, feel free to reach out!</p>
    <form id="contact-form">
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2024 Your Name | Graphic Design Portfolio</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
