<svg width="900" height="200" viewBox="0 0 900 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#8A2BE2">
        <animate attributeName="stop-color" values="#8A2BE2;#FF69B4;#00BFFF;#8A2BE2" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#00BFFF">
        <animate attributeName="stop-color" values="#00BFFF;#8A2BE2;#FF69B4;#00BFFF" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <rect width="900" height="200" rx="22" fill="#0d1117"/>
  <rect x="3" y="3" width="894" height="194" rx="19" fill="none" stroke="url(#grad1)" stroke-width="3"/>

  <text x="450" y="85" text-anchor="middle" font-family="Trebuchet MS, Verdana, sans-serif" font-size="34" font-weight="bold" fill="url(#grad1)" filter="url(#glow)">
    Hi, I'm Sathiyapriya
    <animate attributeName="opacity" values="0.5;1;0.5" dur="3s" repeatCount="indefinite"/>
  </text>

  <text x="450" y="125" text-anchor="middle" font-family="Fira Code, Courier New, monospace" font-size="17" fill="#c9d1d9">
    Cloud Computing &#8226; Blockchain &#8226; Full-Stack Development
  </text>

  <text x="450" y="160" text-anchor="middle" font-family="Georgia, serif" font-size="15" font-style="italic" fill="#a29bfe">
    "Curious mind, always building something new."
    <animate attributeName="opacity" values="0;1;1;0" dur="5s" repeatCount="indefinite"/>
  </text>

  <!-- floating particles -->
  <circle cx="70" cy="170" r="5" fill="#FF69B4">
    <animate attributeName="cy" values="170;40;170" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;0" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="140" cy="180" r="4" fill="#00BFFF">
    <animate attributeName="cy" values="180;50;180" dur="4s" begin="0.7s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;0" dur="4s" begin="0.7s" repeatCount="indefinite"/>
  </circle>
  <circle cx="810" cy="175" r="5" fill="#8A2BE2">
    <animate attributeName="cy" values="175;45;175" dur="4.5s" begin="1.2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;0" dur="4.5s" begin="1.2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="750" cy="185" r="4" fill="#FF69B4">
    <animate attributeName="cy" values="185;55;185" dur="5.5s" begin="0.3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;0" dur="5.5s" begin="0.3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="450" cy="190" r="3" fill="#00BFFF">
    <animate attributeName="cy" values="190;170;190" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.2;0.8;0.2" dur="3s" repeatCount="indefinite"/>
  </circle>
</svg>
<svg width="880" height="220" viewBox="0 0 880 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="pg1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#FF6B6B"/>
      <stop offset="100%" stop-color="#8A2BE2"/>
    </linearGradient>
    <filter id="shadow1" x="-30%" y="-30%" width="160%" height="160%">
      <feDropShadow dx="0" dy="6" stdDeviation="8" flood-color="#8A2BE2" flood-opacity="0.55"/>
    </filter>
    <filter id="glow1">
      <feGaussianBlur stdDeviation="2.5" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <g filter="url(#shadow1)">
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-6; 0,0" dur="3.5s" repeatCount="indefinite"/>
    <rect x="20" y="15" width="840" height="150" rx="18" fill="#12071f" stroke="url(#pg1)" stroke-width="2.5"/>
    <text x="45" y="55" font-family="Impact, Charcoal, sans-serif" font-size="26" fill="url(#pg1)" filter="url(#glow1)">
      🔐 Dynamic Secret Sharing Scheme
    </text>
    <text x="45" y="80" font-family="Georgia, serif" font-size="15" fill="#c9d1d9">
      RSA-Based Blockchain Encryption &#8226; 2025
    </text>
    <text x="45" y="110" font-family="Trebuchet MS, sans-serif" font-size="13" fill="#a8a8b3">
      Secure text extraction with tamper-proof, transparent access logs
    </text>
    <text x="45" y="130" font-family="Trebuchet MS, sans-serif" font-size="13" fill="#a8a8b3">
      on a blockchain ledger.
    </text>
  </g>

  <!-- floating tag chips -->
  <g font-family="Courier New, monospace" font-size="12" fill="#ffffff">
    <g>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-5; 0,0" dur="2.4s" repeatCount="indefinite"/>
      <rect x="45" y="180" width="70" height="24" rx="12" fill="#FF6B6B"/>
      <text x="80" y="196" text-anchor="middle">Python</text>
    </g>
    <g>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-5; 0,0" dur="2.4s" begin="0.3s" repeatCount="indefinite"/>
      <rect x="125" y="180" width="60" height="24" rx="12" fill="#8A2BE2"/>
      <text x="155" y="196" text-anchor="middle">Flask</text>
    </g>
    <g>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-5; 0,0" dur="2.4s" begin="0.6s" repeatCount="indefinite"/>
      <rect x="195" y="180" width="90" height="24" rx="12" fill="#00BFFF"/>
      <text x="240" y="196" text-anchor="middle">Streamlit</text>
    </g>
    <g>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-5; 0,0" dur="2.4s" begin="0.9s" repeatCount="indefinite"/>
      <rect x="295" y="180" width="100" height="24" rx="12" fill="#FF69B4"/>
      <text x="345" y="196" text-anchor="middle">Blockchain</text>
    </g>
    <g>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-5; 0,0" dur="2.4s" begin="1.2s" repeatCount="indefinite"/>
      <rect x="405" y="180" width="130" height="24" rx="12" fill="#6C5CE7"/>
      <text x="470" y="196" text-anchor="middle">RSA Encryption</text>
    </g>
  </g>
