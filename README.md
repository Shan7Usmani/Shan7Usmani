<div align="center">

<!-- ANIMATED GLOW HEADER SVG -->
<svg xmlns="http://www.w3.org/2000/svg" width="600" height="140" viewBox="0 0 600 140">
  <defs>
    <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00E7FF">
        <animate attributeName="stop-color" values="#00E7FF;#7C6AF7;#FF6F00;#00E7FF" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#7C6AF7">
        <animate attributeName="stop-color" values="#7C6AF7;#FF6F00;#00E7FF;#7C6AF7" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <linearGradient id="grad2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#1FB6A6"/>
      <stop offset="100%" stop-color="#00E7FF"/>
    </linearGradient>
    <linearGradient id="grad3" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#FF6F00"/>
      <stop offset="100%" stop-color="#7C6AF7"/>
    </linearGradient>
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feComposite in="SourceGraphic" in2="blur" operator="over"/>
    </filter>
    <filter id="glowIntense" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="8" result="blur"/>
      <feComposite in="SourceGraphic" in2="blur" operator="over"/>
    </filter>
  </defs>

  <!-- Background glow circles -->
  <circle cx="100" cy="70" r="60" fill="#00E7FF" opacity="0.06">
    <animate attributeName="r" values="60;80;60" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="500" cy="70" r="60" fill="#7C6AF7" opacity="0.06">
    <animate attributeName="r" values="60;80;60" dur="4s" begin="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="300" cy="35" r="40" fill="#1FB6A6" opacity="0.04">
    <animate attributeName="r" values="40;55;40" dur="3s" repeatCount="indefinite"/>
  </circle>

  <!-- Decorative floating particles -->
  <circle cx="50" cy="30" r="2" fill="#00E7FF" opacity="0.4">
    <animate attributeName="cy" values="30;20;30" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0.8;0.4" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="550" cy="100" r="1.5" fill="#7C6AF7" opacity="0.5">
    <animate attributeName="cy" values="100;85;100" dur="4s" begin="1s" repeatCount="indefinite"/>
  </circle>
  <circle cx="200" cy="110" r="2.5" fill="#1FB6A6" opacity="0.3">
    <animate attributeName="cy" values="110;95;110" dur="3.5s" begin="0.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.7;0.3" dur="3.5s" begin="0.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="420" cy="25" r="2" fill="#FF6F00" opacity="0.4">
    <animate attributeName="cy" values="25;15;25" dur="2.8s" begin="2s" repeatCount="indefinite"/>
  </circle>

  <!-- Decorative line -->
  <line x1="80" y1="44" x2="150" y2="44" stroke="url(#grad2)" stroke-width="1" opacity="0.3"/>
  <line x1="450" y1="44" x2="520" y2="44" stroke="url(#grad3)" stroke-width="1" opacity="0.3"/>

  <!-- Name text with glow -->
  <text x="300" y="65" text-anchor="middle" font-family="'Segoe UI',Arial,sans-serif" font-size="42" font-weight="900" fill="url(#grad1)" filter="url(#glow)" letter-spacing="2">Shan Usmani</text>

  <!-- Subtitle -->
  <text x="300" y="98" text-anchor="middle" font-family="'Segoe UI',Arial,sans-serif" font-size="16" fill="#8892b0" letter-spacing="4">
    <tspan fill="#00E7FF">●</tspan>  FULL-STACK DEVELOPER  <tspan fill="#1FB6A6">●</tspan>
  </text>

  <!-- Bottom accent line -->
  <line x1="180" y1="118" x2="420" y2="118" stroke="url(#grad1)" stroke-width="2" opacity="0.5" stroke-linecap="round">
    <animate attributeName="opacity" values="0.3;0.8;0.3" dur="3s" repeatCount="indefinite"/>
  </line>
</svg>

<br>

<!-- BADGE TRAY -->
<div style="display:flex;flex-wrap:wrap;justify-content:center;gap:8px;margin:10px 0">
  <img src="https://img.shields.io/badge/GSSoC_%2726-Contributor-00E7FF?style=flat-square&logo=google&logoColor=white&labelColor=0d1117"/>
  <img src="https://img.shields.io/github/followers/Shan7Usmani?style=flat-square&logo=github&logoColor=white&label=Followers&labelColor=0d1117&color=7C6AF7"/>
  <img src="https://komarev.com/ghpvc/?username=Shan7Usmani&style=flat-square&label=Profile+Views&labelColor=0d1117&color=1FB6A6"/>
