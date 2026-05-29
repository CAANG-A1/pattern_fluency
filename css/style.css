@import url('https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@400;600;700&family=Libre+Baskerville:ital,wght@0,400;0,700;1,400&family=IBM+Plex+Mono:wght@400;500&display=swap');

:root {
  --navy: #0d1b2a;
  --navy-mid: #152336;
  --navy-light: #1e3250;
  --amber: #e8a020;
  --amber-light: #f5b942;
  --amber-dim: rgba(232,160,32,0.15);
  --white: #f4f0e8;
  --white-dim: rgba(244,240,232,0.7);
  --white-faint: rgba(244,240,232,0.15);
  --teal: #2a9d8f;
  --coral: #c1440e;
  --border: rgba(244,240,232,0.12);
  --font-display: 'Barlow Condensed', sans-serif;
  --font-body: 'Libre Baskerville', serif;
  --font-mono: 'IBM Plex Mono', monospace;
  --max: 860px;
  --sidebar: 260px;
}

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

html { scroll-behavior: smooth; }

body {
  background: var(--navy);
  color: var(--white);
  font-family: var(--font-body);
  font-size: 17px;
  line-height: 1.75;
  min-height: 100vh;
}

/* ── LAYOUT ── */
.site-wrapper {
  display: flex;
  min-height: 100vh;
}

/* ── SIDEBAR ── */
.sidebar {
  width: var(--sidebar);
  background: var(--navy-mid);
  border-right: 1px solid var(--border);
  position: fixed;
  top: 0;
  left: 0;
  height: 100vh;
  overflow-y: auto;
  display: flex;
  flex-direction: column;
  z-index: 100;
  transition: transform 0.3s ease;
}

.sidebar-brand {
  padding: 28px 24px 20px;
  border-bottom: 1px solid var(--border);
}

.sidebar-brand .wordmark {
  font-family: var(--font-display);
  font-size: 22px;
  font-weight: 700;
  letter-spacing: 0.04em;
  text-transform: uppercase;
  color: var(--amber);
  line-height: 1.1;
  display: block;
  text-decoration: none;
}

.sidebar-brand .sub {
  font-family: var(--font-mono);
  font-size: 10px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: var(--white-dim);
  margin-top: 4px;
  display: block;
}

.sidebar-nav {
  padding: 16px 0;
  flex: 1;
}

.nav-section {
  padding: 12px 24px 6px;
}

.nav-section-label {
  font-family: var(--font-mono);
  font-size: 9px;
  letter-spacing: 0.14em;
  text-transform: uppercase;
  color: var(--amber);
  opacity: 0.7;
}

.nav-link {
  display: flex;
  align-items: center;
  gap: 10px;
  padding: 8px 24px;
  color: var(--white-dim);
  text-decoration: none;
  font-family: var(--font-display);
  font-size: 14px;
  font-weight: 600;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  transition: all 0.15s;
  border-left: 2px solid transparent;
  position: relative;
}

.nav-link:hover {
  color: var(--white);
  background: var(--white-faint);
}

.nav-link.active {
  color: var(--amber);
  border-left-color: var(--amber);
  background: var(--amber-dim);
}

.nav-link .num {
  font-family: var(--font-mono);
  font-size: 10px;
  opacity: 0.5;
  min-width: 18px;
}

.nav-link.active .num { opacity: 1; }

.sidebar-footer {
  padding: 20px 24px;
  border-top: 1px solid var(--border);
  font-family: var(--font-mono);
  font-size: 10px;
  color: var(--white-dim);
  opacity: 0.5;
  letter-spacing: 0.06em;
}

/* ── MAIN CONTENT ── */
.main-content {
  margin-left: var(--sidebar);
  flex: 1;
  min-height: 100vh;
}

/* ── TOP BAR ── */
.topbar {
  background: var(--navy-mid);
  border-bottom: 1px solid var(--border);
  padding: 16px 48px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  position: sticky;
  top: 0;
  z-index: 50;
}

.topbar-breadcrumb {
  font-family: var(--font-mono);
  font-size: 11px;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: var(--white-dim);
}

.topbar-breadcrumb span {
  color: var(--amber);
}

.progress-indicator {
  display: flex;
  gap: 5px;
  align-items: center;
}

.progress-dot {
  width: 7px;
  height: 7px;
  border-radius: 50%;
  background: var(--white-faint);
  border: 1px solid var(--border);
  transition: all 0.2s;
}

