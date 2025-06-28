---
layout: default
title: Projetos
---

<div class="section-header">Projetos e Sistemas</div>

<div class="experiencia-container">

  <!-- Projeto Esperança -->
  <div class="experiencia-card">
    <div class="experiencia-titulo">
      <h3>Projeto Esperança – Sistema de Gestão de Voluntariado</h3>
      <p><strong>Stack:</strong> HTML, CSS, JavaScript, Node.js, Express, PostgreSQL</p>
    </div>
    <div class="experiencia-conteudo">
      <strong>Descrição:</strong> Sistema completo para cadastro e gestão de voluntários e beneficiários de um programa social. Desenvolvido para ajudar uma iniciativa real que apoia pessoas em situação de rua e famílias de catadores de lixo.
      <details>
        <summary class="ver-mais">Ver mais detalhes</summary>
        <h4>Funcionalidades</h4>
        <ul>
          <li>🧍 <strong>Cadastro de Pessoas, Famílias, Visitas, Doações, Voluntários, Presenças e Atividades:</strong> Registre todos os dados relevantes de forma organizada e interligada, com preenchimento automático e integração entre módulos.</li>
          <li>📋 <strong>Perfis Detalhados:</strong> Histórico completo por pessoa: visitas, doações, presenças e atividades.</li>
          <li>📂 <strong>Exportação para Excel:</strong> Exporta tabelas com filtros aplicados e colunas visíveis.</li>
          <li>🔎 <strong>Busca Inteligente:</strong> Campos com sugestão automática e preenchimento dinâmico de endereço.</li>
          <li>🌓 <strong>Modo Claro/Escuro + Acessibilidade:</strong> Suporte a contraste e botão para aumentar a fonte.</li>
        </ul>
        <h4>Tecnologias Utilizadas</h4>
        <ul>
          <li>🔙 <strong>Backend:</strong> Python, Flask, SQLite, Jinja2.</li>
          <li>🔝 <strong>Frontend:</strong> HTML, CSS, JavaScript, com foco em usabilidade e acessibilidade.</li>
        </ul>
        <h4>Organização e Distribuição</h4>
        <ul>
          <li>🗃️ <strong>Modularização:</strong> Blueprints por funcionalidade (pessoa, visita, doação, etc.).</li>
          <li>📦 <strong>Distribuição Offline:</strong> Executável para Windows com banco e fotos salvos localmente e backups automáticos.</li>
        </ul>
        <h4>Imagens</h4>
        <div class="projeto-imagens">
          <img src="{{ '/assets/img/pd2.png' | relative_url }}" alt="Cadastro de Pessoas" onclick="expandirImagem(this)">
          <img src="{{ '/assets/img/pd3.png' | relative_url }}" alt="Cadastro de Famílias" onclick="expandirImagem(this)">
          <img src="{{ '/assets/img/pd4.png' | relative_url }}" alt="Lista" onclick="expandirImagem(this)">
          <img src="{{ '/assets/img/pd5.png' | relative_url }}" alt="Visitas Domiciliares" onclick="expandirImagem(this)">
          <img src="{{ '/assets/img/pd6.png' | relative_url }}" alt="Doações" onclick="expandirImagem(this)">
        </div>
        <p style="margin-top: 16px;">
          👉 <a href="https://github.com/Marcelo0070/ProjetoDignidade" target="_blank" rel="noopener noreferrer"><strong>Acesse o projeto completo aqui</strong></a>
        </p>
      </details>
    </div>
  </div>

  <!-- Currículo com API -->
  <div class="experiencia-card">
    <div class="experiencia-titulo">
      <h3>Currículo com API (Node.js)</h3>
      <p><strong>Stack:</strong> Node.js, Express, PostgreSQL</p>
    </div>
    <div class="experiencia-conteudo">
      <strong>Descrição:</strong> Aplicação backend para expor dados de currículo por meio de APIs REST. Projeto voltado ao estudo de estruturação de rotas, modelagem de banco e consumo de dados via frontend.
      <details>
        <summary class="ver-mais">Ver mais detalhes</summary>
        <h4>Funcionalidades</h4>
        <ul>
          <li>🧾 <strong>CRUD de Experiências:</strong> Adicione, edite e exclua experiências diretamente no card, com atualização em tempo real.</li>
          <li>📆 <strong>Seletores personalizados de Mês e Ano:</strong> Interface intuitiva para inserir datas com autocomplete e rolagem inteligente.</li>
          <li>💾 <strong>Salvamento Temporário:</strong> Armazena dados no localStorage enquanto o usuário preenche o formulário.</li>
          <li>🌓 <strong>Modo Claro/Escuro:</strong> Interface adaptável com preferências salvas no navegador.</li>
          <li>🖨️ <strong>Exportação para PDF:</strong> Geração de currículo em PDF a partir dos dados preenchidos.</li>
        </ul>
        <h4>Tecnologias Utilizadas</h4>
        <ul>
          <li>🔙 <strong>Backend:</strong> Node.js, Express, PostgreSQL, Knex.</li>
          <li>🔝 <strong>Frontend:</strong> React (Vite), CSS modularizado, localStorage, fetch API.</li>
        </ul>
        <h4>Organização e Modularidade</h4>
        <ul>
          <li>📁 <strong>Separação por camadas:</strong> Controllers, Models, Routes e Services organizados de forma clara e reutilizável.</li>
          <li>💡 <strong>Boas práticas de UX:</strong> Feedback visual nos campos, inputs inteligentes e layout responsivo.</li>
        </ul>
        <p style="margin-top: 16px;">
          👉 <a href="https://github.com/Marcelo0070/criador_curriculo" target="_blank" rel="noopener noreferrer"><strong>Acesse o repositório do projeto</strong></a>
        </p>
      </details>
    </div>
  </div>

  <!-- Jogo Visual -->
  <div class="experiencia-card">
    <div class="experiencia-titulo">
      <h3>Jogo Visual com Parallax</h3>
      <p><strong>Stack:</strong> Ren'Py (Python)</p>
    </div>
    <div class="experiencia-conteudo">
      <strong>Descrição:</strong> Projeto em andamento de uma visual novel interativa com efeitos de parallax. Explora narrativa, lógica de eventos e construção de cenas dinâmicas com foco em storytelling e experiência de usuário.
      <details>
        <summary class="ver-mais">Ver mais detalhes</summary>
        <h4>Funcionalidades e Destaques</h4>
        <ul>
          <li>🎭 <strong>Roteiro Interativo:</strong> Diálogos com múltiplas escolhas, narrativa com loops, eventos condicionais e evolução de relacionamento entre personagens.</li>
          <li>🌌 <strong>Parallax Dinâmico:</strong> Movimento das camadas de fundo em resposta ao mouse para maior imersão.</li>
          <li>🖼️ <strong>Visual Personalizado:</strong> Imagens desenhadas sob medida, com sobreposição de camadas e transparência para simular profundidade e atmosfera.</li>
          <li>🔄 <strong>Sistema de Variáveis e Flags:</strong> Ações do jogador afetam diálogos futuros, desbloqueiam cenas ou alteram comportamentos dos personagens.</li>
          <li>🖱️ <strong>Cursor Customizado:</strong> Interface com elementos visuais adaptados ao clima do jogo.</li>
        </ul>
        <h4>Objetivo do Projeto</h4>
        <p>
          Explorar storytelling emocional com estética sombria e imersiva, integrando arte, roteiro e programação. O projeto visa desenvolver uma experiência envolvente e reflexiva sobre laços afetivos, identidade e medo.
        </p>
        <h4>Imagens</h4>
        <div class="projeto-imagens">
          <img src="{{ '/assets/img/ani1.gif' | relative_url }}" alt="Cena da Cabana" onclick="expandirImagem(this)">
          <img src="{{ '/assets/img/ani2.gif' | relative_url }}" alt="Personagem Mãe com Lenço" onclick="expandirImagem(this)">
          <img src="{{ '/assets/img/ani3.png' | relative_url }}" alt="Efeito Parallax" onclick="expandirImagem(this)">
        </div>
        <p style="margin-top: 16px;">
          👉 <a href="https://github.com/Marcelo0070/jogo_visual_base" target="_blank" rel="noopener noreferrer"><strong>Acompanhe o desenvolvimento no GitHub</strong></a>
        </p>
      </details>
    </div>
  </div>

</div>

<!-- Modal para Imagem Expandida -->
<div id="imagem-modal" onclick="fecharImagem()">
  <img id="imagem-ampliada" src="" alt="">
</div>

<script>
  function expandirImagem(img) {
    const modal = document.getElementById("imagem-modal");
    const ampliada = document.getElementById("imagem-ampliada");
    ampliada.src = img.src;
    modal.style.display = "flex";
  }

  function fecharImagem() {
    document.getElementById("imagem-modal").style.display = "none";
  }
</script>
