<svg width="100%" viewBox="0 0 680 860" xmlns="http://www.w3.org/2000/svg">
<defs>
  <style>
    @keyframes float    { 0%,100%{transform:translateY(0)}   50%{transform:translateY(-9px)} }
    @keyframes tail     { 0%,100%{transform:rotate(-16deg)}  50%{transform:rotate(16deg)} }
    @keyframes blink    { 0%,85%,100%{transform:scaleY(1)}   91%{transform:scaleY(0.07)} }
    @keyframes sparkle  { 0%,100%{opacity:0;transform:scale(0) rotate(0deg)} 50%{opacity:1;transform:scale(1) rotate(180deg)} }
    @keyframes hbeat    { 0%,100%{transform:scale(1)}        50%{transform:scale(1.22)} }
    @keyframes orbit    { from{transform:rotate(0deg)}       to{transform:rotate(360deg)} }
    @keyframes orbitr   { from{transform:rotate(0deg)}       to{transform:rotate(-360deg)} }
    @keyframes pulse    { 0%,100%{opacity:0.35} 50%{opacity:0.8} }
    @keyframes slidein  { from{opacity:0;transform:translateX(-18px)} to{opacity:1;transform:translateX(0)} }
    @keyframes shimmer  { 0%,100%{opacity:0.5} 50%{opacity:1} }
    .cat-float { animation: float 3.2s ease-in-out infinite; transform-origin: 510px 290px; }
    .tail-sw   { animation: tail  1.6s ease-in-out infinite; transform-origin: 453px 340px; }
    .eye-l     { animation: blink 4s  ease-in-out infinite;  transform-origin: 487px 268px; }
    .eye-r     { animation: blink 4s  ease-in-out infinite 0.12s; transform-origin: 533px 268px; }
    .sp1 { animation: sparkle 2.2s ease-in-out infinite;       transform-origin: 610px 120px; }
    .sp2 { animation: sparkle 2.2s ease-in-out infinite 0.7s;  transform-origin: 420px 100px; }
    .sp3 { animation: sparkle 2.2s ease-in-out infinite 1.4s;  transform-origin: 630px 200px; }
    .hrt { animation: hbeat   1.3s ease-in-out infinite;       transform-origin: 600px 175px; }
    .orb1 { animation: orbit  12s  linear infinite;            transform-origin: 170px 200px; }
    .orb2 { animation: orbitr 8s   linear infinite;            transform-origin: 170px 200px; }
    .orb3 { animation: orbit  18s  linear infinite;            transform-origin: 170px 200px; }
    .pulse1 { animation: pulse 2s ease-in-out infinite; }
    .pulse2 { animation: pulse 2s ease-in-out infinite 0.5s; }
    .pulse3 { animation: pulse 2s ease-in-out infinite 1s; }
    .sl1 { animation: slidein 0.6s 0.2s ease both; opacity:0; }
    .sl2 { animation: slidein 0.6s 0.4s ease both; opacity:0; }
    .sl3 { animation: slidein 0.6s 0.6s ease both; opacity:0; }
    .sl4 { animation: slidein 0.6s 0.8s ease both; opacity:0; }
    .sl5 { animation: slidein 0.6s 1.0s ease both; opacity:0; }
    .shim { animation: shimmer 2.5s ease-in-out infinite; }
  </style>
  <linearGradient id="bgGrad" x1="0" y1="0" x2="0" y2="1">
    <stop offset="0%"   stop-color="#0d1117"/>
    <stop offset="45%"  stop-color="#130820"/>
    <stop offset="100%" stop-color="#081008"/>
  </linearGradient>
  <linearGradient id="nameGrad" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0%"   stop-color="#ff69b4"/>
    <stop offset="50%"  stop-color="#ffb6c1"/>
    <stop offset="100%" stop-color="#00e676"/>
  </linearGradient>
  <linearGradient id="divGrad" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0%"   stop-color="#ff69b400"/>
    <stop offset="30%"  stop-color="#ff69b4"/>
    <stop offset="70%"  stop-color="#00e676"/>
    <stop offset="100%" stop-color="#00e67600"/>
  </linearGradient>
  <linearGradient id="sb1" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#ff69b4"/><stop offset="100%" stop-color="#ff85a2"/></linearGradient>
  <linearGradient id="sb2" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#00e676"/><stop offset="100%" stop-color="#69ff47"/></linearGradient>
  <linearGradient id="sb3" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#ff85a2"/><stop offset="100%" stop-color="#ffb6c1"/></linearGradient>
  <linearGradient id="sb4" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#00c853"/><stop offset="100%" stop-color="#00e676"/></linearGradient>
  <linearGradient id="sb5" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#ff69b4"/><stop offset="100%" stop-color="#00e676"/></linearGradient>
  <linearGradient id="waveTop" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0%"   stop-color="#ff69b4"/>
    <stop offset="50%"  stop-color="#ff85a2"/>
    <stop offset="100%" stop-color="#00e676"/>
  </linearGradient>
  <linearGradient id="waveBtm" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0%"   stop-color="#00e676"/>
    <stop offset="50%"  stop-color="#ff85a2"/>
    <stop offset="100%" stop-color="#ff69b4"/>
  </linearGradient>
