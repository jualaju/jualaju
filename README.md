<div align="center">

<svg width="680" height="260" viewBox="0 0 680 260" xmlns="http://www.w3.org/2000/svg">
  <rect width="680" height="260" fill="#080808" rx="8"/>

  <!-- Binary rain streams (CSS animated) -->
  <style>
    .s1 { animation: fall1 6s linear infinite; }
    .s2 { animation: fall2 8s linear infinite; }
    .s3 { animation: fall3 7s linear infinite; }
    @keyframes fall1 {
      0%   { transform: translateY(-220px); opacity: 0; }
      10%  { opacity: 1; }
      85%  { opacity: 1; }
      100% { transform: translateY(260px); opacity: 0; }
    }
    @keyframes fall2 {
      0%   { transform: translateY(-160px); opacity: 0; }
      10%  { opacity: 1; }
      85%  { opacity: 1; }
      100% { transform: translateY(260px); opacity: 0; }
    }
    @keyframes fall3 {
      0%   { transform: translateY(-300px); opacity: 0; }
      10%  { opacity: 1; }
      85%  { opacity: 1; }
      100% { transform: translateY(260px); opacity: 0; }
    }
  </style>

  <!-- Stream 1 — x=600, len 18 -->
  <g class="s1">
    <text x="600" y="30"  font-family="Courier New" font-size="11" fill="#e2d4ff">1</text>
    <text x="600" y="43"  font-family="Courier New" font-size="11" fill="#c4b5fd">0</text>
    <text x="600" y="56"  font-family="Courier New" font-size="11" fill="#c4b5fd">1</text>
    <text x="600" y="69"  font-family="Courier New" font-size="11" fill="#7c3aed">0</text>
    <text x="600" y="82"  font-family="Courier New" font-size="11" fill="#7c3aed">1</text>
    <text x="600" y="95"  font-family="Courier New" font-size="11" fill="#5b21b6">0</text>
    <text x="600" y="108" font-family="Courier New" font-size="11" fill="#5b21b6">1</text>
    <text x="600" y="121" font-family="Courier New" font-size="11" fill="#4c1d95">0</text>
    <text x="600" y="134" font-family="Courier New" font-size="11" fill="#4c1d95">1</text>
    <text x="600" y="147" font-family="Courier New" font-size="11" fill="#3b0764">0</text>
    <text x="600" y="160" font-family="Courier New" font-size="11" fill="#3b0764">1</text>
    <text x="600" y="173" font-family="Courier New" font-size="11" fill="#2e0657">0</text>
    <text x="600" y="186" font-family="Courier New" font-size="11" fill="#220448">1</text>
    <text x="600" y="199" font-family="Courier New" font-size="11" fill="#1a0338">0</text>
  </g>

  <!-- Stream 2 — x=625, len 12 -->
  <g class="s2">
    <text x="625" y="30"  font-family="Courier New" font-size="11" fill="#e2d4ff">0</text>
    <text x="625" y="43"  font-family="Courier New" font-size="11" fill="#c4b5fd">1</text>
    <text x="625" y="56"  font-family="Courier New" font-size="11" fill="#c4b5fd">0</text>
    <text x="625" y="69"  font-family="Courier New" font-size="11" fill="#7c3aed">1</text>
    <text x="625" y="82"  font-family="Courier New" font-size="11" fill="#7c3aed">0</text>
    <text x="625" y="95"  font-family="Courier New" font-size="11" fill="#5b21b6">1</text>
    <text x="625" y="108" font-family="Courier New" font-size="11" fill="#4c1d95">0</text>
    <text x="625" y="121" font-family="Courier New" font-size="11" fill="#3b0764">1</text>
    <text x="625" y="134" font-family="Courier New" font-size="11" fill="#2e0657">0</text>
    <text x="625" y="147" font-family="Courier New" font-size="11" fill="#220448">1</text>
  </g>

  <!-- Stream 3 — x=648, len 22 -->
  <g class="s3">
    <text x="648" y="30"  font-family="Courier New" font-size="11" fill="#e2d4ff">1</text>
    <text x="648" y="43"  font-family="Courier New" font-size="11" fill="#c4b5fd">1</text>
    <text x="648" y="56"  font-family="Courier New" font-size="11" fill="#c4b5fd">0</text>
    <text x="648" y="69"  font-family="Courier New" font-size="11" fill="#a78bfa">1</text>
    <text x="648" y="82"  font-family="Courier New" font-size="11" fill="#7c3aed">0</text>
    <text x="648" y="95"  font-family="Courier New" font-size="11" fill="#7c3aed">1</text>
    <text x="648" y="108" font-family="Courier New" font-size="11" fill="#5b21b6">0</text>
    <text x="648" y="121" font-family="Courier New" font-size="11" fill="#5b21b6">1</text>
    <text x="648" y="134" font-family="Courier New" font-size="11" fill="#4c1d95">0</text>
    <text x="648" y="147" font-family="Courier New" font-size="11" fill="#4c1d95">1</text>
    <text x="648" y="160" font-family="Courier New" font-size="11" fill="#3b0764">0</text>
    <text x="648" y="173" font-family="Courier New" font-size="11" fill="#3b0764">1</text>
    <text x="648" y="186" font-family="Courier New" font-size="11" fill="#2e0657">0</text>
    <text x="648" y="199" font-family="Courier New" font-size="11" fill="#220448">1</text>
    <text x="648" y="212" font-family="Courier New" font-size="11" fill="#1a0338">0</text>
    <text x="648" y="225" font-family="Courier New" font-size="11" fill="#150229">1</text>
  </g>

  <!-- Name -->
  <text x="40" y="62" font-family="Courier New" font-size="34" font-weight="500" letter-spacing="5">
    <tspan fill="#7c3aed">J</tspan><tspan fill="#d8b4fe">U</tspan><tspan fill="#7c3aed">A</tspan><tspan fill="#d8b4fe">L</tspan><tspan fill="#e2e8f0"> </tspan><tspan fill="#7c3aed">A</tspan><tspan fill="#d8b4fe">J</tspan><tspan fill="#7c3aed">U</tspan>
  </text>

  <!-- Subtitle -->
  <text x="40" y="82" font-family="Courier New" font-size="10" letter-spacing="7" fill="#2e2e2e">CS_UNDERGRAD</text>

  <!-- Tagline -->
  <text x="40" y="104" font-family="Courier New" font-size="11" fill="#383838">// built from curiosity. running on coffee and a passion for tech.</text>

  <!-- Divider -->
  <line x1="40" y1="116" x2="580" y2="116" stroke="#111" stroke-width="0.5"/>

  <!-- Left border -->
  <line x1="40" y1="130" x2="40" y2="198" stroke="#1a1a1a" stroke-width="1"/>

  <!-- Interest rows -->
  <text x="56" y="144" font-family="Courier New" font-size="12" fill="#22c55e">▸</text>
  <text x="72" y="144" font-family="Courier New" font-size="12" fill="#94a3b8">linux mint</text>
  <text x="195" y="144" font-family="Courier New" font-size="12" fill="#1e1e1e">················</text>
  <text x="348" y="144" font-family="Courier New" font-size="12" fill="#64748b">daily driver</text>

  <text x="56" y="160" font-family="Courier New" font-size="12" fill="#22c55e">▸</text>
  <text x="72" y="160" font-family="Courier New" font-size="12" fill="#94a3b8">networking / OS</text>
  <text x="228" y="160" font-family="Courier New" font-size="12" fill="#1e1e1e">·········</text>
  <text x="348" y="160" font-family="Courier New" font-size="12" fill="#64748b">primary interest</text>

  <text x="56" y="176" font-family="Courier New" font-size="12" fill="#f59e0b">▸</text>
  <text x="72" y="176" font-family="Courier New" font-size="12" fill="#94a3b8">cybersecurity</text>
  <text x="207" y="176" font-family="Courier New" font-size="12" fill="#1e1e1e">··········</text>
  <text x="348" y="176" font-family="Courier New" font-size="12" fill="#64748b">currently exploring</text>

  <text x="56" y="192" font-family="Courier New" font-size="12" fill="#a855f7">▸</text>
  <text x="72" y="192" font-family="Courier New" font-size="12" fill="#94a3b8">web + AI/ML</text>
  <text x="192" y="192" font-family="Courier New" font-size="12" fill="#1e1e1e">············</text>
  <text x="348" y="192" font-family="Courier New" font-size="12" fill="#64748b">side quests</text>

  <!-- Divider 2 -->
  <line x1="40" y1="208" x2="580" y2="208" stroke="#111" stroke-width="0.5"/>

  <!-- Women in tech -->
  <rect x="40" y="216" width="5" height="26" rx="2" fill="#7c3aed"/>
  <text x="54" y="227" font-family="Courier New" font-size="11" fill="#d8b4fe">Women In Tech — lead at Tinkerhub</text>
  <text x="54" y="241" font-family="Courier New" font-size="10" fill="#444">opening doors for girls who haven't found theirs yet.</text>

  <!-- Tech stack -->
  <text x="40" y="257" font-family="Courier New" font-size="10" fill="#1e1e1e">── python · c · c++ · next.js · node · postgresql · opencv · yolov8 · rpi ──</text>
</svg>

</div>
