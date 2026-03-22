<svg width="400" height="420" viewBox="0 0 400 420" xmlns="http://www.w3.org/2000/svg">
<style>
  @keyframes blink { 0%,90%,100%{transform:scaleY(1)} 95%{transform:scaleY(0.1)} }
  @keyframes tail { 0%,100%{transform:rotate(-15deg)} 50%{transform:rotate(15deg)} }
  @keyframes float { 0%,100%{transform:translateY(0px)} 50%{transform:translateY(-8px)} }
  @keyframes sparkle { 0%,100%{opacity:0;transform:scale(0)} 50%{opacity:1;transform:scale(1)} }
  @keyframes heartbeat { 0%,100%{transform:scale(1)} 50%{transform:scale(1.2)} }
  .cat-group { animation: float 3s ease-in-out infinite; transform-origin: 200px 270px; }
  .tail-group { animation: tail 1.5s ease-in-out infinite; transform-origin: 155px 310px; }
  .blink-l { animation: blink 4s ease-in-out infinite; transform-origin: 170px 218px; }
  .blink-r { animation: blink 4s ease-in-out infinite 0.1s; transform-origin: 228px 218px; }
  .sp1 { animation: sparkle 2s ease-in-out infinite; transform-origin: 310px 80px; }
  .sp2 { animation: sparkle 2s ease-in-out infinite 0.6s; transform-origin: 80px 100px; }
  .sp3 { animation: sparkle 2s ease-in-out infinite 1.2s; transform-origin: 330px 160px; }
  .sp4 { animation: sparkle 2s ease-in-out infinite 0.3s; transform-origin: 60px 180px; }
  .heart { animation: heartbeat 1.2s ease-in-out infinite; transform-origin: 280px 115px; }
</style>

<!-- bg -->
<rect width="400" height="420" rx="20" fill="#fff0f5"/>
<pattern id="dots" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
  <circle cx="10" cy="10" r="1.5" fill="#FFB6C1" opacity="0.4"/>
</pattern>
<rect width="400" height="420" rx="20" fill="url(#dots)"/>

<!-- sparkles -->
<g class="sp1">
  <polygon points="310,66 313,74 321,74 315,79 317,87 310,82 303,87 305,79 299,74 307,74" fill="#FF85A2" opacity="0.9"/>
</g>
<g class="sp2">
  <polygon points="80,88 83,96 91,96 85,101 87,109 80,104 73,109 75,101 69,96 77,96" fill="#FF69B4" opacity="0.9"/>
</g>
<g class="sp3">
  <polygon points="330,148 332,154 338,154 333,158 335,164 330,160 325,164 327,158 322,154 328,154" fill="#FFB6C1" opacity="0.85"/>
</g>
<g class="sp4">
  <polygon points="60,168 62,174 68,174 63,178 65,184 60,180 55,184 57,178 52,174 58,174" fill="#FF85A2" opacity="0.85"/>
</g>

<!-- bg hearts -->
<g opacity="0.25">
  <path d="M48,72 Q48,60 57,65 Q60,55 69,65 Q78,60 78,72 Q78,84 60,94 Q42,84 48,72Z" fill="#FF69B4"/>
  <path d="M322,50 Q322,40 330,44 Q333,35 341,44 Q349,40 349,50 Q349,60 333,69 Q317,60 322,50Z" fill="#FF85A2"/>
</g>

