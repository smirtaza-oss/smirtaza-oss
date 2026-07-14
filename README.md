<div align="center">

<!-- ANIMATED BANNER (inline SVG) -->
<svg width="100%" height="320" viewBox="0 0 1440 320" preserveAspectRatio="none">
  <defs>
    <linearGradient id="waveGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#667eea">
        <animate attributeName="stop-color" values="#667eea;#764ba2;#f093fb;#667eea" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#f093fb">
        <animate attributeName="stop-color" values="#f093fb;#667eea;#764ba2;#f093fb" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
  </defs>
  <path fill="url(#waveGrad)" d="M0,160 C320,320 640,0 960,160 C1280,320 1600,0 1920,160 L1920,320 L0,320 Z">
    <animateTransform attributeName="transform" type="translate" values="0,0; -1920,0; 0,0" dur="20s" repeatCount="indefinite"/>
  </path>
  <text x="720" y="140" text-anchor="middle" fill="white" font-size="80" font-weight="bold" font-family="Arial, sans-serif">
    MIRTAZA
    <animate attributeName="opacity" values="0;1" dur="2s" fill="freeze"/>
  </text>
  <text x="720" y="200" text-anchor="middle" fill="#f0f0f0" font-size="22" font-family="Arial, sans-serif">
    Computer Science Graduate | AI Researcher | Systems Programmer
    <animate attributeName="opacity" values="0;1" dur="2.5s" fill="freeze"/>
  </text>
</svg>

<br>

<!-- ANIMATED TYPING TEXT (SVG with blinking cursor) -->
<svg width="1100" height="300" viewBox="0 0 1100 300">
  <rect width="1100" height="300" fill="#0d1117" rx="15"/>
  <g fill="#00F7FF" font-family="'Courier New', monospace" font-size="24">
    <text x="50" y="60">👋 Hello, World! I'm Mirtaza</text>
    <text x="50" y="110">💻 Computer Science Enthusiast</text>
    <text x="50" y="160">📚 Algorithms &amp; Data Structures</text>
    <text x="50" y="210">⚙️ Operating Systems &amp; Compilers</text>
    <text x="50" y="260">🤖 Artificial Intelligence Researcher</text>
    <text x="50" y="310">🧪 Building Systems that Scale</text>
  </g>
  <!-- blinking cursor -->
  <rect x="52" y="280" width="12" height="24" fill="#00F7FF">
    <animate attributeName="opacity" values="1;0;1" dur="0.8s" repeatCount="indefinite"/>
  </rect>
</svg>

<br><br>

<!-- ANIMATED BADGES (inline SVGs with gradient) -->
<div>
  <!-- Followers badge -->
  <svg width="140" height="28" viewBox="0 0 140 28">
    <defs><linearGradient id="bg1" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stop-color="#181717"/><stop offset="100%" stop-color="#30363d"/></linearGradient></defs>
    <rect width="140" height="28" rx="6" fill="url(#bg1)"/>
    <text x="10" y="18" fill="#fff" font-size="11" font-family="Arial">Followers</text>
    <text x="75" y="18" fill="#fff" font-size="11" font-weight="bold">123</text>
  </svg>
  <!-- Stars badge -->
  <svg width="120" height="28" viewBox="0 0 120 28">
    <defs><linearGradient id="bg2" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stop-color="#FFD700"/><stop offset="100%" stop-color="#B8860B"/></linearGradient></defs>
    <rect width="120" height="28" rx="6" fill="url(#bg2)"/>
    <text x="10" y="18" fill="#000" font-size="11" font-family="Arial">Stars</text>
    <text x="65" y="18" fill="#000" font-size="11" font-weight="bold">45</text>
  </svg>
  <!-- Views badge -->
  <svg width="140" height="28" viewBox="0 0 140 28">
    <defs><linearGradient id="bg3" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stop-color="#8A2BE2"/><stop offset="100%" stop-color="#4B0082"/></linearGradient></defs>
    <rect width="140" height="28" rx="6" fill="url(#bg3)"/>
    <text x="10" y="18" fill="#fff" font-size="11" font-family="Arial">Views</text>
    <text x="75" y="18" fill="#fff" font-size="11" font-weight="bold">12k</text>
  </svg>
  <!-- Open Source badge -->
  <svg width="160" height="28" viewBox="0 0 160 28">
    <rect width="160" height="28" rx="6" fill="#00C853"/>
    <text x="10" y="18" fill="#fff" font-size="11" font-family="Arial">Open Source Advocate</text>
  </svg>
  <!-- CS Student badge -->
  <svg width="130" height="28" viewBox="0 0 130 28">
    <rect width="130" height="28" rx="6" fill="#7B61FF"/>
    <text x="10" y="18" fill="#fff" font-size="11" font-family="Arial">CS Student</text>
  </svg>
  <!-- Research badge -->
  <svg width="150" height="28" viewBox="0 0 150 28">
    <rect width="150" height="28" rx="6" fill="#FF8C00"/>
    <text x="10" y="18" fill="#fff" font-size="11" font-family="Arial">AI &amp; Systems Research</text>
  </svg>