</div>

</div>

<!-- GLASS ABOUT CARD -->
<div style="background:rgba(13,17,23,0.85);backdrop-filter:blur(12px);border:1px solid rgba(0,231,255,0.15);border-radius:16px;padding:24px;margin:24px 0;box-shadow:0 8px 32px rgba(0,231,255,0.06),inset 0 1px 0 rgba(255,255,255,0.05)">

<details open>
<summary style="font-size:20px;font-weight:700;cursor:pointer;color:#00E7FF;font-family:'Segoe UI',Arial,sans-serif">🚀 About Me</summary>
<br>

<pre style="background:rgba(0,231,255,0.03);border:1px solid rgba(0,231,255,0.08);border-radius:10px;padding:16px;font-family:monospace;font-size:13px;color:#c9d1d9;line-height:1.6">
<span style="color:#00E7FF">name</span>: <span style="color:#ffa657">Shan Usmani</span>
<span style="color:#00E7FF">location</span>: <span style="color:#ffa657">Greater Noida, India</span>
<span style="color:#00E7FF">college</span>: <span style="color:#ffa657">IIT Madras</span>
<span style="color:#00E7FF">role</span>: <span style="color:#ffa657">GSSoC 2026 Contributor</span>
<span style="color:#00E7FF">currently</span>: <span style="color:#ffa657">Building PAOS</span>
<span style="color:#00E7FF">status</span>: <span style="color:#7ee787">⚡ active</span>
<span style="color:#00E7FF">stack</span>: <span style="color:#79c0ff">TypeScript</span> <span style="color:#d2a8ff">•</span> <span style="color:#79c0ff">Python</span> <span style="color:#d2a8ff">•</span> <span style="color:#79c0ff">Java</span> <span style="color:#d2a8ff">•</span> <span style="color:#79c0ff">React</span> <span style="color:#d2a8ff">•</span> <span style="color:#79c0ff">Node</span>
</pre>

</details>
</div>

<!-- GSSoC STATS GLASS CARDS -->
<div style="display:flex;flex-wrap:wrap;gap:12px;margin:24px 0;justify-content:center">

  <div style="flex:1;min-width:140px;background:rgba(13,17,23,0.85);backdrop-filter:blur(12px);border:1px solid rgba(0,231,255,0.15);border-radius:14px;padding:18px;text-align:center;box-shadow:0 4px 20px rgba(0,231,255,0.05)">
    <div style="font-size:28px;font-weight:800;font-family:'Segoe UI',Arial,sans-serif;background:linear-gradient(135deg,#00E7FF,#7C6AF7);-webkit-background-clip:text;-webkit-text-fill-color:transparent">6,607</div>
    <div style="font-size:11px;color:#8b949e;text-transform:uppercase;letter-spacing:1px;margin-top:4px">Score</div>
  </div>

  <div style="flex:1;min-width:140px;background:rgba(13,17,23,0.85);backdrop-filter:blur(12px);border:1px solid rgba(124,106,247,0.15);border-radius:14px;padding:18px;text-align:center;box-shadow:0 4px 20px rgba(124,106,247,0.05)">
    <div style="font-size:28px;font-weight:800;font-family:'Segoe UI',Arial,sans-serif;background:linear-gradient(135deg,#7C6AF7,#FF6F00);-webkit-background-clip:text;-webkit-text-fill-color:transparent">#451</div>
    <div style="font-size:11px;color:#8b949e;text-transform:uppercase;letter-spacing:1px;margin-top:4px">Global Rank</div>
    <div style="font-size:10px;color:#484f58;margin-top:2px">of 43,587</div>
  </div>

  <div style="flex:1;min-width:140px;background:rgba(13,17,23,0.85);backdrop-filter:blur(12px);border:1px solid rgba(31,182,166,0.15);border-radius:14px;padding:18px;text-align:center;box-shadow:0 4px 20px rgba(31,182,166,0.05)">
    <div style="font-size:28px;font-weight:800;font-family:'Segoe UI',Arial,sans-serif;background:linear-gradient(135deg,#1FB6A6,#00E7FF);-webkit-background-clip:text;-webkit-text-fill-color:transparent">13</div>
    <div style="font-size:11px;color:#8b949e;text-transform:uppercase;letter-spacing:1px;margin-top:4px">PRs Merged</div>
  </div>

  <div style="flex:1;min-width:140px;background:rgba(13,17,23,0.85);backdrop-filter:blur(12px);border:1px solid rgba(255,111,0,0.15);border-radius:14px;padding:18px;text-align:center;box-shadow:0 4px 20px rgba(255,111,0,0.05)">
    <div style="font-size:28px;font-weight:800;font-family:'Segoe UI',Arial,sans-serif;background:linear-gradient(135deg,#FF6F00,#FFD700);-webkit-background-clip:text;-webkit-text-fill-color:transparent">5</div>
    <div style="font-size:11px;color:#8b949e;text-transform:uppercase;letter-spacing:1px;margin-top:4px">Projects</div>
  </div>

  <div style="flex:1;min-width:140px;background:rgba(13,17,23,0.85);backdrop-filter:blur(12px);border:1px solid rgba(255,215,0,0.15);border-radius:14px;padding:18px;text-align:center;box-shadow:0 4px 20px rgba(255,215,0,0.05)">
    <div style="font-size:28px;font-weight:800;font-family:'Segoe UI',Arial,sans-serif;background:linear-gradient(135deg,#FFD700,#FF6F00);-webkit-background-clip:text;-webkit-text-fill-color:transparent">5</div>
    <div style="font-size:11px;color:#8b949e;text-transform:uppercase;letter-spacing:1px;margin-top:4px">Bounties</div>
  </div>

