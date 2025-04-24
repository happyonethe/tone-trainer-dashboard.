<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TONE Trainer Mobile Dashboard</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="dashboard">
    <h1>TONE Trainer</h1>
    <p class="tagline">Tap a ritual to begin.</p>o
    <div class="button-grid">
      <button onclick="trigger('Run Morning Ritual')">Morning Ritual</button>
      <button onclick="trigger('Test Distraction Response')">Distraction Test</button>
      <button onclick="trigger('Give me the Drop to Obey Flow')">Drop to Obey Flow</button>
      <button onclick="trigger('Start Whisper Cadence Practice')">Whisper Cadence</button>
    </div>
    <div id="output"></div>
  </div>
  <script src="script.js"></script>
</body>
</html>
function trigger(command) {
  const output = document.getElementById("output");
  switch (command) {
    case "Run Morning Ritual":
      output.innerText = "Morning Ritual Activated: Secret Vessel Creed + Eye Direction (Right → Left – Identity Lock)";
      break;
    case "Test Distraction Response":
      output.innerText = "Testing Focus: Initiate Flirt Loop + NLP Redirect.";
      break;
    case "Give me the Drop to Obey Flow":
      output.innerText = "Drop to Obey Flow Running: Level 2/3 Trance + Eye Sequence";
      break;
    case "Start Whisper Cadence Practice":
      output.innerText = "Whisper Practice: ‘You’re mine. Say it again…’ Cadence Mode Enabled.";
      break;
    default:
      output.innerText = "Command not recognized.";
  }
}
