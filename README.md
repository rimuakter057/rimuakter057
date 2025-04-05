<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rimu Akter's Profile</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f7f6;
      color: #333;
      margin: 0;
      padding: 20px;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      text-align: center;
    }
    .content {
      max-width: 600px;
      padding: 20px;
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    h1 {
      font-size: 2.5rem;
      font-weight: bold;
    }
    .highlight {
      color: #FF5722;
      font-weight: bold;
    }
    .typed-text {
      display: inline;
      font-weight: bold;
      color: #2196F3;
    }
    a {
      color: #0D47A1;
      text-decoration: none;
    }
    .typing {
      font-size: 1.2rem;
      color: #333;
    }
  </style>
</head>
<body>

<div class="content">
  <h1>👋 Hi, I'm <span class="highlight">Rimu Akter!</span></h1>
  <p>I'm learning <span class="highlight">Flutter</span> and aiming to become a skilled Software Engineer in the future.</p>
  <p>So far, I've worked with <span class="highlight">Flutter UI</span>, <span class="highlight">GetX</span>, <span class="highlight">Firebase</span>, and <span class="highlight">API integration</span>.</p>
  <p>Recently, I worked on building an <span class="highlight">e_commerce app</span> and improving my Flutter skills.</p>
  <p>I'm currently learning <span class="highlight">software engineering concepts</span>.</p>
  
  <p>How to reach me: <a href="https://www.linkedin.com" target="_blank">https://www.linkedin.com/in/rimu-akter-32923233a/</a></p>
  <p>Pronouns: She/Her</p>

  <p class="typing" id="typing-animation">Fun fact: I love learning new technologies and building practical projects!</p>

  <div class="typing" id="animated-text"></div>

  <script>
    let text = 'Assalamu Alaikum!';
    let i = 0;
    let typingAnimation = document.getElementById('typing-animation');

    function typeText() {
      if (i < text.length) {
        typingAnimation.innerHTML += text.charAt(i);
        i++;
        setTimeout(typeText, 150);
      }
    }

    window.onload = function() {
      typeText();
    };
  </script>
</div>

</body>
</html>