</div>

<!-- ACHIEVEMENT BADGES -->
<div align="center" style="margin:20px 0">
  <img src="assets/pull-shark.png" width="80" style="border-radius:12px;border:2px solid rgba(0,231,255,0.2);margin:0 8px"/>
  <img src="assets/quickdraw.png" width="80" style="border-radius:12px;border:2px solid rgba(124,106,247,0.2);margin:0 8px"/>
</div>

<!-- ACTIVITY GRAPH CARD -->
<div style="background:rgba(13,17,23,0.85);backdrop-filter:blur(12px);border:1px solid rgba(0,231,255,0.15);border-radius:16px;padding:20px;margin:24px 0;box-shadow:0 8px 32px rgba(0,231,255,0.04);text-align:center">

  <div style="font-size:14px;font-weight:600;color:#00E7FF;margin-bottom:12px;letter-spacing:2px">CONTRIBUTION ACTIVITY</div>

  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Shan7Usmani&theme=react-dark&hide_border=true&area=true&bg_color=0d1117&color=00E7FF&line=7C6AF7&point=1FB6A6" width="100%"/>

</div>

<!-- GITHUB STATS CARDS -->
<div style="display:flex;flex-wrap:wrap;gap:12px;margin:24px 0;justify-content:center">
  <img src="https://github-readme-stats.vercel.app/api?username=Shan7Usmani&show_icons=true&theme=transparent&icon_color=00E7FF&title_color=00E7FF&text_color=c9d1d9&text_bold=false&hide_border=true&bg_color=0d1117" style="border-radius:12px;border:1px solid rgba(0,231,255,0.1)"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Shan7Usmani&layout=compact&theme=transparent&title_color=00E7FF&text_color=c9d1d9&hide_border=true&bg_color=0d1117" style="border-radius:12px;border:1px solid rgba(0,231,255,0.1)"/>
</div>

