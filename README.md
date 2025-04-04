<!DOCTYPE html><html lang="hi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sanjeet Raj - Voice Assistant</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: #000;
      color: #0f0;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
    }
    h1 {
      font-size: 2.5em;
      animation: glow 2s infinite alternate;
    }
    img {
      width: 200px;
      border-radius: 20px;
      margin: 20px;
      box-shadow: 0 0 20px #0f0;
    }
    .mic-button {
      padding: 20px;
      border-radius: 50%;
      background: #0f0;
      color: #000;
      font-size: 20px;
      border: none;
      cursor: pointer;
      margin-top: 30px;
    }
    @keyframes glow {
      from { text-shadow: 0 0 10px #0f0; }
      to { text-shadow: 0 0 20px #0ff; }
    }
  </style>
</head>
<body>
  <h1>Welcome to SanjeetRaj.in</h1>
  <img src="https://via.placeholder.com/200x200.png?text=Sanjeet+Raj" alt="Sanjeet Raj">
  <p>"Hello Sanjeet Raj" boliye aur apne phone ko bina haath lagaye control kijiye!</p>
  <button class="mic-button" onclick="startAssistant()">🎤 Start Voice Assistant</button>  <script>
    function startAssistant() {
      alert("सुन रहा हूँ Sanjeet Raj... aapka command kya hai?");
      // Yahan future mein aapke saare features add kiye jaa sakte hain.
    }
  </script></body>
</html>
