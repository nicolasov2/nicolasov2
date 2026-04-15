<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 220">
  <defs>
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;700&amp;family=Space+Mono&amp;display=swap');

      .bg { fill: #000000; }
      .title {
        font-family: 'Space Grotesk', sans-serif;
        font-weight: 700;
        font-size: 42px;
        fill: #ffffff;
      }
      .subtitle {
        font-family: 'Space Mono', monospace;
        font-size: 14px;
        fill: #888888;
      }
      .accent-dot {
        fill: #ff2d00;
        animation: pulse 2.5s ease-in-out infinite;
      }
      .line {
        stroke: #ff2d00;
        stroke-width: 1.5;
        animation: draw 2s ease-out forwards;
        stroke-dasharray: 200;
        stroke-dashoffset: 200;
      }
      .grid-line {
        stroke: #111111;
        stroke-width: 0.5;
      }
      .tag {
        font-family: 'Space Mono', monospace;
        font-size: 11px;
        fill: #444444;
      }
      .tag-active {
        font-family: 'Space Mono', monospace;
        font-size: 11px;
        fill: #ff2d00;
      }
      .version {
        font-family: 'Space Mono', monospace;
        font-size: 10px;
        fill: #333333;
      }
      .nr-box {
        fill: none;
        stroke: #222222;
        stroke-width: 1;
      }
      .nr-text {
        font-family: 'Space Grotesk', sans-serif;
        font-weight: 700;
        font-size: 22px;
        fill: #ffffff;
      }

      /* Scan line effect */
      .scanline {
        fill: rgba(255, 45, 0, 0.03);
        animation: scan 4s linear infinite;
      }

      @keyframes pulse {
        0%, 100% { opacity: 1; r: 5; }
        50% { opacity: 0.4; r: 3; }
      }
      @keyframes draw {
        to { stroke-dashoffset: 0; }
      }
      @keyframes scan {
        0% { transform: translateY(-220px); }
        100% { transform: translateY(220px); }
      }

      /* Fade in for text elements */
      .fade-in {
        opacity: 0;
        animation: fadeIn 1s ease-out forwards;
      }
      .fade-in-delay-1 { animation-delay: 0.3s; }
      .fade-in-delay-2 { animation-delay: 0.6s; }
      .fade-in-delay-3 { animation-delay: 0.9s; }

      @keyframes fadeIn {
        to { opacity: 1; }
      }

      /* Blinking cursor */
      .cursor {
        fill: #ff2d00;
        animation: blink 1s step-end infinite;
      }
      @keyframes blink {
        0%, 100% { opacity: 1; }
        50% { opacity: 0; }
      }
    </style>
  </defs>

  <!-- Background -->
  <rect class="bg" width="900" height="220" rx="6"/>

  <!-- Subtle grid -->
  <line class="grid-line" x1="0" y1="55" x2="900" y2="55"/>
  <line class="grid-line" x1="0" y1="110" x2="900" y2="110"/>
  <line class="grid-line" x1="0" y1="165" x2="900" y2="165"/>
  <line class="grid-line" x1="60" y1="0" x2="60" y2="220"/>
  <line class="grid-line" x1="840" y1="0" x2="840" y2="220"/>

  <!-- Scan line -->
  <rect class="scanline" x="0" y="0" width="900" height="4"/>

  <!-- NR mark -->
  <rect class="nr-box" x="20" y="20" width="28" height="28" rx="2"/>
  <text class="nr-text" x="23" y="42">NR</text>
  <circle class="accent-dot" cx="50" cy="22" r="3"/>

  <!-- Version tag top right -->
  <text class="version" x="830" y="35" text-anchor="end">v2026.04</text>

  <!-- Main title -->
  <text class="title fade-in" x="80" y="95">Nicolás Ramírez</text>
  <rect class="cursor" x="455" y="68" width="2" height="32" rx="1"/>

  <!-- Red accent line -->
  <line class="line" x1="80" y1="110" x2="280" y2="110"/>

  <!-- Subtitle -->
  <text class="subtitle fade-in fade-in-delay-1" x="80" y="138">full-stack developer · typescript · next.js · postgresql</text>

  <!-- Tags bottom -->
  <text class="tag fade-in fade-in-delay-2" x="80" y="185">valparaíso, chile</text>
  <text class="tag" x="250" y="185">·</text>
  <text class="tag-active fade-in fade-in-delay-2" x="270" y="185">open to opportunities</text>
  <text class="tag" x="460" y="185">·</text>
  <text class="tag fade-in fade-in-delay-3" x="480" y="185">nfr innovaciones web spa</text>

  <!-- Decorative dots bottom right -->
  <circle cx="810" cy="180" r="1.5" fill="#222222"/>
  <circle cx="820" cy="180" r="1.5" fill="#222222"/>
  <circle cx="830" cy="180" r="1.5" fill="#ff2d00" opacity="0.6"/>
  <circle cx="810" cy="190" r="1.5" fill="#222222"/>
  <circle cx="820" cy="190" r="1.5" fill="#ff2d00" opacity="0.4"/>
  <circle cx="830" cy="190" r="1.5" fill="#222222"/>
  <circle cx="810" cy="200" r="1.5" fill="#ff2d00" opacity="0.8"/>
  <circle cx="820" cy="200" r="1.5" fill="#222222"/>
  <circle cx="830" cy="200" r="1.5" fill="#222222"/>
</svg>
