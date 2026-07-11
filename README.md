<svg viewBox="0 0 1200 520" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0d0e1a"/>
      <stop offset="50%" stop-color="#1a1b27"/>
      <stop offset="100%" stop-color="#12141f"/>
    </linearGradient>
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#7aa2f7"/>
      <stop offset="50%" stop-color="#bb9af7"/>
      <stop offset="100%" stop-color="#7dcfff"/>
    </linearGradient>
    <radialGradient id="glow1" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#7aa2f7" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#7aa2f7" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glow2" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#bb9af7" stop-opacity="0.3"/>
      <stop offset="100%" stop-color="#bb9af7" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="screenGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#1f2540"/>
      <stop offset="100%" stop-color="#0d0e1a"/>
    </linearGradient>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#7aa2f7" stroke-opacity="0.06" stroke-width="1"/>
    </pattern>
  </defs>

  <!-- background -->
  <rect width="1200" height="520" fill="url(#bg)"/>
  <rect width="1200" height="520" fill="url(#grid)"/>
  <circle cx="220" cy="120" r="220" fill="url(#glow1)"/>
  <circle cx="980" cy="400" r="240" fill="url(#glow2)"/>

  <!-- floating code decorations -->
  <text x="70" y="90" font-family="Fira Code, monospace" font-size="26" fill="#7aa2f7" opacity="0.5">&lt;/&gt;</text>
  <text x="1080" y="470" font-family="Fira Code, monospace" font-size="30" fill="#bb9af7" opacity="0.45">{ }</text>
  <text x="60" y="470" font-family="Fira Code, monospace" font-size="22" fill="#7dcfff" opacity="0.4">01010</text>
  <text x="1090" y="80" font-family="Fira Code, monospace" font-size="22" fill="#7dcfff" opacity="0.4">;;</text>

  <!-- name and details, top center -->
  <text x="600" y="80" font-family="Poppins, Segoe UI, Arial, sans-serif" font-size="52" font-weight="700" fill="url(#nameGrad)" text-anchor="middle" letter-spacing="1">
    SIVABALAN MANOGAR
  </text>
  <text x="600" y="118" font-family="Fira Code, monospace" font-size="20" fill="#c0caf5" text-anchor="middle" letter-spacing="1">
    B.Tech Information Technology · Full Stack Developer
  </text>
  <text x="600" y="148" font-family="Fira Code, monospace" font-size="17" fill="#7aa2f7" text-anchor="middle" letter-spacing="1">
    MERN Stack &#8226; Data Science &#8226; Machine Learning
  </text>

  <!-- divider -->
  <line x1="420" y1="172" x2="780" y2="172" stroke="url(#nameGrad)" stroke-width="2" opacity="0.6"/>

  <!-- desk illustration -->
  <g transform="translate(600,340)">
    <!-- desk surface -->
    <ellipse cx="0" cy="150" rx="480" ry="34" fill="#0a0b14"/>

    <!-- monitor 1 (left) -->
    <g transform="translate(-160,-20)">
      <rect x="-115" y="-95" width="230" height="150" rx="10" fill="#12141f" stroke="#7aa2f7" stroke-width="2"/>
      <rect x="-100" y="-80" width="200" height="120" rx="4" fill="url(#screenGrad)"/>
      <!-- code lines -->
      <rect x="-88" y="-68" width="60" height="6" rx="3" fill="#7aa2f7" opacity="0.9"/>
      <rect x="-88" y="-54" width="100" height="6" rx="3" fill="#bb9af7" opacity="0.8"/>
      <rect x="-88" y="-40" width="80" height="6" rx="3" fill="#7dcfff" opacity="0.8"/>
      <rect x="-70" y="-26" width="90" height="6" rx="3" fill="#7aa2f7" opacity="0.7"/>
      <rect x="-88" y="-12" width="70" height="6" rx="3" fill="#bb9af7" opacity="0.7"/>
      <rect x="-70" y="2" width="60" height="6" rx="3" fill="#7dcfff" opacity="0.6"/>
      <rect x="-88" y="16" width="110" height="6" rx="3" fill="#7aa2f7" opacity="0.6"/>
      <rect x="-88" y="30" width="40" height="6" rx="3" fill="#bb9af7" opacity="0.5"/>
      <!-- stand -->
      <rect x="-14" y="55" width="28" height="18" fill="#12141f" stroke="#7aa2f7" stroke-width="1.5"/>
      <rect x="-46" y="73" width="92" height="10" rx="4" fill="#12141f" stroke="#7aa2f7" stroke-width="1.5"/>
    </g>

    <!-- monitor 2 (right, main) -->
    <g transform="translate(100,-45)">
      <rect x="-140" y="-115" width="280" height="185" rx="12" fill="#12141f" stroke="#bb9af7" stroke-width="2.5"/>
      <rect x="-122" y="-98" width="244" height="150" rx="6" fill="url(#screenGrad)"/>
      <!-- dashboard: pie chart -->
      <circle cx="-55" cy="-40" r="34" fill="none" stroke="#1f2540" stroke-width="14"/>
      <circle cx="-55" cy="-40" r="34" fill="none" stroke="#7aa2f7" stroke-width="14" stroke-dasharray="90 130" stroke-linecap="round"/>
      <circle cx="-55" cy="-40" r="34" fill="none" stroke="#bb9af7" stroke-width="14" stroke-dasharray="55 130" stroke-dashoffset="-90" stroke-linecap="round"/>
      <circle cx="-55" cy="-40" r="34" fill="none" stroke="#7dcfff" stroke-width="14" stroke-dasharray="30 130" stroke-dashoffset="-145" stroke-linecap="round"/>
      <!-- bar chart -->
      <rect x="10" y="-30" width="14" height="34" fill="#7aa2f7"/>
      <rect x="30" y="-48" width="14" height="52" fill="#bb9af7"/>
      <rect x="50" y="-20" width="14" height="24" fill="#7dcfff"/>
      <rect x="70" y="-58" width="14" height="62" fill="#7aa2f7"/>
      <rect x="90" y="-38" width="14" height="42" fill="#bb9af7"/>
      <!-- line graph -->
      <polyline points="-115,25 -85,10 -55,32 -25,5 5,20 35,-5 65,15 95,-8" fill="none" stroke="#7dcfff" stroke-width="3" opacity="0.9"/>
      <!-- stand -->
      <rect x="-16" y="70" width="32" height="20" fill="#12141f" stroke="#bb9af7" stroke-width="1.5"/>
      <rect x="-55" y="90" width="110" height="11" rx="4" fill="#12141f" stroke="#bb9af7" stroke-width="1.5"/>
    </g>

    <!-- phone -->
    <g transform="translate(-330,90)">
      <rect x="-16" y="-30" width="32" height="60" rx="6" fill="#12141f" stroke="#7aa2f7" stroke-width="1.5"/>
      <rect x="-11" y="-23" width="22" height="46" rx="2" fill="#1f2540"/>
      <rect x="-8" y="-16" width="16" height="4" rx="2" fill="#7dcfff"/>
      <rect x="-8" y="-6" width="12" height="4" rx="2" fill="#bb9af7"/>
    </g>

    <!-- keyboard -->
    <rect x="-30" y="95" width="150" height="45" rx="8" fill="#12141f" stroke="#7aa2f7" stroke-width="1.5" transform="skewX(-8)"/>

    <!-- person from back -->
    <g transform="translate(70,60)">
      <!-- body -->
      <path d="M -95,120 Q -100,20 -20,-10 Q 40,-30 100,-5 Q 150,15 150,120 Z" fill="#1b2030"/>
      <!-- headphone band -->
      <path d="M -40,-70 Q 0,-100 40,-70" fill="none" stroke="#7dcfff" stroke-width="6" stroke-linecap="round"/>
      <!-- head -->
      <circle cx="0" cy="-55" r="42" fill="#e8b98a"/>
      <path d="M -42,-60 Q -45,-95 0,-98 Q 45,-95 42,-60 Q 42,-80 0,-84 Q -42,-80 -42,-60 Z" fill="#2b2438"/>
      <!-- headphone cups -->
      <ellipse cx="-40" cy="-50" rx="12" ry="18" fill="#7dcfff"/>
      <ellipse cx="40" cy="-50" rx="12" ry="18" fill="#7dcfff"/>
      <!-- arms typing -->
      <path d="M -60,10 Q -30,55 10,60" fill="none" stroke="#e8b98a" stroke-width="20" stroke-linecap="round"/>
      <path d="M 90,5 Q 70,50 40,58" fill="none" stroke="#e8b98a" stroke-width="20" stroke-linecap="round"/>
    </g>
  </g>

  <!-- border frame -->
  <rect x="4" y="4" width="1192" height="512" rx="16" fill="none" stroke="url(#nameGrad)" stroke-width="2" opacity="0.35"/>
</svg>
