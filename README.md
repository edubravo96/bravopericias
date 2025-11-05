<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bravo Perícias | Eduardo Bravo</title>

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />

  <style>
    html {
      scroll-behavior: smooth;
    }
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      line-height: 1.6;
      background-color: #fff;
      color: #000;
      transition: background-color 0.3s, color 0.3s;
    }
    body.dark-mode {
      background-color: #121212;
      color: #f0f0f0;
    }
    section {
      margin-bottom: 40px;
    }
    h2 {
      color: #003366;
    }
    ul {
      list-style-type: disc;
      padding-left: 20px;
    }
    a {
      color: #0066cc;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      margin-right: 15px;
      font-weight: bold;
    }
  </style>
</head>

<body>
  <header>
    <h1>BRAVO PERÍCIAS</h1>
    <h2>Eduardo Bravo</h2>
    <p><em>Perito Judicial Financeiro / Assistência Técnica | Administrador CRA-SP 093563</em></p>
    <p><strong>Atuação técnica precisa e imparcial em processos judiciais. Especialista em perícias financeiras.</strong></p>
    <nav>
      <a href="#servicos">📄 Ver Serviços</a>
      <a href="#contato">📧 Fale Comigo</a>
    </nav>
  </header>

  <main>
    <section id="sobre">
      <h2>Sobre</h2>
      <p>
        Sou Administrador com registro ativo no CRA-SP e atuo como Perito Judicial Financeiro e Assistente Técnico,
        auxiliando o Poder Judiciário, advogados e empresas na análise técnica de questões financeiras.
      </p>
      <ul>
        <li><strong>Formação:</strong> Bacharel em Administração</li>
        <li><strong>Registro:</strong> CRA-SP nº 093563</li>
        <li><strong>Cadastro:</strong> Perito no TJSP</li>
        <li><strong>Atuação:</strong> Todo o território nacional (online)</li>
      </ul>
    </section>

    <section id="servicos">
      <h2>Serviços</h2>
      <ul>
        <li>Análise e contestação de laudos periciais</li>
        <li>Emissão de laudo/parecer técnico</li>
        <li>Apoio técnico a advogados em todas as fases do processo</li>
      </ul>
    </section>

    <section id="areas">
      <h2>Áreas de Atuação</h2>
      <p>Perícia e cálculos financeiros</p>
    </section>

    <section id="contato">
      <h2>Contato</h2>
      <ul>
        <li><strong>E-mail:</strong> <a href="mailto:eduardo@bravopericias.com.br">eduardo@bravopericias.com.br</a></li>
        <li><strong>WhatsApp:</strong> <a href="https://wa.me/5518991298238?text=Olá%20Eduardo,%20gostaria%20de%20falar%20sobre%20perícia%20financeira" target="_blank">(18) 99129-8238</a></li>
        <li><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/paulo-eduardo-dias-bravo-1aaa71243" target="_blank">Perfil</a></li>
        <li><strong>Atendimento:</strong> Todo o Brasil (online e presencial sob agendamento)</li>
      </ul>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Bravo Perícias | Todos os direitos reservados</p>
  </footer>

  <!-- Botão de alternância de modo escuro -->
  <button id="toggle-dark" title="Alternar modo"
    style="position:fixed;top:20px;right:20px;padding:10px;border:none;border-radius:50%;background:#003366;color:#fff;cursor:pointer;z-index:1000;">
    <i class="fa-solid fa-moon"></i>
  </button>

  <!-- Botão flutuante do WhatsApp -->
  <a href="https://wa.me/5518991298238?text=Olá%20Eduardo,%20gostaria%20de%20falar%20sobre%20perícia%20financeira"
     target="_blank" title="Fale pelo WhatsApp"
     style="position:fixed;bottom:20px;right:20px;background:#25D366;color:#fff;padding:15px;border-radius:50%;box-shadow:0 2px 6px rgba(0,0,0,0.3);z-index:1000;">
    <i class="fa-brands fa-whatsapp fa-xl"></i>
  </a>

  <script>
    const toggleBtn = document.getElementById('toggle-dark');
    toggleBtn.addEventListener('click', () => {
      document.body.classList.toggle('dark-mode');
      toggleBtn.innerHTML = document.body.classList.contains('dark-mode')
        ? '<i class="fa-solid fa-sun"></i>'
        : '<i class="fa-solid fa-moon"></i>';
    });
  </script>
</body>
</html>