</div>

</div>

---

<!-- ANIMATED SYSTEM INFORMATION (pulsing terminal box) -->
<div align="center">
  <h2 style="text-align:center; font-size:36px; color:#c9d1d9;">SYSTEM INFORMATION</h2>
  <svg width="850" height="420" viewBox="0 0 850 420">
    <rect width="100%" height="100%" fill="#0d1117" rx="15" stroke="#00FF41" stroke-width="2">
      <animate attributeName="stroke-opacity" values="0.2;1;0.2" dur="2s" repeatCount="indefinite"/>
    </rect>
    <text x="20" y="40" fill="#00FF41" font-family="'Courier New', monospace" font-size="18">
      <tspan x="20" dy="0">user@cs-lab:~$ neofetch</tspan>
      <tspan x="20" dy="25">OS: Arch Linux x86_64</tspan>
      <tspan x="20" dy="25">Kernel: 6.1.12-custom</tspan>
      <tspan x="20" dy="25">Shell: zsh 5.8</tspan>
      <tspan x="20" dy="25">DE: i3-gaps</tspan>
      <tspan x="20" dy="25">Theme: Tokyo Night</tspan>
      <tspan x="20" dy="25">CPU: Intel i7-11800H (16) @ 4.6GHz</tspan>
      <tspan x="20" dy="25">GPU: NVIDIA GeForce RTX 3070</tspan>
      <tspan x="20" dy="25">Memory: 32GB DDR4</tspan>
      <tspan x="20" dy="25">Storage: 1TB NVMe SSD</tspan>
      <tspan x="20" dy="25">Uptime: 42 days 7 hours</tspan>
      <tspan x="20" dy="25">Packages: 1847 (pacman)</tspan>
      <tspan x="20" dy="25">Editor: VSCode / Neovim</tspan>
      <tspan x="20" dy="25" fill="#00F7FF">user@cs-lab:~$ _</tspan>
    </text>
  </svg>
</div>

---

<!-- CONNECT (gradient text via SVG) -->
<div align="center">
  <svg width="100%" height="80" viewBox="0 0 1000 80">
    <defs>
      <linearGradient id="connectGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#12c2e9">
          <animate attributeName="stop-color" values="#12c2e9;#c471ed;#f64f59;#12c2e9" dur="4s" repeatCount="indefinite"/>
        </stop>
        <stop offset="100%" stop-color="#f64f59">
          <animate attributeName="stop-color" values="#f64f59;#12c2e9;#c471ed;#f64f59" dur="4s" repeatCount="indefinite"/>
        </stop>
      </linearGradient>
    </defs>
    <text x="500" y="55" text-anchor="middle" fill="url(#connectGrad)" font-size="40" font-weight="bold" font-family="Arial">🌌 CONNECT</text>
  </svg>
  <p>
    <a href="#" style="color: #58a6ff; text-decoration: none;">GitHub</a> · 
    <a href="#" style="color: #58a6ff; text-decoration: none;">LinkedIn</a> · 
    <a href="#" style="color: #58a6ff; text-decoration: none;">Discord</a> · 
    <a href="#" style="color: #58a6ff; text-decoration: none;">Instagram</a> · 
    <a href="#" style="color: #58a6ff; text-decoration: none;">Email</a>
  </p>
</div>

---

