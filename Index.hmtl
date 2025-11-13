<!DOCTYPE html>
<html>
<head>
  <title>Conversor NIO a USD</title>
  <style>
    body {font-family: Arial; text-align: center; padding: 50px; background: #e8f5e9;}
    input, button {padding: 12px; font-size: 18px; margin: 10px;}
    button {background: #2e7d32; color: white; border: none; cursor: pointer; border-radius: 8px;}
    h1 {color: #1b5e20;}
  </style>
</head>
<body>
  <h1>Conversor NIO → USD</h1>
  <p>Ingresa cantidad en córdobas:</p>
  <input type="number" id="nio" placeholder="Ej: 1000">
  <button onclick="convertir()">Convertir</button>
  <h2 id="resultado"></h2>

  <script>
    function convertir() {
      let nio = document.getElementById("nio").value;
      if (nio === "" || nio < 0) {
        document.getElementById("resultado").innerHTML = "<strong style='color:red;'>¡Ingresa un número válido!</strong>";
        return;
      }
      let usd = (nio / 36.8).toFixed(2);
      document.getElementById("resultado").innerHTML = 
        `<strong style="color:green;">$${usd} USD</strong>`;
    }
  </script>
</body>
</html>
