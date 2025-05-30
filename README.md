<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Shirinov Muhammad Portfolio</title>
<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: #121212;
    color: #fff;
    margin: 0;
    padding: 20px;
  }
  .container {
    max-width: 800px;
    margin: 0 auto;
    text-align: center;
  }
  .shimmer {
    animation: shimmer 2s infinite;
    background: linear-gradient(90deg, #f0f0f0 25%, #c0c0c0 50%, #f0f0f0 75%);
    background-size: 400% 100%;
    color: transparent;
    -webkit-background-clip: text;
    background-clip: text;
    font-size: 2.5em;
    font-weight: bold;
  }
  @keyframes shimmer {
    0% { background-position: -400% 0; }
    100% { background-position: 400% 0; }
  }
  .info {
    margin-top: 20px;
    line-height: 1.6;
    font-size: 1.1em;
  }
  .links a {
    display: inline-block;
    margin: 10px;
    text-decoration: none;
    color: #00bcd4;
    font-weight: 500;
    transition: transform 0.3s ease;
  }
  .links a:hover {
    transform: scale(1.1);
  }
  .section {
    margin-top: 40px;
  }
  .tools img {
    margin: 10px;
    transition: transform 0.3s ease;
  }
  .tools img:hover {
    transform: scale(1.2);
  }
</style>
</head>
<body>
<div class="container">
  <h1 class="shimmer">Muhammad Shirinov</h1>
  <h3 class="shimmer">🚀 Backend Developer</h3>
  
  <div class="info">
    <p>🎓 Talaba, innovatsion fikrli dasturchi</p>
    <p>🌐 Asosiy yo'nalishlar: Java, Spring, Express.js, va Node.js</p>
  </div>
  
  <div class="section links">
    <a href="https://t.me/Shirinov_m" target="_blank">
      <img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png" width="30" height="30" alt="Telegram"/> Telegram
    </a>
    <a href="mailto:shirinovmuhammad11@gmail.com" target="_blank">
      <img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" width="30" height="30" alt="Email"/> Email
    </a>
    <a href="https://www.linkedin.com/in/muhammad-shirinov-1a5b35366" target="_blank">
      <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" width="30" height="30" alt="LinkedIn"/> LinkedIn
    </a>
  </div>
  
  <div class="section">
    <h3>🛠️ Languages and Tools</h3>
    <div class="tools">
      <a href="https://www.java.com/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="40" height="40" alt="Java"/>
      </a>
      <a href="https://spring.io/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/spring/spring-original.svg" width="40" height="40" alt="Spring"/>
      </a>
      <a href="https://nodejs.org" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" width="40" height="40" alt="Node.js"/>
      </a>
      <a href="https://expressjs.com" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" width="40" height="40" alt="Express"/>
      </a>
      <a href="https://www.w3.org/html/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" width="40" height="40" alt="HTML5"/>
      </a>
      <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40" height="40" alt="JavaScript"/>
      </a>
    </div>
  </div>
</div>
</body>
</html>
