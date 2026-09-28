<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#111111">
  <meta name="description" content="Ninguém Está Atrasado, de Faustino Mananga. Um livro sobre tempo, propósito, recomeço e construção de novos caminhos.">

  <title>Ninguém Está Atrasado | Faustino Mananga</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      color: #171717;
      line-height: 1.6;
    }

    header {
      background: #111;
      color: white;
      padding: 25px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 28px;
      margin-bottom: 5px;
    }

    header p {
      color: #d4af37;
      font-size: 15px;
    }

    .hero {
      background: linear-gradient(135deg, #111, #292929);
      color: white;
      text-align: center;
      padding: 55px 20px;
    }

    .hero h2 {
      font-size: 34px;
      margin-bottom: 15px;
    }

    .hero p {
      max-width: 600px;
      margin: auto;
      color: #ddd;
    }

    .btn {
      display: inline-block;
      margin-top: 25px;
      padding: 14px 24px;
      background: #d4af37;
      color: #111;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
    }

    section {
      max-width: 900px;
      margin: auto;
      padding: 45px 20px;
    }

    section h2 {
      margin-bottom: 18px;
      font-size: 26px;
    }

    .card {
      background: white;
      padding: 25px;
      margin-top: 20px;
      border-radius: 12px;
      box-shadow: 0 3px 15px rgba(0,0,0,0.08);
    }

    .book {
      border-left: 5px solid #d4af37;
    }

    .book h3 {
      margin-bottom: 8px;
    }

    footer {
      background: #111;
      color: #aaa;
      text-align: center;
      padding: 30px 20px;
      margin-top: 30px;
    }

    footer strong {
      color: #d4af37;
    }
  </style>
</head>

<body>

<header>
  <h1>ManangaLivros</h1>
  <p>Conhecimento que abre novos caminhos</p>
</header>

<div class="hero">
  <h2>Ninguém Está Atrasado</h2>

  <p>
    Uma reflexão sobre tempo, propósito, recomeço e a capacidade
    de construir um novo caminho, independentemente do momento da vida.
  </p>

  <a class="btn" href="livro.pdf" target="_blank">
    📖 Ler o livro
  </a>
</div>

<section>
  <h2>Sobre o livro</h2>

  <div class="card">
    <p>
      <strong>Ninguém Está Atrasado</strong> nasceu para lembrar que
      cada pessoa possui uma trajetória própria. Comparar o nosso
      caminho com o dos outros pode fazer parecer que estamos atrasados,
      quando muitas vezes estamos apenas a construir algo diferente.
    </p>

    <br>

    <p>
      Este livro convida o leitor a olhar para o próprio tempo,
      transformar experiências em aprendizagem e continuar a avançar.
    </p>
  </div>
</section>

<section>
  <h2>Sobre o autor</h2>

  <div class="card">
    <h3>Faustino Mananga</h3>

    <p>
      Faustino Mananga é autor e criador de conteúdos voltados para
      desenvolvimento pessoal, trabalho, oportunidades, educação,
      tecnologia e construção de novos caminhos.
    </p>

    <br>

    <p>
      A sua produção literária procura transformar ideias em ferramentas
      práticas para leitores de Angola e de diferentes partes do mundo.
    </p>
  </div>
</section>

<section>
  <h2>ManangaLivros</h2>

  <div class="card">
    <p>
      A <strong>ManangaLivros</strong> é o espaço dedicado aos livros
      de Faustino Mananga e ao desenvolvimento de novos projetos
      editoriais.
    </p>

    <br>

    <p>
      Novos livros poderão ser adicionados futuramente a esta aplicação,
      criando uma biblioteca digital em constante crescimento.
    </p>
  </div>
</section>

<section>
  <h2>📚 Próximos livros</h2>

  <div class="card book">
    <h3>Em desenvolvimento</h3>
    <p>
      Novos títulos de Faustino Mananga serão apresentados aqui
      à medida que forem preparados para publicação.
    </p>
  </div>

  <div class="card book">
    <h3>Biblioteca ManangaLivros</h3>
    <p>
      Esta área será atualizada com os próximos lançamentos,
      versões digitais e outras publicações.
    </p>
  </div>
</section>

<section>
  <h2>📲 Partilhar</h2>

  <div class="card">
    <p>
      Partilhe esta aplicação com amigos e leitores.
    </p>

    <button class="btn" onclick="partilhar()">
      Partilhar aplicativo
    </button>
  </div>
</section>

<footer>
  <p>
    © 2026 <strong>ManangaLivros</strong>
  </p>

  <p>
    Faustino Mananga
  </p>
</footer>

<script>
  function partilhar() {
    if (navigator.share) {
      navigator.share({
        title: "Ninguém Está Atrasado",
        text: "Conheça o livro Ninguém Está Atrasado, de Faustino Mananga.",
        url: window.location.href
      });
    } else {
      alert("Copie o endereço desta página e partilhe com os seus amigos.");
    }
  }
</script>

</body>
</html>
