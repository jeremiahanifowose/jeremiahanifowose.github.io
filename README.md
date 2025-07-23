# jeremiahanifowose.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Anifowose Jeremiah - Backend Developer</title>
  <!-- Google Fonts for a professional look -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet" />
  <!-- Font Awesome for icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #e3f2fd, #bbdefb);
      color: #333;
      line-height: 1.6;
    }

    nav {
      background: #1a2a44;
      padding: 1rem;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 2rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: 400;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #64b5f6;
    }

    header {
      background: #1a2a44;
      color: white;
      text-align: center;
      padding: 3rem 1rem;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    header img.profile-pic {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #64b5f6;
      margin-bottom: 1rem;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.2rem;
      color: #b0bec5;
    }

    section {
      max-width: 1000px;
      margin: 2rem auto;
      background: white;
      padding: 2rem;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    }

    h2 {
      color: #1a2a44;
      margin-bottom: 1rem;
      font-size: 1.8rem;
      border-bottom: 2px solid #64b5f6;
      padding-bottom: 0.5rem;
    }

    .skills ul {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 1rem;
      list-style: none;
    }

    .skills li {
      background: #e3f2fd;
      padding: 0.8rem;
      border-radius: 5px;
      text-align: center;
      font-weight: 500;
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }

    .projects .project-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 1.5rem;
    }

    .project-card {
      background: #f5f5f5;
      padding: 1rem;
      border-radius: 8px;
      text-align: center;
      transition: transform 0.3s;
    }

    .project-card:hover {
      transform: translateY(-5px);
    }

    .project-card img {
      max-width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 5px;
      margin-bottom: 1rem;
    }

    .contact div {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }

    .contact a {
      color: #64b5f6;
      text-decoration: none;
      font-weight: 500;
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }

    .contact a:hover {
      color: #1a2a44;
    }

    footer {
      text-align: center;
      padding: 2rem;
      background: #1a2a44;
      color: #b0bec5;
      margin-top: 2rem;
    }

    @media (max-width: 768px) {
      header img.profile-pic {
        width: 120px;
        height: 120px;
      }

      header h1 {
        font-size: 2rem;
      }

      section {
        margin: 1rem;
        padding: 1.5rem;
      }

      nav ul {
        flex-direction: column;
        gap: 1rem;
      }
    }
  </style>
</head>
<body>
  <nav>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <header>
    <!-- Placeholder profile picture -->
    <img src="https://placeimg.com/150/150/people" alt="Anifowose Jeremiah Profile Picture" class="profile-pic" />
    <h1>Anifowose Jeremiah</h1>
    <p>Back-End Web Developer</p>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>
      I am an enthusiastic backend web developer eager to craft efficient and scalable digital solutions. Proficient in Python, Node.js, and SQL, I am dedicated to mastering server-side development and ensuring seamless functionality. Known for my problem-solving mindset and commitment to learning, I bring a fresh perspective to every project. Outside of coding, I enjoy exploring tech trends and creative writing, fueling my curiosity and drive.
    </p>
  </section>

  <section id="skills" class="skills">
    <h2>Skills</h2>
    <ul>
      <li><i class="fab fa-python"></i> Python</li>
      <li><i class="fab fa-node-js"></i> Node.js</li>
      <li><i class="fas fa-database"></i> SQL</li>
      <li><i class="fas fa-code"></i> RESTful APIs</li>
      <li><i class="fas fa-server"></i> Database Management</li>
      <li><i class="fab fa-git-alt"></i> Version Control (Git/GitHub)</li>
    </ul>
  </section>

  <section id="projects" class="projects">
    <h2>Projects</h2>
    <div class="project-grid">
      <div class="project-card">
        <!-- Placeholder project image 1 -->
        <img src="https://placeimg.com/300/150/tech" alt="RESTful API Project" />
        <h3>Task Management API</h3>
        <p>Built a RESTful API with Node.js and Express for a task management app, featuring user authentication and task CRUD operations.</p>
        <a href="https://github.com/yourusername/task-management-api" target="_blank">View on GitHub</a>
      </div>
      <div class="project-card">
        <!-- Placeholder project image 2 -->
        <img src="https://placeimg.com/300/150/tech" alt="Blog Platform Backend" />
        <h3>Blog Platform Backend</h3>
        <p>Developed a Python-based backend for a blog platform with SQL database integration, supporting post creation and user management.</p>
        <a href="https://github.com/yourusername/blog-platform" target="_blank">View on GitHub</a>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact</h2>
    <div>
      <p><i class="fas fa-envelope"></i> <a href="mailto:jeremiahanifowose026@gmail.com">jeremiahanifowose026@gmail.com</a></p>
      <p><i class="fab fa-github"></i> <a href="https://github.com/yourusername" target="_blank">GitHub Profile</a></p>
      <p><i class="fas fa-file-pdf"></i> <a href="path/to/resume.pdf" target="_blank">Download Resume</a></p>
    </div>
  </section>

  <footer>
    <p>© 2025 Anifowose Jeremiah. All rights reserved.</p>
  </footer>
</body>
</html>