<!-- CAT -->
<g class="cat-group">
  <!-- tail -->
  <g class="tail-group">
    <rect x="128" y="306" width="16" height="16" fill="#FFB6C1"/>
    <rect x="112" y="306" width="16" height="16" fill="#FF85A2"/>
    <rect x="96" y="306" width="16" height="16" fill="#FF85A2"/>
    <rect x="96" y="290" width="16" height="16" fill="#FFB6C1"/>
    <rect x="96" y="274" width="16" height="16" fill="#FF85A2"/>
    <rect x="96" y="258" width="16" height="16" fill="#FF69B4"/>
    <rect x="112" y="258" width="16" height="16" fill="#FFB6C1"/>
  </g>

  <!-- body -->
  <rect x="144" y="242" width="112" height="96" rx="8" fill="#FFB6C1"/>
  <rect x="160" y="258" width="80" height="64" rx="6" fill="#FFF0F5"/>

  <!-- legs -->
  <rect x="144" y="322" width="24" height="32" rx="4" fill="#FF85A2"/>
  <rect x="232" y="322" width="24" height="32" rx="4" fill="#FF85A2"/>
  <rect x="140" y="346" width="32" height="14" rx="7" fill="#FFB6C1"/>
  <rect x="228" y="346" width="32" height="14" rx="7" fill="#FFB6C1"/>
  <rect x="142" y="348" width="8" height="6" rx="3" fill="#FF85A2" opacity="0.6"/>
  <rect x="152" y="348" width="8" height="6" rx="3" fill="#FF85A2" opacity="0.6"/>
  <rect x="162" y="348" width="8" height="6" rx="3" fill="#FF85A2" opacity="0.6"/>
  <rect x="230" y="348" width="8" height="6" rx="3" fill="#FF85A2" opacity="0.6"/>
  <rect x="240" y="348" width="8" height="6" rx="3" fill="#FF85A2" opacity="0.6"/>
  <rect x="250" y="348" width="8" height="6" rx="3" fill="#FF85A2" opacity="0.6"/>

  <!-- head -->
  <rect x="144" y="162" width="112" height="96" rx="12" fill="#FFB6C1"/>

  <!-- ears left -->
  <rect x="144" y="146" width="16" height="20" rx="2" fill="#FF85A2"/>
  <rect x="160" y="138" width="16" height="20" rx="2" fill="#FF85A2"/>
  <rect x="146" y="148" width="10" height="14" rx="2" fill="#FF69B4" opacity="0.6"/>
  <rect x="162" y="140" width="10" height="14" rx="2" fill="#FF69B4" opacity="0.6"/>

  <!-- ears right -->
  <rect x="240" y="146" width="16" height="20" rx="2" fill="#FF85A2"/>
  <rect x="224" y="138" width="16" height="20" rx="2" fill="#FF85A2"/>
  <rect x="244" y="148" width="10" height="14" rx="2" fill="#FF69B4" opacity="0.6"/>
  <rect x="226" y="140" width="10" height="14" rx="2" fill="#FF69B4" opacity="0.6"/>

  <!-- eyes -->
  <g class="blink-l">
    <rect x="157" y="210" width="20" height="20" rx="10" fill="#4a1942"/>
    <rect x="159" y="212" width="8" height="8" rx="4" fill="white" opacity="0.7"/>
    <rect x="167" y="212" width="4" height="4" rx="2" fill="#FF69B4" opacity="0.5"/>
  </g>
  <g class="blink-r">
    <rect x="223" y="210" width="20" height="20" rx="10" fill="#4a1942"/>
    <rect x="225" y="212" width="8" height="8" rx="4" fill="white" opacity="0.7"/>
    <rect x="233" y="212" width="4" height="4" rx="2" fill="#FF69B4" opacity="0.5"/>
  </g>

  <!-- blush -->
  <ellipse cx="154" cy="234" rx="12" ry="8" fill="#FF69B4" opacity="0.35"/>
  <ellipse cx="246" cy="234" rx="12" ry="8" fill="#FF69B4" opacity="0.35"/>

  <!-- nose + mouth -->
  <polygon points="200,228 194,234 206,234" fill="#FF69B4"/>
  <path d="M194,235 Q200,242 206,235" fill="none" stroke="#FF85A2" stroke-width="2" stroke-linecap="round"/>

  <!-- whiskers -->
  <line x1="150" y1="231" x2="188" y2="233" stroke="#FF85A2" stroke-width="1.5" stroke-linecap="round" opacity="0.8"/>
  <line x1="150" y1="237" x2="188" y2="237" stroke="#FF85A2" stroke-width="1.5" stroke-linecap="round" opacity="0.8"/>
  <line x1="152" y1="243" x2="188" y2="240" stroke="#FF85A2" stroke-width="1.5" stroke-linecap="round" opacity="0.8"/>
  <line x1="212" y1="233" x2="250" y2="231" stroke="#FF85A2" stroke-width="1.5" stroke-linecap="round" opacity="0.8"/>
  <line x1="212" y1="237" x2="250" y2="237" stroke="#FF85A2" stroke-width="1.5" stroke-linecap="round" opacity="0.8"/>
  <line x1="212" y1="240" x2="248" y2="243" stroke="#FF85A2" stroke-width="1.5" stroke-linecap="round" opacity="0.8"/>

  <!-- bow -->
  <g transform="translate(200,165)">
    <ellipse cx="-24" cy="-8" rx="10" ry="7" fill="#FF69B4"/>
    <ellipse cx="24" cy="-8" rx="10" ry="7" fill="#FF69B4"/>
    <ellipse cx="0" cy="-8" rx="5" ry="5" fill="#FF85A2"/>
    <ellipse cx="0" cy="-8" rx="3" ry="3" fill="#FFF0F5"/>
  </g>
</g>

<!-- floating heart -->
<g class="heart">
  <path d="M280,128 Q280,115 270,110 Q260,105 260,115 Q260,125 280,138 Q300,125 300,115 Q300,105 290,110 Q280,115 280,128Z" fill="#FF69B4"/>
</g>

<!-- pixel stars -->
<rect x="52" y="300" width="8" height="8" fill="#FFB6C1" rx="1"/>
<rect x="60" y="292" width="8" height="8" fill="#FF85A2" rx="1"/>
<rect x="44" y="292" width="8" height="8" fill="#FF85A2" rx="1"/>
<rect x="52" y="284" width="8" height="8" fill="#FFB6C1" rx="1"/>
<rect x="330" y="280" width="8" height="8" fill="#FFB6C1" rx="1"/>
<rect x="338" y="272" width="8" height="8" fill="#FF85A2" rx="1"/>
<rect x="322" y="272" width="8" height="8" fill="#FF85A2" rx="1"/>
<rect x="330" y="264" width="8" height="8" fill="#FFB6C1" rx="1"/>

<!-- name -->
<text x="200" y="398" text-anchor="middle" font-family="Georgia, serif" font-size="16" fill="#FF69B4" font-style="italic" font-weight="bold">✿ Puja Kumari ✿</text>
</svg>
