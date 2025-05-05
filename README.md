<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bropase Project X</title>
  <style>
    body {
      background-color: #0b0c10;
      color: #66fcf1;
      font-family: 'Courier New', monospace;
      padding: 2rem;
    }
    h1, h2 {
      color: #45a29e;
    }
    .terminal-box {
      background-color: #1f2833;
      border: 2px solid #66fcf1;
      padding: 1rem;
      margin-top: 1rem;
      font-size: 0.9rem;
    }
    .button {
      background-color: #66fcf1;
      color: #0b0c10;
      padding: 0.5rem 1rem;
      border: none;
      cursor: pointer;
      margin-top: 1rem;
      font-weight: bold;
    }
    .hidden-message {
      display: none;
      margin-top: 1rem;
      color: #f8d210;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <h1>Welcome to Project Bropase</h1>
  <p>Restricted Area – Authorized Morotiese Agents Only.</p>

  <div class="terminal-box">
    <p>> Initializing Logitase Protocol...</p>
    <p>> Motoric AI Module Loaded.</p>
    <p>> Status: Stable...for now.</p>
  </div>

  <button class="button" onclick="revealSecret()">Enter Lala Code</button>

  <div id="secret" class="hidden-message">
    ACCESS GRANTED: The BroPulse lives within you. <br>
    Transmission: "01001000 01100101 01101100 01101100 01101111" 
  </div>

  <script>
    function revealSecret() {
      const message = document.getElementById('secret');
      message.style.display = 'block';
    }
  </script>
</body>
</html>
# bropase-project