<!-- CORE CS FOUNDATIONS (animated pills using SVG) -->
<div align="center">
  <h2 style="color: #c9d1d9; font-size: 36px;">🧠 CORE CS FOUNDATIONS</h2>
  <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 8px; margin: 20px;">
    <!-- Each pill is a small animated SVG -->
    <svg width="450" height="30" viewBox="0 0 450 30"><rect width="100%" height="100%" rx="15" fill="#1f6feb"><animate attributeName="opacity" values="0.8;1;0.8" dur="3s" repeatCount="indefinite"/></rect><text x="15" y="20" fill="white" font-size="12">Data Structures: Linked Lists, Trees, Graphs, Hash Tables</text></svg>
    <svg width="380" height="30" viewBox="0 0 380 30"><rect width="100%" height="100%" rx="15" fill="#238636"><animate attributeName="opacity" values="0.8;1;0.8" dur="3s" repeatCount="indefinite"/></rect><text x="15" y="20" fill="white" font-size="12">Algorithms: Sorting, DP, Greedy, Graph Algos</text></svg>
    <svg width="420" height="30" viewBox="0 0 420 30"><rect width="100%" height="100%" rx="15" fill="#da3633"><animate attributeName="opacity" values="0.8;1;0.8" dur="3s" repeatCount="indefinite"/></rect><text x="15" y="20" fill="white" font-size="12">Operating Systems: Linux Kernel, Processes, Concurrency</text></svg>
    <svg width="370" height="30" viewBox="0 0 370 30"><rect width="100%" height="100%" rx="15" fill="#d29922"><animate attributeName="opacity" values="0.8;1;0.8" dur="3s" repeatCount="indefinite"/></rect><text x="15" y="20" fill="black" font-size="12">Computer Networks: TCP/IP, HTTP, DNS, TLS</text></svg>
    <svg width="400" height="30" viewBox="0 0 400 30"><rect width="100%" height="100%" rx="15" fill="#8957e5"><animate attributeName="opacity" values="0.8;1;0.8" dur="3s" repeatCount="indefinite"/></rect><text x="15" y="20" fill="white" font-size="12">Database Systems: SQL, NoSQL, Indexing, Transactions</text></svg>
    <svg width="450" height="30" viewBox="0 0 450 30"><rect width="100%" height="100%" rx="15" fill="#79c0ff"><animate attributeName="opacity" values="0.8;1;0.8" dur="3s" repeatCount="indefinite"/></rect><text x="15" y="20" fill="black" font-size="12">Theory of Computation: Automata, Complexity, Decidability</text></svg>
    <svg width="380" height="30" viewBox="0 0 380 30"><rect width="100%" height="100%" rx="15" fill="#f85149"><animate attributeName="opacity" values="0.8;1;0.8" dur="3s" repeatCount="indefinite"/></rect><text x="15" y="20" fill="white" font-size="12">Compilers: Lexing, Parsing, Code Generation</text></svg>
    <svg width="380" height="30" viewBox="0 0 380 30"><rect width="100%" height="100%" rx="15" fill="#ff69b4"><animate attributeName="opacity" values="0.8;1;0.8" dur="3s" repeatCount="indefinite"/></rect><text x="15" y="20" fill="black" font-size="12">Discrete Math: Logic, Graph Theory, Number Theory</text></svg>
  </div>
</div>

---

<!-- TECH STACK (simple text with subtle animation) -->
<div align="center">
  <h2 style="color: #c9d1d9; font-size: 36px;">⚙️ TECHNOLOGY &amp; TOOLS</h2>
  <p style="font-family: 'Courier New', monospace; font-size: 18px; color: #c9d1d9; line-height: 2;">
    C++ &nbsp; C &nbsp; Java &nbsp; Python &nbsp; JavaScript &nbsp; TypeScript &nbsp; HTML &nbsp; CSS &nbsp; Tailwind<br>
    React &nbsp; Next.js &nbsp; Node.js &nbsp; Express &nbsp; .NET &nbsp; MongoDB &nbsp; MySQL &nbsp; PostgreSQL &nbsp; Redis<br>
    Docker &nbsp; Kubernetes &nbsp; Azure &nbsp; AWS &nbsp; Git &nbsp; GitHub Actions &nbsp; Linux &nbsp; Bash<br>
    Vim &nbsp; LaTeX &nbsp; MATLAB &nbsp; R &nbsp; Assembly &nbsp; Raspberry Pi
  </p>
</div>

---

<!-- SKILL RADAR (placeholder) -->
<div align="center">
  <h2 style="color: #c9d1d9; font-size: 36px;">📡 SKILL RADAR</h2>
  <p style="color: #8b949e;">
    <em>Top languages: JavaScript (35%), Python (25%), C++ (15%), TypeScript (10%), others...</em><br>
    <em>Productive hours: 42h/week • Most active repo: os-kernel</em>
  </p>
