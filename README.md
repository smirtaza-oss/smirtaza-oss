<!-- 
  🎓 COMPUTER SCIENCE HACKER PROFILE – SYSTEMS PROGRAMMER & AI RESEARCHER
  Designed with native CSS animations, structured vectors, and terminal emulator components.
-->

<div align="center">

<!-- Matrix Rain Banner -->
<img width="100%" src="https://media.giphy.com/media/l0HlPwMA6zhHmQdWM/giphy.gif?cid=790b7611ul4v3r29g0f7hx4qk8h0e4h4x4o3p3m7&rid=giphy.gif&ct=g" alt="Matrix Rain" />

<br>

<!-- Dynamic Waving Capsule Header -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=320&color=gradient&customColorList=6,11,20,24,30&text=MIRTAZA&fontColor=ffffff&fontSize=80&animation=fadeIn&fontAlignY=38&desc=Computer%20Science%20Graduate%20%7C%20AI%20Researcher%20%7C%20Systems%20Programmer&descAlignY=58" alt="Mirtaza Capsule Header"/>

<br>

<!-- Multi-Line Typist SVGs -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=30&duration=3000&pause=900&color=00F7FF&center=true&vCenter=true&width=1100&lines=👋+Hello%2C+World!+I'm+Mirtaza;💻+Computer+Science+Enthusiast;📚+Algorithms+%26+Data+Structures;⚙️+Operating+Systems+%26+Compilers;🤖+Artificial+Intelligence+Researcher;🧪+Building+Systems+that+Scale" alt="Typing SVG" />

<br><br>

<!-- Tech Badges -->
<img src="https://img.shields.io/github/followers/smirtaza-oss?style=for-the-badge&logo=github&color=181717" alt="Followers Badge"/>
<img src="https://img.shields.io/github/stars/smirtaza-oss?style=for-the-badge&logo=github&color=FFD700" alt="Stars Badge"/>
<img src="https://komarev.com/ghpvc/?username=smirtaza-oss&style=for-the-badge&color=blueviolet" alt="Profile Views"/>
<img src="https://img.shields.io/badge/Open%20Source-Advocate-00C853?style=for-the-badge" alt="Open Source Advocate"/>
<img src="https://img.shields.io/badge/CS-Graduate-7B61FF?style=for-the-badge" alt="CS Graduate"/>
<img src="https://img.shields.io/badge/Research-AI%20%26%20Systems-orange?style=for-the-badge&logo=arxiv" alt="Research Scholar"/>

<br><br>

