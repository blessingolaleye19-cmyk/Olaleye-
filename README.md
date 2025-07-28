# Olaleye
My personal portfolio website as a teacher and Salesforce admin in training
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Blessing Olaleye Olamiposi</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #4CAF50;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      text-align: center;
      margin: 1rem 0;
    }
    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: #4CAF50;
      font-weight: 600;
    }
    .container {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    .bio, .portfolio, .resume, .contact, .blog {
      margin-bottom: 3rem;
    }
    h2 {
      color: #4CAF50;
    }
    footer {
      background: #4CAF50;
      color: white;
      text-align: center;
      padding: 1rem;
    }
    input, textarea {
      width: 100%;
      padding: 0.5rem;
      margin-bottom: 1rem;
    }
    button {
      background: #4CAF50;
      color: white;
      padding: 0.7rem 1.2rem;
      border: none;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>Blessing Olaleye Olamiposi</h1>
    <p>Primary School Teacher | Salesforce Admin in Training</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#resume">Resume</a>
    <a href="#blog">Blog</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container">
    <section id="about" class="bio">
      <h2>About Me</h2>
      <p>Hi, I’m Blessing Olaleye Olamiposi — an educator and aspiring Salesforce Administrator from Ondo State, Nigeria. With over five years of experience teaching in the basic education sector, I’ve dedicated my career to making learning accessible and impactful for every child.</p>
      <p>Transitioning into technology through Salesforce has allowed me to explore new ways of supporting education systems and organizations in Nigeria. I am driven by the belief that education is the foundation of progress, and I’m excited to combine teaching with tech to improve access and efficiency.</p>
      <p>I love turning lessons into songs — sometimes with rhymes my students never forget! When I'm not in the classroom or studying Salesforce, I enjoy sharing what I learn and helping others grow.</p>
    </section>

    <section id="portfolio" class="portfolio">
      <h2>Portfolio</h2>
      <p>Coming soon: My Salesforce projects and teaching resources.</p>
    </section>

    <section id="resume" class="resume">
      <h2>Resume</h2>
      <p><a href="mailto:blessingolaleye19@gmail.com">Request my full resume via email</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/olaleye-olamiposi-a74a41299" target="_blank">Visit my profile</a></p>
    </section>

    <section id="blog" class="blog">
      <h2>Blog</h2>
      <p>Updates coming soon on teaching tips and learning Salesforce!</p>
    </section>

    <section id="contact" class="contact">
      <h2>Contact Me</h2>
      <form action="mailto:blessingolaleye19@gmail.com" method="post" enctype="text/plain">
        <label>Name:</label>
        <input type="text" name="name" required>
        <label>Email:</label>
        <input type="email" name="email" required>
        <label>Message:</label>
        <textarea name="message" rows="5" required></textarea>
        <button type="submit">Send Message</button>
      </form>
      <p>Phone: 08035296815</p>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 Blessing Olaleye Olamiposi. All rights reserved.</p>
  </footer>
</body>
</html>
