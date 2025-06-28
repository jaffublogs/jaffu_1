<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Portfolio Profile</title>
  <!-- Bootstrap CSS -->
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
    rel="stylesheet"
  />
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    .hero {
      background-color: #f8f9fa;
      padding: 60px 0;
      text-align: center;
    }

    .hero img {
      width: 150px;
      border-radius: 50%;
      margin-bottom: 20px;
    }

    .section {
      padding: 60px 0;
    }

    footer {
      background-color: #343a40;
      color: white;
      text-align: center;
      padding: 20px 0;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">My Portfolio</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero/Profile -->
  <section class="hero">
    <div class="container">
      <img src="https://via.placeholder.com/150" alt="Profile Picture" />
      <h1>Shaik Jaffar Alli</h1>
      <p class="lead">Web Developer | Designer</p>
    </div>
  </section>

  <!-- About Section -->
  <section class="section" id="about">
    <div class="container">
      <h2>About Me</h2>
      <p>
        I'm a passionate web developer with experience in HTML, CSS, JavaScript, and modern frameworks like React and Vue. I love creating responsive, user-friendly websites and applications.
      </p>
    </div>
  </section>

  <!-- Projects Section -->
  <section class="section bg-light" id="projects">
    <div class="container">
      <h2>Projects</h2>
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <img src="https://via.placeholder.com/300x200" class="card-img-top" alt="Project 1">
            <div class="card-body">
              <h5 class="card-title">Project One</h5>
              <p class="card-text">A brief description of your project goes here.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="https://via.placeholder.com/300x200" class="card-img-top" alt="Project 2">
            <div class="card-body">
              <h5 class="card-title">Project Two</h5>
              <p class="card-text">A brief description of your second project.</p>
            </div>
          </div>
        </div>
        <!-- Add more project cards as needed -->
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="section" id="contact">
    <div class="container">
      <h2>Contact</h2>
      <p>Feel free to reach out to me via email or through my social media platforms.</p>
      <ul>
        <li>Email: jaffarallis7661@gmail.com</li>
        <li>LinkedIn: <a href="https://www.linkedin.com/in/s-jaffar-alli-b6813624a?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app">linkedin.com/in/johndoe</a></li>
        <li>GitHub: <a href="">github.com/johndoe</a></li>
      </ul>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>© 2025 John Doe. All rights reserved.</p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