.progress-dot.done { background: var(--teal); border-color: var(--teal); }
.progress-dot.current { background: var(--amber); border-color: var(--amber); }

/* ── PAGE HERO ── */
.page-hero {
  padding: 64px 48px 48px;
  border-bottom: 1px solid var(--border);
  position: relative;
  overflow: hidden;
}

.page-hero::before {
  content: '';
  position: absolute;
  top: 0; right: 0;
  width: 40%;
  height: 100%;
  background: linear-gradient(135deg, transparent 60%, rgba(232,160,32,0.04) 100%);
  pointer-events: none;
}

.hero-eyebrow {
  font-family: var(--font-mono);
  font-size: 11px;
  letter-spacing: 0.14em;
  text-transform: uppercase;
  color: var(--amber);
  margin-bottom: 14px;
  display: flex;
  align-items: center;
  gap: 10px;
}

.hero-eyebrow::before {
  content: '';
  display: inline-block;
  width: 28px;
  height: 1px;
  background: var(--amber);
}

.page-hero h1 {
  font-family: var(--font-display);
  font-size: clamp(36px, 5vw, 58px);
  font-weight: 700;
  letter-spacing: 0.02em;
  text-transform: uppercase;
  line-height: 1.0;
  color: var(--white);
  margin-bottom: 16px;
}

.page-hero .subtitle {
  font-size: 17px;
  color: var(--white-dim);
  max-width: 580px;
  line-height: 1.6;
  font-style: italic;
}

/* ── BELIEF CARDS ── */
.belief-strip {
  display: grid;
  grid-template-columns: 1fr auto 1fr;
  gap: 0;
  margin: 40px 48px;
  border: 1px solid var(--border);
  border-radius: 2px;
  overflow: hidden;
}

.belief-card {
  padding: 24px 28px;
  background: var(--navy-mid);
}

.belief-card.current { border-right: 1px solid var(--border); }
.belief-card.target { background: rgba(42,157,143,0.08); }

.belief-label {
  font-family: var(--font-mono);
  font-size: 9px;
  letter-spacing: 0.14em;
  text-transform: uppercase;
  margin-bottom: 8px;
}

.belief-card.current .belief-label { color: var(--coral); }
.belief-card.target .belief-label { color: var(--teal); }

.belief-text {
  font-family: var(--font-display);
  font-size: 18px;
  font-weight: 600;
  letter-spacing: 0.01em;
  line-height: 1.3;
}

.belief-arrow {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 0 20px;
  background: var(--navy-mid);
  border-right: 1px solid var(--border);
  color: var(--amber);
  font-size: 22px;
}

/* ── LESSON CONTENT ── */
.lesson-body {
  padding: 0 48px 80px;
  max-width: calc(var(--max) + 96px);
}

.lesson-body h2 {
  font-family: var(--font-display);
  font-size: 28px;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  color: var(--white);
  margin: 52px 0 16px;
  padding-bottom: 10px;
  border-bottom: 1px solid var(--border);
  display: flex;
  align-items: center;
  gap: 12px;
}

.lesson-body h2::before {
  content: '';
  display: inline-block;
  width: 4px;
  height: 24px;
  background: var(--amber);
  border-radius: 2px;
  flex-shrink: 0;
}

.lesson-body h3 {
  font-family: var(--font-display);
  font-size: 18px;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.06em;
  color: var(--amber);
  margin: 32px 0 10px;
}

.lesson-body p {
  margin-bottom: 18px;
  color: var(--white-dim);
  max-width: var(--max);
}

.lesson-body strong {
  color: var(--white);
  font-weight: 700;
}

.lesson-body em {
  color: var(--white-dim);
}

/* ── SPECIAL BLOCKS ── */
.coach-pause {
  background: var(--navy-light);
  border-left: 3px solid var(--amber);
  padding: 20px 24px;
  margin: 28px 0;
  max-width: var(--max);
  border-radius: 0 2px 2px 0;
}

.coach-pause .label {
  font-family: var(--font-mono);
  font-size: 9px;
  letter-spacing: 0.14em;
  text-transform: uppercase;
  color: var(--amber);
  margin-bottom: 8px;
}

.coach-pause p {
  margin: 0;
  color: var(--white-dim);
  font-style: italic;
}