<!-- TECH STACK GLASS CARD -->
<div style="background:rgba(13,17,23,0.85);backdrop-filter:blur(12px);border:1px solid rgba(0,231,255,0.15);border-radius:16px;padding:20px;margin:24px 0;box-shadow:0 8px 32px rgba(0,231,255,0.04);text-align:center">

  <div style="font-size:14px;font-weight:600;color:#00E7FF;margin-bottom:16px;letter-spacing:2px">TECH STACK</div>

  <div style="display:flex;flex-wrap:wrap;justify-content:center;gap:6px">
    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white&labelColor=0d1117"/>
    <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white&labelColor=0d1117"/>
    <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black&labelColor=0d1117"/>
    <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white&labelColor=0d1117"/>
    <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=java&logoColor=white&labelColor=0d1117"/>
    <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white&labelColor=0d1117"/>
    <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white&labelColor=0d1117"/>
    <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white&labelColor=0d1117"/>
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white&labelColor=0d1117"/>
    <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white&labelColor=0d1117"/>
    <img src="https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white&labelColor=0d1117"/>
    <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white&labelColor=0d1117"/>
  </div>
</div>

<!-- FEATURED PROJECTS GLASS CARD -->
<div style="background:rgba(13,17,23,0.85);backdrop-filter:blur(12px);border:1px solid rgba(0,231,255,0.15);border-radius:16px;padding:20px;margin:24px 0;box-shadow:0 8px 32px rgba(0,231,255,0.04)">

  <div style="font-size:14px;font-weight:600;color:#00E7FF;margin-bottom:16px;text-align:center;letter-spacing:2px">FEATURED PROJECTS</div>

  <table style="width:100%;border-collapse:collapse">
    <tr>
      <th style="padding:8px 12px;border-bottom:1px solid rgba(0,231,255,0.1);color:#8b949e;font-size:11px;letter-spacing:1px;text-align:left">Project</th>
      <th style="padding:8px 12px;border-bottom:1px solid rgba(0,231,255,0.1);color:#8b949e;font-size:11px;letter-spacing:1px;text-align:left">Description</th>
      <th style="padding:8px 12px;border-bottom:1px solid rgba(0,231,255,0.1);color:#8b949e;font-size:11px;letter-spacing:1px;text-align:center">Status</th>
    </tr>
    <tr>
      <td style="padding:12px;border-bottom:1px solid rgba(255,255,255,0.04);font-weight:600;color:#c9d1d9">🚀 PAOS</td>
      <td style="padding:12px;border-bottom:1px solid rgba(255,255,255,0.04);color:#8b949e;font-size:13px">AI-powered development assistant platform</td>
      <td style="padding:12px;border-bottom:1px solid rgba(255,255,255,0.04);text-align:center"><span style="background:rgba(0,231,255,0.1);color:#00E7FF;padding:2px 10px;border-radius:10px;font-size:11px;font-weight:600">Building</span></td>
    </tr>
    <tr>
      <td style="padding:12px;border-bottom:1px solid rgba(255,255,255,0.04);font-weight:600;color:#c9d1d9">🎙️ Late-Meet</td>
      <td style="padding:12px;border-bottom:1px solid rgba(255,255,255,0.04);color:#8b949e;font-size:13px">Real-time meeting transcription & analysis</td>
      <td style="padding:12px;border-bottom:1px solid rgba(255,255,255,0.04);text-align:center"><span style="background:rgba(124,106,247,0.1);color:#7C6AF7;padding:2px 10px;border-radius:10px;font-size:11px;font-weight:600">Contributing</span></td>
    </tr>
    <tr>
      <td style="padding:12px;border-bottom:1px solid rgba(255,255,255,0.04);font-weight:600;color:#c9d1d9">🔍 GSoC-Org-Finder-</td>
      <td style="padding:12px;border-bottom:1px solid rgba(255,255,255,0.04);color:#8b949e;font-size:13px">Find GSSoC projects by tech stack</td>
      <td style="padding:12px;border-bottom:1px solid rgba(255,255,255,0.04);text-align:center"><span style="background:rgba(124,106,247,0.1);color:#7C6AF7;padding:2px 10px;border-radius:10px;font-size:11px;font-weight:600">Contributing</span></td>
    </tr>
    <tr>
      <td style="padding:12px;font-weight:600;color:#c9d1d9">🏥 sahidawa-india</td>
      <td style="padding:12px;color:#8b949e;font-size:13px">Health platform — counterfeit reports</td>
      <td style="padding:12px;text-align:center"><span style="background:rgba(124,106,247,0.1);color:#7C6AF7;padding:2px 10px;border-radius:10px;font-size:11px;font-weight:600">Contributing</span></td>
    </tr>
  </table>