</svg>
<svg width="880" height="220" viewBox="0 0 880 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="pg2" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#00BFFF"/>
      <stop offset="100%" stop-color="#00e0a0"/>
    </linearGradient>
    <filter id="shadow2" x="-30%" y="-30%" width="160%" height="160%">
      <feDropShadow dx="0" dy="6" stdDeviation="8" flood-color="#00BFFF" flood-opacity="0.55"/>
    </filter>
    <filter id="glow2">
      <feGaussianBlur stdDeviation="2.5" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <g filter="url(#shadow2)">
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-6; 0,0" dur="3.8s" begin="0.4s" repeatCount="indefinite"/>
    <rect x="20" y="15" width="840" height="150" rx="18" fill="#071a1f" stroke="url(#pg2)" stroke-width="2.5"/>
    <text x="45" y="55" font-family="Brush Script MT, cursive, sans-serif" font-size="30" fill="url(#pg2)" filter="url(#glow2)">
      🐾 Vet Care
    </text>
    <text x="45" y="82" font-family="Verdana, sans-serif" font-size="14" fill="#c9d1d9">
      Animal Medical Solution-Based Application &#8226; 2023
    </text>
    <text x="45" y="110" font-family="Trebuchet MS, sans-serif" font-size="13" fill="#a8d8e8">
      Remote vet consultations for farmers &amp; pet owners via video,
    </text>
    <text x="45" y="130" font-family="Trebuchet MS, sans-serif" font-size="13" fill="#a8d8e8">
      audio, image or text — built for rural reach.
    </text>
  </g>

  <g font-family="Courier New, monospace" font-size="12" fill="#04202a">
    <g>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-5; 0,0" dur="2.6s" repeatCount="indefinite"/>
      <rect x="45" y="180" width="80" height="24" rx="12" fill="#00e0a0"/>
      <text x="85" y="196" text-anchor="middle">Android</text>
    </g>
    <g>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-5; 0,0" dur="2.6s" begin="0.35s" repeatCount="indefinite"/>
      <rect x="135" y="180" width="130" height="24" rx="12" fill="#00BFFF"/>
      <text x="200" y="196" text-anchor="middle">AI Diagnostics</text>
    </g>
    <g>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-5; 0,0" dur="2.6s" begin="0.7s" repeatCount="indefinite"/>
      <rect x="275" y="180" width="140" height="24" rx="12" fill="#38ada9"/>
      <text x="345" y="196" text-anchor="middle">Cloud Computing</text>
    </g>
    <g>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-5; 0,0" dur="2.6s" begin="1.05s" repeatCount="indefinite"/>
      <rect x="425" y="180" width="150" height="24" rx="12" fill="#0abde3"/>
      <text x="500" y="196" text-anchor="middle">Mobile App Dev</text>
    </g>
  </g>