.stop-think {
  background: rgba(42,157,143,0.08);
  border: 1px solid rgba(42,157,143,0.25);
  border-radius: 2px;
  padding: 24px 28px;
  margin: 28px 0;
  max-width: var(--max);
}

.stop-think .label {
  font-family: var(--font-mono);
  font-size: 9px;
  letter-spacing: 0.14em;
  text-transform: uppercase;
  color: var(--teal);
  margin-bottom: 10px;
}

.stop-think p { color: var(--white-dim); margin: 0 0 10px; }
.stop-think p:last-child { margin: 0; }

.drill-block {
  background: var(--navy-mid);
  border: 1px solid var(--border);
  border-top: 3px solid var(--amber);
  padding: 24px 28px;
  margin: 28px 0;
  max-width: var(--max);
  border-radius: 0 0 2px 2px;
}

.drill-block .drill-header {
  font-family: var(--font-display);
  font-size: 20px;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.06em;
  color: var(--amber);
  margin-bottom: 14px;
  display: flex;
  align-items: center;
  gap: 10px;
}

.drill-block .drill-header .icon {
  font-size: 14px;
  opacity: 0.7;
}

.drill-block p { color: var(--white-dim); margin: 0 0 8px; }
.drill-block p:last-child { margin: 0; }

.step-block {
  border: 1px solid var(--border);
  border-radius: 2px;
  margin: 28px 0;
  max-width: var(--max);
  overflow: hidden;
}

.step-header {
  background: var(--navy-light);
  padding: 12px 20px;
  font-family: var(--font-display);
  font-size: 13px;
  font-weight: 600;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: var(--amber);
  border-bottom: 1px solid var(--border);
}

.step-content {
  padding: 20px 24px;
  background: var(--navy-mid);
}

.step-content p { color: var(--white-dim); margin: 0 0 12px; }
.step-content p:last-child { margin: 0; }

.step-action {
  display: inline-block;
  background: var(--amber-dim);
  border: 1px solid rgba(232,160,32,0.3);
  border-radius: 2px;
  padding: 3px 10px;
  font-family: var(--font-mono);
  font-size: 13px;
  color: var(--amber-light);
  margin: 2px 2px;
}

/* ── DATA TABLE ── */
.data-table {
  width: 100%;
  max-width: var(--max);
  border-collapse: collapse;
  margin: 20px 0 28px;
  font-family: var(--font-mono);
  font-size: 13px;
}

.data-table th {
  background: var(--navy-light);
  color: var(--amber);
  padding: 10px 16px;
  text-align: left;
  font-weight: 500;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  font-size: 11px;
  border-bottom: 1px solid var(--border);
}

.data-table td {
  padding: 9px 16px;
  color: var(--white-dim);
  border-bottom: 1px solid var(--border);
}

.data-table tr:last-child td { border-bottom: none; }
.data-table tr:hover td { background: var(--white-faint); }
.data-table { border: 1px solid var(--border); border-radius: 2px; overflow: hidden; }

/* ── REFLECTION / MISTAKES LISTS ── */
.numbered-list {
  list-style: none;
  margin: 0 0 24px;
  max-width: var(--max);
}

.numbered-list li {
  display: flex;
  gap: 16px;
  padding: 12px 0;
  border-bottom: 1px solid var(--border);
  color: var(--white-dim);
  align-items: flex-start;
}

.numbered-list li:last-child { border-bottom: none; }

.numbered-list li .n {
  font-family: var(--font-mono);
  font-size: 11px;
  color: var(--amber);
  min-width: 20px;
  padding-top: 2px;
  flex-shrink: 0;
}

.mistake-block {
  border: 1px solid var(--border);
  border-left: 3px solid var(--coral);
  padding: 16px 20px;
  margin: 14px 0;
  max-width: var(--max);
  background: rgba(193,68,14,0.05);
  border-radius: 0 2px 2px 0;
}

.mistake-block strong {
  display: block;
  font-family: var(--font-display);
  font-size: 14px;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  color: var(--coral);
  margin-bottom: 6px;
}

.mistake-block p { margin: 0; font-size: 15px; color: var(--white-dim); }

/* ── HOMEWORK ── */
.homework-block {
  background: var(--navy-mid);
  border: 1px solid var(--border);
  border-top: 3px solid var(--teal);
  padding: 28px;
  margin: 32px 0;
  max-width: var(--max);
  border-radius: 0 0 2px 2px;
}

