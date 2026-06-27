<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Btissam Arehal - Data Scientist & ML Engineer</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: #0a0e27;
      color: #e8eaf6;
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      line-height: 1.8;
      font-size: 15px;
    }

    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 3rem 2rem;
    }

    .header {
      margin-bottom: 3rem;
      border-bottom: 1px solid #1e293b;
      padding-bottom: 2rem;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
      background: linear-gradient(135deg, #00d4ff, #00b4d8);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }

    .tagline {
      font-size: 1.1rem;
      color: #b0bec5;
      margin-bottom: 1.5rem;
    }

    .section {
      margin-bottom: 3rem;
    }

    .section-title {
      font-size: 1.3rem;
      color: #00d4ff;
      margin-bottom: 1.5rem;
      font-weight: 700;
    }

    p {
      color: #b0bec5;
      margin-bottom: 1rem;
      line-height: 1.8;
    }

    .highlight {
      color: #00d4ff;
      font-weight: 600;
    }

    .interests-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1.5rem;
      margin: 1.5rem 0;
    }

    .interest-item {
      background: rgba(26, 31, 58, 0.5);
      border: 1px solid #1e293b;
      padding: 1.5rem;
      border-radius: 8px;
      transition: all 0.3s ease;
    }

    .interest-item:hover {
      border-color: #00d4ff;
      background: rgba(26, 31, 58, 0.8);
      transform: translateY(-2px);
    }

    .interest-title {
      color: #00d4ff;
      font-weight: 700;
      margin-bottom: 0.5rem;
    }

    .interest-desc {
      font-size: 0.9rem;
      color: #b0bec5;
    }

    .quote {
      border-left: 3px solid #00d4ff;
      padding: 1.5rem;
      margin: 2rem 0;
      background: rgba(0, 212, 255, 0.05);
      border-radius: 4px;
      font-style: italic;
      color: #b0bec5;
    }

    .skills-tags {
      display: flex;
      flex-wrap: wrap;
      gap: 0.75rem;
      margin: 1.5rem 0;
    }

    .tag {
      background: rgba(0, 212, 255, 0.1);
      border: 1px solid rgba(0, 212, 255, 0.3);
      padding: 0.5rem 1rem;
      border-radius: 20px;
      font-size: 0.85rem;
      color: #00d4ff;
    }

    .divider {
      height: 1px;
      background: #1e293b;
      margin: 2rem 0;
    }

    code {
      background: rgba(26, 31, 58, 0.5);
      padding: 0.25rem 0.5rem;
      border-radius: 4px;
      color: #00d4ff;
      font-family: 'SF Mono', monospace;
      font-size: 0.9rem;
    }

    .cta {
      margin-top: 3rem;
      padding: 2rem;
      background: linear-gradient(135deg, rgba(0, 212, 255, 0.1), rgba(0, 180, 216, 0.05));
      border: 1px solid #1e293b;
      border-radius: 8px;
      text-align: center;
    }

    .cta-text {
      margin-bottom: 1.5rem;
      color: #b0bec5;
    }

    .cta-link {
      color: #00d4ff;
      text-decoration: none;
      font-weight: 600;
      transition: all 0.3s ease;
    }

    .cta-link:hover {
      text-decoration: underline;
    }

    @media (max-width: 600px) {
      h1 { font-size: 1.8rem; }
      .container { padding: 2rem 1rem; }
      .interests-list { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      <h1>Btissam Arehal</h1>
      <p class="tagline">Data Scientist | ML Engineer | Curious about systems that learn</p>
    </div>

    <div class="section">
      <div class="section-title">👋 About Me</div>
      <p>
        I'm a <span class="highlight">Master's student in Data Science</span> at ENSET Tétouan, passionate about transforming raw data into actionable intelligence. I believe the best solutions come from understanding both the mathematics behind algorithms and the business problems they solve.
      </p>
  
    </div>

    <div class="section">
      <div class="section-title">🧠 What Fascinates Me</div>
      
      <div class="interests-list">
        <div class="interest-item">
          <div class="interest-title">Predictive Systems</div>
          <div class="interest-desc">Anticipating the future from patterns in data. Time series, anomaly detection, maintenance prediction.</div>
        </div>
        
        <div class="interest-item">
          <div class="interest-title">Deep Learning</div>
          <div class="interest-desc">Teaching machines to see, understand, and reason. CNNs, RNNs, Transformers, 3D vision.</div>
        </div>
        
        <div class="interest-item">
          <div class="interest-title">Production ML</div>
          <div class="interest-desc">Moving beyond notebooks. APIs, dashboards, monitoring, real-time inference at scale.</div>
        </div>
        
        <div class="interest-item">
          <div class="interest-title">Data Engineering</div>
          <div class="interest-desc">Building pipelines, ETL workflows, and data infrastructure that scales.</div>
        </div>
      </div>

      <div class="quote">
        "A model that doesn't run in production is just a math exercise."
      </div>
    </div>

    <div class="section">
      <div class="section-title">🛠 How I Work</div>
      <p>
        <span class="highlight">Full-stack approach:</span> I don't believe in handoffs. I take ownership from data exploration to model deployment, including frontend dashboards and backend APIs.
      </p>
      <p>
        <span class="highlight">Rigorous:</span> Testing, validation, and metrics matter. I evaluate models beyond accuracy—looking at RMSE, precision-recall tradeoffs, business impact.
      </p>
      <p>
        <span class="highlight">Curious:</span> I constantly explore new architectures, techniques, and frameworks. Latest in LLMs, time-series forecasting, graph neural networks.
      </p>
    </div>

    <div class="section">
      <div class="section-title">📚 Primary Interests</div>
      <div class="skills-tags">
        <span class="tag">Time Series Analysis</span>
        <span class="tag">Deep Learning</span>
        <span class="tag">Anomaly Detection</span>
        <span class="tag">Forecasting</span>
        <span class="tag">3D Vision</span>
        <span class="tag">Production ML</span>
        <span class="tag">Data Pipelines</span>
        <span class="tag">LLMs & RAG</span>
      </div>
    </div>

    <div class="section">
      <div class="section-title">🚀 Currently Exploring</div>
      <p>
        Building intelligent systems that <span class="highlight">automate decision-making</span> in complex domains. Right now focused on:
      </p>
      <p>
        → Advanced time-series architectures (Temporal Fusion Transformers, N-BEATS)<br>
        → LLM integration with retrieval systems for domain-specific AI<br>
        → Deploying models that <span class="highlight">learn from production data</span> in real-time
      </p>
    </div>

    <div class="section">
      <div class="section-title">🎯 What I'm Looking For</div>
      <p>
        A role where I can build AI systems that <span class="highlight">actually matter</span>. Not just optimizing metrics, but solving real business problems with measurable impact.
      </p>
      <p>
        I want to work with teams that value <span class="highlight">shipping products</span>, not just publishing papers. Where the bar is high, the problems are hard, and the learning is constant.
      </p>
    </div>

    <div class="divider"></div>

    <div class="cta">
      <div class="cta-text">
        Interested in collaborating or discussing data science? Let's connect.
      </div>
      <a href="mailto:arehalbtissam7@email.com" class="cta-link">📧 Email me</a>
      <span style="color: #1e293b; margin: 0 1rem;">•</span>
      <a href="https://github.com/btissam75/btissam75" class="cta-link">🐙 GitHub</a>
      <span style="color: #1e293b; margin: 0 1rem;">•</span>
      <a href="https://www.linkedin.com/in/btissam-arehal-a95ab9266/">💼 LinkedIn</a>
    </div>
  </div>
</body>
</html>
