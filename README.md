<div align="center" style="background:#0a0a0d; color:#e9e6df; padding:40px 28px; border-radius:20px 20px 0 0;">

<!-- Animated metallic logo -->
<svg width="560" height="120" viewBox="0 0 560 120" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Sketchstra">
  <defs>
    <linearGradient id="gold" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#8a6a00"/>
      <stop offset="22%" stop-color="#d4af37"/>
      <stop offset="45%" stop-color="#fff1b8"/>
      <stop offset="60%" stop-color="#f5d76e"/>
      <stop offset="80%" stop-color="#b8860b"/>
      <stop offset="100%" stop-color="#fff1b8"/>
      <animate attributeName="x1" values="-1;2;-1" dur="6s" repeatCount="indefinite"/>
    </linearGradient>
    <radialGradient id="halo">
      <stop offset="0%" stop-color="rgba(212,175,55,0.5)"/>
      <stop offset="60%" stop-color="rgba(212,175,55,0.12)"/>
      <stop offset="100%" stop-color="rgba(0,0,0,0)"/>
    </radialGradient>
    <filter id="soft" x="-40%" y="-40%" width="180%" height="180%">
      <feGaussianBlur stdDeviation="3"/>
    </filter>
  </defs>

  <!-- pulsing halo -->
  <circle cx="300" cy="60" r="90" fill="url(#halo)">
    <animate attributeName="r" values="70;110;70" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.4;1" dur="4s" repeatCount="indefinite"/>
  </circle>

  <!-- diamond in metallic gold -->
  <g>
    <polygon points="70,20 118,60 70,100 22,60" fill="url(#gold)" stroke="#a67c00" stroke-width="2"/>
    <polygon points="70,38 96,60 70,82 44,60" fill="rgba(255,241,184,0.15)"/>
  </g>

  <!-- sparkles -->
  <g fill="#fff1b8" opacity="0.9" filter="url(#soft)">
    <circle cx="34" cy="26" r="2.2">
      <animate attributeName="opacity" values="0;1;0" dur="2.4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="126" cy="92" r="1.8">
      <animate attributeName="opacity" values="0;1;0" dur="3.2s" begin="0.8s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- wordmark -->
  <text x="150" y="80" font-family="'Segoe UI', Arial, sans-serif" font-size="58" font-weight="800" fill="url(#gold)">Sketchstra</text>
  <text x="152" y="106" font-family="'Segoe UI', Arial, sans-serif" font-size="17" letter-spacing="6" fill="#f5d76e" opacity="0.85">VISUAL THINKING · WITHOUT LIMITS</text>
</svg>

<b style="color:#f5d76e; font-size:24px; letter-spacing:1px; font-weight:600;">The page where you can express your creativity.</b>

<!-- badges -->
<div style="margin:16px 0 4px;">
  <img src="https://img.shields.io/badge/License-MIT-0a0a0d?style=flat-square&logo=opensourceinitiative&logoColor=d4af37&labelColor=1a1a1f&color=d4af37" alt="MIT License"/>
  <img src="https://img.shields.io/github/forks/Mahistra/Sketchstra?style=flat-square&logo=github&logoColor=d4af37&labelColor=1a1a1f&color=d4af37" alt="Forks"/>
  <img src="https://img.shields.io/github/stars/Mahistra/Sketchstra?style=flat-square&logo=github&logoColor=d4af37&labelColor=1a1a1f&color=d4af37" alt="Stars"/>
  <img src="https://img.shields.io/github/issues/Mahistra/Sketchstra?style=flat-square&logo=github&logoColor=d4af37&labelColor=1a1a1f&color=d4af37" alt="Open issues"/>
</div>

<img src="Sketchstra.png" alt="Sketchstra" width="52%" style="border-radius:12px; border:1px solid rgba(212,175,55,0.35); box-shadow:0 0 30px rgba(212,175,55,0.15); margin-top:10px;"/>

</div>

---

<div align="center" style="background:#0a0a0d; color:#e9e6df; padding:32px 24px;">

<div style="height:1px; background:linear-gradient(90deg, transparent, #d4af37, transparent); margin:0 0 30px;"></div>

<!-- Open for contribution -->
<div style="color:#d4af37; font-weight:700; letter-spacing:3px; font-size:15px;">🎯 OPEN FOR CONTRIBUTION</div>
<p style="color:#b9b4a8; margin:10px 0 0; font-size:14px; max-width:640px; line-height:1.7;">
This project is built in the open — and <b style="color:#f5d76e;">anyone can participate</b>.
Students, beginners, developers, designers, writers, testers. You don't need to understand the
whole project before making your first contribution.
</p>

