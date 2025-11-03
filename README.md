<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f7fa;
      color: #333;
      text-align: center;
      padding: 2rem;
    }
    header {
      margin-bottom: 2rem;
    }
    .projects {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1.5rem;
    }
    .project {
      background: white;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      padding: 1rem;
      width: 280px;
      transition: transform 0.2s;
    }
    .project:hover {
      transform: translateY(-5px);
    }
    a {
      text-decoration: none;
      color: #007acc;
    }
  </style>
</head>
<body>
  <header>
    <h1>👋 Hi, I'm Giannis - Java Software Developer</h1>
    <p>Software Developer specializing in Java, Quarkus & JSF</p>
  </header>

   <section id="technologies">
    <h2>Technologies & Frameworks</h2>
    <div class="tech-list">
      <div class="tech">Java</div>
      <div class="tech">C#</div>
      <div class="tech">Quarkus</div>
      <div class="tech">JSF (PrimeFaces)</div>
      <div class="tech">Keycloak</div>
      <div class="tech">Hibernate / JPA</div>
      <div class="tech">Flyway</div>
      <div class="tech">MSSQL / PostgreSQL</div>
      <div class="tech">Docker</div>
      <div class="tech">Apache Camel</div>
      <div class="tech">Cloud Computing - AWS</div>
    </div>
  </section>

  <section class="projects">
    <div class="project">
      <h2>RiskAvert</h2>
      <p>RiskAvert is a on-premises, microservices product.
      RiskAvert is the robust Risk & Compliance management platform that assists Financial Institutions to gather and reconcile data, calculate, aggregate and report regulatory credit, market, operational and concentration risk in a natively integrated, yet modular environment.
The platform covers all approaches for Operational, Market and Credit Risk Calculation allowing the Bank to evolve from a standardised approach towards the IRB approaches. The solution also supports XBRL validation and conversion functions for multiple taxonomies. Its comprehensive cube-based MIS reporting engine fully supports Market disclosure requirements, while supervisory review is covered through a holistic stress-testing framework, as well as extensive concentration risk measures and reporting.</p>
    </div>
    <div class="project">
      <h2>Operational Risk Losses</h2>
      <p>Operational Risk Losses is a java based monolith application that acts as a reporting system regarding damages for banks</p>
    </div>

  </section>
</body>
</html>
