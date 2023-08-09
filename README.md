# tojuju
git clone https://github.com/seunomeusuario/namoro-site.git
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pergunta Especial</title>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: #d22020;
    font-family: Arial, sans-serif;
  }
  .question {
    text-align: center;
    padding: 20px;
    background-color: #dd2b2b;
    border-radius: 10px;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
  }
  .question-link {
    color: #fff;
    text-decoration: underline;
    cursor: pointer;
  }
  .button-container {
    margin-top: 20px;
  }
  .button {
    margin: 0 10px;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
    transition: transform 0.3s;
  }
  .button-yes {
    background-color: #4caf50;
    color: rgb(9, 9, 9);
  }
  .button-no {
    background-color: #f44336;
    color: rgb(12, 12, 12);
  }
</style>
<script>
  document.addEventListener("DOMContentLoaded", () => {
    const noButton = document.querySelector(".button-no");

    noButton.addEventListener("mouseover", () => {
      const xOffset = Math.random() * (window.innerWidth - noButton.clientWidth) - 10; // Ajuste a distância aqui
      const yOffset = Math.random() * (window.innerHeight - noButton.clientHeight) - 10; // Ajuste a distância aqui
      noButton.style.transform = `translate(${xOffset}px, ${yOffset}px)`;
    });

    noButton.addEventListener("mouseout", () => {
      noButton.style.transform = "translate(0, 0)";
    });

    const yesButton = document.querySelector(".button-yes");

    yesButton.addEventListener("click", () => {
      window.location.href = "https://www.youtube.com/watch?v=PnAMEe0GGG8";
    });
  });
</script>
</head>
<body>
  <div class="question">
    <h1 class="question-link" onclick="window.location.href='https://www.youtube.com/watch?v=PnAMEe0GGG8'">Quer namorar comigo?</h1>
    <div class="button-container">
      <button class="button button-yes">Sim</button>
      <button class="button button-no" id="no-button">Não</button>
    </div>
  </div>
  <script>
    const noButton = document.getElementById("no-button");

    noButton.addEventListener("mouseover", () => {
      const xOffset = Math.random() * (window.innerWidth - noButton.clientWidth) - 10; // Ajuste a distância aqui
      const yOffset = Math.random() * (window.innerHeight - noButton.clientHeight) - 10; // Ajuste a distância aqui
      noButton.style.transform = `translate(${xOffset}px, ${yOffset}px)`;
    });

    noButton.addEventListener("mouseout", () => {
      noButton.style.transform = "translate(0, 0)";
    });
  </script>
</body>
</html>