</defs>

<rect width="680" height="860" rx="18" fill="url(#bgGrad)"/>

<circle cx="55"  cy="38"  r="1.2" fill="#ff69b4" opacity="0.5"/>
<circle cx="180" cy="22"  r="1"   fill="#aaffaa" opacity="0.4"/>
<circle cx="290" cy="45"  r="1.5" fill="#ffb6c1" opacity="0.4"/>
<circle cx="380" cy="18"  r="1"   fill="#00e676" opacity="0.3"/>
<circle cx="480" cy="35"  r="1.2" fill="#ff85a2" opacity="0.45"/>
<circle cx="570" cy="20"  r="1"   fill="#aaffaa" opacity="0.35"/>
<circle cx="640" cy="42"  r="1.5" fill="#ff69b4" opacity="0.4"/>
<circle cx="110" cy="80"  r="1"   fill="#00e676" opacity="0.25"/>
<circle cx="350" cy="60"  r="1.2" fill="#ffb6c1" opacity="0.3"/>

<path d="M0,0 L680,0 L680,32 Q560,58 510,40 Q420,16 340,44 Q260,68 170,36 Q100,14 0,38 Z" fill="url(#waveTop)" opacity="0.9"/>

<g class="orb3"><ellipse cx="170" cy="200" rx="88" ry="28" fill="none" stroke="#ff69b4" stroke-width="0.8" opacity="0.18"/></g>
<g class="orb1"><ellipse cx="170" cy="200" rx="68" ry="22" fill="none" stroke="#00e676" stroke-width="0.8" opacity="0.22"/><circle cx="238" cy="200" r="4" fill="#00e676" opacity="0.7" class="pulse1"/></g>
<g class="orb2"><ellipse cx="170" cy="200" rx="50" ry="16" fill="none" stroke="#ff85a2" stroke-width="0.8" opacity="0.25"/><circle cx="120" cy="200" r="3" fill="#ff85a2" opacity="0.7" class="pulse2"/></g>
<circle cx="170" cy="200" r="8" fill="#ff69b4" opacity="0.6" class="pulse3"/>
<circle cx="170" cy="200" r="4" fill="#ffb6c1"/>