.homework-block .hw-label {
  font-family: var(--font-mono);
  font-size: 9px;
  letter-spacing: 0.16em;
  text-transform: uppercase;
  color: var(--teal);
  margin-bottom: 14px;
}

.homework-block p { color: var(--white-dim); margin: 0 0 10px; }
.homework-block p:last-child { margin: 0; }

/* ── LESSON SUMMARY ── */
.summary-block {
  background: var(--amber-dim);
  border: 1px solid rgba(232,160,32,0.2);
  padding: 32px;
  margin: 48px 0 32px;
  max-width: var(--max);
  border-radius: 2px;
}

.summary-block .sum-label {
  font-family: var(--font-mono);
  font-size: 9px;
  letter-spacing: 0.16em;
  text-transform: uppercase;
  color: var(--amber);
  margin-bottom: 14px;
}

.summary-block p { color: var(--white); margin: 0 0 12px; }
.summary-block p:last-child { margin: 0; }

/* ── NAV FOOTER ── */
.lesson-nav-footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 32px 48px;
  border-top: 1px solid var(--border);
  margin-top: 40px;
  max-width: calc(var(--max) + 96px);
}

.nav-btn {
  display: flex;
  align-items: center;
  gap: 10px;
  padding: 12px 22px;
  background: var(--navy-mid);
  border: 1px solid var(--border);
  border-radius: 2px;
  color: var(--white-dim);
  text-decoration: none;
  font-family: var(--font-display);
  font-size: 14px;
  font-weight: 600;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  transition: all 0.15s;
}

.nav-btn:hover {
  border-color: var(--amber);
  color: var(--amber);
  background: var(--amber-dim);
}

.nav-btn.primary {
  background: var(--amber);
  color: var(--navy);
  border-color: var(--amber);
}

.nav-btn.primary:hover {
  background: var(--amber-light);
  border-color: var(--amber-light);
  color: var(--navy);
}

/* ── HOME PAGE ── */
.home-hero {
  padding: 80px 64px 64px;
  border-bottom: 1px solid var(--border);
  position: relative;
  overflow: hidden;
}

.home-hero::after {
  content: 'PF';
  position: absolute;
  right: 48px;
  top: 50%;
  transform: translateY(-50%);
  font-family: var(--font-display);
  font-size: 200px;
  font-weight: 700;
  color: rgba(232,160,32,0.04);
  letter-spacing: -0.05em;
  line-height: 1;
  pointer-events: none;
  user-select: none;
}

.home-hero .kicker {
  font-family: var(--font-mono);
  font-size: 11px;
  letter-spacing: 0.16em;
  text-transform: uppercase;
  color: var(--amber);
  margin-bottom: 20px;
}

.home-hero h1 {
  font-family: var(--font-display);
  font-size: clamp(44px, 6vw, 76px);
  font-weight: 700;
  letter-spacing: 0.02em;
  text-transform: uppercase;
  line-height: 0.95;
  color: var(--white);
  margin-bottom: 24px;
}

.home-hero h1 em {
  color: var(--amber);
  font-style: normal;
}

.home-hero .lead {
  font-size: 18px;
  color: var(--white-dim);
  max-width: 520px;
  line-height: 1.65;
  margin-bottom: 36px;
}

.home-hero .start-btn {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  padding: 14px 28px;
  background: var(--amber);
  color: var(--navy);
  text-decoration: none;
  font-family: var(--font-display);
  font-size: 16px;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  border-radius: 2px;
  transition: all 0.15s;
}

.home-hero .start-btn:hover {
  background: var(--amber-light);
  transform: translateY(-1px);
}

.volume-grid {
  padding: 48px 64px;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1px;
  background: var(--border);
  border-bottom: 1px solid var(--border);
}

.volume-card {
  background: var(--navy);
  padding: 36px 32px;
  text-decoration: none;
  display: block;
  transition: background 0.15s;
}

.volume-card:hover { background: var(--navy-mid); }

.vol-num {
  font-family: var(--font-mono);
  font-size: 10px;
  letter-spacing: 0.14em;
  color: var(--amber);
  text-transform: uppercase;
  margin-bottom: 10px;
}

.vol-title {
  font-family: var(--font-display);
  font-size: 26px;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.03em;
  color: var(--white);
  line-height: 1.1;
  margin-bottom: 10px;
}

.vol-desc {
  font-size: 14px;
  color: var(--white-dim);
  line-height: 1.55;
  margin-bottom: 16px;
}

