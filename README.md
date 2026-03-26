
<style>
  .readme-wrap { font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; max-width: 700px; padding: 1.5rem 0; }
  .header-name { font-size: 26px; font-weight: 700; margin: 0 0 4px; color: var(--color-text-primary); }
  .header-title { font-size: 14px; color: var(--color-text-secondary); margin: 0 0 12px; }
  .badges { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 1.5rem; }
  .badge { display: inline-flex; align-items: center; gap: 6px; background: var(--color-background-secondary); border: 0.5px solid var(--color-border-tertiary); border-radius: 20px; padding: 4px 12px; font-size: 12px; color: var(--color-text-secondary); }
  .badge-dot { width: 8px; height: 8px; border-radius: 50%; }
  .section-label { font-size: 11px; font-weight: 500; letter-spacing: 0.08em; text-transform: uppercase; color: var(--color-text-tertiary); margin: 1.5rem 0 0.75rem; border-bottom: 0.5px solid var(--color-border-tertiary); padding-bottom: 6px; }
  .bio { font-size: 14px; color: var(--color-text-secondary); line-height: 1.7; margin-bottom: 1.5rem; border-left: 2px solid #7F77DD; padding-left: 12px; }
  .project-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(0, 1fr)); gap: 10px; margin-bottom: 1.5rem; }
  .proj-card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: 10px; padding: 14px; }
  .proj-title { font-size: 13px; font-weight: 500; color: #378ADD; margin: 0 0 4px; }
  .proj-desc { font-size: 12px; color: var(--color-text-secondary); margin: 0 0 10px; line-height: 1.5; }
  .proj-tags { display: flex; flex-wrap: wrap; gap: 5px; }
  .tag { font-size: 10px; background: var(--color-background-secondary); color: var(--color-text-secondary); padding: 2px 8px; border-radius: 12px; border: 0.5px solid var(--color-border-tertiary); }
  .achievement { font-size: 11px; color: #1D9E75; margin: 4px 0 8px; font-weight: 500; }
  .skills-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 8px; margin-bottom: 1.5rem; }
  .skill-group { background: var(--color-background-secondary); border-radius: 8px; padding: 10px 12px; border: 0.5px solid var(--color-border-tertiary); }
  .skill-group-title { font-size: 11px; font-weight: 500; color: var(--color-text-secondary); margin-bottom: 6px; }
  .skill-item { font-size: 11px; color: var(--color-text-tertiary); line-height: 1.7; }
  .contact-row { display: flex; gap: 10px; flex-wrap: wrap; }
  .contact-chip { font-size: 12px; background: var(--color-background-secondary); border: 0.5px solid var(--color-border-tertiary); border-radius: 20px; padding: 5px 14px; color: var(--color-text-secondary); }
  .stats-row { display: flex; gap: 10px; margin-top: 1rem; }
  .stat-box { background: var(--color-background-secondary); border: 0.5px solid var(--color-border-tertiary); border-radius: 8px; padding: 8px 14px; font-size: 12px; color: var(--color-text-secondary); flex: 1; text-align: center; }
  .stat-num { font-size: 20px; font-weight: 500; color: var(--color-text-primary); display: block; }
</style>
<div class="readme-wrap">
  <p class="header-name">Nguyen Thien Duc (Doug) Vo 👋</p>
  <p class="header-title">Machine Learning / AI Engineer · MSc Student @ University of Oulu, Finland</p>
  <div class="badges">
    <span class="badge"><span class="badge-dot" style="background:#1D9E75"></span>Open to opportunities</span>
    <span class="badge"><span class="badge-dot" style="background:#378ADD"></span>Oulu, Finland</span>
    <span class="badge"><span class="badge-dot" style="background:#7F77DD"></span>ML · MLOps · Cloud</span>
  </div>
  <p class="bio">I build intelligent systems — from RAG pipelines to cloud-deployed ML apps — with a focus on clean architecture and real-world impact. Currently pursuing my MSc in Computer Science at the University of Oulu.</p>

  <div class="section-label">Featured Projects</div>
  <div class="project-grid">
    <div class="proj-card">
      <p class="proj-title">Weather Forecast Dashboard</p>
      <p class="proj-desc">Real-time ML forecasting for 6 Finnish cities using FMI open data, deployed on Azure.</p>
      <p class="achievement">0.99°C MAE for 6h temperature prediction</p>
      <div class="proj-tags"><span class="tag">XGBoost</span><span class="tag">Flask</span><span class="tag">Azure</span><span class="tag">MongoDB</span><span class="tag">Docker</span></div>
    </div>
    <div class="proj-card">
      <p class="proj-title">RAG Knowledge Engine</p>
      <p class="proj-desc">Retrieval-augmented generation system for verified, source-cited answers using LLMs.</p>
      <div class="proj-tags"><span class="tag">Python</span><span class="tag">LLMs</span><span class="tag">NLP</span><span class="tag">RAG</span></div>
    </div>
    <div class="proj-card">
      <p class="proj-title">ML Self Projects</p>
      <p class="proj-desc">EDA, model benchmarking, classification pipelines, and production-ready ML systems.</p>
      <div class="proj-tags"><span class="tag">Scikit-Learn</span><span class="tag">XGBoost</span><span class="tag">EDA</span><span class="tag">Pipeline</span></div>
    </div>
  </div>

  <div class="section-label">Skills & Tools</div>
  <div class="skills-grid">
    <div class="skill-group">
      <p class="skill-group-title">AI / ML</p>
      <p class="skill-item">Python · Scikit-Learn<br>XGBoost · NLP<br>RAG Pipelines</p>
    </div>
    <div class="skill-group">
      <p class="skill-group-title">Data & Cloud</p>
      <p class="skill-item">SQL · MongoDB<br>Azure · GCP<br>Docker · Kubernetes</p>
    </div>
    <div class="skill-group">
      <p class="skill-group-title">Web & DevOps</p>
      <p class="skill-item">Flask · FastAPI · React<br>GitHub Actions<br>Agile / Scrum</p>
    </div>
  </div>

  <div class="section-label">Education</div>
  <div style="font-size:13px; color: var(--color-text-secondary); line-height: 2; margin-bottom: 1.5rem;">
    <span style="font-weight:500; color: var(--color-text-primary)">MSc Computer Science</span> — University of Oulu, Finland (Current)<br>
    <span style="font-weight:500; color: var(--color-text-primary)">BSc Computer Science</span> — Grand Canyon University, USA (2024)
  </div>

  <div class="section-label">Connect</div>
  <div class="contact-row">
    <span class="contact-chip">Portfolio</span>
    <span class="contact-chip">LinkedIn</span>
    <span class="contact-chip">GitHub</span>
    <span class="contact-chip">Email</span>
  </div>
</div>