<text x="60" y="108" font-family="Georgia,serif" font-size="12" fill="#ff69b4" opacity="0.7" letter-spacing="4" class="sl1">&#10025; HELLO WORLD &#10025;</text>
<text x="60" y="158" font-family="Georgia,serif" font-size="42" font-weight="700" fill="url(#nameGrad)" class="sl2">Puja Kumari</text>
<text x="62" y="186" font-family="Courier New,monospace" font-size="13" fill="#aaffaa" letter-spacing="2" class="sl3">Frontend Developer &amp; Web Designer</text>
<rect x="60" y="198" width="320" height="1.5" fill="url(#divGrad)" rx="1" class="sl4"/>
<text x="62" y="226" font-family="Georgia,serif" font-size="13" fill="#ff85a2" font-style="italic" class="sl5">Crafting beautiful digital experiences &#10022;</text>
<text x="62" y="260" font-family="Courier New,monospace" font-size="11" fill="#00e676" opacity="0.6" letter-spacing="1">// B.Tech 2023  ·  Open to Freelance  ·  Bengaluru</text>
<rect x="60" y="276" width="230" height="28" rx="14" fill="#ff69b420" stroke="#ff69b450" stroke-width="1"/>
<text x="85" y="295" font-family="Courier New,monospace" font-size="11" fill="#ffb6c1" letter-spacing="0.5">pujakumarijb@gmail.com</text>
<circle cx="75" cy="290" r="5" fill="#ff69b4" opacity="0.8" class="pulse1"/>

<g class="cat-float">
  <g class="tail-sw">
    <rect x="445" y="336" width="13" height="13" fill="#ff85a2" rx="3"/>
    <rect x="432" y="336" width="13" height="13" fill="#ff69b4" rx="2"/>
    <rect x="419" y="336" width="13" height="13" fill="#ff85a2" rx="2"/>
    <rect x="419" y="323" width="13" height="13" fill="#ffb6c1" rx="2"/>
    <rect x="419" y="310" width="13" height="13" fill="#ff69b4" rx="2"/>
    <rect x="432" y="310" width="13" height="13" fill="#ff85a2" rx="2"/>
  </g>
  <rect x="458" y="296" width="104" height="84" rx="10" fill="#ffb6c1"/>
  <rect x="470" y="308" width="80" height="60" rx="7" fill="#fff0f5"/>
  <rect x="458" y="360" width="22" height="28" rx="5" fill="#ff85a2"/>
  <rect x="540" y="360" width="22" height="28" rx="5" fill="#ff85a2"/>
  <rect x="454" y="382" width="30" height="11" rx="5.5" fill="#ffb6c1"/>
  <rect x="536" y="382" width="30" height="11" rx="5.5" fill="#ffb6c1"/>
  <rect x="456" y="384" width="7" height="5" rx="2" fill="#ff85a2" opacity="0.5"/>
  <rect x="464" y="384" width="7" height="5" rx="2" fill="#ff85a2" opacity="0.5"/>
  <rect x="472" y="384" width="7" height="5" rx="2" fill="#ff85a2" opacity="0.5"/>
  <rect x="538" y="384" width="7" height="5" rx="2" fill="#ff85a2" opacity="0.5"/>
  <rect x="546" y="384" width="7" height="5" rx="2" fill="#ff85a2" opacity="0.5"/>
  <rect x="554" y="384" width="7" height="5" rx="2" fill="#ff85a2" opacity="0.5"/>
  <rect x="458" y="214" width="104" height="90" rx="14" fill="#ffb6c1"/>
  <rect x="458" y="200" width="14" height="19" rx="3" fill="#ff85a2"/>
  <rect x="472" y="192" width="14" height="19" rx="3" fill="#ff85a2"/>
  <rect x="460" y="202" width="9" height="13" rx="2" fill="#ff69b4" opacity="0.5"/>
  <rect x="474" y="194" width="9" height="13" rx="2" fill="#ff69b4" opacity="0.5"/>
  <rect x="548" y="200" width="14" height="19" rx="3" fill="#ff85a2"/>
  <rect x="534" y="192" width="14" height="19" rx="3" fill="#ff85a2"/>
  <rect x="550" y="202" width="9" height="13" rx="2" fill="#ff69b4" opacity="0.5"/>
  <rect x="536" y="194" width="9" height="13" rx="2" fill="#ff69b4" opacity="0.5"/>
  <g class="eye-l"><rect x="477" y="260" width="20" height="20" rx="10" fill="#2d1035"/><rect x="479" y="262" width="8" height="8" rx="4" fill="white" opacity="0.7"/><rect x="487" y="262" width="4" height="4" rx="2" fill="#ff69b4" opacity="0.45"/></g>
  <g class="eye-r"><rect x="523" y="260" width="20" height="20" rx="10" fill="#2d1035"/><rect x="525" y="262" width="8" height="8" rx="4" fill="white" opacity="0.7"/><rect x="533" y="262" width="4" height="4" rx="2" fill="#ff69b4" opacity="0.45"/></g>
  <ellipse cx="471" cy="284" rx="11" ry="7" fill="#ff69b4" opacity="0.3"/>
  <ellipse cx="549" cy="284" rx="11" ry="7" fill="#ff69b4" opacity="0.3"/>
  <polygon points="510,277 505,283 515,283" fill="#ff69b4"/>
  <path d="M505,284 Q510,291 515,284" fill="none" stroke="#ff85a2" stroke-width="1.8" stroke-linecap="round"/>
  <line x1="463" y1="279" x2="500" y2="281" stroke="#ff85a2" stroke-width="1.2" stroke-linecap="round" opacity="0.7"/>
  <line x1="463" y1="285" x2="500" y2="285" stroke="#ff85a2" stroke-width="1.2" stroke-linecap="round" opacity="0.7"/>
  <line x1="465" y1="291" x2="500" y2="288" stroke="#ff85a2" stroke-width="1.2" stroke-linecap="round" opacity="0.7"/>
  <line x1="520" y1="281" x2="557" y2="279" stroke="#ff85a2" stroke-width="1.2" stroke-linecap="round" opacity="0.7"/>
  <line x1="520" y1="285" x2="557" y2="285" stroke="#ff85a2" stroke-width="1.2" stroke-linecap="round" opacity="0.7"/>
  <line x1="520" y1="288" x2="555" y2="291" stroke="#ff85a2" stroke-width="1.2" stroke-linecap="round" opacity="0.7"/>
  <ellipse cx="490" cy="216" rx="10" ry="7" fill="#ff69b4"/>
  <ellipse cx="530" cy="216" rx="10" ry="7" fill="#ff69b4"/>
  <ellipse cx="510" cy="216" rx="5" ry="5" fill="#ff85a2"/>
  <ellipse cx="510" cy="216" rx="3" ry="3" fill="#fff0f5"/>