.vol-status {
  font-family: var(--font-mono);
  font-size: 10px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

.vol-status.available { color: var(--teal); }
.vol-status.coming { color: var(--white-dim); opacity: 0.5; }

.lesson-index {
  padding: 48px 64px;
}

.lesson-index h2 {
  font-family: var(--font-display);
  font-size: 32px;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.04em;
  color: var(--white);
  margin-bottom: 28px;
  padding-bottom: 14px;
  border-bottom: 1px solid var(--border);
}

.lesson-row {
  display: flex;
  align-items: center;
  gap: 20px;
  padding: 16px 0;
  border-bottom: 1px solid var(--border);
  text-decoration: none;
  color: inherit;
  transition: all 0.15s;
}

.lesson-row:hover .lesson-row-title { color: var(--amber); }
.lesson-row:hover .lesson-row-arrow { opacity: 1; transform: translateX(4px); }

.lesson-row-num {
  font-family: var(--font-mono);
  font-size: 12px;
  color: var(--amber);
  min-width: 32px;
  flex-shrink: 0;
}

.lesson-row-body { flex: 1; }

.lesson-row-title {
  font-family: var(--font-display);
  font-size: 18px;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.04em;
  color: var(--white);
  transition: color 0.15s;
  line-height: 1.2;
}

.lesson-row-transformation {
  font-size: 13px;
  color: var(--white-dim);
  margin-top: 3px;
  font-style: italic;
}

.lesson-row-arrow {
  color: var(--amber);
  font-size: 18px;
  opacity: 0.4;
  transition: all 0.15s;
  flex-shrink: 0;
}

/* ── PHILOSOPHY PAGE ── */
.philosophy-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1px;
  background: var(--border);
  margin: 40px 48px;
}

.phil-card {
  background: var(--navy-mid);
  padding: 32px;
}

.phil-card h3 {
  font-family: var(--font-display);
  font-size: 20px;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  color: var(--amber);
  margin-bottom: 10px;
}

.phil-card p {
  font-size: 15px;
  color: var(--white-dim);
  line-height: 1.6;
}

/* ── QUICK REFERENCE ── */
.ref-table {
  width: 100%;
  max-width: var(--max);
  border-collapse: collapse;
  margin: 20px 0 32px;
  font-size: 15px;
}

.ref-table th {
  background: var(--navy-light);
  color: var(--amber);
  padding: 10px 16px;
  text-align: left;
  font-family: var(--font-display);
  font-size: 13px;
  font-weight: 600;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  border-bottom: 1px solid var(--border);
}

.ref-table td {
  padding: 10px 16px;
  color: var(--white-dim);
  border-bottom: 1px solid var(--border);
  vertical-align: top;
}

.ref-table td:first-child { color: var(--white); font-style: italic; }
.ref-table { border: 1px solid var(--border); border-radius: 2px; overflow: hidden; }

/* ── MOBILE TOGGLE ── */
.mobile-toggle {
  display: none;
  position: fixed;
  top: 14px;
  left: 14px;
  z-index: 200;
  background: var(--navy-mid);
  border: 1px solid var(--border);
  border-radius: 2px;
  padding: 8px 12px;
  cursor: pointer;
  color: var(--amber);
  font-family: var(--font-mono);
  font-size: 14px;
}

.sidebar-overlay {
  display: none;
  position: fixed;
  inset: 0;
  background: rgba(0,0,0,0.6);
  z-index: 90;
}

/* ── RESPONSIVE ── */
@media (max-width: 900px) {
  .sidebar {
    transform: translateX(-100%);
  }
  .sidebar.open {
    transform: translateX(0);
  }
  .sidebar-overlay.open {
    display: block;
  }
  .mobile-toggle {
    display: block;
  }
  .main-content {
    margin-left: 0;
  }
  .topbar, .page-hero, .lesson-body, .lesson-nav-footer {
    padding-left: 24px;
    padding-right: 24px;
  }
  .topbar { padding-left: 56px; }
  .belief-strip {
    margin: 28px 24px;
    grid-template-columns: 1fr;
  }
  .belief-arrow { display: none; }
  .belief-card.current { border-right: none; border-bottom: 1px solid var(--border); }
  .home-hero, .lesson-index, .volume-grid { padding: 40px 24px; }
  .volume-grid { grid-template-columns: 1fr; }
  .philosophy-grid { grid-template-columns: 1fr; margin: 28px 24px; }
}