</div>

---

<!-- LIVE ACTIVITY (animated bars via SVG) -->
<div align="center">
  <h2 style="color: #c9d1d9; font-size: 36px;">📊 LIVE ACTIVITY &amp; STATS</h2>
  <svg width="80%" height="120" viewBox="0 0 800 120">
    <rect width="100%" height="100%" fill="#161b22" rx="10"/>
    <!-- Animated bars representing commits/PRs/etc -->
    <rect x="50" y="40" width="20" height="80" fill="#58a6ff">
      <animate attributeName="height" values="20;80;20" dur="2s" repeatCount="indefinite"/>
      <animate attributeName="y" values="100;40;100" dur="2s" repeatCount="indefinite"/>
    </rect>
    <rect x="160" y="50" width="20" height="70" fill="#3fb950">
      <animate attributeName="height" values="30;70;30" dur="2.5s" repeatCount="indefinite"/>
      <animate attributeName="y" values="90;50;90" dur="2.5s" repeatCount="indefinite"/>
    </rect>
    <rect x="270" y="60" width="20" height="60" fill="#d29922">
      <animate attributeName="height" values="10;60;10" dur="1.8s" repeatCount="indefinite"/>
      <animate attributeName="y" values="110;60;110" dur="1.8s" repeatCount="indefinite"/>
    </rect>
    <rect x="380" y="45" width="20" height="75" fill="#f85149">
      <animate attributeName="height" values="25;75;25" dur="3s" repeatCount="indefinite"/>
      <animate attributeName="y" values="95;45;95" dur="3s" repeatCount="indefinite"/>
    </rect>
    <rect x="490" y="55" width="20" height="65" fill="#bc8cff">
      <animate attributeName="height" values="15;65;15" dur="2.2s" repeatCount="indefinite"/>
      <animate attributeName="y" values="105;55;105" dur="2.2s" repeatCount="indefinite"/>
    </rect>
    <!-- Labels -->
    <text x="50" y="15" fill="#c9d1d9" font-size="12" text-anchor="middle">Commits</text>
    <text x="160" y="15" fill="#c9d1d9" font-size="12" text-anchor="middle">PRs</text>
    <text x="270" y="15" fill="#c9d1d9" font-size="12" text-anchor="middle">Issues</text>
    <text x="380" y="15" fill="#c9d1d9" font-size="12" text-anchor="middle">Reviews</text>
    <text x="490" y="15" fill="#c9d1d9" font-size="12" text-anchor="middle">Stars</text>
  </svg>
</div>

---

<!-- FEATURED PROJECTS (animated card-like SVGs) -->
<div align="center">
  <h2 style="color: #c9d1d9; font-size: 36px;">📌 RESEARCH &amp; PROJECTS</h2>
  <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px; width: 80%; margin: auto;">
    <svg width="100%" height="100" viewBox="0 0 400 100"><rect width="100%" height="100%" fill="#0d1117" rx="10" stroke="#30363d" stroke-width="1"><animate attributeName="stroke" values="#30363d;#58a6ff;#30363d" dur="4s" repeatCount="indefinite"/></rect><text x="15" y="35" fill="#58a6ff" font-weight="bold">os-kernel</text><text x="15" y="60" fill="#8b949e" font-size="14">A mini operating system kernel</text><text x="15" y="85" fill="#c9d1d9" font-size="12">⭐ 12  🍴 3</text></svg>
    <svg width="100%" height="100" viewBox="0 0 400 100"><rect width="100%" height="100%" fill="#0d1117" rx="10" stroke="#30363d" stroke-width="1"><animate attributeName="stroke" values="#30363d;#58a6ff;#30363d" dur="4s" repeatCount="indefinite"/></rect><text x="15" y="35" fill="#58a6ff" font-weight="bold">ml-compiler</text><text x="15" y="60" fill="#8b949e" font-size="14">ML‑based code optimizer</text><text x="15" y="85" fill="#c9d1d9" font-size="12">⭐ 8  🍴 2</text></svg>
    <svg width="100%" height="100" viewBox="0 0 400 100"><rect width="100%" height="100%" fill="#0d1117" rx="10" stroke="#30363d" stroke-width="1"><animate attributeName="stroke" values="#30363d;#58a6ff;#30363d" dur="4s" repeatCount="indefinite"/></rect><text x="15" y="35" fill="#58a6ff" font-weight="bold">distributed-systems</text><text x="15" y="60" fill="#8b949e" font-size="14">Raft consensus implementation</text><text x="15" y="85" fill="#c9d1d9" font-size="12">⭐ 15  🍴 5</text></svg>
    <svg width="100%" height="100" viewBox="0 0 400 100"><rect width="100%" height="100%" fill="#0d1117" rx="10" stroke="#30363d" stroke-width="1"><animate attributeName="stroke" values="#30363d;#58a6ff;#30363d" dur="4s" repeatCount="indefinite"/></rect><text x="15" y="35" fill="#58a6ff" font-weight="bold">algorithm-visualizer</text><text x="15" y="60" fill="#8b949e" font-size="14">Interactive algorithm demos</text><text x="15" y="85" fill="#c9d1d9" font-size="12">⭐ 22  🍴 7</text></svg>
  </div>
