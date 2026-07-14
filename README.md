<!-- 
  🎓 COMPUTER SCIENCE ACADEMIC & SYSTEMS PROGRAMMER PROFILE
  Optimized with self-contained, inline animated SVG elements to avoid broken asset dependencies.
-->

<div align="center">

<!-- Matrix Rain Banner -->
<img width="100%" src="https://media.giphy.com/media/l0HlPwMA6zhHmQdWM/giphy.gif?cid=790b7611ul4v3r29g0f7hx4qk8h0e4h4x4o3p3m7&rid=giphy.gif&ct=g" alt="Matrix Rain Banner" />

<br>

<!-- Top Wave Capsule -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=320&color=gradient&customColorList=6,11,20,24,30&text=MIRTAZA&fontColor=ffffff&fontSize=80&animation=fadeIn&fontAlignY=38&desc=Computer%20Science%20Graduate%20%7C%20AI%20Researcher%20%7C%20Systems%20Programmer&descAlignY=58" alt="Mirtaza Header"/>

<br>

<!-- Typing Intro -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=30&duration=3000&pause=900&color=00F7FF&center=true&vCenter=true&width=1100&lines=👋+Hello%2C+World!+I'm+Mirtaza;💻+Computer+Science+Enthusiast;📚+Algorithms+%26+Data+Structures;⚙️+Operating+Systems+%26+Compilers;🤖+Artificial+Intelligence+Researcher;🧪+Building+Systems+that+Scale" alt="Typing Intro"/>

<br><br>

<!-- Badges -->
<img src="https://img.shields.io/github/followers/smirtaza-oss?style=for-the-badge&logo=github&color=181717" alt="GitHub Followers"/>
<img src="https://img.shields.io/github/stars/smirtaza-oss?style=for-the-badge&logo=github&color=FFD700" alt="GitHub Stars"/>
<img src="https://komarev.com/ghpvc/?username=smirtaza-oss&style=for-the-badge&color=blueviolet" alt="Profile Views"/>
<img src="https://img.shields.io/badge/Open%20Source-Advocate-00C853?style=for-the-badge" alt="Open Source"/>
<img src="https://img.shields.io/badge/CS-Graduate-7B61FF?style=for-the-badge" alt="CS Graduate"/>
<img src="https://img.shields.io/badge/Research-AI%20%26%20Systems-orange?style=for-the-badge&logo=arxiv" alt="Research"/>

<br><br>