</div>

<!-- GSSoC PRs DETAILS -->
<div style="background:rgba(13,17,23,0.85);backdrop-filter:blur(12px);border:1px solid rgba(0,231,255,0.15);border-radius:16px;padding:20px;margin:24px 0;box-shadow:0 8px 32px rgba(0,231,255,0.04)">

<details>
<summary style="font-size:14px;font-weight:600;cursor:pointer;color:#00E7FF;letter-spacing:2px">📋 LATEST GSSoC PRs</summary>
<br>

<table style="width:100%;border-collapse:collapse">
  <tr>
    <th style="padding:8px 12px;border-bottom:1px solid rgba(0,231,255,0.1);color:#8b949e;font-size:10px;letter-spacing:1px;text-align:left">PR</th>
    <th style="padding:8px 12px;border-bottom:1px solid rgba(0,231,255,0.1);color:#8b949e;font-size:10px;letter-spacing:1px;text-align:left">Repo</th>
    <th style="padding:8px 12px;border-bottom:1px solid rgba(0,231,255,0.1);color:#8b949e;font-size:10px;letter-spacing:1px;text-align:center">Pts</th>
    <th style="padding:8px 12px;border-bottom:1px solid rgba(0,231,255,0.1);color:#8b949e;font-size:10px;letter-spacing:1px;text-align:center">Diff</th>
  </tr>
  <tr>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);color:#c9d1d9;font-size:12px">fix(store): add equalityFn</td>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);color:#8b949e;font-size:12px">TermUI</td>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);text-align:center;color:#00E7FF;font-weight:600">84</td>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);text-align:center"><span style="background:rgba(0,231,255,0.08);color:#00E7FF;padding:1px 8px;border-radius:8px;font-size:10px">beginner</span></td>
  </tr>
  <tr>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);color:#c9d1d9;font-size:12px">feat(ci): large files check</td>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);color:#8b949e;font-size:12px">AI-dev-assistant</td>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);text-align:center;color:#00E7FF;font-weight:600">107</td>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);text-align:center"><span style="background:rgba(255,111,0,0.08);color:#FF6F00;padding:1px 8px;border-radius:8px;font-size:10px">intermediate</span></td>
  </tr>
  <tr>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);color:#c9d1d9;font-size:12px">Google OAuth token sync</td>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);color:#8b949e;font-size:12px">sahidawa-india</td>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);text-align:center;color:#00E7FF;font-weight:600">166</td>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);text-align:center"><span style="background:rgba(255,0,0,0.08);color:#ff4444;padding:1px 8px;border-radius:8px;font-size:10px">critical</span></td>
  </tr>
  <tr>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);color:#c9d1d9;font-size:12px">Counterfeit report fix</td>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);color:#8b949e;font-size:12px">sahidawa-india</td>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);text-align:center;color:#00E7FF;font-weight:600">175</td>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);text-align:center"><span style="background:rgba(255,0,0,0.08);color:#ff4444;padding:1px 8px;border-radius:8px;font-size:10px">critical</span></td>
  </tr>
  <tr>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);color:#c9d1d9;font-size:12px">Kanban touch handles</td>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);color:#8b949e;font-size:12px">career-pilot</td>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);text-align:center;color:#00E7FF;font-weight:600">95</td>
    <td style="padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);text-align:center"><span style="background:rgba(255,111,0,0.08);color:#FF6F00;padding:1px 8px;border-radius:8px;font-size:10px">intermediate</span></td>
  </tr>
  <tr>
    <td style="padding:10px;color:#c9d1d9;font-size:12px">Listbar widget</td>
    <td style="padding:10px;color:#8b949e;font-size:12px">TermUI</td>
    <td style="padding:10px;text-align:center;color:#00E7FF;font-weight:600">112</td>
    <td style="padding:10px;text-align:center"><span style="background:rgba(255,111,0,0.08);color:#FF6F00;padding:1px 8px;border-radius:8px;font-size:10px">intermediate</span></td>
  </tr>
</table>

<div align="right" style="margin-top:12px">
  <a href="https://gssoc.girlscript.org/profile/ac85deec-3598-47ef-a9e8-f39ae0af5147" style="color:#00E7FF;font-size:12px;font-weight:600;text-decoration:none">View all 13 PRs →</a>