<!-- Native CSS Animated Divider (No external resources needed) -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 20" width="100%">
  <style>
    @keyframes pulse-width {
      0% { stroke-dashoffset: 1000; }
      50% { stroke-dashoffset: 0; }
      100% { stroke-dashoffset: -1000; }
    }
    .neon-line {
      stroke: url(#cyan-purple-grad);
      stroke-width: 3;
      stroke-linecap: round;
      stroke-dasharray: 200 400;
      animation: pulse-width 8s linear infinite;
    }
  </style>
  <defs>
    <linearGradient id="cyan-purple-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00F7FF" />
      <stop offset="50%" stop-color="#7B61FF" />
      <stop offset="100%" stop-color="#00F7FF" />
    </linearGradient>
  </defs>
  <line class="neon-line" x1="10" y1="10" x2="990" y2="10" />
</svg>

</div>

---

<!-- GLOWING NEON LAB BORDERS (Inline Vector) -->
<div align="center">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 120" width="90%">
    <style>
      @keyframes neon-flicker {
        0%, 19%, 21%, 23%, 25%, 54%, 56%, 100% {
          filter: drop-shadow(0 0 2px #00F7FF) drop-shadow(0 0 8px #7B61FF);
        }
        20%, 24%, 55% {
          filter: none;
        }
      }
      .neon-rect {
        stroke: url(#neon-grad);
        stroke-width: 2;
        fill: #0d1117;
        animation: neon-flicker 6s infinite alternate;
      }
      .neon-text {
        font-family: 'JetBrains Mono', monospace;
        font-weight: bold;
        fill: #ffffff;
        font-size: 20px;
        letter-spacing: 4px;
        animation: neon-flicker 4s infinite alternate;
      }
    </style>
    <defs>
      <linearGradient id="neon-grad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#00F7FF" />
        <stop offset="50%" stop-color="#7B61FF" />
        <stop offset="100%" stop-color="#FF007F" />
      </linearGradient>
    </defs>
    <rect class="neon-rect" x="5" y="5" width="790" height="110" rx="15" />
    <text class="neon-text" x="50%" y="62" dominant-baseline="middle" text-anchor="middle">⚡ VIRTUAL COMPUTER SCIENCE LAB ⚡</text>
  </svg>
</div>

<br>

<!-- ROTATING 3D NODE NETWORK LOGO -->
<div align="center">
  <table style="border: none; background: transparent;">
    <tr>
      <td align="center" style="border: none; padding: 20px;">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 400 400" width="220" height="220">
          <style>
            @keyframes orbit-cw {
              0% { transform: rotate(0deg); }
              100% { transform: rotate(360deg); }
            }
            @keyframes orbit-ccw {
              0% { transform: rotate(360deg); }
              100% { transform: rotate(0deg); }
            }
            @keyframes pulse-node {
              0%, 100% { r: 6; fill: #00F7FF; filter: drop-shadow(0 0 2px #00F7FF); }
              50% { r: 10; fill: #7B61FF; filter: drop-shadow(0 0 8px #7B61FF); }
            }
            .orbiting-group-1 {
              transform-origin: 200px 200px;
              animation: orbit-cw 12s linear infinite;
            }
            .orbiting-group-2 {
              transform-origin: 200px 200px;
              animation: orbit-ccw 18s linear infinite;
            }
            .node-pulsing {
              animation: pulse-node 3s ease-in-out infinite;
            }
            .core-node {
              fill: #ffffff;
              filter: drop-shadow(0 0 12px #00F7FF);
              animation: pulse-node 2s ease-in-out infinite alternate;
            }
          </style>
          <!-- Background grids -->
          <circle cx="200" cy="200" r="150" stroke="#1f2937" stroke-width="1" fill="none" stroke-dasharray="5, 5" />
          <circle cx="200" cy="200" r="90" stroke="#1f2937" stroke-width="1" fill="none" stroke-dasharray="3, 3" />
          
          <!-- Connections/Lines -->
          <g opacity="0.4" stroke="#7B61FF" stroke-width="1.5">
            <line x1="200" y1="200" x2="100" y2="100" />
            <line x1="200" y1="200" x2="300" y2="100" />
            <line x1="200" y1="200" x2="300" y2="300" />
            <line x1="200" y1="200" x2="100" y2="300" />
            <line x1="100" y1="100" x2="300" y2="100" />
            <line x1="300" y1="100" x2="300" y2="300" />
            <line x1="300" y1="300" x2="100" y2="300" />
            <line x1="100" y1="300" x2="100" y2="100" />
          </g>

          <!-- Core Node Representing the AI Central Processor -->
          <circle class="core-node" cx="200" cy="200" r="14" />

          <!-- Orbiting System 1 -->
          <g class="orbiting-group-1">
            <line x1="200" y1="50" x2="200" y2="350" stroke="#00F7FF" stroke-width="1" opacity="0.3" />
            <circle class="node-pulsing" cx="200" cy="50" r="8" />
            <circle class="node-pulsing" cx="200" cy="350" r="8" />
            <circle cx="50" cy="200" r="6" fill="#7B61FF" />
            <circle cx="350" cy="200" r="6" fill="#7B61FF" />
          </g>

          <!-- Orbiting System 2 -->
          <g class="orbiting-group-2">
            <rect x="85" y="85" width="230" height="230" stroke="#FF007F" stroke-width="1" fill="none" opacity="0.2" rx="10"/>
            <circle cx="110" cy="110" r="7" fill="#FF007F" />
            <circle cx="290" cy="110" r="7" fill="#FF007F" />
            <circle cx="290" cy="290" r="7" fill="#FF007F" />
            <circle cx="110" cy="290" r="7" fill="#FF007F" />
          </g>
        </svg>
      </td>
    </tr>
  </table>
</div>

---

<!-- LIVE SYSTEM INFORMATION – Interactive Lab Dashboard -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=100&color=gradient&customColorList=6,11,20&text=SYSTEM%20SPECIFICATIONS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="System Info Header"/>
</div>

<div align="center" style="margin:20px 0;">
  <div style="background-color:#0d1117; border:2px solid #00FF41; border-radius:15px; padding:25px; max-width:850px; text-align:left; box-shadow: 0 0 15px rgba(0,255,65,0.2);">
    <div style="display:flex; justify-content:space-between; border-bottom: 2px solid #1f2937; padding-bottom:10px; margin-bottom:15px;">
      <span style="color:#ff5f56; font-size:18px;">● <span style="color:#ffbd2e;">●</span> <span style="color:#27c93f;">●</span></span>
      <span style="color:#8b949e; font-family:'Courier New', Courier, monospace; font-size:14px;">mirtaza@cs-mainframe:~</span>
    </div>
    <div style="font-family:'Fira Code', 'Courier New', monospace; font-size:15px; color:#c9d1d9; line-height:1.6;">
      <span style="color:#58a6ff;">mirtaza@cs-mainframe</span>:<span style="color:#2ea043;">~</span>$ neofetch --profile<br>
      <span style="color:#00FF41;">████████████████████████</span>    <span style="color:#58a6ff;">OS</span>: Arch Linux x86_64 <br>
      <span style="color:#00FF41;">████████████████████████</span>    <span style="color:#58a6ff;">Kernel</span>: Custom 6.6.14-rt-systems-hardened <br>
      <span style="color:#00FF41;">██████</span>        <span style="color:#00FF41;">██████████</span>    <span style="color:#58a6ff;">Shell</span>: zsh 5.9 (omz theme: custom-powerlevel10k) <br>
      <span style="color:#00FF41;">██████</span>        <span style="color:#00FF41;">██████████</span>    <span style="color:#58a6ff;">WM</span>: i3-gaps (Tokyo Night Palette) <br>
      <span style="color:#00FF41;">██████</span>  <span style="color:#00FF41;">████</span>  <span style="color:#00FF41;">██████████</span>    <span style="color:#58a6ff;">CPU</span>: AMD Ryzen 9 5950X (32) @ 4.90GHz <br>
      <span style="color:#00FF41;">██████</span>  <span style="color:#00FF41;">████</span>  <span style="color:#00FF41;">██████████</span>    <span style="color:#58a6ff;">GPU</span>: NVIDIA GeForce RTX 4090 24GB <br>
      <span style="color:#00FF41;">██████</span>  <span style="color:#00FF41;">████</span>  <span style="color:#00FF41;">██████████</span>    <span style="color:#58a6ff;">Memory</span>: 64GB DDR5 ECC @ 5200MHz <br>
      <span style="color:#00FF41;">██████</span>  <span style="color:#00FF41;">████</span>  <span style="color:#00FF41;">██████████</span>    <span style="color:#58a6ff;">Storage</span>: 4TB NVMe SSD PCIe Gen 4 (Raid 0) <br>
      <span style="color:#00FF41;">██████</span>  <span style="color:#00FF41;">████</span>  <span style="color:#00FF41;">██████████</span>    <span style="color:#58a6ff;">Uptime</span>: 104 days, 14 hours, 32 mins <br>
      <span style="color:#00FF41;">████████████████████████</span>    <span style="color:#58a6ff;">Primary Editors</span>: Neovim, Emacs, VSCode <br>
      <span style="color:#00FF41;">████████████████████████</span>    <span style="color:#58a6ff;">Target Fields</span>: Compilers, Microkernels, GNNs <br>
      <br>
      <span style="color:#58a6ff;">mirtaza@cs-mainframe</span>:<span style="color:#2ea043;">~</span>$ <span style="animation: cursor-blink 1s step-end infinite;">_</span>
    </div>
  </div>
</div>

<style>
  @keyframes cursor-blink {
    from, to { opacity: 0; }
    50% { opacity: 1; }
  }
</style>

---

<!-- SOCIAL CHANNELS & PORTFOLIO DECK -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=12,14,18&text=🌌+CONNECT+CHANNELS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Connect Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <a href="https://github.com/smirtaza-oss"><img src="https://skillicons.dev/icons?i=github" height="60" alt="GitHub" /></a>&nbsp;&nbsp;
  <a href="https://linkedin.com/in/smirtaza"><img src="https://skillicons.dev/icons?i=linkedin" height="60" alt="LinkedIn" /></a>&nbsp;&nbsp;
  <a href="https://discord.gg/invite"><img src="https://skillicons.dev/icons?i=discord" height="60" alt="Discord" /></a>&nbsp;&nbsp;
  <a href="https://instagram.com/mirtaza"><img src="https://skillicons.dev/icons?i=instagram" height="60" alt="Instagram" /></a>&nbsp;&nbsp;
  <a href="mailto:smirtaza.dev@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" height="60" alt="Gmail" /></a>
</div>

---

<!-- 🧠 CORE COMPUTER SCIENCE DOMAINS (GRID LAYOUT) -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=10,12,15&text=🧠+COMPUTER+SCIENCE+FOUNDATIONS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="CS Foundations Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <table style="width: 100%; max-width: 900px; border-collapse: collapse; border: none; text-align: left; font-family: 'JetBrains Mono', monospace;">
    <tr style="background-color: #0d1117;">
      <td style="padding: 15px; border: 1px solid #30363d; width: 50%;">
        <h3 style="color: #00F7FF; margin-top: 0;">🔬 Theory of Computation</h3>
        <p style="color: #8b949e; font-size: 13px; line-height: 1.5;">Deterministic/Nondeterministic Finite Automata (DFA/NFA), Context-Free Grammars, Turing completeness, and P vs NP complexity bounds.</p>
        <span style="background: #1f2937; color: #58a6ff; padding: 2px 8px; border-radius: 4px; font-size: 11px;">Chomsky Hierarchy</span>
        <span style="background: #1f2937; color: #58a6ff; padding: 2px 8px; border-radius: 4px; font-size: 11px;">Decidability</span>
      </td>
      <td style="padding: 15px; border: 1px solid #30363d; width: 50%;">
        <h3 style="color: #7B61FF; margin-top: 0;">⚙️ Systems Programming</h3>
        <p style="color: #8b949e; font-size: 13px; line-height: 1.5;">POSIX threads, process synchronization mechanisms, Virtual Memory translation, and low-level kernel development.</p>
        <span style="background: #1f2937; color: #58a6ff; padding: 2px 8px; border-radius: 4px; font-size: 11px;">Linux Core</span>
        <span style="background: #1f2937; color: #58a6ff; padding: 2px 8px; border-radius: 4px; font-size: 11px;">Syscalls</span>
      </td>
    </tr>
    <tr style="background-color: #0d1117;">
      <td style="padding: 15px; border: 1px solid #30363d;">
        <h3 style="color: #FF007F; margin-top: 0;">⚡ Advanced Algorithms</h3>
        <p style="color: #8b949e; font-size: 13px; line-height: 1.5;">Graph traversals, Network Flow optimization (Ford-Fulkerson), Dynamic Programming heuristics, and amortized complexity analyses.</p>
        <span style="background: #1f2937; color: #58a6ff; padding: 2px 8px; border-radius: 4px; font-size: 11px;">Big-O Proofs</span>
        <span style="background: #1f2937; color: #58a6ff; padding: 2px 8px; border-radius: 4px; font-size: 11px;">Data Trees</span>
      </td>
      <td style="padding: 15px; border: 1px solid #30363d;">
        <h3 style="color: #00FF41; margin-top: 0;">🤖 Artificial Intelligence</h3>
        <p style="color: #8b949e; font-size: 13px; line-height: 1.5;">Backpropagation neural paths, Transformers, Graph Neural Networks (GNNs), and reinforcement learning strategies.</p>
        <span style="background: #1f2937; color: #58a6ff; padding: 2px 8px; border-radius: 4px; font-size: 11px;">PyTorch</span>
        <span style="background: #1f2937; color: #58a6ff; padding: 2px 8px; border-radius: 4px; font-size: 11px;">Transformers</span>
      </td>
    </tr>
  </table>
</div>

---

<!-- INTERACTIVE ALGORITHMIC VISUALIZATION: CPU EXECUTION PIPELINE (Native SVG Animation) -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=6,11,20&text=🔄+INSTRUCTION+PIPELINE+SIMULATOR&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Pipeline Simulator Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 200" width="100%" style="background-color: #0d1117; border-radius: 12px; border: 1px solid #30363d;">
    <style>
      @keyframes stage-shift {
        0%, 100% { fill: #00F7FF; }
        25% { fill: #7B61FF; }
        50% { fill: #FF007F; }
        75% { fill: #00FF41; }
      }
      @keyframes data-flow {
        0% { transform: translateX(0px); }
        100% { transform: translateX(150px); }
      }
      .pipeline-node {
        stroke-width: 2;
        stroke: #30363d;
      }
      .p-stage-1 { fill: #00F7FF; }
      .p-stage-2 { fill: #7B61FF; }
      .p-stage-3 { fill: #FF007F; }
      .p-stage-4 { fill: #00FF41; }
      
      .flow-packet {
        animation: data-flow 4s linear infinite;
        fill: #ffffff;
        filter: drop-shadow(0 0 4px #00F7FF);
      }
      .arrow {
        stroke: #8b949e;
        stroke-width: 2;
        fill: none;
      }
    </style>

    <!-- Stage Borders -->
    <rect class="pipeline-node p-stage-1" x="50" y="50" width="120" height="80" rx="8" />
    <text x="110" y="95" fill="#000" font-family="'JetBrains Mono', monospace;" font-weight="bold" text-anchor="middle">1. FETCH</text>

    <path class="arrow" d="M 170,90 L 220,90" />

    <rect class="pipeline-node p-stage-2" x="230" y="50" width="120" height="80" rx="8" />
    <text x="290" y="95" fill="#fff" font-family="'JetBrains Mono', monospace;" font-weight="bold" text-anchor="middle">2. DECODE</text>

    <path class="arrow" d="M 350,90 L 400,90" />

    <rect class="pipeline-node p-stage-3" x="410" y="50" width="120" height="80" rx="8" />
    <text x="470" y="95" fill="#fff" font-family="'JetBrains Mono', monospace;" font-weight="bold" text-anchor="middle">3. EXECUTE</text>

    <path class="arrow" d="M 530,90 L 580,90" />

    <rect class="pipeline-node p-stage-4" x="590" y="50" width="120" height="80" rx="8" />
    <text x="650" y="95" fill="#000" font-family="'JetBrains Mono', monospace;" font-weight="bold" text-anchor="middle">4. WRITE</text>

    <!-- Animated Data Stream Packets -->
    <g>
      <circle class="flow-packet" cx="110" cy="90" r="5" />
      <circle class="flow-packet" cx="290" cy="90" r="5" />
      <circle class="flow-packet" cx="470" cy="90" r="5" />
    </g>

    <!-- Status Bar -->
    <text x="400" y="175" fill="#8b949e" font-family="'JetBrains Mono', monospace;" font-size="12" text-anchor="middle">Active execution clock cycle: 4.8 GHz | Instruction dynamic translation pipeline status: OK</text>
  </svg>
</div>

---

<!-- FULL STACK TECHNOLOGY MATRIX -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=24,23,22&text=⚙️+SYSTEM+ENGINEERING+STACK&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Systems Tech Stack Header"/>
</div>

<div align="center" style="margin:20px 0;">
  <img src="https://skillicons.dev/icons?i=cpp,c,rust,python,java,go,assembly,bash,latex&perline=9" alt="Languages Infrastructure" /><br>
  <img src="https://skillicons.dev/icons?i=linux,docker,kubernetes,aws,gcp,git,github,postgres,redis&perline=9" alt="Platforms Infrastructure" />
</div>

---

<!-- ANALYTICS RADARS & REALTIME METRICS -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=6,11,20&text=📡+DEVELOPER+KPI%20%7C%20METRICS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Analytics Radar Header"/>
</div>

<div align="center" style="margin: 20px 0; display: flex; flex-wrap: wrap; justify-content: center; gap: 20px;">
  <img src="https://raw.githubusercontent.com/smirtaza-oss/smirtaza-oss/main/profile-summary-card-output/tokyonight/4-productive-time.svg" width="410" alt="Activity Wave" />
  <img src="https://raw.githubusercontent.com/smirtaza-oss/smirtaza-oss/main/profile-summary-card-output/tokyonight/5-most-commit-language.svg" width="410" alt="Language Dialects" />
</div>

---

<!-- GITHUB ANALYTICS & REPOSITORY TELEMETRY -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=12,14,18&text=📊+GITHUB+ENGINEERING+METRICS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Metrics Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=smirtaza-oss&show_icons=true&theme=tokyonight&hide_border=true" alt="Github Stats" />
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=smirtaza-oss&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages Map" />
  <br>
  <img width="99%" src="https://streak-stats.demolab.com?user=smirtaza-oss&theme=tokyonight&hide_border=true" alt="Commit Streak" />
  <br>
  <img width="99%" src="https://github-readme-activity-graph.vercel.app/graph?username=smirtaza-oss&theme=tokyo-night&hide_border=true" alt="Telemetry Curve Graph" />
</div>

---

<!-- RECENT ACTIVITY ENGINE -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=24,23,22&text=🕒+REAL-TIME+COMMIT+STREAM&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Commit Stream Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img src="https://github-readme-activity.vercel.app/api?username=smirtaza-oss&theme=tokyonight&hide_border=true" width="90%" alt="Activity Log" />
</div>

---

<!-- PROJECT METRICS / ROADMAP COMPLETED -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=27,28,29&text=📈+ACADEMIC+%26+SYSTEMS+ROADMAP&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Roadmap Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <table style="border: none; background: transparent; font-family: 'JetBrains Mono', monospace; font-size: 14px; width: 85%;">
    <tr>
      <td style="padding: 10px; border: none; text-align: left; color:#fff;">System Kernel Customization</td>
      <td style="padding: 10px; border: none; text-align: right;">
        <img src="https://progress-bar.dev/85/?title=Kernels&width=300&color=00FF41" alt="Kernel Progress" />
      </td>
    </tr>
    <tr>
      <td style="padding: 10px; border: none; text-align: left; color:#fff;">Distributed Machine Learning Systems</td>
      <td style="padding: 10px; border: none; text-align: right;">
        <img src="https://progress-bar.dev/70/?title=DeepLearning&width=300&color=00F7FF" alt="ML Progress" />
      </td>
    </tr>
    <tr>
      <td style="padding: 10px; border: none; text-align: left; color:#fff;">Formal Compiler Construction (RISC-V Backend)</td>
      <td style="padding: 10px; border: none; text-align: right;">
        <img src="https://progress-bar.dev/90/?title=Compilers&width=300&color=7B61FF" alt="Compiler Progress" />
      </td>
    </tr>
  </table>
</div>

---

<!-- MAC-OS SYSTEM STYLE REALTIME ACTIVITY RINGS -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=10,12,15&text=🍎+ACTIVITY+TELEMETRY+RINGS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Activity Rings Header"/>
</div>

<div align="center" style="margin: 20px 0; display: flex; flex-wrap: wrap; justify-content: center; gap: 20px;">
  <img src="https://raw.githubusercontent.com/smirtaza-oss/smirtaza-oss/main/profile-summary-card-output/tokyonight/3-stats.svg" width="49%" alt="System Stats Dial" />
  <img src="https://raw.githubusercontent.com/smirtaza-oss/smirtaza-oss/main/profile-summary-card-output/tokyonight/0-profile-details.svg" width="49%" alt="Interactive System Config" />
</div>

---

<!-- 🌌 DEEP LEARNING COMPILER PIPELINE VISUALIZATION (Inline Vector Model) -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=27,28,29&text=📊+AI+MODEL+DENSE+FORWARD+PROPAGATION&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Neural Net Visualization Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 250" width="100%" style="background-color: #0d1117; border-radius: 12px; border: 1px solid #30363d;">
    <style>
      @keyframes synapse-fire {
        0% { stroke-dashoffset: 100; opacity: 0.2; }
        50% { opacity: 0.8; }
        100% { stroke-dashoffset: 0; opacity: 0.2; }
      }
      @keyframes cell-pulse {
        0%, 100% { transform: scale(1); filter: drop-shadow(0 0 2px rgba(123, 97, 255, 0.4)); }
        50% { transform: scale(1.1); filter: drop-shadow(0 0 10px #7B61FF); }
      }
      .synapse {
        stroke-dasharray: 10;
        animation: synapse-fire 6s linear infinite;
      }
      .neural-node {
        transform-origin: center;
        animation: cell-pulse 3s ease-in-out infinite alternate;
      }
      .nn-layer-1 { fill: #00F7FF; }
      .nn-layer-2 { fill: #7B61FF; }
      .nn-layer-3 { fill: #FF007F; }
    </style>

    <!-- Synapses (Lines) -->
    <g stroke="url(#cyan-purple-grad)" stroke-width="1.5">
      <!-- Input to Hidden Layer -->
      <line class="synapse" x1="100" y1="50" x2="400" y2="50" />
      <line class="synapse" x1="100" y1="50" x2="400" y2="125" />
      <line class="synapse" x1="100" y1="125" x2="400" y2="50" />
      <line class="synapse" x1="100" y1="125" x2="400" y2="125" />
      <line class="synapse" x1="100" y1="125" x2="400" y2="200" />
      <line class="synapse" x1="100" y1="200" x2="400" y2="125" />
      <line class="synapse" x1="100" y1="200" x2="400" y2="200" />

      <!-- Hidden Layer to Output Layer -->
      <line class="synapse" x1="400" y1="50" x2="700" y2="85" />
      <line class="synapse" x1="400" y1="50" x2="700" y2="165" />
      <line class="synapse" x1="400" y1="125" x2="700" y2="85" />
      <line class="synapse" x1="400" y1="125" x2="700" y2="165" />
      <line class="synapse" x1="400" y1="200" x2="700" y2="165" />
    </g>

    <!-- Node Groups -->
    <!-- Input Layer -->
    <g class="neural-node">
      <circle class="nn-layer-1" cx="100" cy="50" r="12" />
      <circle class="nn-layer-1" cx="100" cy="125" r="12" />
      <circle class="nn-layer-1" cx="100" cy="200" r="12" />
    </g>

    <!-- Hidden Representation Layer -->
    <g class="neural-node" style="animation-delay: -1s;">
      <circle class="nn-layer-2" cx="400" cy="50" r="14" />
      <circle class="nn-layer-2" cx="400" cy="125" r="14" />
      <circle class="nn-layer-2" cx="400" cy="200" r="14" />
    </g>

    <!-- Output Strategy Nodes -->
    <g class="neural-node" style="animation-delay: -2s;">
      <circle class="nn-layer-3" cx="700" cy="85" r="16" />
      <circle class="nn-layer-3" cx="700" cy="165" r="16" />
    </g>

    <!-- Labeling the Topology -->
    <text x="100" y="240" fill="#8b949e" font-family="'JetBrains Mono', monospace" font-size="12" text-anchor="middle">Input Vectors (X)</text>
    <text x="400" y="240" fill="#8b949e" font-family="'JetBrains Mono', monospace" font-size="12" text-anchor="middle">Latent Space (Wᵀx + b)</text>
    <text x="700" y="240" fill="#8b949e" font-family="'JetBrains Mono', monospace" font-size="12" text-anchor="middle">Logits (ŷ)</text>
  </svg>
</div>

---

<!-- FEATURED RESEARCH AND SCHOLARLY PROJECTS -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=10,12,15&text=📌+CORE+RESEARCH+PROJECTS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Research Projects Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <a href="https://github.com/smirtaza-oss/os-kernel">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=smirtaza-oss&repo=os-kernel&theme=tokyonight&hide_border=true" alt="Kernel Rep Card" />
  </a>
  <a href="https://github.com/smirtaza-oss/ml-compiler">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=smirtaza-oss&repo=ml-compiler&theme=tokyonight&hide_border=true" alt="Compiler Rep Card" />
  </a>
  <br>
  <a href="https://github.com/smirtaza-oss/distributed-systems">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=smirtaza-oss&repo=distributed-systems&theme=tokyonight&hide_border=true" alt="Distributed System Rep Card" />
  </a>
  <a href="https://github.com/smirtaza-oss/algorithm-visualizer">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=smirtaza-oss&repo=algorithm-visualizer&theme=tokyonight&hide_border=true" alt="Algo Viz Card" />
  </a>
</div>

---

<!-- RECENT TECHNICAL WRITING -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=12,14,18&text=📝+TECHNICAL+PUBLICATIONS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Publications Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <a href="https://dev.to/smirtaza">
    <img src="https://blog-readme.vercel.app/api?username=smirtaza&theme=tokyonight" width="85%" alt="Publications Feed Grid" />
  </a>
</div>

---

<!-- PERSISTENT REPOSITORY CAT COMPANION -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=6,11,20&text=🐱+COMPANION+PROCESS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Companion Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img src="https://cataas.com/cat" width="300" style="border-radius: 12px; border: 1px solid #30363d;" alt="Unix Daemon Companion Cat"/>
</div>

---

<!-- FUNDING & SPONSORSHIP METRICS -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=27,28,29&text=☕+SPONSORSHIP+TELEMETRY&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Sponsorship Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <a href="https://www.buymeacoffee.com/smirtaza">
    <img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black" alt="Coffee Support Card" />
  </a>&nbsp;&nbsp;
  <a href="https://github.com/sponsors/smirtaza-oss">
    <img src="https://img.shields.io/badge/Sponsor-%23EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white" alt="Github Sponsor Badge" />
  </a>
</div>

---

<!-- EMBEDDED DYNAMIC REPOSITORY GRID (THE CONTRIBUTION SNAKE) -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=10,12,15&text=🐍+MEMETIC+GRID+STATE&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Snake Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img src="https://raw.githubusercontent.com/smirtaza-oss/smirtaza-oss/output/github-contribution-grid-snake-dark.svg" width="85%" alt="Grid Simulation Engine Output" />
</div>

---

<!-- DETAILED CYBERPUNK VIM MASTERY INTERACTIVE TERMINAL EMULATOR -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=12,14,18&text=⌨️+VI+IMPROVED+REGISTRY&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Vim Registry Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <div style="background-color:#1e1e2e; border: 1px solid #7B61FF; border-radius: 8px; width:85%; max-width:800px; text-align:left; font-family:'JetBrains Mono', 'Fira Code', monospace; font-size:14px; box-shadow:0 0 10px rgba(123,97,255,0.15);">
    <div style="background-color:#252538; padding: 10px; border-top-left-radius: 8px; border-top-right-radius: 8px; display:flex; justify-content:space-between; color:#a6adc8;">
      <span>[No Name] - NVIM</span>
      <span>utf-8 | unix</span>
    </div>
    <div style="padding:15px; line-height:1.7;">
      <span style="color:#6c7086;">1</span> <span style="color:#eed49f;">:w</span> <span style="color:#a6adc8;">// Write to block device disk storage</span><br>
      <span style="color:#6c7086;">2</span> <span style="color:#eed49f;">:q!</span> <span style="color:#a6adc8;">// Exit editor unconditionally</span><br>
      <span style="color:#6c7086;">3</span> <span style="color:#eed49f;">dd</span> <span style="color:#a6adc8;">// Delete line memory register buffer</span><br>
      <span style="color:#6c7086;">4</span> <span style="color:#eed49f;">yy</span> <span style="color:#a6adc8;">// Yank target sequence into copy buffer</span><br>
      <span style="color:#6c7086;">5</span> <span style="color:#eed49f;">p</span> <span style="color:#a6adc8;">// Flush register contents after cursor</span><br>
      <span style="color:#6c7086;">6</span> <span style="color:#eed49f;">/sys</span> <span style="color:#a6adc8;">// Compile-time forward lookup search target</span><br>
      <span style="color:#6c7086;">7</span> <span style="color:#eed49f;">gg=G</span> <span style="color:#a6adc8;">// Format abstract syntax indentation tree</span>
    </div>
    <div style="background-color:#cdd6f4; color:#1e1e2e; padding:5px 15px; font-weight:bold; font-size:12px; border-bottom-left-radius: 8px; border-bottom-right-radius: 8px;">
      NORMAL ➔ main.rs ➔ line: 7/7 [100%]
    </div>
  </div>
</div>

---

<!-- AI POETRY & LATEST ARXIV RESEARCH SECTOR -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=24,23,22&text=📄+ACADEMIC+SYSTEMS+DIGEST&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Academic Digest Header"/>
</div>

<div align="center" style="margin: 20px 0; font-family: 'Georgia', serif; font-style: italic; color: #c9d1d9;">
  "Attention Is All You Need — Vaswani et al. (NeurIPS)"<br>
  <span style="font-size: 13px; font-family: 'JetBrains Mono', monospace; color: #8b949e;">[A mathematical framework shifting sequence networks to self-attention dynamics]</span><br>
  <a href="https://arxiv.org/abs/1706.03762" style="color: #00F7FF; text-decoration: none; font-size:14px; font-weight:bold;">[Access Core PDF Node]</a>
</div>

---

<!-- COMPETITIVE PROGRAMMING DECK -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=12,14,18&text=⚔️+COMPETITIVE+PROGRAMMING+CHANNELS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Competitive Programming Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img src="https://leetcard.jacoblin.cool/smirtaza?theme=tokyonight&font=JetBrains%20Mono&ext=heatmap" width="49%" alt="Leetcode Metrics" />
  <img src="https://codeforces-readme-stats.vercel.app/api/card?username=smirtaza&theme=tokyonight" width="49%" alt="Codeforces Metrics" />
</div>

---

<!-- REAL-TIME COMPILING WORKLOAD TRACKER -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=24,23,22&text=⏱️+WAKATIME+COMPLEXITY+METRICS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Wakatime Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img src="https://github-readme-stats.vercel.app/api/wakatime?username=smirtaza&theme=tokyonight&hide_border=true&layout=compact&langs_count=10" alt="Wakatime Language Layout" />
  <br>
  <img src="https://wakatime.com/share/@smirtaza/5b3c5f6e-1f45-4b7a-b08e-38b1a2f3f7cd.svg" width="49%" alt="Weekly Telemetry Pie Chart" />
</div>

---

<!-- SPOTIFY AMBIENT TRACKER -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=12,14,18&text=🎵+COMPILING+AMBIENT+TRACK&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Spotify Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img src="https://spotify-github-profile.vercel.app/api/view?uid=YOUR_SPOTIFY_USER_ID&cover_image=true&theme=novatorem&show_offline=false&background_color=121212&interchange=true&bar_color=53b14f&bar_color_cover=true" alt="Spotify Realtime Stream" />
</div>

---

<!-- SYSTEM TIME synchronizer -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=24,23,22&text=⏰+SYSTEM+CLOCK+SYNCHRONIZER&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Clock Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img src="https://readme-clock.vercel.app/?timezone=Asia/Karachi&theme=tokyonight" alt="UTC Local Time Core" />
</div>

---

<!-- TELEMETRY INFRASTRUCTURE HEALTH STATUS -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=27,28,29&text=📡+INFRASTRUCTURE+HEALTH+MATRIX&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="System Status Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img src="https://img.shields.io/badge/CLUSTER--LOAD-35%25-brightgreen?style=for-the-badge&logo=kubernetes" alt="Cluster Metrics" />
  <img src="https://img.shields.io/badge/RAM--CAPACITY-24.8GB%2F64GB-blue?style=for-the-badge&logo=pypy" alt="Memory Segment" />
  <img src="https://img.shields.io/badge/MAIN--SERVER--UPTIME-104%20DAYS-orange?style=for-the-badge&logo=linux" alt="Node Uptime" />
</div>

---

<!-- INSPIRATION / JOKE SECTOR -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=6,11,20&text=💡+THEORETICAL+INSIGHTS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Insights Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="CS Quotes" />
  <br>
  <img src="https://readme-jokes.vercel.app/api?theme=tokyonight" width="500" alt="Hacker Humor Array" />
  <br>
  <a href="https://xkcd.com/" target="_blank">
    <img src="https://xkcd.com/s/0b7742.png" width="300" alt="xkcd Strip Segment" />
  </a>
</div>

---

<!-- ANIMATED GRADIENT SVGS (Inline CSS Animation replacement for broken local assets) -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=10,12,15&text=✨+DYNAMIC+SIGNAL+DYNAMICS&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Signal Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 500 80" width="100%" height="80">
    <style>
      @keyframes gradient-shift {
        0% { stop-color: #00F7FF; }
        50% { stop-color: #7B61FF; }
        100% { stop-color: #00F7FF; }
      }
      .grad-text {
        font-family: 'JetBrains Mono', monospace;
        font-size: 32px;
        font-weight: 800;
        fill: url(#text-grad-shift);
        text-anchor: middle;
      }
    </style>
    <defs>
      <linearGradient id="text-grad-shift" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#00F7FF">
          <animate attributeName="stop-color" values="#00F7FF;#7B61FF;#FF007F;#00F7FF" dur="6s" repeatCount="indefinite" />
        </stop>
        <stop offset="100%" stop-color="#7B61FF">
          <animate attributeName="stop-color" values="#7B61FF;#FF007F;#00F7FF;#7B61FF" dur="6s" repeatCount="indefinite" />
        </stop>
      </linearGradient>
    </defs>
    <text class="grad-text" x="50%" y="50" dominant-baseline="middle">NULL POINTER EXCEPTION</text>
  </svg>
</div>

---

<!-- SOUNDWAVE OSCILLATION MATRIX (Native Animated Vector) -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=27,28,29&text=🔊+FREQUENCY+SPECTRUM&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Frequency Header"/>
</div>

<div align="center" style="margin: 20px 0;">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 100" width="85%" style="background-color: #0d1117; border-radius: 8px;">
    <style>
      @keyframes wave-height {
        0%, 100% { transform: scaleY(0.3); }
        50% { transform: scaleY(1); }
      }
      .wave-bar {
        fill: url(#cyan-purple-grad);
        transform-origin: bottom;
        animation: wave-height 1.5s ease-in-out infinite;
      }
    </style>
    <!-- Multi-frequency Sound Wave Array -->
    <rect class="wave-bar" x="40" y="10" width="10" height="80" rx="3" style="animation-delay: 0.1s;" />
    <rect class="wave-bar" x="70" y="10" width="10" height="80" rx="3" style="animation-delay: 0.4s;" />
    <rect class="wave-bar" x="100" y="10" width="10" height="80" rx="3" style="animation-delay: 0.2s;" />
    <rect class="wave-bar" x="130" y="10" width="10" height="80" rx="3" style="animation-delay: 0.6s;" />
    <rect class="wave-bar" x="160" y="10" width="10" height="80" rx="3" style="animation-delay: 0.3s;" />
    <rect class="wave-bar" x="190" y="10" width="10" height="80" rx="3" style="animation-delay: 0.8s;" />
    <rect class="wave-bar" x="220" y="10" width="10" height="80" rx="3" style="animation-delay: 0.5s;" />
    <rect class="wave-bar" x="250" y="10" width="10" height="80" rx="3" style="animation-delay: 0.7s;" />
    <rect class="wave-bar" x="280" y="10" width="10" height="80" rx="3" style="animation-delay: 0.12s;" />
    <rect class="wave-bar" x="310" y="10" width="10" height="80" rx="3" style="animation-delay: 0.44s;" />
    <rect class="wave-bar" x="340" y="10" width="10" height="80" rx="3" style="animation-delay: 0.22s;" />
    <rect class="wave-bar" x="370" y="10" width="10" height="80" rx="3" style="animation-delay: 0.66s;" />
    <rect class="wave-bar" x="400" y="10" width="10" height="80" rx="3" style="animation-delay: 0.33s;" />
    <rect class="wave-bar" x="430" y="10" width="10" height="80" rx="3" style="animation-delay: 0.88s;" />
    <rect class="wave-bar" x="460" y="10" width="10" height="80" rx="3" style="animation-delay: 0.55s;" />
    <rect class="wave-bar" x="490" y="10" width="10" height="80" rx="3" style="animation-delay: 0.77s;" />
    <rect class="wave-bar" x="520" y="10" width="10" height="80" rx="3" style="animation-delay: 0.15s;" />
    <rect class="wave-bar" x="550" y="10" width="10" height="80" rx="3" style="animation-delay: 0.48s;" />
    <rect class="wave-bar" x="580" y="10" width="10" height="80" rx="3" style="animation-delay: 0.25s;" />
    <rect class="wave-bar" x="610" y="10" width="10" height="80" rx="3" style="animation-delay: 0.61s;" />
    <rect class="wave-bar" x="640" y="10" width="10" height="80" rx="3" style="animation-delay: 0.35s;" />
    <rect class="wave-bar" x="670" y="10" width="10" height="80" rx="3" style="animation-delay: 0.82s;" />
    <rect class="wave-bar" x="700" y="10" width="10" height="80" rx="3" style="animation-delay: 0.52s;" />
    <rect class="wave-bar" x="730" y="10" width="10" height="80" rx="3" style="animation-delay: 0.71s;" />
  </svg>
</div>

---

<!-- TERMINAL LOG MOTTO -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=80&color=gradient&customColorList=12,14,18&text=⚡+OPERATIVE+PHILOSOPHY&fontColor=ffffff&fontSize=40&animation=fadeIn" alt="Motto Header"/>
</div>

<div align="center" style="margin: 20px 0; font-family: 'JetBrains Mono', monospace;">
  <h2>「 Think • Code • Research • Repeat 」</h2>
  <h3 style="color: #7B61FF;">🧠 Translating abstract theory into performant, real‑world systems.</h3>
</div>

<!-- Footer Wave Module -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=220&color=gradient&customColorList=6,11,20,24,30" alt="Footer Wave"/>
