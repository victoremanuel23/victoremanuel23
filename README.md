<head>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@700&family=Poppins:wght@600&display=swap" rel="stylesheet">
  <style>
    body {
      background-color: #1e1e1e;
      color: #DCDCDC;
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    
    h1 {
      font-family: 'Poppins', sans-serif;
      font-size: 3.5rem;
      color: #FFFFFF;
      font-weight: 700;
      margin-top: 50px;
      letter-spacing: 2px;
    }

    p {
      font-size: 1.2rem;
      font-weight: 600;
      color: #DCDCDC;
      margin: 0 20px;
      line-height: 1.6;
    }

    a {
      text-decoration: none;
    }

    .social-links {
      display: flex;
      justify-content: center;
      gap: 15px;
      margin-top: 20px;
    }

    .social-links img {
      transition: transform 0.3s ease;
    }

    .social-links img:hover {
      transform: scale(1.1);
    }

    .badge {
      margin-top: 30px;
    }

    .skills-container {
      display: flex;
      justify-content: center;
      gap: 30px;
      margin-top: 50px;
    }

    .skills-container img {
      width: 50px;
      height: 50px;
      transition: transform 0.3s ease;
    }

    .skills-container img:hover {
      transform: scale(1.1);
    }

    .projects-table {
      width: 100%;
      max-width: 1200px;
      margin: 50px auto;
      border-collapse: collapse;
    }

    .projects-table th, .projects-table td {
      padding: 15px;
      text-align: center;
      border: 1px solid #333;
      color: #DCDCDC;
    }

    .projects-table th {
      background-color: #333;
    }

    .projects-table td {
      background-color: #2a2a2a;
    }

    .footer {
      margin-top: 50px;
      font-size: 0.9rem;
      color: #A9A9A9;
      font-family: 'Roboto', sans-serif;
      margin-bottom: 30px;
    }

    .footer i {
      font-style: italic;
    }
    
    .project-link {
      display: block;
      color: #00B0B9;
      font-weight: bold;
      text-decoration: none;
      margin-top: 5px;
    }

    .project-link:hover {
      text-decoration: underline;
    }
  </style>
</head>

<body>
  <h1>Vitor Emanuel</h1>

  <p>
    <b>Especialista em Quality Assurance | Desenvolvedor Front-End</b><br/>
    <i>Garantindo excelência no desenvolvimento e qualidade de software através de testes eficazes e automação.</i>
  </p>

  <div class="social-links">
    <a href="mailto:devprestacoes@gmail.com">
      <img src="https://img.shields.io/badge/Email-devprestacoes@gmail.com-FF3D00?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://github.com/victoremanuel23">
      <img src="https://img.shields.io/badge/GitHub-victoremanuel23-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
    <a href="https://www.linkedin.com/in/vitor-emanuel-006369361">
      <img src="https://img.shields.io/badge/LinkedIn-vitor--emanuel-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
  </div>

  <div class="badge">
    <img src="https://img.shields.io/badge/Quality%20Assurance-%E2%9C%93-4CAF50?style=for-the-badge" />
  </div>

  <p>
    Tenho 16 anos e sou um **Especialista em Quality Assurance (QA)** com um forte foco em **desenvolvimento front-end**. Meu objetivo é garantir a qualidade de produtos digitais através de testes rigorosos, tanto manuais quanto automatizados, com ênfase em **APIs**, **mobile**, e **performance**.
  </p>

  <div class="skills-container">
    <div>
      <img src="https://img.shields.io/badge/Cypress-4D61C1?style=for-the-badge&logo=cypress&logoColor=white" alt="Cypress"/>
      <p>Cypress</p>
    </div>
    <div>
      <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman"/>
      <p>Postman</p>
    </div>
    <div>
      <img src="https://img.shields.io/badge/Detox-00B0B9?style=for-the-badge&logo=detox&logoColor=white" alt="Detox"/>
      <p>Detox</p>
    </div>
    <div>
      <img src="https://img.shields.io/badge/JMeter-FB5B00?style=for-the-badge&logo=apache&logoColor=white" alt="JMeter"/>
      <p>JMeter</p>
    </div>
  </div>

  <table class="projects-table">
    <thead>
      <tr>
        <th>Projeto</th>
        <th>Descrição</th>
        <th>Tecnologias</th>
        <th>Link</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Automação com Cypress</td>
        <td>Automação de testes para aplicações web</td>
        <td>Cypress, JavaScript</td>
        <td><a href="https://github.com/victoremanuel23/testes-cypress" class="project-link" target="_blank">Ver Projeto</a></td>
      </tr>
      <tr>
        <td>Testes de API com Postman</td>
        <td>Testes de APIs usando Postman</td>
        <td>Postman, Newman</td>
        <td><a href="https://github.com/victoremanuel23/api-postman" class="project-link" target="_blank">Ver Projeto</a></td>
      </tr>
      <tr>
        <td>Testes Mobile com Detox</td>
        <td>Testes de apps móveis com Detox</td>
        <td>Detox, JavaScript</td>
        <td><a href="https://github.com/victoremanuel23/testes-mobile-detox" class="project-link" target="_blank">Ver Projeto</a></td>
      </tr>
    </tbody>
  </table>

  <div class="footer">
    <p>
      <i>“Qualidade nunca é um acidente; é sempre o resultado de um esforço inteligente.” – John Ruskin</i>
    </p>
  </div>
</body>
