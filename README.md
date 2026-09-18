<html>
<head>
<meta charset="utf-8">
<title>Ibrahim Yalcin - CV</title>
<meta name="description" content="Ibrahim Yalcin - Senior Software Engineer, AI-Native Platform Engineering">
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Source+Serif+4:opsz,wght@8..60,600;8..60,700&family=IBM+Plex+Sans:wght@400;500;600&family=IBM+Plex+Mono:wght@400;500;600&display=swap">
<style>:root{color-scheme:light;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}html{scroll-padding-top:env(safe-area-inset-top,0px)}body{margin:0;padding:0;font:14px -apple-system,BlinkMacSystemFont,sans-serif;background:#faf9f5;color:#141413}img{max-width:100%}[hidden]:not([hidden=until-found i]){display:none!important}</style>
<style>
  :root {
    --bg: #eef0ec;
    --sheet: #ffffff;
    --ink: #1b2430;
    --ink-soft: #5b6774;
    --ink-faint: #8a93a0;
    --accent: #1f3864;
    --accent-soft: rgba(31, 56, 100, 0.08);
    --rule: #8ea9c1;
    --chip-bg: #eef1f5;
    --border: #dfe3de;
    --shadow: 0 1px 2px rgba(27, 36, 48, 0.04), 0 12px 32px -16px rgba(27, 36, 48, 0.18);
  }
  @media (prefers-color-scheme: dark) {
    :root:not([data-theme="light"]) {
      --bg: #10151a; --sheet: #171e25; --ink: #e8ebec; --ink-soft: #9aa5ad; --ink-faint: #6d7780;
      --accent: #82abe0; --accent-soft: rgba(130, 171, 224, 0.14); --rule: #3a4a5e;
      --chip-bg: #1d252c; --border: #29323a;
      --shadow: 0 1px 2px rgba(0,0,0,0.3), 0 20px 40px -20px rgba(0,0,0,0.6);
    }
  }
  :root[data-theme="dark"] {
    --bg: #10151a; --sheet: #171e25; --ink: #e8ebec; --ink-soft: #9aa5ad; --ink-faint: #6d7780;
    --accent: #82abe0; --accent-soft: rgba(130, 171, 224, 0.14); --rule: #3a4a5e;
    --chip-bg: #1d252c; --border: #29323a;
    --shadow: 0 1px 2px rgba(0,0,0,0.3), 0 20px 40px -20px rgba(0,0,0,0.6);
  }

  * { box-sizing: border-box; }

  .cv-shell {
    background: var(--bg);
    color: var(--ink);
    font-family: "IBM Plex Sans", -apple-system, "Segoe UI", sans-serif;
    padding-inline: 16px;
    padding-block: 32px;
  }

  .preview-note {
    max-width: 820px; width: 100%;
    font-family: "IBM Plex Mono", monospace;
    font-size: 0.72rem;
    color: var(--ink-faint);
    text-align: center;
    margin-bottom: 16px;
  }

  .tabs {
    display: flex;
    gap: 6px;
    background: var(--chip-bg);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 4px;
    margin-bottom: 22px;
  }
  .tab-btn {
    font-family: "IBM Plex Mono", monospace;
    font-size: 0.78rem;
    letter-spacing: 0.02em;
    padding: 9px 18px;
    border: none;
    background: transparent;
    color: var(--ink-soft);
    border-radius: 6px;
    cursor: pointer;
  }
  .tab-btn[aria-selected="true"] {
    background: var(--sheet);
    color: var(--accent);
    font-weight: 600;
    box-shadow: 0 1px 3px rgba(0,0,0,0.08);
  }
  .tab-btn:focus-visible { outline: 2px solid var(--accent); outline-offset: 2px; }

  .sheet-wrap { width: 100%; max-width: 900px; margin: 0 auto; }

  .sheet {
    background: var(--sheet);
    border: 1px solid var(--border);
    border-radius: 6px;
    box-shadow: var(--shadow);
    padding: clamp(22px, 5vw, 48px);
    container-type: inline-size;
  }

  .badge-row {
    display: flex; flex-wrap: wrap; gap: 8px;
    justify-content: center; margin-bottom: 18px;
  }
  .badge {
    font-family: "IBM Plex Mono", monospace;
    font-size: 0.7rem;
    padding: 3px 9px;
    border-radius: 20px;
    background: var(--accent-soft);
    color: var(--accent);
    border: 1px solid var(--accent-soft);
  }

  header.identity { text-align: center; margin-bottom: 22px; }
  h1.name {
    font-family: "Source Serif 4", Georgia, serif;
    font-weight: 700;
    font-size: clamp(1.7rem, 4vw, 2.2rem);
    margin: 0 0 4px;
    text-wrap: balance;
    color: var(--accent);
  }
  .tagline { font-size: 0.92rem; color: var(--ink-soft); margin: 0 0 12px; }
  .contact-row {
    display: flex; flex-wrap: wrap; justify-content: center; align-items: baseline;
    gap: 3px 7px; font-size: 0.8rem; color: var(--ink-soft);
    padding-bottom: 12px; border-bottom: 1px solid var(--rule);
    max-width: 100%; row-gap: 4px;
  }
  .contact-row a, .contact-row span.plain { white-space: nowrap; }
  .contact-row a { color: var(--accent); text-decoration: underline; text-underline-offset: 2px; }
  .contact-row span.plain { color: var(--ink-soft); }
  .dot-sep { color: var(--ink-faint); }

  h2.section-label {
    font-family: "IBM Plex Mono", monospace;
    font-size: 0.72rem; font-weight: 600; letter-spacing: 0.1em; text-transform: uppercase;
    color: var(--accent);
    margin: 26px 0 12px;
    padding-bottom: 6px;
    border-bottom: 1px solid var(--rule);
  }
  h2.section-label:first-of-type { margin-top: 20px; }

  .summary {
    font-size: 0.92rem; line-height: 1.65; margin: 0;
    text-align: justify; text-align-last: left; text-justify: inter-word;
  }

  .role { margin-bottom: 18px; }
  .role:last-child { margin-bottom: 0; }
  .role-head { display: flex; flex-wrap: wrap; justify-content: space-between; align-items: baseline; gap: 4px 10px; }
  .role-title { font-weight: 600; font-size: 0.92rem; color: var(--accent); }
  .role-dates {
    font-family: "IBM Plex Mono", monospace; font-size: 0.72rem; color: var(--ink-faint);
    font-variant-numeric: tabular-nums; white-space: nowrap;
  }
  .role-intro { font-size: 0.85rem; font-style: italic; color: var(--ink-soft); margin: 4px 0 6px; line-height: 1.55; }
  .subproject { font-size: 0.85rem; font-weight: 600; font-style: italic; color: var(--accent); margin: 10px 0 4px; }

  ul.bullets { margin: 6px 0 0; padding-left: 18px; }
  ul.bullets li { font-size: 0.85rem; line-height: 1.58; margin-bottom: 6px; }
  ul.bullets li:last-child { margin-bottom: 0; }
  ul.bullets li::marker { color: var(--accent); }

  .edu-entry { margin-bottom: 10px; font-size: 0.87rem; line-height: 1.55; }
  .edu-entry:last-child { margin-bottom: 0; }
  .edu-degree { font-weight: 600; color: var(--accent); }
  .edu-meta { color: var(--ink-soft); }

  .skill-line { font-size: 0.85rem; line-height: 1.6; margin-bottom: 7px; }
  .skill-line:last-child { margin-bottom: 0; }
  .skill-label { font-weight: 600; color: var(--accent); }

  .cert-line { font-size: 0.85rem; line-height: 1.65; color: var(--ink); }

  .role-title a, .edu-degree a, .edu-meta a, .cert-line a {
    color: inherit;
    text-decoration: underline;
    text-decoration-color: var(--accent);
    text-underline-offset: 2px;
  }
  .cert-line a, .edu-meta a { color: var(--accent); }

  footer.trailer {
    margin-top: 22px; padding-top: 14px; border-top: 1px solid var(--rule);
    text-align: center; font-size: 0.78rem; color: var(--ink-soft);
  }

  [hidden] { display: none !important; }

  @media (max-width: 500px) {
    .contact-row { flex-direction: column; gap: 3px; }
    .dot-sep { display: none; }
  }

  /* ================= Double-column (showcase) tab — scoped palette ================= */
  .dc-scope {
    --accent: #2a6f6b;
    --accent-ink: #1e504d;
    --accent-soft: rgba(42, 111, 107, 0.1);
    --gold: #a8752e;
    --gold-soft: rgba(168, 117, 46, 0.1);
    --rail: #d5dad2;
  }
  @media (prefers-color-scheme: dark) {
    :root:not([data-theme="light"]) .dc-scope {
      --accent: #63c2b4; --accent-ink: #8fd6cb; --accent-soft: rgba(99,194,180,0.14);
      --gold: #d6a75f; --gold-soft: rgba(214,167,95,0.14); --rail: #2c363f;
    }
  }
  :root[data-theme="dark"] .dc-scope {
    --accent: #63c2b4; --accent-ink: #8fd6cb; --accent-soft: rgba(99,194,180,0.14);
    --gold: #d6a75f; --gold-soft: rgba(214,167,95,0.14); --rail: #2c363f;
  }

  .dc-name { color: var(--accent); }
  .dc-tagline { color: var(--accent-ink); font-weight: 500; }
  .dc-contact-row a { color: var(--accent-ink); }

  .dc-summary { font-size: 0.92rem; line-height: 1.65; }

  .dc-grid { display: grid; grid-template-columns: minmax(0, 1.6fr) minmax(0, 1fr); gap: 34px; margin-top: 22px; }
  .dc-grid > * { min-width: 0; }

  .dc-employer-group { position: relative; margin-bottom: 26px; }
  .dc-employer-group:last-child { margin-bottom: 0; }
  .dc-employer-name {
    display: flex; align-items: baseline; gap: 8px;
    font-family: "Source Serif 4", serif; font-weight: 700; font-size: 1.02rem; margin-bottom: 4px;
  }
  .dc-employer-name a { color: var(--ink); text-decoration: none; border-bottom: 1px solid var(--accent); }
  .dc-employer-name a:hover { color: var(--accent-ink); }
  .dc-employer-name .loc { font-weight: 400; font-size: 0.78rem; color: var(--ink-faint); }

  .dc-timeline { position: relative; padding-left: 20px; border-left: 2px solid var(--rail); }
  .dc-role { position: relative; padding-bottom: 18px; }
  .dc-role:last-child { padding-bottom: 0; }
  .dc-role::before {
    content: ""; position: absolute; left: -25px; top: 5px; width: 9px; height: 9px; border-radius: 50%;
    background: var(--accent); border: 2px solid var(--sheet); box-shadow: 0 0 0 1px var(--rail);
  }
  .dc-role-head { display: flex; flex-wrap: wrap; justify-content: space-between; align-items: baseline; gap: 4px 12px; margin-bottom: 5px; }
  .dc-role-title { font-weight: 600; font-size: 0.9rem; }
  .dc-role-dates { font-family: "IBM Plex Mono", monospace; font-size: 0.7rem; color: var(--ink-faint); font-variant-numeric: tabular-nums; white-space: nowrap; }
  .dc-role-intro { font-size: 0.83rem; font-style: italic; color: var(--ink-soft); margin: 0 0 7px; line-height: 1.5; }
  .dc-bullets { margin: 0; padding-left: 17px; }
  .dc-bullets li { font-size: 0.83rem; line-height: 1.55; margin-bottom: 6px; }
  .dc-bullets li:last-child { margin-bottom: 0; }
  .dc-bullets li::marker { color: var(--accent); }

  .dc-callout { margin-top: 10px; padding: 10px 13px; background: var(--gold-soft); border-left: 3px solid var(--gold); border-radius: 0 4px 4px 0; }
  .dc-callout-label { font-family: "IBM Plex Mono", monospace; font-size: 0.65rem; letter-spacing: 0.07em; text-transform: uppercase; color: var(--gold); font-weight: 600; margin-bottom: 5px; display: block; }
  .dc-callout p { font-size: 0.83rem; line-height: 1.55; margin: 0; }

  .dc-aside { display: flex; flex-direction: column; gap: 24px; min-width: 0; }
  .dc-edu-entry { margin-bottom: 12px; font-size: 0.85rem; }
  .dc-edu-entry:last-child { margin-bottom: 0; }
  .dc-edu-degree { font-weight: 600; }
  .dc-edu-degree a { color: var(--ink); text-decoration: none; border-bottom: 1px solid var(--accent); }
  .dc-edu-degree a:hover { color: var(--accent-ink); }
  .dc-edu-meta { font-size: 0.76rem; color: var(--ink-soft); margin-top: 2px; line-height: 1.5; }
  .dc-edu-meta a { color: var(--ink-soft); border-bottom: 1px dotted var(--ink-faint); text-decoration: none; }
  .dc-edu-meta a:hover { color: var(--accent-ink); border-bottom-color: var(--accent); }
  .dc-gpa-tag { display: inline-block; font-family: "IBM Plex Mono", monospace; font-size: 0.66rem; color: var(--accent-ink); background: var(--accent-soft); padding: 1px 6px; border-radius: 3px; margin-left: 4px; }

  .dc-skill-group { margin-bottom: 12px; }
  .dc-skill-group:last-child { margin-bottom: 0; }
  .dc-skill-label { font-family: "IBM Plex Mono", monospace; font-size: 0.66rem; letter-spacing: 0.05em; text-transform: uppercase; color: var(--ink-faint); margin-bottom: 5px; display: block; }
  .dc-chips { display: flex; flex-wrap: wrap; gap: 5px; }
  .dc-chip { font-size: 0.73rem; background: var(--chip-bg); padding: 3px 8px; border-radius: 3px; border: 1px solid var(--border); max-width: 100%; }

  .dc-cert-list { display: flex; flex-direction: column; gap: 8px; }
  .dc-cert-item a {
    display: flex; align-items: center; justify-content: space-between; gap: 8px; font-size: 0.81rem;
    color: var(--ink); text-decoration: none; padding: 6px 9px; background: var(--chip-bg);
    border: 1px solid var(--border); border-radius: 4px; transition: border-color .15s, color .15s;
  }
  .dc-cert-item a:hover { border-color: var(--gold); color: var(--accent-ink); }
  .dc-cert-item svg { width: 10px; height: 10px; stroke: var(--gold); flex-shrink: 0; }

  @media (max-width: 700px) {
    .dc-grid { grid-template-columns: 1fr; }
  }
</style>

<style>
@media print {
  @page { size: A4; margin: 6mm 8mm; }
  html, body {
    background: #ffffff !important;
    -webkit-print-color-adjust: exact; print-color-adjust: exact;
    padding: 0 !important; margin: 0 !important;
    display: block !important;
  }
  * { -webkit-print-color-adjust: exact; print-color-adjust: exact; }
  .sheet-wrap { max-width: 100% !important; }
  .sheet {
    box-shadow: none !important;
    border: none !important;
    padding: 0 !important;
  }

  /* ---- One-page fill v4: only vertical-only properties touched (no wrap-affecting horizontal changes) ---- */
  body { font-size: 12px !important; }
  header.identity { margin-bottom: 7px !important; }
  h1.name { font-size: 1.35rem !important; margin-bottom: 2px !important; }
  .tagline { font-size: 0.68rem !important; margin-bottom: 5px !important; }
  .contact-row { font-size: 0.62rem !important; padding-bottom: 5px !important; }
  .summary { font-size: 0.68rem !important; line-height: 1.25 !important; }
  .dc-grid { gap: 16px !important; margin-top: 8px !important; }
  h2.section-label { margin: 7px 0 4px !important; font-size: 0.6rem !important; padding-bottom: 3px !important; }
  h2.section-label:first-of-type { margin-top: 6px !important; }
  .dc-employer-group { margin-bottom: 6px !important; }
  .dc-employer-name { font-size: 0.78rem !important; margin-bottom: 2px !important; }
  .dc-timeline { padding-left: 12px !important; }
  .dc-role { padding-bottom: 4px !important; }
  .dc-role::before { width: 6px !important; height: 6px !important; left: -16px !important; top: 4px !important; }
  .dc-role-head { margin-bottom: 1px !important; }
  .dc-role-title { font-size: 0.68rem !important; }
  .dc-role-dates { font-size: 0.56rem !important; }
  .dc-role-intro { font-size: 0.62rem !important; line-height: 1.22 !important; margin: 0 0 3px !important; }
  .dc-bullets { padding-left: 12px !important; }
  .dc-bullets li { font-size: 0.62rem !important; line-height: 1.18 !important; margin-bottom: 1px !important; }
  .dc-callout { padding: 5px 6px !important; margin-top: 4px !important; }
  .dc-callout-label { font-size: 0.52rem !important; margin-bottom: 1px !important; }
  .dc-callout p { font-size: 0.62rem !important; line-height: 1.2 !important; }
  .dc-aside { gap: 12px !important; }
  .dc-edu-entry { margin-bottom: 6px !important; font-size: 0.62rem !important; }
  .dc-edu-meta { font-size: 0.56rem !important; line-height: 1.32 !important; margin-top: 2px !important; }
  .dc-gpa-tag { font-size: 0.5rem !important; padding: 0 4px !important; }
  .dc-skill-group { margin-bottom: 7px !important; }
  .dc-skill-label { font-size: 0.5rem !important; margin-bottom: 3px !important; }
  .dc-chips { gap: 3px !important; }
  .dc-chip { font-size: 0.56rem !important; padding: 1px 5px !important; }
  .dc-cert-list { gap: 5px !important; }
  .dc-cert-item a { font-size: 0.58rem !important; padding: 2px 6px !important; }
  footer.trailer { margin-top: 3px !important; padding-top: 2px !important; font-size: 0.55rem !important; }
  /* Fix: the on-screen contact row scrolls horizontally; in print it must wrap instead */
  .contact-row {
    flex-wrap: wrap !important;
    overflow: visible !important;
    max-width: 100% !important;
    row-gap: 4px !important;
  }
}
</style>

</head>
<body>
<div class="cv-shell">
<div class="sheet-wrap">
  <section class="sheet dc-scope">
    <header class="identity">
      <h1 class="name dc-name">Ibrahim Yalcin</h1>
      <p class="tagline dc-tagline">Senior Software Engineer · AI-Native Platform Engineering</p>
      <div class="contact-row dc-contact-row">
        <span class="plain">Beverley, UK</span><span class="dot-sep">&middot;</span>
        <span class="plain">+44 7443 855025</span><span class="dot-sep">&middot;</span>
        <span class="plain">abrahamdevop@gmail.com</span><span class="dot-sep">&middot;</span>
        <a href="https://www.linkedin.com/in/abraham-yalcin/" target="_blank" rel="noopener">linkedin.com/in/abraham-yalcin</a><span class="dot-sep">&middot;</span>
        <a href="https://github.com/abrahamsteep90" target="_blank" rel="noopener">github.com/abrahamsteep90</a><span class="dot-sep">&middot;</span>
        <a href="Ibrahim-Yalcin-CV.pdf" target="_blank" rel="noopener">Download PDF</a>
      </div>
    </header>

    <p class="summary dc-summary">Senior full-stack software engineer with <strong>7+ years</strong> building mission-critical payroll, HR and pensions systems for UK schools and Multi-Academy Trusts. One of two senior engineers with full technical ownership of Juniper Education's Catalyst payroll platform through a major organisational restructure and a live third-party (PeopleFirst) migration; following the decision to move off that dependency, now co-building Juniper's own in-house payroll &amp; HR platform and contributing to an AI-powered school-insights product. Independently designed, built and shipped a CFO-commissioned production integration end-to-end using agentic AI tooling (Claude Code, MCP servers). Works day-to-day in Clean/Onion Architecture, DDD, CQRS, multi-tenant database isolation, and cloud deployment across Azure (AKS) and AWS. MSc Financial Engineering (93% GPA) adds a quantitative edge that suits regulated, numbers-heavy domains like payroll.</p>

    <div class="dc-grid">
      <!-- LEFT: EXPERIENCE -->
      <div>
        <h2 class="section-label">Experience</h2>

        <div class="dc-employer-group">
          <div class="dc-employer-name">
            <a href="https://junipereducation.org/" target="_blank" rel="noopener">Juniper Education</a>
          </div>
          <div class="dc-timeline">
            <div class="dc-role">
              <div class="dc-role-head"><span class="dc-role-title">Senior Software Engineer</span><span class="dc-role-dates">Apr 2024 &ndash; Present</span></div>
              <p class="dc-role-intro">One of two senior engineers retained during a major organisational restructure, sharing full ownership of the technical roadmap, third-party migrations, and the production platform.</p>
              <ul class="dc-bullets">
                <li>Designed and co-led the live integration of PeopleFirst as the new payroll calculation engine, maintaining backward compatibility across three simultaneous migration states (legacy-only, hybrid, fully migrated) in a single production codebase.</li>
                <li>Helped identify and close a critical reporting gap: PeopleFirst provided no LGPS pension returns, no BACS file generation, no payroll reporting. Contributed to a dedicated reporting layer consuming PeopleFirst data, protecting all existing client contracts post-migration.</li>
                <li>Contributed to a parallel-run quality gate that compared old and new system outputs byte-for-byte before each school cutover, catching zero financial discrepancies across all migrated schools.</li>
                <li>Helped maintain a three-tier multi-tenant database architecture (central registry, per-school SQL Server databases, and MAT shared databases) serving hundreds of isolated client datasets under GDPR.</li>
                <li>Part of the team responsible for 50+ bespoke LGPS pension fund report templates for individual UK council pension schemes (Bexley, Croydon, Dorset, Surrey, Gloucestershire, Kent, Wiltshire, Suffolk).</li>
                <li>Co-building Juniper's own in-house payroll &amp; HR platform with an HMRC-spec-compliant tax/NI engine, using an AI-native workflow (Claude Code, MCP servers) for implementation, migration tooling and tests.</li>
                <li>Contributing engineer on Juniper Intelligence, an Anthropic Claude-powered product giving school staff conversational access to attendance and assessment insights.</li>
              </ul>
              <div class="dc-callout">
                <span class="dc-callout-label">Independent Project &middot; CFO-commissioned</span>
                <p>SugarCRM / Zendesk integration, built solo end-to-end using Claude Code: a .NET 8 worker with watermark-based sync and resilient API handling, deployed on AWS (ECS/EventBridge) with 298 automated tests.</p>
              </div>
            </div>

            <div class="dc-role">
              <div class="dc-role-head"><span class="dc-role-title">Software Engineer &mdash; .NET Payroll</span><span class="dc-role-dates">Dec 2021 &ndash; Apr 2024</span></div>
              <ul class="dc-bullets">
                <li>Part of the team that rebuilt the core payroll platform from a legacy codebase using Onion Architecture alongside the legacy layer, applying a strangler fig pattern to migrate features incrementally without disrupting live payroll for hundreds of schools.</li>
                <li>Contributed to the per-tenant database resolution layer: a runtime resolver reads the central school registry, fetches server credentials from Azure Key Vault via Managed Identity, and assembles a per-school connection string at runtime, so no secrets ever touch disk.</li>
                <li>Helped architect the Application layer as vertical feature slices (Bank Accounts, Contracts, Employees, Back Pay, Pension Schemes) using typed request/response models, CQRS application services, and functional result types in place of exceptions.</li>
                <li>Contributed to the background worker scheduling engine: a .NET BackgroundService with a 60-second database-polling loop, a priority queue with jump-queue override, a master kill switch for zero-redeployment shutdowns, and 10+ typed processors covering LGPS, BACS, RTI, payslip email, approval, and queue processing.</li>
                <li>Helped establish Gitflow branching and Azure DevOps PR-driven state transitions for the team.</li>
              </ul>
            </div>
          </div>
        </div>

        <div class="dc-employer-group">
          <div class="dc-employer-name">
            <a href="https://www.paragon.com.kh/" target="_blank" rel="noopener">Paragon Education</a>
            <span class="loc">Cambodia</span>
          </div>
          <div class="dc-timeline">
            <div class="dc-role">
              <div class="dc-role-head"><span class="dc-role-title">Data Scientist</span><span class="dc-role-dates">2019 &ndash; Aug 2021</span></div>
              <ul class="dc-bullets">
                <li>Applied Python (Pandas, NumPy) and statistical analysis to build financial forecasting, reporting, and data-analysis tooling for school group leadership, alongside graduate study in Financial Engineering.</li>
                <li>Analysed financial and operational datasets to support data-driven decision-making across a Kindergarten-to-university international school group.</li>
              </ul>
            </div>
            <div class="dc-role">
              <div class="dc-role-head"><span class="dc-role-title">Mathematics Teacher</span><span class="dc-role-dates">2014 &ndash; 2019</span></div>
              <ul class="dc-bullets">
                <li>Taught A-Level Maths and Statistics in the high school section of a Kindergarten-to-university international school group before moving into data science.</li>
              </ul>
            </div>
          </div>
        </div>

        <h2 class="section-label">Personal Projects</h2>
        <div class="dc-employer-group">
          <div class="dc-timeline">
            <div class="dc-role">
              <div class="dc-role-head"><span class="dc-role-title">TakeawaySaaS &mdash; Multi-Tenant Takeaway Ordering Platform</span><span class="dc-role-dates">2026 &ndash; Present</span></div>
              <ul class="dc-bullets">
                <li>Designed and built a multi-tenant SaaS platform for takeaway ordering using an AI-native workflow (Claude Code): .NET 10, Blazor, Next.js 15, PostgreSQL and Stripe Connect. Real payments proven end-to-end; 950+ commits over 5 months.</li>
              </ul>
            </div>
          </div>
        </div>
      </div>

      <!-- RIGHT: SIDEBAR -->
      <aside class="dc-aside">
        <div>
          <h2 class="section-label">Education</h2>
          <div class="dc-edu-entry">
            <div class="dc-edu-degree">
              <a href="https://www.wqu.edu/applied-ai-fundamentals" target="_blank" rel="noopener">Graduate Certificate in Applied AI Fundamentals</a>
              <span class="dc-gpa-tag">In Progress</span>
            </div>
            <div class="dc-edu-meta">WorldQuant University</div>
          </div>
          <div class="dc-edu-entry">
            <div class="dc-edu-degree">
              <a href="https://www.credly.com/badges/8ff2e4d6-fb3c-462a-8570-5251b9ee35fc/public_url" target="_blank" rel="noopener">MSc Financial Engineering</a>
              <span class="dc-gpa-tag">93% GPA</span>
            </div>
            <div class="dc-edu-meta">
              WorldQuant University &middot; 2019&ndash;2021 &middot; USA<br>
              Thesis: <a href="https://github.com/abrahamsteep90/MSs_CapstoneProject" target="_blank" rel="noopener">PCA of the US Treasury Yield Curve</a>
            </div>
          </div>
          <div class="dc-edu-entry">
            <div class="dc-edu-degree">BSc Mathematics</div>
            <div class="dc-edu-meta">Ataturk University &middot; 2007&ndash;2011 &middot; Turkey</div>
          </div>
        </div>

        <div>
          <h2 class="section-label">Key Skills</h2>
          <div class="dc-skill-group">
            <span class="dc-skill-label">Languages</span>
            <div class="dc-chips"><span class="dc-chip">C#</span><span class="dc-chip">SQL/T-SQL</span><span class="dc-chip">Python</span><span class="dc-chip">TypeScript</span><span class="dc-chip">JavaScript</span><span class="dc-chip">R</span></div>
          </div>
          <div class="dc-skill-group">
            <span class="dc-skill-label">Frameworks</span>
            <div class="dc-chips"><span class="dc-chip">ASP.NET Core</span><span class="dc-chip">React</span><span class="dc-chip">Angular</span><span class="dc-chip">Vue.js</span><span class="dc-chip">Entity Framework Core</span><span class="dc-chip">EPPlus</span></div>
          </div>
          <div class="dc-skill-group">
            <span class="dc-skill-label">Data</span>
            <div class="dc-chips"><span class="dc-chip">SQL Server</span><span class="dc-chip">PostgreSQL</span><span class="dc-chip">SQLite</span><span class="dc-chip">Redis</span></div>
          </div>
          <div class="dc-skill-group">
            <span class="dc-skill-label">Cloud &amp; DevOps</span>
            <div class="dc-chips"><span class="dc-chip">Azure (AKS, Key Vault, Service Bus)</span><span class="dc-chip">AWS (ECS, EventBridge)</span><span class="dc-chip">Docker</span><span class="dc-chip">Azure DevOps</span><span class="dc-chip">GitHub Actions</span><span class="dc-chip">CI/CD</span></div>
          </div>
          <div class="dc-skill-group">
            <span class="dc-skill-label">Architecture</span>
            <div class="dc-chips"><span class="dc-chip">Clean/Onion Architecture</span><span class="dc-chip">DDD</span><span class="dc-chip">CQRS</span><span class="dc-chip">Multi-Tenant</span><span class="dc-chip">Microservices</span><span class="dc-chip">RESTful APIs</span></div>
          </div>
          <div class="dc-skill-group">
            <span class="dc-skill-label">AI-Native Engineering</span>
            <div class="dc-chips"><span class="dc-chip">Claude Code</span><span class="dc-chip">MCP servers</span><span class="dc-chip">Antigravity</span><span class="dc-chip">Codex</span><span class="dc-chip">JetBrains AIR</span><span class="dc-chip">JetBrains Junie</span></div>
          </div>
          <div class="dc-skill-group">
            <span class="dc-skill-label">Data &amp; ML</span>
            <div class="dc-chips"><span class="dc-chip">NumPy</span><span class="dc-chip">Pandas</span><span class="dc-chip">scikit-learn</span><span class="dc-chip">TensorFlow</span><span class="dc-chip">Keras</span></div>
          </div>
          <div class="dc-skill-group">
            <span class="dc-skill-label">Testing &amp; Delivery</span>
            <div class="dc-chips"><span class="dc-chip">xUnit</span><span class="dc-chip">NUnit</span><span class="dc-chip">TDD</span><span class="dc-chip">Playwright</span><span class="dc-chip">Kanban/Scrum</span><span class="dc-chip">Jira/Confluence</span></div>
          </div>
        </div>

        <div>
          <h2 class="section-label">Certifications</h2>
          <div class="dc-cert-list">
            <div class="dc-cert-item"><a href="https://www.coursera.org/account/accomplishments/specialization/certificate/VW22TKUX9E8S" target="_blank" rel="noopener">TensorFlow: Deployment <svg viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M7 17 17 7"/><path d="M7 7h10v10"/></svg></a></div>
            <div class="dc-cert-item"><a href="https://www.coursera.org/account/accomplishments/specialization/certificate/FREDR8Q42YSJ" target="_blank" rel="noopener">TensorFlow Developer <svg viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M7 17 17 7"/><path d="M7 7h10v10"/></svg></a></div>
            <div class="dc-cert-item"><a href="https://www.coursera.org/account/accomplishments/specialization/certificate/2FX8MYXMYV33" target="_blank" rel="noopener">IBM Applied AI <svg viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M7 17 17 7"/><path d="M7 7h10v10"/></svg></a></div>
            <div class="dc-cert-item"><a href="https://wqu.thedataincubator.com/certificate/5626716970024960_full" target="_blank" rel="noopener">WQU Applied Data Science <svg viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M7 17 17 7"/><path d="M7 7h10v10"/></svg></a></div>
            <div class="dc-cert-item"><a href="https://www.coursera.org/account/accomplishments/specialization/certificate/3S3EMMR8GJ45" target="_blank" rel="noopener">IBM Data Science Professional <svg viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M7 17 17 7"/><path d="M7 7h10v10"/></svg></a></div>
            <div class="dc-cert-item"><a href="https://www.coursera.org/account/accomplishments/specialization/certificate/HXH5XG6LB3R3" target="_blank" rel="noopener">Google IT Support <svg viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M7 17 17 7"/><path d="M7 7h10v10"/></svg></a></div>
            <div class="dc-cert-item"><a href="https://www.coursera.org/account/accomplishments/specialization/certificate/7SEMAG8WQTW8" target="_blank" rel="noopener">IBM Cybersecurity Analyst <svg viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M7 17 17 7"/><path d="M7 7h10v10"/></svg></a></div>
          </div>
        </div>
      </aside>
    </div>

    <footer class="trailer">Indefinite Leave to Remain &mdash; full right to work in the UK &middot; 2 weeks' notice period &middot; References on request</footer>
  </section>
</div>
</div>
</body>
</html>