<!-- INLINE SELF-CONTAINED ANIMATED NEON DIVIDER (Fixed broken local file reference) -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 20" width="100%">
  <style>
    @keyframes pulse-dash {
      0% { stroke-dashoffset: 1000; }
      100% { stroke-dashoffset: 0; }
    }
    .neon-flow-line {
      stroke: url(#neon-gradient-split);
      stroke-width: 4;
      stroke-linecap: round;
      stroke-dasharray: 150 300;
      animation: pulse-dash 10s linear infinite;
    }
  </style>
  <defs>
    <linearGradient id="neon-gradient-split" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00F7FF" />
      <stop offset="50%" stop-color="#7B61FF" />
      <stop offset="100%" stop-color="#FF007F" />
    </linearGradient>
  </defs>
  <line class="neon-flow-line" x1="10" y1="10" x2="890" y2="10" />
</svg>

</div>

---

<!-- INLINE SELF-CONTAINED GLOWING NEON BORDER (Fixed broken assets/neon-border.svg references) -->
<div align="center">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 100" width="90%">
    <style>
      @keyframes neon-glow-pulse {
        0%, 100% {
          filter: drop-shadow(0 0 3px #00F7FF) drop-shadow(0 0 8px #7B61FF);
          opacity: 0.9;
        }
        50% {
          filter: drop-shadow(0 0 6px #00F7FF) drop-shadow(0 0 15px #7B61FF);
          opacity: 1;
        }
      }
      .neon-border-box {
        stroke: url(#neon-border-grad);
        stroke-width: 2.5;
        fill: #0d1117;
        animation: neon-glow-pulse 4s ease-in-out infinite;
      }
      .neon-border-text {
        font-family: 'JetBrains Mono', 'Fira Code', monospace;
        font-weight: 700;
        fill: #ffffff;
        font-size: 18px;
        letter-spacing: 5px;
      }
    </style>
    <defs>
      <linearGradient id="neon-border-grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#00F7FF" />
        <stop offset="100%" stop-color="#7B61FF" />
      </linearGradient>
    </defs>
    <rect class="neon-border-box" x="10" y="10" width="780" height="80" rx="12" />
    <text class="neon-border-text" x="50%" y="52" dominant-baseline="middle" text-anchor="middle">✨ CS RESEARCH LAB ENVIRONMENT ✨</text>
  </svg>
</div>

<br>

<!-- ROTATING 3D GRAPH NODE SYSTEM (Self-Contained SVG Animation) -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=27,28,29&text=🌀+COMPLEX+SYSTEMS+REPRESENTATION&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Systems Representation Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 400 400" width="220" height="220" style="background-color: transparent;">
    <style>
      @keyframes spin-clockwise {
        0% { transform: rotate(0deg); }
        100% { transform: rotate(360deg); }
      }
      @keyframes spin-counter-clockwise {
        0% { transform: rotate(360deg); }
        100% { transform: rotate(0deg); }
      }
      @keyframes node-flash {
        0%, 100% { fill: #00F7FF; r: 6; filter: drop-shadow(0 0 2px #00F7FF); }
        50% { fill: #FF007F; r: 9; filter: drop-shadow(0 0 8px #FF007F); }
      }
      .rotation-layer-1 {
        transform-origin: 200px 200px;
        animation: spin-clockwise 20s linear infinite;
      }
      .rotation-layer-2 {
        transform-origin: 200px 200px;
        animation: spin-counter-clockwise 15s linear infinite;
      }
      .flashing-node {
        animation: node-flash 3s ease-in-out infinite;
      }
    </style>
    <!-- Grid Rings -->
    <circle cx="200" cy="200" r="160" stroke="#1f2937" stroke-width="1.5" fill="none" stroke-dasharray="8, 6" />
    <circle cx="200" cy="200" r="100" stroke="#30363d" stroke-width="1" fill="none" stroke-dasharray="4, 4" />
    <circle cx="200" cy="200" r="40" stroke="#30363d" stroke-width="1" fill="none" />

    <!-- Central Node -->
    <circle cx="200" cy="200" r="12" fill="#7B61FF" filter="drop-shadow(0 0 10px #7B61FF)" />

    <!-- Clockwise Rotating Structure -->
    <g class="rotation-layer-1">
      <line x1="200" y1="200" x2="200" y2="40" stroke="#7B61FF" stroke-width="1.5" opacity="0.5" />
      <line x1="200" y1="200" x2="340" y2="200" stroke="#7B61FF" stroke-width="1.5" opacity="0.5" />
      <line x1="200" y1="200" x2="60" y2="200" stroke="#7B61FF" stroke-width="1.5" opacity="0.5" />
      <circle class="flashing-node" cx="200" cy="40" r="7" />
      <circle class="flashing-node" cx="340" cy="200" r="7" style="animation-delay: -1s;" />
      <circle class="flashing-node" cx="60" cy="200" r="7" style="animation-delay: -2s;" />
    </g>

    <!-- Counter-Clockwise Rotating Structure -->
    <g class="rotation-layer-2">
      <polygon points="200,100 286,250 114,250" stroke="#00F7FF" stroke-width="1" fill="none" opacity="0.3" />
      <circle cx="200" cy="100" r="6" fill="#00F7FF" />
      <circle cx="286" cy="250" r="6" fill="#00F7FF" />
      <circle cx="114" cy="250" r="6" fill="#00F7FF" />
    </g>
  </svg>
</div>

---

<!-- LIVE SYSTEM INFORMATION – Terminal Interface -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=100&color=gradient&customColorList=6,11,20&text=SYSTEM%20INFORMATION&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="System Information Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <div style="background-color:#0d1117; border:1px solid #00FF41; border-radius:15px; padding:25px; max-width:850px; text-align:left; box-shadow: 0 0 15px rgba(0,255,65,0.15);">
    <div style="display:flex; justify-content:space-between; border-bottom:1px solid #1f2937; padding-bottom:10px; margin-bottom:15px;">
      <span style="color:#ff5f56; font-size:18px;">● <span style="color:#ffbd2e;">●</span> <span style="color:#27c93f;">●</span></span>
      <span style="color:#8b949e; font-family:'Courier New', monospace; font-size:14px;">mirtaza@cs-lab:~</span>
    </div>
    <div style="font-family:'Fira Code', 'Courier New', monospace; font-size:15px; color:#c9d1d9; line-height:1.6;">
      <span style="color:#58a6ff;">mirtaza@cs-lab</span>:<span style="color:#2ea043;">~</span>$ neofetch<br>
      <span style="color:#00FF41;">OS</span>: Arch Linux x86_64 <br>
      <span style="color:#00FF41;">Kernel</span>: 6.6.15-lts-custom-perf <br>
      <span style="color:#00FF41;">Shell</span>: zsh 5.9 (configured with custom integrations) <br>
      <span style="color:#00FF41;">DE/WM</span>: i3-gaps (Custom Tokyo Night layout) <br>
      <span style="color:#00FF41;">CPU</span>: AMD Ryzen 9 5900X (24) @ 4.80GHz <br>
      <span style="color:#00FF41;">GPU</span>: NVIDIA GeForce RTX 3080 Ti <br>
      <span style="color:#00FF41;">Memory</span>: 64GB DDR4 ECC RAM <br>
      <span style="color:#00FF41;">Storage</span>: 2TB NVMe PCIe Gen4 SSD <br>
      <span style="color:#00FF41;">Uptime</span>: 42 days, 7 hours, 12 minutes <br>
      <span style="color:#00FF41;">Packages</span>: 1948 (pacman) <br>
      <span style="color:#00FF41;">Editor</span>: Neovim (LazyVim custom profile) / VSCode <br>
      <span style="color:#58a6ff;">mirtaza@cs-lab</span>:<span style="color:#2ea043;">~</span>$ <span style="animation: cursor-flicker 1s step-end infinite;">_</span>
    </div>
  </div>
</div>

<style>
  @keyframes cursor-flicker {
    from, to { opacity: 0; }
    50% { opacity: 1; }
  }
</style>

---

<!-- SOCIAL CONNECTIONS -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=12,14,18&text=🌌+CONNECT&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Connect Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <a href="https://github.com/smirtaza-oss"><img src="https://skillicons.dev/icons?i=github" height="58" alt="GitHub" /></a>&nbsp;
  <a href="https://linkedin.com/in/smirtaza"><img src="https://skillicons.dev/icons?i=linkedin" height="58" alt="LinkedIn" /></a>&nbsp;
  <a href="https://discord.gg/invite"><img src="https://skillicons.dev/icons?i=discord" height="58" alt="Discord" /></a>&nbsp;
  <a href="https://instagram.com/mirtaza"><img src="https://skillicons.dev/icons?i=instagram" height="58" alt="Instagram" /></a>&nbsp;
  <a href="mailto:smirtaza.dev@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" height="58" alt="Email" /></a>
</div>

---

<!-- COMPUTER SCIENCE FOUNDATIONS -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=10,12,15&text=🧠+CORE+CS+FOUNDATIONS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Core CS Foundations Header"/>
</div>

<div align="center" style="display:flex; flex-wrap:wrap; justify-content:center; gap:10px; margin:20px 0;">
  <img src="https://img.shields.io/badge/Data%20Structures-Linked%20Lists%2C%20Trees%2C%20Graphs%2C%20Hash%20Tables-blue" alt="Data Structures"/>
  <img src="https://img.shields.io/badge/Algorithms-Sorting%2C%20DP%2C%20Greedy%2C%20Graph%20Algos-brightgreen" alt="Algorithms"/>
  <img src="https://img.shields.io/badge/Operating%20Systems-Linux%20Kernel%2C%20Processes%2C%20Concurrency-red" alt="Operating Systems"/>
  <img src="https://img.shields.io/badge/Computer%20Networks-TCP%2FIP%2C%20HTTP%2C%20DNS%2C%20TLS-orange" alt="Computer Networks"/>
  <img src="https://img.shields.io/badge/Database%20Systems-SQL%2C%20NoSQL%2C%20Indexing%2C%20Transactions-blueviolet" alt="Databases"/>
  <img src="https://img.shields.io/badge/Theory%20of%20Computation-Automata%2C%20Complexity%2C%20Decidability-9cf" alt="Theory of Computation"/>
  <img src="https://img.shields.io/badge/Compilers-Lexing%2C%20Parsing%2C%20Code%20Generation-critical" alt="Compilers"/>
  <img src="https://img.shields.io/badge/Discrete%20Math-Logic%2C%20Graph%20Theory%2C%20Number%20Theory-ff69b4" alt="Discrete Math"/>
</div>

---

<!-- ADVANCED COMPILER AUTOMATA VISUALIZATION (Inline Interactive SVG) -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=24,23,22&text=⚙️+COMPILER+STATE+MACHINE+SIMULATOR&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="State Machine Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 200" width="100%" style="background-color: #0d1117; border-radius: 12px; border: 1px solid #30363d;">
    <style>
      @keyframes state-transition {
        0%, 100% { fill: #1f2937; stroke: #30363d; }
        33% { fill: rgba(0, 247, 255, 0.1); stroke: #00F7FF; }
        66% { fill: rgba(123, 97, 255, 0.1); stroke: #7B61FF; }
      }
      @keyframes token-flow {
        0% { cx: 150; cy: 100; opacity: 1; }
        50% { cx: 400; cy: 100; }
        100% { cx: 650; cy: 100; opacity: 1; }
      }
      .state-circle {
        stroke-width: 3;
        animation: state-transition 6s ease-in-out infinite;
      }
      .flow-token {
        fill: #FF007F;
        filter: drop-shadow(0 0 6px #FF007F);
        animation: token-flow 4s linear infinite;
      }
      .state-text {
        font-family: 'JetBrains Mono', monospace;
        font-size: 14px;
        fill: #ffffff;
        font-weight: bold;
      }
    </style>
    
    <!-- State Nodes -->
    <circle class="state-circle" cx="150" cy="100" r="40" style="animation-delay: 0s;" />
    <text class="state-text" x="150" y="105" text-anchor="middle">q0 (Idle)</text>

    <circle class="state-circle" cx="400" cy="100" r="40" style="animation-delay: 2s;" />
    <text class="state-text" x="400" y="105" text-anchor="middle">q1 (Parse)</text>

    <circle class="state-circle" cx="650" cy="100" r="40" style="animation-delay: 4s;" />
    <text class="state-text" x="650" y="105" text-anchor="middle">q2 (Accept)</text>

    <!-- Transition Arcs -->
    <path d="M 190,100 L 360,100" stroke="#8b949e" stroke-width="2" marker-end="url(#arrow)" fill="none" />
    <path d="M 440,100 L 610,100" stroke="#8b949e" stroke-width="2" marker-end="url(#arrow)" fill="none" />

    <!-- Self Loops -->
    <path d="M 385,63 A 20,20 0 1,1 415,63" stroke="#8b949e" stroke-width="2" fill="none" />

    <!-- Animated Parsing Token -->
    <circle class="flow-token" cx="150" cy="100" r="8" />

    <!-- SVG Markers -->
    <defs>
      <marker id="arrow" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
        <path d="M 0 0 L 10 5 L 0 10 z" fill="#8b949e" />
      </marker>
    </defs>
  </svg>
</div>

---

<!-- TECHNOLOGY STACK -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=24,23,22&text=⚙️+TECHNOLOGY+%26+TOOLS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Technology Stack Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img src="https://skillicons.dev/icons?i=cpp,c,rust,python,java,go,assembly,bash,latex,git,github,linux,docker,kubernetes,postgres,mysql,redis,mongodb&perline=9" alt="Technology Grid"/>
</div>

---

<!-- ANALYTICS RADAR & METRICS -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=6,11,20&text=📡+SKILLS+RADAR&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Skills Radar Header"/>
</div>

<div align="center" style="margin: 20px 0; display: flex; flex-wrap: wrap; justify-content: center; gap: 20px;">
  <img src="https://raw.githubusercontent.com/smirtaza-oss/smirtaza-oss/main/profile-summary-card-output/tokyonight/4-productive-time.svg" width="400" alt="Productive Time Tracker" />
  <img src="https://raw.githubusercontent.com/smirtaza-oss/smirtaza-oss/main/profile-summary-card-output/tokyonight/5-most-commit-language.svg" width="400" alt="Commit Language Tracker" />
</div>

---

<!-- GITHUB ANALYTICS -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=12,14,18&text=📊+GITHUB+ANALYTICS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="GitHub Analytics Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=smirtaza-oss&show_icons=true&theme=tokyonight&hide_border=true" alt="Stats Summary" />
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=smirtaza-oss&layout=compact&theme=tokyonight&hide_border=true" alt="Language Statistics" />
  <br>
  <img width="99%" src="https://streak-stats.demolab.com?user=smirtaza-oss&theme=tokyonight&hide_border=true" alt="Streak Tracker" />
  <br>
  <img width="99%" src="https://github-readme-activity-graph.vercel.app/graph?username=smirtaza-oss&theme=tokyo-night&hide_border=true" alt="Contribution Wave" />
</div>

---

<!-- RECENT ACTIVITY -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=24,23,22&text=🕒+RECENT+ACTIVITY&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Recent Activity Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img src="https://github-readme-activity.vercel.app/api?username=smirtaza-oss&theme=tokyonight&hide_border=true" width="90%" alt="Recent Activity Tracker" />
</div>

---

<!-- LEARNING PROGRESS -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=27,28,29&text=📈+LEARNING+PROGRESS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Learning Progress Header"/>
</div>

<div align="center" style="margin: 20px 0; display: flex; flex-direction: column; align-items: center; gap: 15px;">
  <img src="https://progress-bar.dev/75/?title=Distributed%20Systems%20Architecture&width=400&color=00FF41" alt="Distributed Systems Progress" />
  <img src="https://progress-bar.dev/60/?title=Deep%20Learning%20Compiler%20Backends&width=400&color=00F7FF" alt="Deep Learning Compiler Progress" />
  <img src="https://progress-bar.dev/85/?title=High%20Performance%20Computing&width=400&color=7B61FF" alt="High Performance Computing Progress" />
</div>

---

<!-- MAC-OS STYLE RINGS -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=10,12,15&text=🍎+ACTIVITY+RINGS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Activity Rings Header"/>
</div>

<div align="center" style="margin: 20px 0; display: flex; flex-wrap: wrap; justify-content: center; gap: 20px;">
  <img src="https://raw.githubusercontent.com/smirtaza-oss/smirtaza-oss/main/profile-summary-card-output/tokyonight/3-stats.svg" width="49%" alt="System Stats Ring" />
  <img src="https://raw.githubusercontent.com/smirtaza-oss/smirtaza-oss/main/profile-summary-card-output/tokyonight/0-profile-details.svg" width="49%" alt="Details Ring" />
</div>

---

<!-- FEATURED PROJECTS -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=10,12,15&text=📌+RESEARCH+%26+PROJECTS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Research Projects Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <a href="https://github.com/smirtaza-oss/os-kernel">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=smirtaza-oss&repo=os-kernel&theme=tokyonight&hide_border=true" alt="OS Kernel Project" />
  </a>
  <a href="https://github.com/smirtaza-oss/ml-compiler">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=smirtaza-oss&repo=ml-compiler&theme=tokyonight&hide_border=true" alt="ML Compiler Project" />
  </a>
  <br>
  <a href="https://github.com/smirtaza-oss/distributed-systems">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=smirtaza-oss&repo=distributed-systems&theme=tokyonight&hide_border=true" alt="Distributed Systems Project" />
  </a>
  <a href="https://github.com/smirtaza-oss/algorithm-visualizer">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=smirtaza-oss&repo=algorithm-visualizer&theme=tokyonight&hide_border=true" alt="Algorithm Visualizer Project" />
  </a>
</div>

---

<!-- CS TECHNICAL BLOG -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=12,14,18&text=📝+CS+ARTICLES&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="CS Articles Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <a href="https://dev.to/smirtaza">
    <img src="https://blog-readme.vercel.app/api?username=smirtaza&theme=tokyonight" width="80%" alt="Articles Feed" />
  </a>
</div>

---

<!-- TERMINAL SNAKE GAME -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=10,12,15&text=🐍+SNAKE+GAME&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Snake Game Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img src="https://raw.githubusercontent.com/smirtaza-oss/smirtaza-oss/output/github-contribution-grid-snake-dark.svg" width="70%" alt="Contribution Snake Visualizer" />
</div>

---

<!-- VIM REGISTER CONFIGURATION TERMINAL -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=12,14,18&text=⌨️+VIM+MASTERY&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Vim Mastery Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <div style="background-color:#1e1e2e; border:1px solid #7B61FF; border-radius:10px; padding:20px; max-width:700px; text-align:left; font-family:'Fira Code', 'Courier New', monospace; box-shadow: 0 0 10px rgba(123, 97, 255, 0.15);">
    <div style="color:#f5e0dc; font-size:16px; border-bottom:1px solid #313244; padding-bottom:8px; margin-bottom:12px; font-weight:bold;">
      ~/.config/nvim/lua/keymaps.lua
    </div>
    <div style="font-size:14px; color:#cdd6f4; line-height:1.7;">
      <span style="color:#6c7086;">-- Native fast registers & utility shortcuts</span><br>
      <span style="color:#f38ba8;">vim.keymap.set</span>(<span style="color:#a6e3a1;">"n"</span>, <span style="color:#a6e3a1;">"&lt;leader&gt;w"</span>, <span style="color:#a6e3a1;">":w&lt;CR&gt;"</span>, { desc = <span style="color:#89b4fa;">"Write buffer to disk"</span> })<br>
      <span style="color:#f38ba8;">vim.keymap.set</span>(<span style="color:#a6e3a1;">"n"</span>, <span style="color:#a6e3a1;">"&lt;leader&gt;q"</span>, <span style="color:#a6e3a1;">":q!&lt;CR&gt;"</span>, { desc = <span style="color:#89b4fa;">"Force quit without saving"</span> })<br>
      <span style="color:#f38ba8;">vim.keymap.set</span>(<span style="color:#a6e3a1;">"n"</span>, <span style="color:#a6e3a1;">"dd"</span>, <span style="color:#a6e3a1;">'"_dd'</span>, { desc = <span style="color:#89b4fa;">"Delete line without overwriting register"</span> })<br>
      <span style="color:#f38ba8;">vim.keymap.set</span>(<span style="color:#a6e3a1;">"n"</span>, <span style="color:#a6e3a1;">"&lt;leader&gt;f"</span>, <span style="color:#f38ba8;">function</span>() <span style="color:#f38ba8;">vim.lsp.buf.format</span>() <span style="color:#f38ba8;">end</span>, { desc = <span style="color:#89b4fa;">"Auto-indent syntax tree"</span> })<br>
      <span style="color:#f38ba8;">vim.keymap.set</span>(<span style="color:#a6e3a1;">"v"</span>, <span style="color:#a6e3a1;">"p"</span>, <span style="color:#a6e3a1;">'"_dP'</span>, { desc = <span style="color:#89b4fa;">"Paste preserve register"</span> })
    </div>
  </div>
</div>

---

<!-- CS RESEARCH JOURNAL INDEX -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=24,23,22&text=📄+LATEST+CS+PAPER&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Research Paper Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <div style="border-left: 4px solid #00F7FF; background-color: #0d1117; padding: 15px 25px; max-width: 600px; text-align: left; border-radius: 0 8px 8px 0;">
    <strong style="color: #ffffff; font-family: 'JetBrains Mono', monospace;">📌 "Attention Is All You Need" — Vaswani et al.</strong>
    <p style="color: #8b949e; font-size: 14px; line-height: 1.5; margin: 8px 0 12px 0;">
      A fundamental architectural breakthrough replacing recurrent sequence structures with dynamic multi-head self-attention mechanisms.
    </p>
    <a href="https://arxiv.org/abs/1706.03762" style="color: #00F7FF; text-decoration: none; font-size: 13px; font-weight: bold; font-family: 'JetBrains Mono', monospace;">→ Access Paper PDF Instance</a>
  </div>
</div>

---

<!-- COMPETITIVE PROGRAMMING PLATFORMS -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=12,14,18&text=⚔️+COMPETITIVE+PROGRAMMING&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Competitive Programming Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img src="https://leetcard.jacoblin.cool/smirtaza?theme=tokyonight&font=JetBrains%20Mono&ext=heatmap" width="49%" alt="Leetcode Card" />
  <img src="https://codeforces-readme-stats.vercel.app/api/card?username=smirtaza&theme=tokyonight" width="49%" alt="Codeforces Card" />
</div>

---

<!-- WAKATIME CODING METRICS -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=24,23,22&text=⏱️+CODING+METRICS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Coding Metrics Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img src="https://github-readme-stats.vercel.app/api/wakatime?username=smirtaza&theme=tokyonight&hide_border=true&layout=compact&langs_count=10" alt="WakaTime Statistics" />
  <br>
  <img src="https://wakatime.com/share/@smirtaza/5b3c5f6e-1f45-4b7a-b08e-38b1a2f3f7cd.svg" width="49%" alt="WakaTime Chart" />
</div>

---

<!-- SPOTIFY INTEGRATION -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=12,14,18&text=🎵+CODING+PLAYLIST&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Coding Playlist Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img src="https://spotify-github-profile.vercel.app/api/view?uid=YOUR_SPOTIFY_USER_ID&cover_image=true&theme=novatorem&show_offline=false&background_color=121212&interchange=true&bar_color=53b14f&bar_color_cover=true" alt="Spotify Live Player" />
</div>

---

<!-- LOCAL SYSTEM CLOCK -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=24,23,22&text=⏰+LOCAL+TIME&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Local Time Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img src="https://readme-clock.vercel.app/?timezone=Asia/Karachi&theme=tokyonight" alt="Local Time Clock" />
</div>

---

<!-- INFRASTRUCTURE STATUS -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=27,28,29&text=📡+SYSTEM+STATUS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="System Status Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img src="https://img.shields.io/badge/CPU-35%25-brightgreen?style=for-the-badge&logo=intel" alt="CPU Badges" />
  <img src="https://img.shields.io/badge/RAM-12.4GB%2F64GB-blue?style=for-the-badge&logo=mem" alt="Memory Badges" />
  <img src="https://img.shields.io/badge/Uptime-42%20days-orange?style=for-the-badge&logo=linux" alt="Uptime Badges" />
</div>

---

<!-- INTEGRATIVE INSPIRATIONAL ENGINE -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=6,11,20&text=💡+INSPIRATION&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Inspiration Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="CS Quotes" />
  <br>
  <img src="https://readme-jokes.vercel.app/api?theme=tokyonight" width="500" alt="Tech Jokes" />
  <br>
  <a href="https://xkcd.com/" target="_blank">
    <img src="https://xkcd.com/s/0b7742.png" width="300" alt="xkcd Comic" />
  </a>
</div>

---

<!-- FINANCIAL SPONSORSHIP PORTALS -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=6,11,20&text=❤️+SUPPORT+MY+WORK&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Support Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <a href="https://www.buymeacoffee.com/smirtaza">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="60" alt="Buy Me A Coffee" />
  </a>&nbsp;
  <a href="https://github.com/sponsors/smirtaza-oss">
    <img src="https://img.shields.io/badge/Sponsor-%23EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white" height="60" alt="GitHub Sponsor" />
  </a>
</div>

---

<!-- SOUNDWAVE OSCILLATOR FREQUENCY DISPLAY (Self-Contained Inline Animated SVG) -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=27,28,29&text=🔊+DYNAMIC+SOUNDWAVE+SPECTRUM&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Soundwave Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 100" width="85%" height="100" style="background-color: #0d1117; border-radius: 8px;">
    <style>
      @keyframes soundwave-bounce {
        0%, 100% { transform: scaleY(0.2); }
        50% { transform: scaleY(1); }
      }
      .wave-frequency-bar {
        fill: url(#wave-gradient);
        transform-origin: bottom;
        animation: soundwave-bounce 1.2s ease-in-out infinite;
      }
    </style>
    <defs>
      <linearGradient id="wave-gradient" x1="0%" y1="0%" x2="0%" y2="100%">
        <stop offset="0%" stop-color="#00F7FF" />
        <stop offset="100%" stop-color="#7B61FF" />
      </linearGradient>
    </defs>
    <!-- Multi-Node Oscillating Frequency Array -->
    <rect class="wave-frequency-bar" x="50" y="10" width="8" height="80" rx="3" style="animation-delay: 0.1s;" />
    <rect class="wave-frequency-bar" x="80" y="10" width="8" height="80" rx="3" style="animation-delay: 0.4s;" />
    <rect class="wave-frequency-bar" x="110" y="10" width="8" height="80" rx="3" style="animation-delay: 0.2s;" />
    <rect class="wave-frequency-bar" x="140" y="10" width="8" height="80" rx="3" style="animation-delay: 0.6s;" />
    <rect class="wave-frequency-bar" x="170" y="10" width="8" height="80" rx="3" style="animation-delay: 0.3s;" />
    <rect class="wave-frequency-bar" x="200" y="10" width="8" height="80" rx="3" style="animation-delay: 0.8s;" />
    <rect class="wave-frequency-bar" x="230" y="10" width="8" height="80" rx="3" style="animation-delay: 0.5s;" />
    <rect class="wave-frequency-bar" x="260" y="10" width="8" height="80" rx="3" style="animation-delay: 0.7s;" />
    <rect class="wave-frequency-bar" x="290" y="10" width="8" height="80" rx="3" style="animation-delay: 0.15s;" />
    <rect class="wave-frequency-bar" x="320" y="10" width="8" height="80" rx="3" style="animation-delay: 0.45s;" />
    <rect class="wave-frequency-bar" x="350" y="10" width="8" height="80" rx="3" style="animation-delay: 0.25s;" />
    <rect class="wave-frequency-bar" x="380" y="10" width="8" height="80" rx="3" style="animation-delay: 0.65s;" />
    <rect class="wave-frequency-bar" x="410" y="10" width="8" height="80" rx="3" style="animation-delay: 0.35s;" />
    <rect class="wave-frequency-bar" x="440" y="10" width="8" height="80" rx="3" style="animation-delay: 0.85s;" />
    <rect class="wave-frequency-bar" x="470" y="10" width="8" height="80" rx="3" style="animation-delay: 0.55s;" />
    <rect class="wave-frequency-bar" x="500" y="10" width="8" height="80" rx="3" style="animation-delay: 0.75s;" />
    <rect class="wave-frequency-bar" x="530" y="10" width="8" height="80" rx="3" style="animation-delay: 0.18s;" />
    <rect class="wave-frequency-bar" x="560" y="10" width="8" height="80" rx="3" style="animation-delay: 0.48s;" />
    <rect class="wave-frequency-bar" x="590" y="10" width="8" height="80" rx="3" style="animation-delay: 0.28s;" />
    <rect class="wave-frequency-bar" x="620" y="10" width="8" height="80" rx="3" style="animation-delay: 0.68s;" />
    <rect class="wave-frequency-bar" x="650" y="10" width="8" height="80" rx="3" style="animation-delay: 0.38s;" />
    <rect class="wave-frequency-bar" x="680" y="10" width="8" height="80" rx="3" style="animation-delay: 0.88s;" />
    <rect class="wave-frequency-bar" x="710" y="10" width="8" height="80" rx="3" style="animation-delay: 0.58s;" />
    <rect class="wave-frequency-bar" x="740" y="10" width="8" height="80" rx="3" style="animation-delay: 0.78s;" />
  </svg>
</div>

---

<!-- SYSTEM PHILOSOPHY -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=12,14,18&text=⚡+PHILOSOPHY&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Philosophy Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <h2>「 Think • Code • Research • Repeat 」</h2>
  <h3 style="color:#7B61FF;">🧠 Turning abstract complexity into robust runtime systems.</h3>
</div>

<!-- Bottom Wave Capsule -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=220&color=gradient&customColorList=6,11,20,24,30" alt="Footer Wave"/>
