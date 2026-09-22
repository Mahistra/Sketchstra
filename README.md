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
    <linearGradient id="glow" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#d4af37"/>
      <stop offset="100%" stop-color="#0a0a0d"/>
      <animate attributeName="y1" values="0;1;0" dur="4s" repeatCount="indefinite"/>
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

<b style="color:#d4af37; font-size:22px; letter-spacing:1px;">A simple, beautiful, and enjoyable space to draw.</b>

<p style="color:#b9b4a8; max-width:640px; margin:14px auto; line-height:1.6;">
Open a tab. Pick a tool. Draw. An open-source visual canvas that makes drawing on
the web <b style="color:#f5d76e;">feel good</b> — no account, no backend, no friction.
</p>

<!-- badges -->
<div style="margin:12px 0 4px;">
  <img src="https://img.shields.io/badge/License-MIT-0a0a0d?style=flat-square&logo=opensourceinitiative&logoColor=d4af37&labelColor=1a1a1f&color=d4af37" alt="MIT License"/>
  <img src="https://img.shields.io/github/forks/Mahistra/Sketchstra?style=flat-square&logo=github&logoColor=d4af37&labelColor=1a1a1f&color=d4af37" alt="Forks"/>
  <img src="https://img.shields.io/github/stars/Mahistra/Sketchstra?style=flat-square&logo=github&logoColor=d4af37&labelColor=1a1a1f&color=d4af37" alt="Stars"/>
  <img src="https://img.shields.io/github/issues/Mahistra/Sketchstra?style=flat-square&logo=github&logoColor=d4af37&labelColor=1a1a1f&color=d4af37" alt="Open issues"/>
</div>

<img src="Sketchstra.png" alt="Sketchstra" width="52%" style="border-radius:12px; border:1px solid rgba(212,175,55,0.35); box-shadow:0 0 30px rgba(212,175,55,0.15); margin-top:10px;"/>

</div>

---

<div align="center" style="background:#0a0a0d; color:#e9e6df; padding:32px 24px;">

<!-- Features -->
<table width="100%" cellpadding="0" cellspacing="0" border="0" style="border-collapse:separate; border-spacing:12px;">
  <tr>
    <td align="center" style="background:#121218; border:1px solid rgba(212,175,55,0.3); border-radius:16px; padding:20px 12px; width:25%;">
      <b style="color:#f5d76e; font-size:26px;">✏️</b>
      <div style="color:#d4af37; font-weight:700; margin-top:6px;">Full Toolkit</div>
      <div style="color:#9d978a; font-size:13px; margin-top:4px;">Pen, shapes, arrows, text, eraser — every tool on a shortcut.</div>
    </td>
    <td align="center" style="background:#121218; border:1px solid rgba(212,175,55,0.3); border-radius:16px; padding:20px 12px; width:25%;">
      <b style="color:#f5d76e; font-size:26px;">🗺️</b>
      <div style="color:#d4af37; font-weight:700; margin-top:6px;">Infinite Canvas</div>
      <div style="color:#9d978a; font-size:13px; margin-top:4px;">Pan anywhere, zoom 0.1× – 10× on a smooth dotted grid.</div>
    </td>
    <td align="center" style="background:#121218; border:1px solid rgba(212,175,55,0.3); border-radius:16px; padding:20px 12px; width:25%;">
      <b style="color:#f5d76e; font-size:26px;">⚡</b>
      <div style="color:#d4af37; font-weight:700; margin-top:6px;">Instant Start</div>
      <div style="color:#9d978a; font-size:13px; margin-top:4px;">No account, no sign-up, no backend. Just open and draw.</div>
    </td>
    <td align="center" style="background:#121218; border:1px solid rgba(212,175,55,0.3); border-radius:16px; padding:20px 12px; width:25%;">
      <b style="color:#f5d76e; font-size:26px;">🎨</b>
      <div style="color:#d4af37; font-weight:700; margin-top:6px;">Style It Your Way</div>
      <div style="color:#9d978a; font-size:13px; margin-top:4px;">Stroke, fill, width, opacity — plus dark &amp; light themes.</div>
    </td>
  </tr>
</table>

<details style="margin-top:6px;">
<summary style="color:#d4af37; font-weight:600; cursor:pointer;"><b>✦&nbsp; More features</b></summary>

<table width="100%" cellpadding="0" cellspacing="0" border="0" style="border-collapse:separate; border-spacing:12px;">
  <tr>
    <td align="center" style="background:#121218; border:1px solid rgba(212,175,55,0.3); border-radius:16px; padding:18px 12px; width:50%;">
      <div style="color:#d4af37; font-weight:700;">🖱️ Canvas &amp; Editing</div>
      <div style="color:#9d978a; font-size:13px; margin-top:6px; line-height:1.7;">
        Move &amp; multi-select (Shift) · Delete · Undo / Redo history <br/>
        Zoom controls · Keyboard shortcuts for every tool
      </div>
    </td>
    <td align="center" style="background:#121218; border:1px solid rgba(212,175,55,0.3); border-radius:16px; padding:18px 12px; width:50%;">
      <div style="color:#d4af37; font-weight:700;">🗺️ On the Roadmap (V1)</div>
      <div style="color:#9d978a; font-size:13px; margin-top:6px; line-height:1.7;">
        Save / Open · PNG &amp; SVG export · Copy / Paste <br/>
        Resize handles · Responsive &amp; accessibility polish
      </div>
    </td>
  </tr>
</table>
</details>