</svg>
<svg width="900" height="420" viewBox="0 0 900 420" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <filter id="cshadow" x="-40%" y="-40%" width="180%" height="180%">
      <feDropShadow dx="0" dy="8" stdDeviation="9" flood-color="#000000" flood-opacity="0.5"/>
    </filter>
    <filter id="cglow">
      <feGaussianBlur stdDeviation="1.6" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <rect width="900" height="420" fill="#0a0a12"/>
  <text x="450" y="30" text-anchor="middle" font-family="Trebuchet MS, sans-serif" font-size="18" fill="#ffffff" font-weight="bold">
    📜 Certifications &amp; Achievements
  </text>

  <!-- Card 1 -->
  <g filter="url(#cshadow)">
    <animateTransform attributeName="transform" type="translate" values="30,50; 30,42; 30,50" dur="3.2s" repeatCount="indefinite"/>
    <rect width="260" height="150" rx="16" fill="#1b0f2e" stroke="#FF6B6B" stroke-width="2"/>
    <text x="20" y="35" font-size="22">🔗</text>
    <text x="20" y="70" font-family="Georgia, serif" font-size="16" fill="#FF6B6B" font-weight="bold" filter="url(#cglow)">Blockchain &amp;</text>
    <text x="20" y="92" font-family="Georgia, serif" font-size="16" fill="#FF6B6B" font-weight="bold" filter="url(#cglow)">Cybersecurity</text>
    <text x="20" y="120" font-family="Verdana, sans-serif" font-size="12" fill="#c9c9d9">Itronix Solutions</text>
    <text x="20" y="138" font-family="Verdana, sans-serif" font-size="12" fill="#8b8ba0">2025</text>
  </g>

  <!-- Card 2 -->
  <g filter="url(#cshadow)">
    <animateTransform attributeName="transform" type="translate" values="320,50; 320,58; 320,50" dur="3.6s" begin="0.4s" repeatCount="indefinite"/>
    <rect width="260" height="150" rx="16" fill="#0f1e2e" stroke="#00BFFF" stroke-width="2"/>
    <text x="20" y="35" font-size="22">☁️</text>
    <text x="20" y="70" font-family="Trebuchet MS, sans-serif" font-size="16" fill="#00BFFF" font-weight="bold" filter="url(#cglow)">AWS Cloud</text>
    <text x="20" y="92" font-family="Trebuchet MS, sans-serif" font-size="16" fill="#00BFFF" font-weight="bold" filter="url(#cglow)">Technical Essentials</text>
    <text x="20" y="120" font-family="Verdana, sans-serif" font-size="12" fill="#c9c9d9">Coursera &#8226; AWS</text>
    <text x="20" y="138" font-family="Verdana, sans-serif" font-size="12" fill="#8b8ba0">2025</text>
  </g>

  <!-- Card 3 -->
  <g filter="url(#cshadow)">
    <animateTransform attributeName="transform" type="translate" values="610,50; 610,42; 610,50" dur="3.9s" begin="0.8s" repeatCount="indefinite"/>
    <rect width="260" height="150" rx="16" fill="#1e0f2a" stroke="#8A2BE2" stroke-width="2"/>
    <text x="20" y="35" font-size="22">🤖</text>
    <text x="20" y="70" font-family="Courier New, monospace" font-size="15" fill="#c07dff" font-weight="bold" filter="url(#cglow)">AI Agents:</text>
    <text x="20" y="92" font-family="Courier New, monospace" font-size="15" fill="#c07dff" font-weight="bold" filter="url(#cglow)">RAG &amp; LangChain</text>
    <text x="20" y="120" font-family="Verdana, sans-serif" font-size="12" fill="#c9c9d9">Coursera &#8226; IBM</text>
    <text x="20" y="138" font-family="Verdana, sans-serif" font-size="12" fill="#8b8ba0">2025</text>
  </g>

  <!-- Card 4 -->
  <g filter="url(#cshadow)">
    <animateTransform attributeName="transform" type="translate" values="30,230; 30,238; 30,230" dur="3.4s" begin="0.2s" repeatCount="indefinite"/>
    <rect width="260" height="150" rx="16" fill="#0f2a1e" stroke="#00e0a0" stroke-width="2"/>
    <text x="20" y="35" font-size="22">🧪</text>
    <text x="20" y="70" font-family="Impact, sans-serif" font-size="18" fill="#00e0a0" filter="url(#cglow)">SOFTWARE</text>
    <text x="20" y="92" font-family="Impact, sans-serif" font-size="18" fill="#00e0a0" filter="url(#cglow)">TESTING</text>
    <text x="20" y="120" font-family="Verdana, sans-serif" font-size="12" fill="#c9c9d9">SWAYAM NPTEL</text>
    <text x="20" y="138" font-family="Verdana, sans-serif" font-size="12" fill="#8b8ba0">2024</text>
  </g>

  <!-- Card 5 -->
  <g filter="url(#cshadow)">
    <animateTransform attributeName="transform" type="translate" values="320,230; 320,222; 320,230" dur="3.1s" begin="0.6s" repeatCount="indefinite"/>
    <rect width="260" height="150" rx="16" fill="#1a1a2e" stroke="#FFD93D" stroke-width="2"/>
    <text x="20" y="35" font-size="22">📊</text>
    <text x="20" y="70" font-family="Segoe UI, sans-serif" font-size="15" fill="#FFD93D" font-weight="bold" filter="url(#cglow)">Data Analysis</text>
    <text x="20" y="92" font-family="Segoe UI, sans-serif" font-size="15" fill="#FFD93D" font-weight="bold" filter="url(#cglow)">with Excel</text>
    <text x="20" y="120" font-family="Verdana, sans-serif" font-size="12" fill="#c9c9d9">Coursera &#8226; Microsoft</text>
    <text x="20" y="138" font-family="Verdana, sans-serif" font-size="12" fill="#8b8ba0">2025</text>
  </g>

  <!-- Card 6 -->
  <g filter="url(#cshadow)">
    <animateTransform attributeName="transform" type="translate" values="610,230; 610,238; 610,230" dur="3.7s" begin="1s" repeatCount="indefinite"/>
    <rect width="260" height="150" rx="16" fill="#0f1f2a" stroke="#38ada9" stroke-width="2"/>
    <text x="20" y="35" font-size="22">☁️</text>
    <text x="20" y="70" font-family="Brush Script MT, cursive" font-size="22" fill="#38ada9" filter="url(#cglow)">Cloud 101</text>
    <text x="20" y="95" font-family="Georgia, serif" font-size="13" fill="#8ce0d8">Cloud Computing Basics</text>
    <text x="20" y="120" font-family="Verdana, sans-serif" font-size="12" fill="#c9c9d9">Coursera</text>
    <text x="20" y="138" font-family="Verdana, sans-serif" font-size="12" fill="#8b8ba0">2022</text>
  </g>
</svg>
