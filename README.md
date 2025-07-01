
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Minha Página Pessoal</title>
  <link rel="stylesheet" href="style.css">
  <style>
    body {
      background-color: #add8e6; 
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    .capa {
      background-color: white;
      text-align: center;
      padding: 40px 20px;
      border-bottom: 2px solid #000;
    }

    .capa img {
      max-width: 200px;
      margin-bottom: 20px;
    }

    .capa h1,
    .capa h2,
    .capa h3,
    .capa p {
      margin: 5px 0;
    }

    .capa .titulo-atividade {
      margin-top: 40px;
      font-size: 1.5em;
      font-weight: bold;
    }

    .capa .dados-aluno {
      margin-top: 40px;
      font-size: 1em;
    }

    h1 {
      text-align: center;
      margin-top: 40px;
      color: #333;
    }

    .pais-link {
      display: block;
      margin: 10px 0;
    }

    .mensagem-btn {
      margin: 5px 0;
    }

    #mensagem {
      font-weight: bold;
      color: darkred;
    }

    a {
      color: #000099;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    main {
      padding: 20px;
    }
  </style>
</head>
<body>

  
  <div class="capa">
    <img src="https://upload.wikimedia.org/wikipedia/commons/c/c7/Centro_Universitário_Internacional.jpg" alt="Logo UNINTER" />
    <h2>CENTRO UNIVERSITÁRIO INTERNACIONAL UNINTER</h2>
    <h3>ESCOLA SUPERIOR POLITÉCNICA</h3>
    <p><strong>FUNDAMENTOS DE DESENVOLVIMENTO DE SOFTWARE</strong></p>

    <div class="titulo-atividade">ATIVIDADE PRÁTICA</div>

    <div class="dados-aluno">
      <p>Wellynton Toniolli – RU: 4920788</p>
      <p>Santa Izabel do Oeste – PR</p>
      <p>2025</p>
    </div>
  </div>

  <main>
    <h1>Minha Biografia</h1>

    <p id="bio">
      Olá! Sou Wellynton, tenho 20 anos, moro em Santa Izabel do Oeste - PR. Gosto de correr em arrancadas de carros, viajar e assistir filmes e séries de terror.
    </p>

    <a href="https://fueltech.com.br/blogs/news/fueltech-no-armageddon-a-maior-audiencia-da-historia-da-arrancada-no-brasil" target="_blank">
      Conheça meu hobbie favorito
    </a>

    <button class="mensagem-btn" onclick="mostrarMensagem()">Clique para ver uma mensagem!</button>
    <p id="mensagem"></p>

    <h2>Países que quero conhecer</h2>
    <a class="pais-link" href="https://br.freepik.com/fotos/suica" target="_blank">Conheça meu país favorito: Suíça</a>
    <a class="pais-link" href="https://br.freepik.com/search?query=estados+unidos" target="_blank">Conheça meu país favorito: Estados Unidos</a>
    <a class="pais-link" href="https://br.freepik.com/search?query=chile" target="_blank">Conheça meu país favorito: Chile</a>

    <h2>Site Favorito</h2>
    <a href="https://www.instagram.com/wellynton_toniolli/" target="_blank">Visite meu Instagram</a>
  </main>

  <script>
    function mostrarMensagem() {
      const msg = document.getElementById('mensagem');
      msg.textContent = 'Obrigado por visitar minha página!';
    }
  </script>
</body>
</html>