<!-- Tech stack -->
<div style="margin-top:22px; color:#9d978a;">
  <span style="color:#d4af37; font-weight:700; letter-spacing:3px;">TECH STACK</span>
  <div style="margin-top:10px;">
    <span style="display:inline-block; background:#121218; border:1px solid rgba(212,175,55,0.35); color:#f5d76e; border-radius:999px; padding:5px 14px; font-size:13px; margin:3px;">⚛️ React 19</span>
    <span style="display:inline-block; background:#121218; border:1px solid rgba(212,175,55,0.35); color:#f5d76e; border-radius:999px; padding:5px 14px; font-size:13px; margin:3px;">🔷 TypeScript</span>
    <span style="display:inline-block; background:#121218; border:1px solid rgba(212,175,55,0.35); color:#f5d76e; border-radius:999px; padding:5px 14px; font-size:13px; margin:3px;">⚡ Vite</span>
    <span style="display:inline-block; background:#121218; border:1px solid rgba(212,175,55,0.35); color:#f5d76e; border-radius:999px; padding:5px 14px; font-size:13px; margin:3px;">🎨 Tailwind CSS</span>
    <span style="display:inline-block; background:#121218; border:1px solid rgba(212,175,55,0.35); color:#f5d76e; border-radius:999px; padding:5px 14px; font-size:13px; margin:3px;">🐻 Zustand</span>
    <span style="display:inline-block; background:#121218; border:1px solid rgba(212,175,55,0.35); color:#f5d76e; border-radius:999px; padding:5px 14px; font-size:13px; margin:3px;">🖼️ Canvas 2D</span>
  </div>
</div>

<!-- Getting started -->
<div align="left" style="margin-top:24px; color:#d4af37; font-weight:700; letter-spacing:3px;">🚀 QUICK START</div>
<div align="left" style="margin-top:8px;">

```bash
git clone https://github.com/Mahistra/Sketchstra.git
cd Sketchstra
npm install
npm run dev   # open http://localhost:5173
```

</div>

<!-- Contributors -->
<div style="margin-top:26px; color:#d4af37; font-weight:700; letter-spacing:3px;">👑 CONTRIBUTORS</div>
<p style="color:#9d978a; margin:8px 0 0; font-size:14px;">Every picture was earned by a pull request.</p>
<br/>
<div align="center">
  <a href="https://github.com/Mahistra"><img src="https://avatars.githubusercontent.com/u/215033926?v=4&s=128" width="76" height="76" title="Mahistra" style="border-radius:50%; border:3px solid #d4af37; box-shadow:0 0 14px rgba(212,175,55,0.55); margin:8px;" alt="Mahistra"/></a>
  <a href="https://github.com/ManoShruthiS"><img src="https://avatars.githubusercontent.com/u/202288415?v=4&s=128" width="76" height="76" title="ManoShruthiS" style="border-radius:50%; border:3px solid #d4af37; box-shadow:0 0 14px rgba(212,175,55,0.55); margin:8px;" alt="ManoShruthiS"/></a>
</div>

<details style="margin-top:16px;">
<summary style="color:#d4af37; font-weight:600; cursor:pointer;"><b>🌱&nbsp; Soon to be contributors</b></summary>
<br/>
<p style="color:#9d978a; margin:0; font-size:14px;">Forked Sketchstra and gearing up to join — welcome aboard! 🎉</p>
<br/>
<div align="center">
  <a href="https://github.com/prabhakarReddykanakanti"><img src="https://avatars.githubusercontent.com/u/225586480?v=4&s=128" width="76" height="76" title="prabhakarReddykanakanti" style="border-radius:50%; border:3px solid #8a6a00; box-shadow:0 0 10px rgba(212,175,55,0.3); margin:8px;" alt="prabhakarReddykanakanti"/></a>
</div>
</details>

<!-- Contribute -->
<div style="margin-top:28px; color:#d4af37; font-weight:700; letter-spacing:3px;">🤝 OPEN FOR CONTRIBUTION</div>
<p style="color:#9d978a; margin:8px 0; font-size:14px; max-width:600px; line-height:1.6;">
Students, beginners, developers, designers, and writers — you don't need to understand the whole
project to make your first contribution. Check the
<b style="color:#f5d76e;">good first issue</b> labels
and open your first PR.
</p>
<p style="margin:4px 0 0;">
  <a href="https://github.com/Mahistra/Sketchstra/issues" style="display:inline-block; background:linear-gradient(135deg,#a67c00,#d4af37); color:#0a0a0d; font-weight:700; border-radius:999px; padding:9px 22px; text-decoration:none;">Browse issues</a>
  &nbsp;
  <a href="plan.md" style="display:inline-block; border:1px solid #d4af37; color:#d4af37; font-weight:700; border-radius:999px; padding:9px 22px; text-decoration:none;">Read the plan</a>
  &nbsp;
  <a href="CONTRIBUTING.md" style="display:inline-block; border:1px solid #d4af37; color:#d4af37; font-weight:700; border-radius:999px; padding:9px 22px; text-decoration:none;">Contributing guide</a>
</p>

<div style="height:1px; background:linear-gradient(90deg, transparent, #d4af37, transparent); margin:34px 0 18px;"></div>

<div style="color:#8b8470; font-size:13px; letter-spacing:1px;">
  ✦&nbsp; MIT Licensed · Built by the <b style="color:#d4af37;">Mahistra</b> organization &nbsp;✦
</div>
<div style="margin-top:6px;">
  <a href="https://github.com/Mahistra/Sketchstra" style="color:#d4af37; text-decoration:none; font-weight:700;">⭐ Star the repo — it fuels us</a>
</div>

</div>