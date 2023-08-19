<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      background-color: #121212;
      font-family: Arial, sans-serif;
    }

    .container {
      background-color: #1E1E1E;
      border-radius: 10px;
      padding: 30px;
      box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
      margin: 50px auto;
      max-width: 800px;
    }

    .profile-img {
      display: block;
      margin: 0 auto;
      border-radius: 50%;
      width: 150px;
      height: 150px;
      object-fit: cover;
      animation: rotate 10s linear infinite;
    }

    @keyframes rotate {
      0% {
        transform: rotate(0deg);
      }
      100% {
        transform: rotate(360deg);
      }
    }

    .header {
      font-size: 28px;
      color: white;
      margin-top: 20px;
      text-align: center;
    }

    .subtitle {
      font-size: 18px;
      color: #A0A0A0;
      margin-top: 10px;
      text-align: center;
    }

    .social-links {
      text-align: center;
      margin-top: 20px;
    }

    .social-link {
      display: inline-block;
      margin: 0 10px;
      transition: transform 0.3s ease-in-out;
    }

    .social-link:hover {
      transform: scale(1.2);
    }

    .about {
      font-size: 18px;
      color: white;
      margin-top: 30px;
    }

    .tools {
      font-size: 18px;
      color: white;
      margin-top: 30px;
    }

    .stats {
      text-align: center;
      margin-top: 30px;
    }

    .stats-img {
      max-width: 100%;
      animation: pulse 2s ease-in-out infinite;
    }

    @keyframes pulse {
      0% {
        transform: scale(1);
      }
      50% {
        transform: scale(1.05);
      }
      100% {
        transform: scale(1);
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <img class="profile-img" src="https://bchhar-img--brendanc8.repl.co/img.jpeg" alt="Profile Image">
    <h1 class="header">Hello there! 👋 I'm Brendan, a Mechatronics Engineering student from the University of Waterloo.</h1>
    <p class="subtitle">Passionate about Machine Learning, Robotics, and Innovation</p>
    <div class="social-links">
      <a class="social-link" href="https://www.linkedin.com/in/brendan-chharawala/" target="_blank">
        <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="30" alt="LinkedIn">
      </a>
      <a class="social-link" href="mailto:brendancmechatronics@gmail.com" target="_blank">
        <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="30" alt="Gmail">
      </a>
    </div>
    <p class="about">
      Welcome to my profile! I'm a passionate Mechatronics Engineering student at the esteemed University of Waterloo.
      - 🧠 I'm a Machine Learning and Robotics Developer 🤖
      - ⚡ When I'm not studying, I'm busy building robots and innovative gizmos. 🛠️
      - 💻 Explore my website: <a href="https://bchharaw.github.io/#/" style="color: #007bff; text-decoration: none;">bchharaw.github.io</a>
      - 🌌 My universe revolves around machine learning, computer vision, and more. I'm well-versed in Python and skilled with libraries like TensorFlow, PyTorch, OpenCV, and Isaac Gym. 📊🤖👾
    </p>
    <p class="tools">
      <strong>Languages and Tools:</strong>
      Python, C++, TensorFlow, PyTorch, OpenCV, C, HTML5, CSS3, JavaScript, React, Git
    </p>
    <div class="stats">
      <h3>My Stats:</h3>
      <img class="stats-img" src="https://streak-stats.demolab.com?user=BChharaw&locale=en&mode=daily&theme=dark&hide_border=false&border_radius=5&order=3" alt="Streak Graph">
    </div>
  </div>
</body>
</html>