</g>

<g class="sp1"><polygon points="610,112 613,120 621,120 615,125 617,133 610,128 603,133 605,125 599,120 607,120" fill="#ff85a2" opacity="0.9"/></g>
<g class="sp2"><polygon points="420,92 423,100 431,100 425,105 427,113 420,108 413,113 415,105 409,100 417,100" fill="#aaffaa" opacity="0.9"/></g>
<g class="sp3"><polygon points="630,192 632,198 638,198 633,202 635,208 630,204 625,208 627,202 622,198 628,198" fill="#ffb6c1" opacity="0.8"/></g>
<g class="hrt"><path d="M600,185 Q600,173 591,169 Q582,165 582,173 Q582,181 600,191 Q618,181 618,173 Q618,165 609,169 Q600,173 600,185Z" fill="#ff69b4" opacity="0.85"/></g>

<rect x="40" y="418" width="600" height="1" fill="url(#divGrad)" rx="1"/>
<text x="340" y="412" text-anchor="middle" font-family="Georgia,serif" font-size="11" fill="#ff69b4" opacity="0.5" letter-spacing="5">&#10022; &#10022; &#10022;</text>

<text x="60" y="452" font-family="Georgia,serif" font-size="11" fill="#ff69b4" letter-spacing="4" opacity="0.7">SKILLS &amp; TECHNOLOGIES</text>