</div>
</details>

</div>

<!-- CONNECT GLASS CARD -->
<div style="background:rgba(13,17,23,0.85);backdrop-filter:blur(12px);border:1px solid rgba(0,231,255,0.15);border-radius:16px;padding:20px;margin:24px 0;box-shadow:0 8px 32px rgba(0,231,255,0.04);text-align:center">

  <div style="font-size:14px;font-weight:600;color:#00E7FF;margin-bottom:16px;letter-spacing:2px">LET'S CONNECT</div>

  <div style="display:flex;flex-wrap:wrap;justify-content:center;gap:10px">
    <a href="mailto:shan7usmani@gmail.com">
      <svg xmlns="http://www.w3.org/2000/svg" width="42" height="42" viewBox="0 0 42 42">
        <circle cx="21" cy="21" r="20" fill="rgba(209,72,54,0.1)" stroke="#D14836" stroke-width="1.5"/>
        <text x="21" y="27" text-anchor="middle" fill="#D14836" font-size="18" font-weight="bold">@</text>
      </svg>
    </a>
    <a href="https://github.com/Shan7Usmani">
      <svg xmlns="http://www.w3.org/2000/svg" width="42" height="42" viewBox="0 0 42 42">
        <circle cx="21" cy="21" r="20" fill="rgba(255,255,255,0.05)" stroke="#c9d1d9" stroke-width="1.5"/>
        <text x="21" y="27" text-anchor="middle" fill="#c9d1d9" font-size="14" font-weight="bold">GH</text>
      </svg>
    </a>
    <a href="https://gssoc.girlscript.org/profile/ac85deec-3598-47ef-a9e8-f39ae0af5147">
      <svg xmlns="http://www.w3.org/2000/svg" width="42" height="42" viewBox="0 0 42 42">
        <defs><linearGradient id="g-gs" x1="0" y1="0" x2="42" y2="42"><stop offset="0%" stop-color="#1FB6A6"/><stop offset="100%" stop-color="#00E7FF"/></linearGradient></defs>
        <circle cx="21" cy="21" r="20" fill="rgba(31,182,166,0.1)" stroke="url(#g-gs)" stroke-width="1.5"/>
        <text x="21" y="27" text-anchor="middle" fill="#1FB6A6" font-size="10" font-weight="bold">GS</text>
      </svg>
    </a>
    <a href="https://www.linkedin.com/in/shan-u-6b26b7361/">
      <svg xmlns="http://www.w3.org/2000/svg" width="42" height="42" viewBox="0 0 42 42">
        <circle cx="21" cy="21" r="20" fill="rgba(0,119,181,0.1)" stroke="#0077B5" stroke-width="1.5"/>
        <text x="21" y="27" text-anchor="middle" fill="#0077B5" font-size="14" font-weight="bold">in</text>
      </svg>
    </a>
  </div>

</div>

<!-- FOOTER -->
<div align="center" style="margin:30px 0 10px">

  <svg xmlns="http://www.w3.org/2000/svg" width="400" height="40">
    <defs>
      <linearGradient id="footGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#00E7FF">
          <animate attributeName="stop-color" values="#00E7FF;#7C6AF7;#1FB6A6;#00E7FF" dur="8s" repeatCount="indefinite"/>
        </stop>
        <stop offset="100%" stop-color="#7C6AF7">
          <animate attributeName="stop-color" values="#7C6AF7;#1FB6A6;#00E7FF;#7C6AF7" dur="8s" repeatCount="indefinite"/>
        </stop>
      </linearGradient>
    </defs>
    <text x="200" y="25" text-anchor="middle" font-family="monospace" font-size="12" fill="url(#footGrad)" opacity="0.8" letter-spacing="1">ranked #451 / 43,587 — and climbing ⚡</text>
  </svg>

  <div style="margin-top:8px">
    <span style="color:#00E7FF;opacity:0.3">━━━━━━━━━</span>
    <span style="color:#7C6AF7;opacity:0.3">━━━━━━━━━</span>
    <span style="color:#1FB6A6;opacity:0.3">━━━━━━━━━</span>
  </div>

</div>
