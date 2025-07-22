<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Clínica Ágora | Psicologia em Caxias do Sul</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f8f0f5;
      color: #333;
    }

    header {
      background-color: #c19e9a;
      padding: 30px;
      text-align: center;
      color: white;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
    }

    nav {
      background-color: #a98387;
      display: flex;
      justify-content: center;
      gap: 40px;
      padding: 10px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 40px;
      text-align: center;
    }

    .cards {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
    }

    .card {
      background-color: #fff;
      padding: 25px;
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      width: 280px;
    }

    footer {
      background-color: #c19e9a;
      color: white;
      text-align: center;
      padding: 20px;
    }

    .btn {
      background-color: #a98387;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 10px;
      font-size: 1em;
      cursor: pointer;
    }

    .btn:hover {
      background-color: #8d6d6f;
    }
  </style>
</head>
<body>

  <header>
    <h1>Clínica Ágora</h1>
    <p>Psicologia e Bem-Estar em Caxias do Sul</p>
  </header>

  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#servicos">Serviços</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="sobre">
    <h2>Sobre a Clínica</h2>
    <p>Na Clínica Ágora, oferecemos acolhimento, escuta qualificada e acompanhamento psicológico para todas as fases da vida. Estamos localizados no coração de Caxias do Sul, com uma equipe comprometida com o seu bem-estar emocional.</p>
  </section>

  <section id="servicos">
    <h2>Nossos Serviços</h2>
    <div class="cards">
      <div class="card">
        <h3>Psicoterapia Individual</h3>
        <p>Atendimento personalizado para adultos e adolescentes.</p>
      </div>
      <div class="card">
        <h3>Atendimento Infantil</h3>
        <p>Espaço lúdico e terapêutico para crianças com acompanhamento familiar.</p>
      </div>
      <div class="card">
        <h3>Orientação de Pais</h3>
        <p>Ajuda especializada para lidar com os desafios da parentalidade.</p>
      </div>
    </div>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <p><strong>Endereço:</strong> Rua Treze de Maio, 583 - Sala Térrea 3, Caxias do Sul - RS</p>
    <p><strong>WhatsApp:</strong> <a href="https://wa.me/5554991698867" target="_blank">(54) 99169-8867</a></p>
    <p><strong>Email:</strong> agoraclin@gmail.com</p>
    <br>
    <button class="btn" onclick="window.location.href='https://wa.me/5554991698867'">Agendar Consulta</button>
  </section>

  <footer>
    <p>© 2025 Clínica Ágora - Todos os direitos reservados</p>
  </footer>

</body>
</html>

