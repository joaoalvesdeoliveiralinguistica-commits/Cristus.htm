# Cristus.htm
Essa é uma página que fala de esperança e da volta de Cristo.

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>A Esperança da Volta de Cristo</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      min-height: 100vh;
      font-family: Arial, sans-serif;
      color: #fff;
      background:
        linear-gradient(rgba(10, 20, 40, 0.65), rgba(10, 20, 40, 0.85)),
        url("https://images.unsplash.com/photo-1470770841072-f978cf4d019e?auto=format&fit=crop&w=1800&q=85")
        center / cover fixed;
    }

    header {
      padding: 24px 8%;
      text-align: center;
      background: rgba(0, 0, 0, 0.25);
    }

    header h1 {
      font-size: clamp(1.8rem, 5vw, 3rem);
      letter-spacing: 1px;
    }

    main {
      width: min(850px, 90%);
      margin: 70px auto;
    }

    article {
      padding: clamp(24px, 5vw, 48px);
      border: 1px solid rgba(255, 255, 255, 0.25);
      border-radius: 18px;
      background: rgba(8, 18, 35, 0.78);
      box-shadow: 0 12px 35px rgba(0, 0, 0, 0.35);
      line-height: 1.8;
    }

    article h2 {
      margin-bottom: 18px;
      color: #f3d58a;
      font-size: 1.8rem;
    }

    article p {
      margin-bottom: 16px;
      font-size: 1.05rem;
    }

    blockquote {
      margin: 24px 0;
      padding: 16px 20px;
      border-left: 4px solid #f3d58a;
      color: #f8eac5;
      font-style: italic;
      background: rgba(255, 255, 255, 0.07);
    }

    button {
      margin-top: 8px;
      padding: 12px 20px;
      border: 0;
      border-radius: 8px;
      color: #172033;
      background: #f3d58a;
      font-size: 1rem;
      font-weight: bold;
      cursor: pointer;
      transition: transform 0.2s, background 0.2s;
    }

    button:hover {
      transform: translateY(-2px);
      background: #ffe6a6;
    }

    footer {
      padding: 28px 8%;
      text-align: center;
      color: #e4e8ef;
      background: rgba(5, 10, 20, 0.9);
      border-top: 3px solid #f3d58a;
    }

    footer p + p {
      margin-top: 8px;
      font-size: 0.9rem;
      color: #b9c2d0;
    }
  </style>
</head>

<body>
  <header>
    <h1>Uma esperança para o futuro</h1>
  </header>

  <main>
    <article>
      <h2>A volta de Cristo</h2>

      <p>
        Para os cristãos, a volta de Cristo representa a esperança de um futuro
        marcado pela justiça, pela paz e pela renovação. Essa promessa inspira
        fé e encoraja muitas pessoas a viverem com amor, compaixão e atenção ao
        próximo.
      </p>

      <p>
        Mais do que tentar prever datas, a mensagem convida à reflexão sobre
        como nossas escolhas de hoje podem tornar o mundo melhor. A esperança,
        nesse sentido, também se expressa em gestos de bondade e solidariedade.
      </p>

      <blockquote>
        “Portanto, estejam preparados, porque o Filho do Homem virá numa hora
        em que vocês menos esperam.” — Mateus 24:44
      </blockquote>

      <p>
        A fé na volta de Cristo é compreendida de maneiras diferentes entre as
        tradições cristãs, mas costuma apontar para a importância de viver com
        propósito, esperança e amor.
      </p>

      <button onclick="mostrarMensagem()">Leia uma mensagem</button>
      <p id="mensagem" aria-live="polite"></p>
      
      <h3 class="titulo-video">Assista ao vídeo</h3>

<div class="video">
  <iframe
    src="https://www.youtube-nocookie.com/embed/HynYEEr8AvY"
    title="Vídeo sobre a volta de Cristo"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen>
  </iframe>
</div>    
    </article>
  </main>

  <footer>
    <p>✨ Que a esperança inspire suas atitudes todos os dias. ✨</p>
    <p>© <span id="ano"></span> — Página feita para estudo no Geany</p>
  </footer>

  <script>
    document.getElementById("ano").textContent = new Date().getFullYear();

    function mostrarMensagem() {
      document.getElementById("mensagem").textContent =
        "Que a fé, a esperança e o amor estejam presentes em seu caminho.";
    }
  </script>
</body>
</html>
