<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Our Love Story</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      font-family: 'Great Vibes', cursive;
      background: linear-gradient(to bottom right, #4a1c40, #e8c1c8);
      color: white;
      overflow-x: hidden;
    }
    section {
      display: none;
      padding: 40px 20px;
      min-height: 100vh;
      text-align: center;
    }
    .visible {
      display: flex !important;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
    .container {
      background: rgba(255, 255, 255, 0.1);
      border-radius: 20px;
      padding: 30px;
      max-width: 800px;
      width: 90%;
      box-shadow: 0 0 20px rgba(255, 192, 203, 0.4);
    }
    input[type="password"], input[type="text"], textarea {
      padding: 12px;
      border: none;
      border-radius: 8px;
      margin-top: 10px;
      width: 80%;
      font-size: 1.1em;
      text-align: center;
    }
    button {
      margin-top: 20px;
      padding: 10px 24px;
      font-size: 1em;
      background-color: #b95c84;
      color: white;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      font-weight: bold;
    }
    iframe {
      width: 300px;
      height: 400px;
      border: none;
      border-radius: 15px;
      margin: 10px;
      background-color: #fff0f3;
      box-shadow: 0 0 10px rgba(255, 255, 255, 0.2);
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .quote {
      font-size: 1.2em;
      margin-top: 10px;
      max-width: 300px;
    }
  </style>
</head>
<body><section id="passwordPage" class="visible">
  <div class="container">
    <h1>When we both get connected with each other... then it’s just love</h1>
    <p>You can open it by connecting us</p>
    <input type="password" id="password" placeholder="Enter your love..." />
    <br />
    <button onclick="checkPassword()">Unlock</button>
    <div id="errorMsg" class="error"></div>
  </div>
</section><section id="welcomePage">
  <div class="container">
    <h1>Welcome My Love</h1>
    <p>
      If you ever ask me what you are to me I will say 👀❤️<br>
      You are the sun ☀️ with whom my day begins.❤️<br>
      You are my sunset 🌄 with whom my day ends.💗<br>
      You are my moon 🌕 that makes me shine like a star 🌟✨ in the dark sky filled with darkness.🌌<br>
      You are my rainbow 🌈 that fills my colourless life with so many beautiful colours.🥹❤️<br>
      You are my waterfall 🏞️ from which your love flows into my life ❤️<br>
      You are my mountain ⛰️ surrounded by whom I feel safe. ❤️🫂<br>
      You are my universe 🌌 sheltering each and every world of mine. 🥹❤️🫂<br><br>
      <strong>Let’s See If You Know Me Well!</strong><br>
      What is the one thing I always say?
    </p>
    <input type="text" id="riddleAnswer" placeholder="Type your answer...">
    <br>
    <button onclick="checkAnswer()">Continue</button>
    <div id="riddleError" class="error"></div>
  </div>
</section><section id="galleryPage">
  <h1>Our Memories</h1>
  <div class="gallery">
    <div>
      <iframe src="https://drive.google.com/file/d/1eRGILUKYFL6SExPgNNEX3IKUgPqscGIr/preview"></iframe>
      <div class="quote">Can't help falling in love with you 💗</div>
    </div>
    <div>
      <iframe src="https://drive.google.com/file/d/1ePTdrz9WUaPlC-d2igQW5Ak2fR29IriU/preview"></iframe>
      <div class="quote">You are the best decision of my life 💕</div>
    </div>
    <div>
      <iframe src="https://drive.google.com/file/d/1einXKBHWlDx59klbT9AMF8lJvyI6Fatk/preview"></iframe>
      <div class="quote">Don't know about the destination but the journey with you is beautiful ❤️</div>
    </div>
    <div>
      <iframe src="https://drive.google.com/file/d/1eiggkzkrlHJHuWoUX8hy8MlidGw_XlfG/preview"></iframe>
      <div class="quote">Every picture is a heartbeat of our love</div>
    </div>
    <div>
      <iframe src="https://drive.google.com/file/d/1eebP1ca1TemUGojMlg3M6CC4UYYTYEBh/preview"></iframe>
      <div class="quote">You're the reason behind my smile</div>
    </div>
    <div>
      <iframe src="https://drive.google.com/file/d/1eVX_XrcxUgdxo2zk5_975656fhYf1Zox/preview"></iframe>
      <div class="quote">You and me — a forever vibe</div>
    </div>
    <div>
      <iframe src="https://drive.google.com/file/d/1eNr5_2BvkoHf9wH6TQFjntFVmYAJuGJ3/preview"></iframe>
      <div class="quote">You're the love I never saw coming</div>
    </div>
    <div>
      <iframe src="https://drive.google.com/file/d/1eWpcbt4PSqPtvA3fFxQVwNGpaia9PmMe/preview"></iframe>
      <div class="quote">Forever grateful for your love</div>
    </div>
    <div>
      <button onclick="showThankYou()">The Last Thing I Want to Say</button>
    </div>
  </div>
</section><section id="thankYouPage">
  <div class="container">
    <h1 style="font-size: 3em;">Thank You, My Love</h1>
    <p style="font-size: 1.5em; line-height: 1.6;">
      For letting me know how love feels ❤️<br>
      For letting me know how someone can be so much important in your life 👀❤️<br>
      For letting me know how to love 😘❤️<br>
      Thank you my love for everything you have gave me 🥹 which I will never forget ❣️<br>
      I wish I could get a little more time to tell you how much I love you 🥹❤️<br>
      But unfortunately we don't get what we wanted and expected,<br>
      But I got so many beautiful memories which I will never forget 🥹❤️<br>
      Thank you for forgiving me for the things I have done which you didn't like 🥹❤️<br>
      Hope I get more time to love you 🥹<br>
      Hope I get another life in which you will be mine — just mine 🥹💗<br>
      At the end, I just want to tell you that...<br>
      <strong>Thanks for everything 🥹❤️ and I love you so much ❤️ I always will ❤️✨</strong>
    </p>
    <h2>Let me know the thing you want to tell me ❤️</h2>
    <textarea id="userMessage" rows="5" placeholder="Type your message here..." style="width:80%; border-radius: 10px; margin-top:10px;"></textarea>
    <br>
    <button onclick="shareMessage()">Share</button>
    <div id="sharedMsg" style="margin-top: 20px; font-size: 1.4em;"></div>
  </div>
</section><script>
  function checkPassword() {
    const pass = document.getElementById("password").value.trim().toLowerCase();
    if (pass === "nish") {
      document.getElementById("passwordPage").classList.remove("visible");
      document.getElementById("passwordPage").style.display = "none";
      document.getElementById("welcomePage").classList.add("visible");
    } else {
      document.getElementById("errorMsg").innerText = "Oops! You didn’t send enough love. Try again with your heart.";
    }
  }

  function checkAnswer() {
    const answer = document.getElementById("riddleAnswer").value.trim().toLowerCase();
    if (answer === "kitne bure he aap") {
      document.getElementById("welcomePage").classList.remove("visible");
      document.getElementById("welcomePage").style.display = "none";
      document.getElementById("galleryPage").classList.add("visible");
    } else {
      document.getElementById("riddleError").innerText = "Oops! Not quite. Think again, my love.";
    }
  }

  function showThankYou() {
    document.getElementById("galleryPage").classList.remove("visible");
    document.getElementById("galleryPage").style.display = "none";
    document.getElementById("thankYouPage").classList.add("visible");
  }

  function shareMessage() {
    const msg = document.getElementById("userMessage").value.trim();
    if (msg) {
      document.getElementById("sharedMsg").innerText = "Love you so much ❤️✨\nThanks for sharing ❤️✨";
    }
  }
</script></body>
</html>