<text x="60" y="478" font-family="Courier New,monospace" font-size="12" fill="#ffb6c1">HTML · CSS · Bootstrap · Tailwind</text>
<rect x="60" y="482" width="240" height="6" rx="3" fill="#ffffff10"/>
<rect x="60" y="482" width="222" height="6" rx="3" fill="url(#sb1)"/>
<text x="286" y="490" font-family="Courier New,monospace" font-size="10" fill="#ff85a2">92%</text>

<text x="60" y="510" font-family="Courier New,monospace" font-size="12" fill="#ffb6c1">React.js · Next.js · TypeScript</text>
<rect x="60" y="514" width="240" height="6" rx="3" fill="#ffffff10"/>
<rect x="60" y="514" width="204" height="6" rx="3" fill="url(#sb3)"/>
<text x="268" y="522" font-family="Courier New,monospace" font-size="10" fill="#ff85a2">85%</text>

<text x="60" y="542" font-family="Courier New,monospace" font-size="12" fill="#ffb6c1">Three.js · Web Animation</text>
<rect x="60" y="546" width="240" height="6" rx="3" fill="#ffffff10"/>
<rect x="60" y="546" width="192" height="6" rx="3" fill="url(#sb5)"/>
<text x="256" y="554" font-family="Courier New,monospace" font-size="10" fill="#aaffaa">80%</text>

<text x="370" y="478" font-family="Courier New,monospace" font-size="12" fill="#aaffaa">Node.js · PHP · Java</text>
<rect x="370" y="482" width="240" height="6" rx="3" fill="#ffffff10"/>
<rect x="370" y="482" width="168" height="6" rx="3" fill="url(#sb2)"/>
<text x="542" y="490" font-family="Courier New,monospace" font-size="10" fill="#aaffaa">70%</text>

<text x="370" y="510" font-family="Courier New,monospace" font-size="12" fill="#aaffaa">Figma · Canva · Adobe Suite</text>
<rect x="370" y="514" width="240" height="6" rx="3" fill="#ffffff10"/>
<rect x="370" y="514" width="216" height="6" rx="3" fill="url(#sb4)"/>
<text x="590" y="522" font-family="Courier New,monospace" font-size="10" fill="#aaffaa">90%</text>

<text x="370" y="542" font-family="Courier New,monospace" font-size="12" fill="#aaffaa">UI/UX · Responsive Design</text>
<rect x="370" y="546" width="240" height="6" rx="3" fill="#ffffff10"/>
<rect x="370" y="546" width="228" height="6" rx="3" fill="url(#sb4)"/>
<text x="602" y="554" font-family="Courier New,monospace" font-size="10" fill="#aaffaa">95%</text>

<rect x="40" y="576" width="600" height="1" fill="url(#divGrad)" rx="1"/>

<text x="340" y="604" text-anchor="middle" font-family="Georgia,serif" font-size="11" fill="#ff69b4" letter-spacing="4" opacity="0.7">WHAT I DO</text>

<rect x="40"  y="618" width="138" height="76" rx="10" fill="#ff69b408" stroke="#ff69b430" stroke-width="1"/>
<text x="109" y="645" text-anchor="middle" font-family="Georgia,serif" font-size="18" fill="#ff69b4">&#10024;</text>
<text x="109" y="663" text-anchor="middle" font-family="Courier New,monospace" font-size="11" fill="#ffb6c1" font-weight="700">UI / UX Design</text>
<text x="109" y="678" text-anchor="middle" font-family="Georgia,serif" font-size="10" fill="#ff69b4" opacity="0.6">pixel-perfect</text>

