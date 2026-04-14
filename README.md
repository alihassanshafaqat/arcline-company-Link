
<style>
  .arc-root { padding: 1.5rem 0; font-family: var(--font-sans); }
  .arc-card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); overflow: hidden; max-width: 720px; }
  .arc-header { padding: 1.5rem 1.5rem 1.25rem; border-bottom: 0.5px solid var(--color-border-tertiary); }
  .arc-logo-row { display: flex; align-items: center; gap: 12px; margin-bottom: 10px; }
  .arc-logo { width: 40px; height: 40px; border-radius: 10px; background: #0d0d0d; display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
  .arc-logo svg { width: 22px; height: 22px; }
  .arc-title { font-size: 20px; font-weight: 500; color: var(--color-text-primary); margin: 0; }
  .arc-subtitle { font-size: 13px; color: var(--color-text-secondary); margin: 4px 0 0; }
  .arc-badges { display: flex; flex-wrap: wrap; gap: 6px; margin-top: 12px; }
  .badge { font-size: 11px; font-weight: 500; padding: 3px 10px; border-radius: 20px; letter-spacing: 0.02em; }
  .badge-blue { background: #E6F1FB; color: #0C447C; }
  .badge-teal { background: #E1F5EE; color: #085041; }
  .badge-amber { background: #FAEEDA; color: #633806; }
  .badge-gray { background: #F1EFE8; color: #444441; }
  .badge-purple { background: #EEEDFE; color: #3C3489; }
  .arc-demo { display: flex; align-items: center; gap: 8px; margin-top: 12px; }
  .arc-demo-dot { width: 7px; height: 7px; border-radius: 50%; background: #22c55e; flex-shrink: 0; }
  .arc-demo-link { font-size: 13px; color: var(--color-text-info); text-decoration: none; cursor: pointer; }
  .arc-body { padding: 1.25rem 1.5rem; }
  .arc-section { margin-bottom: 1.25rem; }
  .arc-section:last-child { margin-bottom: 0; }
  .arc-section-label { font-size: 11px; font-weight: 500; color: var(--color-text-tertiary); text-transform: uppercase; letter-spacing: 0.08em; margin-bottom: 10px; }
  .feature-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(0, 1fr)); gap: 8px; }
  .feature-item { background: var(--color-background-secondary); border-radius: var(--border-radius-md); padding: 10px 12px; }
  .feature-name { font-size: 13px; font-weight: 500; color: var(--color-text-primary); margin: 0 0 2px; }
  .feature-desc { font-size: 12px; color: var(--color-text-secondary); margin: 0; }
  .stack-row { display: flex; flex-wrap: wrap; gap: 6px; }
  .stack-item { background: var(--color-background-secondary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-md); padding: 6px 12px; font-size: 12px; color: var(--color-text-primary); }
  .arc-footer { padding: 1rem 1.5rem; border-top: 0.5px solid var(--color-border-tertiary); background: var(--color-background-secondary); display: flex; align-items: center; justify-content: space-between; flex-wrap: gap; gap: 8px; }
  .footer-text { font-size: 12px; color: var(--color-text-secondary); }
  .footer-links { display: flex; gap: 12px; }
  .footer-link { font-size: 12px; color: var(--color-text-info); text-decoration: none; cursor: pointer; }
  @media (prefers-color-scheme: dark) {
    .badge-blue { background: #0C447C; color: #B5D4F4; }
    .badge-teal { background: #085041; color: #9FE1CB; }
    .badge-amber { background: #633806; color: #FAC775; }
    .badge-gray { background: #444441; color: #D3D1C7; }
    .badge-purple { background: #3C3489; color: #CECBF6; }
    .arc-logo { background: #1a1a1a; }
  }
</style>

<div class="arc-root">
  <div class="arc-card">
    <div class="arc-header">
      <div class="arc-logo-row">
        <div class="arc-logo">
          <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M4 20 Q4 4 12 4 Q20 4 20 12" stroke="#7dd3fc" stroke-width="2" stroke-linecap="round" fill="none"/>
            <circle cx="20" cy="12" r="2.5" fill="#7dd3fc"/>
            <path d="M8 20 Q8 9 12 9 Q16 9 16 14" stroke="#38bdf8" stroke-width="1.5" stroke-linecap="round" fill="none" opacity="0.7"/>
            <circle cx="16" cy="14" r="1.8" fill="#38bdf8" opacity="0.7"/>
          </svg>
        </div>
        <div>
          <p class="arc-title">Arcline Analytics Dashboard</p>
          <p class="arc-subtitle">AI Receptionist Intelligence Platform · Sydney, AU</p>
        </div>
      </div>
      <div class="arc-badges">
        <span class="badge badge-blue">Live</span>
        <span class="badge badge-teal">Retell AI</span>
        <span class="badge badge-purple">Mini CRM</span>
        <span class="badge badge-amber">Call Analytics</span>
        <span class="badge badge-gray">Vanilla JS</span>
      </div>
      <div class="arc-demo">
        <span class="arc-demo-dot"></span>
        <span class="arc-demo-link" onclick="openLink('https://arcline-company.vercel.app/')">arcline-dashboard.netlify.app</span>
      </div>
    </div>

    <div class="arc-body">
      <div class="arc-section">
        <p class="arc-section-label">Features</p>
        <div class="feature-grid">
          <div class="feature-item">
            <p class="feature-name">Call Analytics</p>
            <p class="feature-desc">Live call logs, duration tracking, sentiment overview via Retell AI</p>
          </div>
          <div class="feature-item">
            <p class="feature-name">Mini CRM</p>
            <p class="feature-desc">Contact profiles, call history, notes — inline or separate page</p>
          </div>
          <div class="feature-item">
            <p class="feature-name">AI Receptionist Stats</p>
            <p class="feature-desc">Answered %, missed calls, avg handle time, peak hours</p>
          </div>
          <div class="feature-item">
            <p class="feature-name">Webhook Integration</p>
            <p class="feature-desc">Retell AI post-call events piped into real-time dashboard updates</p>
          </div>
        </div>
      </div>

      <div class="arc-section">
        <p class="arc-section-label">Stack</p>
        <div class="stack-row">
          <span class="stack-item">HTML · CSS · Vanilla JS</span>
          <span class="stack-item">Retell AI API</span>
          <span class="stack-item">Webhook Events</span>
          <span class="stack-item">Single-file App</span>
          <span class="stack-item">Firebase (planned)</span>
        </div>
      </div>

      <div class="arc-section">
        <p class="arc-section-label">Client</p>
        <div class="stack-row">
          <span class="stack-item">Arcline — Australian AI Receptionist Company</span>
          <span class="stack-item">Active Contract</span>
          <span class="stack-item">Discord Collab</span>
        </div>
      </div>
    </div>

    <div class="arc-footer">
      <span class="footer-text">Built by Ali Hassan Shafaqat · profess0r.carrd.co</span>
      <div class="footer-links">
        <span class="footer-link" onclick="openLink('https://github.com/alihassanshafaqat')">GitHub</span>
        <span class="footer-link" onclick="openLink('https://linkedin.com/in/alihassanshafaqat')">LinkedIn</span>
      </div>
    </div>
  </div>
</div>
