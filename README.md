<!-- HERO ESPACIAL ------------------------------------------------------>

<div align="center" style="
  background: radial-gradient(circle at top, #1e293b 0, #020617 55%, #000000 100%);
  padding: 2.5rem 1rem 3rem;
  border-radius: 1.5rem;
  border: 1px solid rgba(148, 163, 184, 0.4);
  box-shadow: 0 0 40px rgba(59, 130, 246, 0.5);
  position: relative;
  overflow: hidden;
">

  <!-- Meteoros decorativos -->
  <div style="
    position: absolute;
    top: 10%;
    left: -5%;
    font-size: 2rem;
    opacity: 0.4;
  ">☄️</div>

  <div style="
    position: absolute;
    top: 20%;
    right: -3%;
    font-size: 2.3rem;
    opacity: 0.5;
  ">☄️</div>

  <div style="
    position: absolute;
    bottom: 12%;
    left: 10%;
    font-size: 1.7rem;
    opacity: 0.35;
  ">✨</div>

  <!-- Astronauta (substitua o src pela sua imagem) -->
  <img 
    src="./assets/astronaut-galaxy.png" 
    alt="Astronauta flutuando no espaço com meteoros"
    width="220"
    style="border-radius: 999px; border: 2px solid rgba(148, 163, 184, 0.7); margin-bottom: 1rem; background: radial-gradient(circle, #0f172a 0, #020617 100%);"
  />

  <h1 style="color: #e5e7eb; font-size: 2.3rem; margin: 0.2rem 0;">
    👨‍🚀 Yago Cerqueira Regis
  </h1>

  <p style="color: #9ca3af; font-size: 0.95rem; max-width: 460px; margin: 0.5rem auto 0;">
    Desenvolvedor Full-Stack focado em experiências web modernas.<br/>
    React • TypeScript • Ruby on Rails • Node.js • PostgreSQL
  </p>

  <p style="color: #a855f7; font-size: 0.85rem; margin-top: 0.9rem;">
    <strong>“Coding from planet Terra, deploying para a galáxia inteira.”</strong>
  </p>

</div>

<br/>

<!-- SOBRE MIM --------------------------------------------------------->

<h2 align="center">✨ Sobre mim</h2>

<p align="center">
  💼 Desenvolvedor Full-Stack construindo aplicações web completas, do banco de dados ao front.<br/>
  🚀 Gosto de focar em performance, acessibilidade e código limpo.<br/>
  🌌 Apaixonado por interfaces com personalidade, animações sutis e temas espaciais.
</p>

<br/>

<!-- GALÁXIA DAS STACKS (GRÁFICO) -------------------------------------->

<h2 align="center">🪐 Galáxia das minhas stacks</h2>

<p align="center">
  Cada planeta representa uma tecnologia que eu uso no dia a dia.<br/>
  Quanto mais próximo do núcleo, mais domínio/prática no meu fluxo atual.
</p>

<div align="center">

<!-- SVG GALÁXIA ANIMADA -->
<svg width="420" height="420" viewBox="0 0 420 420" xmlns="http://www.w3.org/2000/svg">

  <!-- Fundo -->
  <defs>
    <radialGradient id="spaceGradient" cx="50%" cy="40%" r="70%">
      <stop offset="0%" stop-color="#1f2937"/>
      <stop offset="45%" stop-color="#020617"/>
      <stop offset="100%" stop-color="#000000"/>
    </radialGradient>
  </defs>

  <rect x="0" y="0" width="420" height="420" fill="url(#spaceGradient)" rx="24" />

  <!-- Estrelinhas -->
  <g fill="#e5e7eb" opacity="0.7">
    <circle cx="60" cy="80" r="1.2"/>
    <circle cx="120" cy="40" r="1.5"/>
    <circle cx="340" cy="70" r="1.4"/>
    <circle cx="380" cy="140" r="1.1"/>
    <circle cx="300" cy="40" r="1.3"/>
    <circle cx="80" cy="320" r="1.2"/>
    <circle cx="360" cy="300" r="1.6"/>
    <circle cx="210" cy="380" r="1.2"/>
  </g>

  <!-- Núcleo -->
  <g transform="translate(210,210)">
    <circle r="45" fill="#0f172a" stroke="#38bdf8" stroke-width="2.5"/>
    <text x="0" y="-4" text-anchor="middle" font-size="11" fill="#e5e7eb" font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif">
      Full-Stack
    </text>
    <text x="0" y="12" text-anchor="middle" font-size="9" fill="#9ca3af" font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif">
      Dev
    </text>
  </g>

  <!-- Órbitas -->
  <g transform="translate(210,210)" stroke="#1f2937" stroke-width="1.2" stroke-dasharray="4 6">
    <circle r="85" fill="none"/>
    <circle r="125" fill="none"/>
    <circle r="165" fill="none"/>
  </g>

  <!-- PLANETAS / STACKS -->
  <!-- Órbita 1 - Domínio alto -->
  <g transform="translate(210,210)">
    <g>
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="40s" repeatCount="indefinite"/>
      <!-- React -->
      <g transform="translate(85,0)">
        <circle r="13" fill="#22c55e" />
        <text x="0" y="3" text-anchor="middle" font-size="8" fill="#0b1120" font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif">
          React
        </text>
      </g>

      <!-- TypeScript -->
      <g transform="rotate(120) translate(85,0)">
        <circle r="13" fill="#3b82f6" />
        <text x="0" y="3" text-anchor="middle" font-size="7.5" fill="#eff6ff" font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif">
          TS
        </text>
      </g>

      <!-- Ruby on Rails -->
      <g transform="rotate(240) translate(85,0)">
        <circle r="13" fill="#ef4444" />
        <text x="0" y="3" text-anchor="middle" font-size="7.2" fill="#fee2e2" font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif">
          Rails
        </text>
      </g>
    </g>
  </g>

  <!-- Órbita 2 - Muito usado -->
  <g transform="translate(210,210)">
    <g>
      <animateTransform attributeName="transform" type="rotate" from="360" to="0" dur="55s" repeatCount="indefinite"/>
      <!-- Node.js -->
      <g transform="translate(0,125)">
        <circle r="12" fill="#16a34a" />
        <text x="0" y="3" text-anchor="middle" font-size="7.2" fill="#ecfdf5" font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif">
          Node
        </text>
      </g>

      <!-- PostgreSQL -->
      <g transform="rotate(72) translate(0,125)">
        <circle r="12" fill="#0ea5e9" />
        <text x="0" y="3" text-anchor="middle" font-size="7" fill="#e0f2fe" font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif">
          Postgres
        </text>
      </g>

      <!-- Tailwind -->
      <g transform="rotate(144) translate(0,125)">
        <circle r="12" fill="#22d3ee" />
        <text x="0" y="3" text-anchor="middle" font-size="7" fill="#0f172a" font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif">
          Tailwind
        </text>
      </g>

      <!-- HTML/CSS -->
      <g transform="rotate(216) translate(0,125)">
        <circle r="12" fill="#f97316" />
        <text x="0" y="3" text-anchor="middle" font-size="7" fill="#0b1120" font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif">
          HTML/CSS
        </text>
      </g>

      <!-- Git/GitHub -->
      <g transform="rotate(288) translate(0,125)">
        <circle r="12" fill="#facc15" />
        <text x="0" y="3" text-anchor="middle" font-size="7" fill="#0b1120" font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif">
          Git
        </text>
      </g>
    </g>
  </g>

  <!-- Órbita 3 - Explorando / ampliando -->
  <g transform="translate(210,210)">
    <g opacity="0.95">
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="80s" repeatCount="indefinite"/>
      <!-- Testing -->
      <g transform="translate(165,0)">
        <circle r="10" fill="#a855f7" />
        <text x="0" y="3" text-anchor="middle" font-size="6.8" fill="#fdf2ff" font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif">
          Tests
        </text>
      </g>

      <!-- Docker -->
      <g transform="rotate(90) translate(165,0)">
        <circle r="10" fill="#38bdf8" />
        <text x="0" y="3" text-anchor="middle" font-size="6.8" fill="#0f172a" font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif">
          Docker
        </text>
      </g>

      <!-- DevOps / CI -->
      <g transform="rotate(180) translate(165,0)">
        <circle r="10" fill="#f97316" />
        <text x="0" y="3" text-anchor="middle" font-size="6.5" fill="#0f172a" font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif">
          CI/CD
        </text>
      </g>

      <!-- A11y / UX -->
      <g transform="rotate(270) translate(165,0)">
        <circle r="10" fill="#22c55e" />
        <text x="0" y="3" text-anchor="middle" font-size="6.5" fill="#022c22" font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif">
          A11y
        </text>
      </g>
    </g>
  </g>

</svg>

</div>

<br/>

<!-- LEGENDA DOS NÍVEIS ----------------------------------------------->

<div align="center">

| Órbita | Nível de domínio | Tecnologias |
|-------|-------------------|-------------|
| Núcleo | 🚀 Principal | Full-Stack (integração front + back + DB) |
| 1ª Órbita | 🔥 Muito forte | React, TypeScript, Ruby on Rails |
| 2ª Órbita | 💪 Uso constante | Node.js, PostgreSQL, Tailwind, HTML/CSS, Git |
| 3ª Órbita | 🌱 Em expansão | Testes, Docker, CI/CD, Acessibilidade/UX |

</div>

<br/>

<!-- PROJETOS EM DESTAQUE --------------------------------------------->

<h2 align="center">🚀 Projetos em destaque</h2>

<div align="center">

| Projeto | Descrição | Tecnologias |
|--------|-----------|-------------|
| [Portfólio Pessoal](https://yagocerqueiraregis.netlify.app/) | Página para apresentar meus projetos e contato | React, Vite, Tailwind |
| [Sistema de Aluguel de Jogos](#) | Plataforma para gerenciar aluguel de jogos de tabuleiro | Ruby on Rails, PostgreSQL |
| [Dashboard de Análise de Dados](#) | Dashboard interativa com gráficos e filtros | React, TypeScript, Node.js |

</div>

<br/>

<!-- CONTATO ----------------------------------------------------------->

<h2 align="center">📫 Contato</h2>

<p align="center">
  🌐 <a href="https://yagocerqueiraregis.netlify.app/" target="_blank">Portfólio</a> •
  💼 <a href="https://www.linkedin.com/in/yago-cerqueira-regis/" target="_blank">LinkedIn</a> •
  📧 <a href="mailto:seu-email-aqui@exemplo.com">seu-email-aqui@exemplo.com</a>
</p>