<rect x="188" y="618" width="138" height="76" rx="10" fill="#ff85a208" stroke="#ff85a230" stroke-width="1"/>
<text x="257" y="645" text-anchor="middle" font-family="Georgia,serif" font-size="18" fill="#ff85a2">&#9889;</text>
<text x="257" y="663" text-anchor="middle" font-family="Courier New,monospace" font-size="11" fill="#ffb6c1" font-weight="700">Frontend Dev</text>
<text x="257" y="678" text-anchor="middle" font-family="Georgia,serif" font-size="10" fill="#ff85a2" opacity="0.6">responsive apps</text>

<rect x="336" y="618" width="138" height="76" rx="10" fill="#00e67608" stroke="#00e67630" stroke-width="1"/>
<text x="405" y="645" text-anchor="middle" font-family="Georgia,serif" font-size="18" fill="#00e676">&#127760;</text>
<text x="405" y="663" text-anchor="middle" font-family="Courier New,monospace" font-size="11" fill="#aaffaa" font-weight="700">3D &amp; Animation</text>
<text x="405" y="678" text-anchor="middle" font-family="Georgia,serif" font-size="10" fill="#00e676" opacity="0.6">Three.js magic</text>

<rect x="484" y="618" width="138" height="76" rx="10" fill="#00c85308" stroke="#00c85330" stroke-width="1"/>
<text x="553" y="645" text-anchor="middle" font-family="Georgia,serif" font-size="18" fill="#69ff47">&#127775;</text>
<text x="553" y="663" text-anchor="middle" font-family="Courier New,monospace" font-size="11" fill="#aaffaa" font-weight="700">Brand Design</text>
<text x="553" y="678" text-anchor="middle" font-family="Georgia,serif" font-size="10" fill="#69ff47" opacity="0.6">visual identity</text>

<rect x="40" y="712" width="600" height="1" fill="url(#divGrad)" rx="1"/>

<text x="340" y="738" text-anchor="middle" font-family="Georgia,serif" font-size="11" fill="#ff69b4" letter-spacing="4" opacity="0.7">CONNECT WITH ME</text>

<rect x="115" y="750" width="210" height="32" rx="16" fill="#ff69b420" stroke="#ff69b450" stroke-width="1"/>
<circle cx="136" cy="766" r="6" fill="#ff69b4" opacity="0.8"/>
<text x="150" y="770" font-family="Courier New,monospace" font-size="11" fill="#ffb6c1">pujakumarijb@gmail.com</text>

<rect x="345" y="750" width="210" height="32" rx="16" fill="#00e67615" stroke="#00e67640" stroke-width="1"/>
<circle cx="366" cy="766" r="6" fill="#00e676" opacity="0.8"/>
<text x="380" y="770" font-family="Courier New,monospace" font-size="11" fill="#aaffaa">Open to Freelance &#10024;</text>

<text x="340" y="812" text-anchor="middle" font-family="Georgia,serif" font-size="12" fill="#ff69b4" opacity="0.5" font-style="italic">&#10085; "Design is how it works — beautifully." &#10085;</text>

<rect x="92"  y="730" width="7" height="7" fill="#ffb6c1" rx="1" opacity="0.5" class="shim"/>
<rect x="99"  y="723" width="7" height="7" fill="#ff85a2" rx="1" opacity="0.5" class="shim"/>
<rect x="85"  y="723" width="7" height="7" fill="#ff85a2" rx="1" opacity="0.5" class="shim"/>
<rect x="570" y="730" width="7" height="7" fill="#aaffaa" rx="1" opacity="0.5" class="shim"/>
<rect x="577" y="723" width="7" height="7" fill="#00e676" rx="1" opacity="0.5" class="shim"/>
<rect x="563" y="723" width="7" height="7" fill="#00e676" rx="1" opacity="0.5" class="shim"/>

<path d="M0,838 Q80,820 170,836 Q260,852 340,828 Q420,808 510,832 Q580,848 680,824 L680,860 L0,860 Z" fill="url(#waveBtm)" opacity="0.85"/>
</svg>