<!-- Docs usage -->
<table width="100%" cellpadding="0" cellspacing="0" border="0" style="border-collapse:separate; border-spacing:12px; margin-top:16px;">
  <tr>
    <td align="left" style="background:#121218; border:1px solid rgba(212,175,55,0.3); border-radius:14px; padding:16px 18px; width:50%; vertical-align:top;">
      <div style="color:#d4af37; font-weight:700;">📘 Project plan — <span style="color:#f5d76e;"><a href="plan.md" style="color:#f5d76e;">plan.md</a></span></div>
      <div style="color:#9d978a; font-size:13px; margin-top:6px; line-height:1.7;">The vision, features, and roadmap of Sketchstra. Read this first to understand what we build and why.</div>
    </td>
    <td align="left" style="background:#121218; border:1px solid rgba(212,175,55,0.3); border-radius:14px; padding:16px 18px; width:50%; vertical-align:top;">
      <div style="color:#d4af37; font-weight:700;">📝 Contributing guide — <span style="color:#f5d76e;"><a href="CONTRIBUTING.md" style="color:#f5d76e;">CONTRIBUTING.md</a></span></div>
      <div style="color:#9d978a; font-size:13px; margin-top:6px; line-height:1.7;">How to pick an issue, make changes, and submit a pull request — step by step.</div>
    </td>
  </tr>
  <tr>
    <td align="left" style="background:#121218; border:1px solid rgba(212,175,55,0.3); border-radius:14px; padding:16px 18px; width:50%; vertical-align:top;">
      <div style="color:#d4af37; font-weight:700;">🚩 Open issues — <span style="color:#f5d76e;"><a href="https://github.com/Mahistra/Sketchstra/issues" style="color:#f5d76e;">issues</a></span></div>
      <div style="color:#9d978a; font-size:13px; margin-top:6px; line-height:1.7;">Find the work. Look for <b style="color:#f5d76e;">good first issue</b> and <b style="color:#f5d76e;">difficulty:easy</b> labels to start.</div>
    </td>
    <td align="left" style="background:#121218; border:1px solid rgba(212,175,55,0.3); border-radius:14px; padding:16px 18px; width:50%; vertical-align:top;">
      <div style="color:#d4af37; font-weight:700;">✨ AI tools are welcome</div>
      <div style="color:#9d978a; font-size:13px; margin-top:6px; line-height:1.7;">Using AI assistants to help you contribute is <b style="color:#f5d76e;">allowed and encouraged</b> — for learning, coding, and reviewing.</div>
    </td>
  </tr>
</table>

<!-- How to start -->
<div style="margin-top:26px; color:#d4af37; font-weight:700; letter-spacing:3px; font-size:15px;">🚀 HOW TO START</div>
<div align="left" style="margin-top:10px; color:#b9b4a8; font-size:14px; line-height:1.9; max-width:520px;">
1. Read the <a href="plan.md" style="color:#f5d76e;">project plan</a><br/>
2. Read the <a href="CONTRIBUTING.md" style="color:#f5d76e;">contributing guide</a><br/>
3. Pick an <a href="https://github.com/Mahistra/Sketchstra/issues" style="color:#f5d76e;">open issue</a><br/>
4. Fork, contribute, and open a pull request 🎉
</div>

<!-- How to launch locally -->
<div style="margin-top:24px; color:#d4af37; font-weight:700; letter-spacing:3px; font-size:15px;">💻 HOW TO LAUNCH ON YOUR LAPTOP</div>
<div align="left" style="margin-top:10px;">

```bash
git clone https://github.com/Mahistra/Sketchstra.git
cd Sketchstra
npm install
npm run dev   # open http://localhost:5173
```

</div>

<div style="height:1px; background:linear-gradient(90deg, transparent, #d4af37, transparent); margin:34px 0 22px;"></div>

<!-- Contributors -->
<div style="color:#d4af37; font-weight:700; letter-spacing:3px; font-size:15px;">👑 CONTRIBUTORS</div>
<p style="color:#9d978a; margin:8px 0 0; font-size:14px;">Thanks to everyone who has built Sketchstra.</p>
<br/>
<div align="center">
  <a href="https://github.com/Mahistra"><img src="https://avatars.githubusercontent.com/u/215033926?v=4&s=128" width="76" height="76" title="Mahistra" style="border-radius:50%; border:3px solid #d4af37; box-shadow:0 0 14px rgba(212,175,55,0.55); margin:8px;" alt="Mahistra"/></a>
  <a href="https://github.com/ManoShruthiS"><img src="https://avatars.githubusercontent.com/u/202288415?v=4&s=128" width="76" height="76" title="ManoShruthiS" style="border-radius:50%; border:3px solid #d4af37; box-shadow:0 0 14px rgba(212,175,55,0.55); margin:8px;" alt="ManoShruthiS"/></a>
</div>

<div style="height:1px; width:40%; background:linear-gradient(90deg, transparent, #d4af37, transparent); margin:26px auto;"></div>

<!-- Soon to be contributors -->
<div style="color:#d4af37; font-weight:700; letter-spacing:3px; font-size:15px;">🌱 SOON TO BE CONTRIBUTORS</div>
<p style="color:#9d978a; margin:8px 0 0; font-size:14px;">They forked the repo — their first PR is on the way. Welcome aboard! 🎉</p>
<br/>
<div align="center">
  <a href="https://github.com/prabhakarReddykanakanti"><img src="https://avatars.githubusercontent.com/u/225586480?v=4&s=128" width="76" height="76" title="prabhakarReddykanakanti" style="border-radius:50%; border:3px solid #8a6a00; box-shadow:0 0 10px rgba(212,175,55,0.3); margin:8px;" alt="prabhakarReddykanakanti"/></a>
</div>

<div style="margin-top:40px;">
<div style="background:linear-gradient(135deg,#8a6a00 0%,#d4af37 30%,#fff1b8 50%,#d4af37 70%,#8a6a00 100%); border-radius:14px; padding:22px 24px; box-shadow:0 0 40px rgba(212,175,55,0.25);">
  <div style="color:#0a0a0d; font-weight:800; font-size:26px; letter-spacing:6px;">MAHISTRA</div>
  <div style="color:#3a2c00; font-weight:600; font-size:14px; letter-spacing:4px; margin-top:4px;">SINCE 2025</div>
</div>
</div>

</div>