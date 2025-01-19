<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Troy Garcia | Aspiring Software Developer</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f9;
      color: #333;
    }

    header {
      text-align: center;
      padding: 50px 20px;
      background: linear-gradient(135deg, #2e3b4e, #1d2c42);
      color: white;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    h2 {
      font-weight: 300;
      margin: 10px 0;
    }

    p {
      font-size: 1.1rem;
      margin: 0;
    }

    main {
      max-width: 900px;
      margin: 20px auto;
      padding: 20px;
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
    }

    section {
      margin-bottom: 25px;
    }

    h2 {
      color: #444;
      border-bottom: 2px solid #ddd;
      padding-bottom: 5px;
    }

    ul {
      list-style: none;
      padding-left: 0;
    }

    ul li {
      margin-bottom: 10px;
    }

    a {
      text-decoration: none;
      color: #1d6b99;
      font-weight: 500;
      transition: color 0.3s;
    }

    a:hover {
      color: #287b9b;
    }

    .progress-bar-container {
      width: 100%;
      background-color: #ddd;
      border-radius: 5px;
      height: 15px;
      margin-bottom: 15px;
    }

    .progress-bar {
      height: 100%;
      border-radius: 5px;
      text-align: center;
      color: white;
      line-height: 15px;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #222;
      color: white;
      font-size: 14px;
    }

    /* Sticky navbar (optional) */
    nav {
      position: sticky;
      top: 0;
      background-color: #333;
      padding: 10px 20px;
      text-align: center;
      z-index: 1000;
    }

    nav a {
      color: white;
      padding: 10px 15px;
      text-decoration: none;
      font-weight: 600;
      margin: 0 10px;
    }

    nav a:hover {
      background-color: #555;
    }

    /* Mobile responsive */
    @media (max-width: 768px) {
      header h1 {
        font-size: 2rem;
      }

      main {
        padding: 15px;
      }

      .progress-bar-container {
        width: 100%;
        height: 10px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>💻 Troy Garcia</h1>
    <h2>Aspiring Software Developer</h2>
    <p>Blending technology, fitness, and personal growth.</p>
  </header>

  <main>
    <section>
      <h2>📜 About Me</h2>
      <p>
        Hi! I’m <strong>Troy Garcia</strong>, a tech enthusiast and Computer Science student based in Markham, ON. Outside of coding, I enjoy staying active at the gym, reading thought-provoking books, and exploring the open road on my motorcycle.
      </p>
    </section>

    <section>
      <h2>🛠️ Technical Skills</h2>
      <ul>
        <li><strong>Programming Languages:</strong> JavaScript, Python, Java, C/C++</li>
        <li><strong>Web Development:</strong> React, Node.js, HTML, CSS</li>
        <li><strong>Database Management:</strong> SQL, PostgreSQL, MongoDB</li>
        <li><strong>Frameworks & Tools:</strong> Git, Docker, REST APIs</li>
        <li><strong>Core Knowledge:</strong> Data Structures, Algorithms, MERN Stack</li>
      </ul>

      <h3>Skills Proficiency</h3>
      <div class="progress-bar-container">
        <div class="progress-bar" style="width: 90%; background-color: #1d6b99;">JavaScript (90%)</div>
      </div>
      <div class="progress-bar-container">
        <div class="progress-bar" style="width: 85%; background-color: #4caf50;">React (85%)</div>
      </div>
      <div class="progress-bar-container">
        <div class="progress-bar" style="width: 75%; background-color: #ff9800;">Python (75%)</div>
      </div>
    </section>

    <section>
      <h2>🌟 Highlights</h2>
      <ul>
        <li>Analytical thinker with a passion for solving problems.</li>
        <li>Enthusiastic about applying technology to enhance everyday life.</li>
        <li>Committed to personal growth, both mentally and physically.</li>
      </ul>
    </section>

    <section>
      <h2>🖥️ Projects</h2>
      <p>Coming soon! Check back for some exciting projects I’m working on.</p>
    </section>

    <section>
      <h2>📬 Let’s Connect</h2>
      <p>
        <strong>Email:</strong> <a href="mailto:troygarcia@icloud.com">troygarcia@icloud.com</a><br>
        <strong>GitHub:</strong> <a href="https://github.com/grayveins" target="_blank">github.com/grayveins</a>
      </p>
    </section>
  </main>

  <footer>
    <p>Made with ❤️ by Troy Garcia</p>
  </footer>
</body>
</html>
