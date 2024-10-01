<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Música Inspiradora de Vendas</title>
  <style>
    /* CSS */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f2f2f2;
    }
    
    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 40px;
      background-color: white;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
    }
    
    h1 {
      text-align: center;
      margin-bottom: 30px;
    }
    
    .lyrics {
      white-space: pre-wrap;
      font-size: 18px;
      line-height: 1.6;
    }
    
    .play-button {
      display: block;
      margin: 30px auto;
      padding: 10px 20px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 4px;
      font-size: 16px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Música Inspiradora de Vendas</h1>
    <div class="lyrics">
      <!-- Insira a letra da música aqui -->
    </div>
    <button class="play-button">Ouvir a Música</button>
  </div>

  <script>
    // JavaScript
    const playButton = document.querySelector('.play-button');

    playButton.addEventListener('click', () => {
      // Adicione aqui o código para reproduzir a música
      alert('A música está tocando!');
    });
  </script>
</body>
</html>
