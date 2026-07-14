<style>
/* ===== GLOBAL STYLES ===== */
* { margin: 0; padding: 0; box-sizing: border-box; }

body {
  background-color: #0d1117;
  color: #c9d1d9;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
  line-height: 1.6;
}

/* ===== ANIMATIONS ===== */
@keyframes fadeInUp {
  from { opacity: 0; transform: translateY(30px); }
  to   { opacity: 1; transform: translateY(0); }
}

@keyframes pulse {
  0%, 100% { box-shadow: 0 0 5px rgba(0,255,65,0.2); }
  50%      { box-shadow: 0 0 20px rgba(0,255,65,0.5); }
}

@keyframes gradientShift {
  0%   { background-position: 0% 50%; }
  50%  { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

@keyframes neonBorder {
  0%, 100% { border-color: #00FF41; box-shadow: 0 0 5px #00FF41; }
  50%      { border-color: #39FF14; box-shadow: 0 0 20px #39FF14, 0 0 30px #00FF41; }
}

@keyframes typingCursor {
  0%, 100% { border-right-color: #00F7FF; }
  50%      { border-right-color: transparent; }
}

@keyframes spinSlow {
  from { transform: rotate(0deg); }
  to   { transform: rotate(360deg); }
}

@keyframes float {
  0%, 100% { transform: translateY(0); }
  50%      { transform: translateY(-5px); }
}

/* ===== ELEMENT STYLES ===== */
/* Banner */
.banner {
  animation: fadeInUp 0.8s ease-out;
}

.banner h1 {
  animation: float 3s ease-in-out infinite;
}

/* Typing effect block */
.typing-block {
  border-right: 3px solid #00F7FF;
  animation: typingCursor 0.8s infinite;
  display: inline-block;
  padding-right: 5px;
  white-space: pre-line; /* preserve line breaks */
}

/* Badges */
.badge {
  display: inline-block;
  margin: 5px;
  transition: transform 0.2s;
}

.badge:hover {
  transform: translateY(-3px);
}

/* Terminal box */
.terminal-box {
  animation: pulse 2s infinite;
}

.terminal-box pre {
  margin: 0;
  font-size: 16px;
  line-height: 1.6;
  overflow-x: auto;
}

/* Gradient text headings (applied to h2) */
.gradient-text {
  background-size: 200% auto;
  animation: gradientShift 4s linear infinite;
}

/* Project cards */
.project-card {
  background: #0d1117;
  border: 1px solid #30363d;
  border-radius: 8px;
  padding: 15px;
  transition: all 0.3s ease;
}

.project-card:hover {
  border-color: #58a6ff;
  box-shadow: 0 0 15px rgba(88,166,255,0.3);
  transform: translateY(-5px);
}

/* Support buttons */
.support-btn {
  display: inline-block;
  padding: 10px 20px;
  border-radius: 5px;
  text-decoration: none;
  font-weight: bold;
  transition: transform 0.2s, box-shadow 0.2s;
}

.support-btn:hover {
  transform: scale(1.05);
  box-shadow: 0 5px 15px rgba(0,0,0,0.3);
}

/* Footer wave */
.footer-wave {
  animation: fadeInUp 1s ease-out;
}

/* Badge label pills */
.cs-badge {
  animation: fadeInUp 0.6s ease-out;
  transition: transform 0.2s;
}

.cs-badge:hover {
  transform: scale(1.05);
}
</style>

<div align="center">

<!-- TOP BANNER -->
<div class="banner" style="background: linear-gradient(135deg, #667eea, #764ba2, #f093fb); padding: 60px 20px 30px; border-radius: 0 0 50% 50% / 80px 80px; margin-bottom: 20px;">
  <h1 style="color: #fff; font-size: 64px; margin: 0; text-shadow: 2px 2px 4px rgba(0,0,0,0.3);">MIRTAZA</h1>
  <p style="color: #f0f0f0; font-size: 22px; margin: 10px 0 0;">Computer Science Graduate | AI Researcher | Systems Programmer</p>
</div>

<!-- TYPING EFFECT -->
<p class="typing-block" style="font-family: 'Courier New', monospace; font-size: 24px; color: #00F7FF; background: #0d1117; padding: 15px; border-radius: 8px;">
  👋 Hello, World! I'm Mirtaza<br>
  💻 Computer Science Enthusiast<br>
  📚 Algorithms & Data Structures<br>
  ⚙️ Operating Systems & Compilers<br>
  🤖 Artificial Intelligence Researcher<br>
  🧪 Building Systems that Scale
</p>

<br><br>

<!-- BADGES -->
<div>
  <span class="badge"><svg xmlns="http://www.w3.org/2000/svg" width="140" height="28"><linearGradient id="g" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stop-color="#181717"/><stop offset="100%" stop-color="#30363d"/></linearGradient><rect width="140" height="28" rx="6" fill="url(#g)"/><text x="10" y="18" fill="#fff" font-size="11" font-family="Arial, sans-serif">Followers</text><text x="75" y="18" fill="#fff" font-size="11" font-weight="bold">123</text></svg></span>
  <span class="badge"><svg xmlns="http://www.w3.org/2000/svg" width="120" height="28"><linearGradient id="g2" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stop-color="#FFD700"/><stop offset="100%" stop-color="#B8860B"/></linearGradient><rect width="120" height="28" rx="6" fill="url(#g2)"/><text x="10" y="18" fill="#000" font-size="11" font-family="Arial, sans-serif">Stars</text><text x="65" y="18" fill="#000" font-size="11" font-weight="bold">45</text></svg></span>
  <span class="badge"><svg xmlns="http://www.w3.org/2000/svg" width="140" height="28"><linearGradient id="g3" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stop-color="#8A2BE2"/><stop offset="100%" stop-color="#4B0082"/></linearGradient><rect width="140" height="28" rx="6" fill="url(#g3)"/><text x="10" y="18" fill="#fff" font-size="11" font-family="Arial, sans-serif">Views</text><text x="75" y="18" fill="#fff" font-size="11" font-weight="bold">12k</text></svg></span>
  <span class="badge"><svg xmlns="http://www.w3.org/2000/svg" width="160" height="28"><rect width="160" height="28" rx="6" fill="#00C853"/><text x="10" y="18" fill="#fff" font-size="11" font-family="Arial, sans-serif">Open Source Advocate</text></svg></span>
  <span class="badge"><svg xmlns="http://www.w3.org/2000/svg" width="130" height="28"><rect width="130" height="28" rx="6" fill="#7B61FF"/><text x="10" y="18" fill="#fff" font-size="11" font-family="Arial, sans-serif">CS Student</text></svg></span>
  <span class="badge"><svg xmlns="http://www.w3.org/2000/svg" width="150" height="28"><rect width="150" height="28" rx="6" fill="#FF8C00"/><text x="10" y="18" fill="#fff" font-size="11" font-family="Arial, sans-serif">AI &amp; Systems Research</text></svg></span>
</div>

</div>

---

<!-- SYSTEM INFORMATION (terminal box) -->
<div align="center">
  <div class="terminal-box" style="background: linear-gradient(135deg, #0d1117, #161b22); padding: 20px; border-radius: 10px; border: 1px solid #00FF41; display: inline-block; text-align: left; font-family: 'Courier New', monospace; color: #00FF41;">
    <pre>
user@cs-lab:~$ neofetch
OS: Arch Linux x86_64
Kernel: 6.1.12-custom
Shell: zsh 5.8
DE: i3-gaps
Theme: Tokyo Night
CPU: Intel i7-11800H (16) @ 4.6GHz
GPU: NVIDIA GeForce RTX 3070
Memory: 32GB DDR4
Storage: 1TB NVMe SSD
Uptime: 42 days 7 hours
Packages: 1847 (pacman)
Editor: VSCode / Neovim
    </pre>
  </div>
</div>

---

<!-- CONNECT -->
<div align="center">
  <h2 class="gradient-text" style="background: linear-gradient(to right, #12c2e9, #c471ed, #f64f59); -webkit-background-clip: text; -webkit-text-fill-color: transparent; font-size: 36px; background-size: 200% auto;">🌌 CONNECT</h2>
  <p>
    <a href="#" style="color: #58a6ff; text-decoration: none;">GitHub</a> · 
    <a href="#" style="color: #58a6ff; text-decoration: none;">LinkedIn</a> · 
    <a href="#" style="color: #58a6ff; text-decoration: none;">Discord</a> · 
    <a href="#" style="color: #58a6ff; text-decoration: none;">Instagram</a> · 
    <a href="#" style="color: #58a6ff; text-decoration: none;">Email</a>
  </p>
</div>

---

<!-- 🧠 CORE CS FOUNDATIONS -->
<div align="center">
  <h2 class="gradient-text" style="background: linear-gradient(to right, #00c6ff, #0072ff); -webkit-background-clip: text; -webkit-text-fill-color: transparent; font-size: 36px; background-size: 200% auto;">🧠 CORE CS FOUNDATIONS</h2>
  <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 8px; margin: 20px;">
    <span class="cs-badge" style="background: #1f6feb; color: white; padding: 6px 12px; border-radius: 12px; font-size: 14px;">Data Structures: Linked Lists, Trees, Graphs, Hash Tables</span>
    <span class="cs-badge" style="background: #238636; color: white; padding: 6px 12px; border-radius: 12px; font-size: 14px;">Algorithms: Sorting, DP, Greedy, Graph Algos</span>
    <span class="cs-badge" style="background: #da3633; color: white; padding: 6px 12px; border-radius: 12px; font-size: 14px;">Operating Systems: Linux Kernel, Processes, Concurrency</span>
    <span class="cs-badge" style="background: #d29922; color: black; padding: 6px 12px; border-radius: 12px; font-size: 14px;">Computer Networks: TCP/IP, HTTP, DNS, TLS</span>
    <span class="cs-badge" style="background: #8957e5; color: white; padding: 6px 12px; border-radius: 12px; font-size: 14px;">Database Systems: SQL, NoSQL, Indexing, Transactions</span>
    <span class="cs-badge" style="background: #79c0ff; color: black; padding: 6px 12px; border-radius: 12px; font-size: 14px;">Theory of Computation: Automata, Complexity, Decidability</span>
    <span class="cs-badge" style="background: #f85149; color: white; padding: 6px 12px; border-radius: 12px; font-size: 14px;">Compilers: Lexing, Parsing, Code Generation</span>
    <span class="cs-badge" style="background: #ff69b4; color: black; padding: 6px 12px; border-radius: 12px; font-size: 14px;">Discrete Math: Logic, Graph Theory, Number Theory</span>
  </div>
</div>

---

<!-- TECH STACK -->
<div align="center">
  <h2 class="gradient-text" style="background: linear-gradient(to right, #c471ed, #f64f59); -webkit-background-clip: text; -webkit-text-fill-color: transparent; font-size: 36px; background-size: 200% auto;">⚙️ TECHNOLOGY &amp; TOOLS</h2>
  <p style="font-family: 'Courier New', monospace; font-size: 18px; color: #c9d1d9; line-height: 2;">
    C++ &nbsp; C &nbsp; Java &nbsp; Python &nbsp; JavaScript &nbsp; TypeScript &nbsp; HTML &nbsp; CSS &nbsp; Tailwind<br>
    React &nbsp; Next.js &nbsp; Node.js &nbsp; Express &nbsp; .NET &nbsp; MongoDB &nbsp; MySQL &nbsp; PostgreSQL &nbsp; Redis<br>
    Docker &nbsp; Kubernetes &nbsp; Azure &nbsp; AWS &nbsp; Git &nbsp; GitHub Actions &nbsp; Linux &nbsp; Bash<br>
    Vim &nbsp; LaTeX &nbsp; MATLAB &nbsp; R &nbsp; Assembly &nbsp; Raspberry Pi
  </p>
</div>

---

<!-- SKILL RADAR -->
<div align="center">
  <h2 class="gradient-text" style="background: linear-gradient(to right, #00c6ff, #0072ff); -webkit-background-clip: text; -webkit-text-fill-color: transparent; font-size: 36px; background-size: 200% auto;">📡 SKILL RADAR</h2>
  <p style="color: #8b949e;">
    <em>Top languages: JavaScript (35%), Python (25%), C++ (15%), TypeScript (10%), others...</em><br>
    <em>Productive hours: 42h/week • Most active repo: os-kernel</em>
  </p>
</div>

---

<!-- LIVE ACTIVITY & STATS -->
<div align="center">
  <h2 class="gradient-text" style="background: linear-gradient(to right, #12c2e9, #c471ed); -webkit-background-clip: text; -webkit-text-fill-color: transparent; font-size: 36px; background-size: 200% auto;">📊 LIVE ACTIVITY &amp; STATS</h2>
  <div style="display: flex; justify-content: center; gap: 30px; color: #c9d1d9; background: #161b22; padding: 20px; border-radius: 10px; width: 80%; margin: auto;">
    <div><strong>Total Commits</strong><br>1,234</div>
    <div><strong>PRs Merged</strong><br>56</div>
    <div><strong>Issues Opened</strong><br>23</div>
    <div><strong>Current Streak</strong><br>7 days</div>
    <div><strong>Longest Streak</strong><br>21 days</div>
  </div>
  <p style="color: #8b949e; margin-top: 10px;">
    <em>Latest activity: pushed to os-kernel, reviewed PR in ml-compiler, starred 3 repos</em>
  </p>
</div>

---

<!-- FEATURED PROJECTS -->
<div align="center">
  <h2 class="gradient-text" style="background: linear-gradient(to right, #f64f59, #c471ed); -webkit-background-clip: text; -webkit-text-fill-color: transparent; font-size: 36px; background-size: 200% auto;">📌 RESEARCH &amp; PROJECTS</h2>
  <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px; width: 80%; margin: auto; text-align: left;">
    <div class="project-card">
      <strong style="color: #58a6ff;">os-kernel</strong><br>
      <span style="color: #8b949e;">A mini operating system kernel</span><br>
      ⭐ 12 &nbsp; 🍴 3
    </div>
    <div class="project-card">
      <strong style="color: #58a6ff;">ml-compiler</strong><br>
      <span style="color: #8b949e;">ML‑based code optimizer</span><br>
      ⭐ 8 &nbsp; 🍴 2
    </div>
    <div class="project-card">
      <strong style="color: #58a6ff;">distributed-systems</strong><br>
      <span style="color: #8b949e;">Raft consensus implementation</span><br>
      ⭐ 15 &nbsp; 🍴 5
    </div>
    <div class="project-card">
      <strong style="color: #58a6ff;">algorithm-visualizer</strong><br>
      <span style="color: #8b949e;">Interactive algorithm demos</span><br>
      ⭐ 22 &nbsp; 🍴 7
    </div>
  </div>
</div>

---

<!-- CS BLOG -->
<div align="center">
  <h2 class="gradient-text" style="background: linear-gradient(to right, #00c6ff, #0072ff); -webkit-background-clip: text; -webkit-text-fill-color: transparent; font-size: 36px; background-size: 200% auto;">📝 CS ARTICLES</h2>
  <p style="color: #c9d1d9;">
    Latest post: <em>"Understanding Meltdown and Spectre"</em> (Mar 2024)<br>
    <a href="#" style="color: #58a6ff;">View all articles on dev.to/mirtaza</a>
  </p>
</div>

---

<!-- COMPETITIVE PROGRAMMING -->
<div align="center">
  <h2 class="gradient-text" style="background: linear-gradient(to right, #f64f59, #c471ed); -webkit-background-clip: text; -webkit-text-fill-color: transparent; font-size: 36px; background-size: 200% auto;">⚔️ COMPETITIVE PROGRAMMING</h2>
  <table style="margin: auto; color: #c9d1d9; background: #161b22; border-radius: 8px; padding: 10px;">
    <tr><td>LeetCode</td><td>150 problems solved</td></tr>
    <tr><td>Codeforces</td><td>Rating: 1450 (Pupil)</td></tr>
  </table>
</div>

---

<!-- CODING METRICS -->
<div align="center">
  <h2 class="gradient-text" style="background: linear-gradient(to right, #12c2e9, #c471ed); -webkit-background-clip: text; -webkit-text-fill-color: transparent; font-size: 36px; background-size: 200% auto;">⏱️ CODING METRICS</h2>
  <p style="color: #c9d1d9;">
    Last week: 42h coding<br>
    Top languages: JavaScript 12h, Python 10h, C++ 6h, TypeScript 5h<br>
    Editors: VS Code 30h, Neovim 12h
  </p>
</div>

---

<!-- LATEST CS PAPER -->
<div align="center">
  <h2 class="gradient-text" style="background: linear-gradient(to right, #c471ed, #f64f59); -webkit-background-clip: text; -webkit-text-fill-color: transparent; font-size: 36px; background-size: 200% auto;">📄 LATEST CS PAPER</h2>
  <p style="color: #c9d1d9;">
    📌 “Attention Is All You Need” – Vaswani et al. (NeurIPS 2017)<br>
    <a href="#" style="color: #58a6ff;">arXiv:1706.03762</a>
  </p>
</div>

---

<!-- SUPPORT -->
<div align="center">
  <h2 class="gradient-text" style="background: linear-gradient(to right, #00c6ff, #0072ff); -webkit-background-clip: text; -webkit-text-fill-color: transparent; font-size: 36px; background-size: 200% auto;">❤️ SUPPORT MY RESEARCH</h2>
  <p>
    <a href="#" class="support-btn" style="background: #FFDD00; color: black;">☕ Buy Me a Coffee</a>
    &nbsp;
    <a href="#" class="support-btn" style="background: #EA4AAA; color: white;">❤️ Sponsor</a>
  </p>
</div>

---

<!-- MOTTO -->
<div align="center">
  <h2 class="gradient-text" style="background: linear-gradient(to right, #f64f59, #c471ed); -webkit-background-clip: text; -webkit-text-fill-color: transparent; font-size: 36px; background-size: 200% auto;">⚡ MOTTO</h2>
  <h2 style="color: #c9d1d9;">「 Think • Code • Research • Repeat 」</h2>
  <h3 style="color: #8b949e;">🧠 Turning abstract theory into real‑world systems.</h3>
</div>

<!-- FOOTER WAVE -->
<div class="footer-wave" style="height: 30px; background: linear-gradient(135deg, #667eea, #764ba2, #f093fb); border-radius: 50% 50% 0 0 / 40px 40px; margin-top: 30px;"></div>