</div>

---

<!-- CS BLOG (text) -->
<div align="center">
  <h2 style="color: #c9d1d9; font-size: 36px;">📝 CS ARTICLES</h2>
  <p style="color: #c9d1d9;">
    Latest post: <em>"Understanding Meltdown and Spectre"</em> (Mar 2024)<br>
    <a href="#" style="color: #58a6ff;">View all articles on dev.to/mirtaza</a>
  </p>
</div>

---

<!-- COMPETITIVE PROGRAMMING (table) -->
<div align="center">
  <h2 style="color: #c9d1d9; font-size: 36px;">⚔️ COMPETITIVE PROGRAMMING</h2>
  <table style="margin: auto; color: #c9d1d9; background: #161b22; border-radius: 8px; padding: 10px;">
    <tr><td>LeetCode</td><td>150 problems solved</td></tr>
    <tr><td>Codeforces</td><td>Rating: 1450 (Pupil)</td></tr>
  </table>
</div>

---

<!-- CODING METRICS -->
<div align="center">
  <h2 style="color: #c9d1d9; font-size: 36px;">⏱️ CODING METRICS</h2>
  <p style="color: #c9d1d9;">
    Last week: 42h coding<br>
    Top languages: JavaScript 12h, Python 10h, C++ 6h, TypeScript 5h<br>
    Editors: VS Code 30h, Neovim 12h
  </p>
</div>

---

<!-- LATEST CS PAPER -->
<div align="center">
  <h2 style="color: #c9d1d9; font-size: 36px;">📄 LATEST CS PAPER</h2>
  <p style="color: #c9d1d9;">
    📌 “Attention Is All You Need” – Vaswani et al. (NeurIPS 2017)<br>
    <a href="#" style="color: #58a6ff;">arXiv:1706.03762</a>
  </p>
</div>

---

<!-- SUPPORT (buttons) -->
<div align="center">
  <h2 style="color: #c9d1d9; font-size: 36px;">❤️ SUPPORT MY RESEARCH</h2>
  <p>
    <a href="#" style="background: #FFDD00; color: black; padding: 10px 20px; border-radius: 5px; text-decoration: none; font-weight: bold;">☕ Buy Me a Coffee</a>
    &nbsp;
    <a href="#" style="background: #EA4AAA; color: white; padding: 10px 20px; border-radius: 5px; text-decoration: none; font-weight: bold;">❤️ Sponsor</a>
  </p>
</div>

---

<!-- MOTTO -->
<div align="center">
  <h2 style="color: #c9d1d9; font-size: 36px;">⚡ MOTTO</h2>
  <h2 style="color: #c9d1d9;">「 Think • Code • Research • Repeat 」</h2>
  <h3 style="color: #8b949e;">🧠 Turning abstract theory into real‑world systems.</h3>
</div>

<!-- ANIMATED FOOTER WAVE -->
<svg width="100%" height="220" viewBox="0 0 1440 220" preserveAspectRatio="none">
  <defs>
    <linearGradient id="footerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#667eea">
        <animate attributeName="stop-color" values="#667eea;#764ba2;#f093fb;#667eea" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#f093fb">
        <animate attributeName="stop-color" values="#f093fb;#667eea;#764ba2;#f093fb" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
  </defs>
  <path fill="url(#footerGrad)" d="M0,128 C320,256 640,0 960,128 C1280,256 1600,0 1920,128 L1920,320 L0,320 Z">
    <animateTransform attributeName="transform" type="translate" values="0,0; -1920,0; 0,0" dur="20s" repeatCount="indefinite"/>
  </path>
</svg>
