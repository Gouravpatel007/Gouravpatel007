<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Gourav Patel - Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
      color: #333;
      padding: 20px;
      line-height: 1.6;
    }

    h1, h2 {
      text-align: center;
    }

    #role {
      font-size: 1.5rem;
      font-weight: bold;
      transition: color 0.5s ease;
      margin-bottom: 20px;
    }

    p, ul {
      max-width: 800px;
      margin: 0 auto;
    }

    ul {
      padding-left: 20px;
    }

    a {
      color: #0073b1;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .section-title {
      font-size: 1.3rem;
      margin-top: 30px;
      text-align: center;
      color: #2c3e50;
    }
  </style>
</head>
<body>

  <h1>👋 Hi there, I'm <strong>Gourav Patel</strong>!</h1>

  <p align="center">
    <img src="https://gifdb.com/images/high/coding-girl-animation-fe7t4gejurmtof8v.gif" width="350" alt="Live Coding Animation">
  </p>

  <h2 id="role">💻 Welcome to Frontend Developer</h2>

  <p>🎓 I'm currently pursuing <strong>B.Tech in Computer Science and Engineering (AI & ML)</strong>.</p>
  <p>💻 I'm passionate about web development and actively building projects using the <strong>MERN Stack</strong> (MongoDB, Express.js, React.js, Node.js).</p>
  <p>🚀 My goal is to become a full-stack developer and looking ahead to be a part of coding community.</p>

  <hr>

  <div class="section-title">🌟 About Me</div>
  <ul>
    <li>🛠️ Tech Stack: <strong>JavaScript</strong>, <strong>React.js</strong>, <strong>Node.js</strong>, <strong>Express.js</strong>, <strong>MongoDB</strong>, <strong>MySQL</strong></li>
    <li>🔐 Familiar with Authentication using JWT and Payment Gateways like Razorpay/Stripe</li>
    <li>🧠 Practicing DSA: Solved problems on <strong>Arrays, Strings, Searching, Sorting, Recursion, Linked Lists</strong></li>
    <li>📚 Always ready to learn and explore new technologies and frameworks</li>
  </ul>

  <div class="section-title">📌 Interests</div>
  <ul>
    <li>💡 Web Development (Frontend + Backend)</li>
    <li>📈 Building Scalable and Real-world Applications</li>
    <li>🎥 Creating educational/animated videos for YouTube</li>
    <li>🌐 Open Source and Community Learning</li>
    <li>⚡ Cloud & DevOps (Beginner level interest)</li>
  </ul>

  <div class="section-title">📫 Connect with Me</div>
  <ul>
    <li>📧 Email: kp180284@gmail.com</li>
    <li>💼 <a href="https://www.linkedin.com/in/gourav12patel" target="_blank">LinkedIn</a></li>
    <li>🌐 <a href="https://portfolio-1my.netlify.app/" target="_blank">Portfolio</a></li>
  </ul>

  <script>
    const roles = [
      { text: "Frontend Developer", color: "#e91e63" },
      { text: "Backend Developer", color: "#3f51b5" },
      { text: "MERN Developer", color: "#009688" },
      { text: "Full Stack Developer", color: "#ff9800" }
    ];

    let index = 0;
    const roleElement = document.getElementById("role");

    function updateRole() {
      roleElement.textContent = `💻 Welcome to ${roles[index].text}`;
      roleElement.style.color = roles[index].color;
      index = (index + 1) % roles.length;
    }

    updateRole();
    setInterval(updateRole, 2000);
  </script>

</body>
</html>


