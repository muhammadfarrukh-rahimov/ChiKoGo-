<!DOCTYPE html>
<html>
<head>
  <title>Трекинг посылок</title>
  <style>
    body { font-family: sans-serif; text-align: center; margin-top: 50px; }
    input, button { padding: 10px; margin: 5px; font-size: 16px; }
  </style>
</head>
<body>
  <h2>Отследи свою посылку</h2>
  <input type="text" id="trackInput" placeholder="Введи трек-код">
  <br>
  <button onclick="track()">Отследить</button>
  <p id="result"></p>

  <script>
    function track() {
      const code = document.getElementById("trackInput").value.trim();
      if (code) {
        const link = `https://t.17track.net/en#nums=${code}`;
        document.getElementById("result").innerHTML = `<a href="${link}" target="_blank">Перейти к отслеживанию</a>`;
      } else {
        document.getElementById("result").innerText = "Введите трек-код!";
      }
    }
  </script>
</body>
</html><!DOCTYPE html>
<html>
<head>
  <title>Трекинг посылок</title>
  <style>
    body { font-family: sans-serif; text-align: center; margin-top: 50px; }
    input, button { padding: 10px; margin: 5px; font-size: 16px; }
  </style>
</head>
<body>
  <h2>Отследи свою посылку</h2>
  <input type="text" id="trackInput" placeholder="Введи трек-код">
  <br>
  <button onclick="track()">Отследить</button>
  <p id="result"></p>

  <script>
    function track() {
      const code = document.getElementById("trackInput").value.trim();
      if (code) {
        const link = `https://t.17track.net/en#nums=${code}`;
        document.getElementById("result").innerHTML = `<a href="${link}" target="_blank">Перейти к отслеживанию</a>`;
      } else {
        document.getElementById("result").innerText = "Введите трек-код!";
      }
    }
  </script>
</body>
</html>
