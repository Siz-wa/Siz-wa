<p align="center">
  <img src="./assets/header.svg" alt="Azis Macatanong · Service order · status: in production" width="100%">
</p>

<p align="center">
  <b>Developer and an obsessive finisher.</b> Every job goes from <code>pending</code> to <code>released</code>.
</p>

---

### 🧵 Order details

| | |
|---|---|
| **Customer** | Azis Macatanong · [@Siz-wa](https://github.com/Siz-wa) |
| **Job** | Full-stack web apps for real businesses |
| **Thread** | Laravel · React · TypeScript · Inertia · Tailwind |
| **On the machine now** | A calendar planner and a phone layout for an embroidery shop floor |
| **Ask me about** | Turning paper forms and spreadsheets into software staff actually use |
| **Off the clock** | _your thing here_ |

### 🪡 How every job runs

<p align="center">
  <img src="./assets/pipeline.svg" alt="pending → digitizing → production → QC → ready → released" width="100%">
</p>

I build the way a production line runs: get the brief right, plan it, build it, test it, polish it, ship it. Nothing skips QC.

### 📦 Released

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🪡 Eli Prints · production system</h4>
      Runs an embroidery shop from order to pickup: intake, digitizing, machine runs, quality checks and release.
      Separate queues for five staff roles, stitch-file reading (DST/PES) with previews, Google Drive filing,
      staff bonuses, and a phone layout for the floor.
      <br><br>
      <code>Laravel</code> <code>React</code> <code>TypeScript</code> <code>Inertia</code> <code>MySQL</code>
      <br><sub>Client work · live in production · private repo</sub>
    </td>
    <td width="50%" valign="top">
      <h4>🩺 WellCare · clinic records</h4>
      Patient records and appointment scheduling for a clinic and laboratory, replacing paper files
      and manual booking.
      <br><br>
      <code>Laravel</code> <code>React 19</code> <code>TypeScript</code> <code>shadcn/ui</code>
      <br><sub>Capstone project</sub>
    </td>
  </tr>
</table>

### 🧰 Thread rack

<p align="left">
  <img src="https://skillicons.dev/icons?i=laravel,php,react,ts,tailwind,vite,mysql,git,linux&perline=9" alt="Laravel, PHP, React, TypeScript, Tailwind, Vite, MySQL, Git, Linux">
</p>

---

<p align="center">
  <sub>QC: <b>passed</b> ✅ &nbsp;·&nbsp; Released by: <b>Azis</b> ✍️ &nbsp;·&nbsp; Thanks for stopping by.</sub>
</p>

assets/header.svg

<svg xmlns="http://www.w3.org/2000/svg" width="1000" height="280" viewBox="0 0 1000 280" role="img" aria-labelledby="title">
  <title id="title">Azis Macatanong · Service order · status: in production</title>
  <style>
    .stitch { fill: none; stroke: #3dd6c3; stroke-width: 3; stroke-dasharray: 10 7; stroke-linecap: round; animation: sew 5s linear infinite; }
    .perf   { stroke: #3dd6c3; stroke-width: 2; stroke-dasharray: 2 8; stroke-linecap: round; opacity: .6; }
    .eyebrow{ font: 700 14px 'Courier New', Courier, monospace; letter-spacing: 4px; fill: #3dd6c3; }
    .name   { font: 900 50px 'Arial Black', 'Segoe UI Black', Impact, sans-serif; fill: #f4e7cf; letter-spacing: 1px; }
    .role   { font: 700 20px 'Courier New', Courier, monospace; fill: #e9c46a; }
    .stack  { font: 700 13px 'Courier New', Courier, monospace; letter-spacing: 3px; fill: #8b949e; }
    .label  { font: 700 12px 'Courier New', Courier, monospace; letter-spacing: 3px; fill: #8b949e; }
    .val    { font: 700 22px 'Courier New', Courier, monospace; fill: #f4e7cf; }
    .dot    { fill: #3dd6c3; animation: pulse 1.6s ease-in-out infinite; }
    .cursor { fill: #e9c46a; animation: blink 1s steps(1) infinite; }
    @keyframes sew   { to { stroke-dashoffset: -170; } }
    @keyframes pulse { 50% { opacity: .2; } }
    @keyframes blink { 50% { opacity: 0; } }
  </style>

  <rect width="1000" height="280" rx="6" fill="#111418"/>
  <rect x="14" y="14" width="972" height="252" rx="4" class="stitch"/>

  <!-- left: the order -->
  <text x="56" y="78" class="eyebrow">SERVICE ORDER · FULL-STACK DEVELOPER</text>
  <text x="52" y="146" class="name">AZIS MACATANONG</text>
  <rect x="56" y="162" width="120" height="5" fill="#e9c46a"/>
  <text x="56" y="204" class="role">I build the systems shops run on</text>
  <rect x="446" y="188" width="11" height="20" class="cursor"/>
  <text x="56" y="238" class="stack">LARAVEL · REACT · TYPESCRIPT · INERTIA</text>

  <!-- tear-off stub -->
  <line x1="700" y1="34" x2="700" y2="246" class="perf"/>
  <text x="732" y="72" class="label">ORDER NO.</text>
  <text x="732" y="100" class="val">SIZ-WA-001</text>
  <text x="732" y="142" class="label">STATUS</text>
  <circle cx="740" cy="163" r="6" class="dot"/>
  <text x="756" y="170" class="val">IN PRODUCTION</text>
  <text x="732" y="212" class="label">STITCH COUNT</text>
  <text x="732" y="240" class="val">999,999+</text>
</svg>

assets/pipeline.svg

<svg xmlns="http://www.w3.org/2000/svg" width="1000" height="150" viewBox="0 0 1000 150" role="img" aria-labelledby="title">
  <title id="title">How I work: pending, digitizing, production, QC, ready, released</title>
  <style>
    .rail  { stroke: #3dd6c3; stroke-width: 2; stroke-dasharray: 6 6; opacity: .25; }
    .run   { stroke: #3dd6c3; stroke-width: 3; stroke-dasharray: 820; stroke-dashoffset: 820; animation: grow 8s linear infinite; }
    .ring  { fill: #111418; stroke: #3dd6c3; stroke-width: 2; }
    .lit   { fill: #3dd6c3; opacity: 0; }
    .last  { fill: #e9c46a; }
    .stage { font: 700 13px 'Courier New', Courier, monospace; letter-spacing: 2px; fill: #f4e7cf; text-anchor: middle; }
    .note  { font: 700 12px 'Courier New', Courier, monospace; fill: #8b949e; text-anchor: middle; }
    .s1 { animation: s1 8s linear infinite; } .s2 { animation: s2 8s linear infinite; }
    .s3 { animation: s3 8s linear infinite; } .s4 { animation: s4 8s linear infinite; }
    .s5 { animation: s5 8s linear infinite; } .s6 { animation: s6 8s linear infinite; }
    @keyframes grow { 0% { stroke-dashoffset: 820; opacity: 1; } 75%, 92% { stroke-dashoffset: 0; opacity: 1; } 100% { stroke-dashoffset: 0; opacity: 0; } }
    @keyframes s1 { 0% { opacity: 0; } 3%,  92% { opacity: 1; } 100% { opacity: 0; } }
    @keyframes s2 { 0%, 15% { opacity: 0; } 18%, 92% { opacity: 1; } 100% { opacity: 0; } }
    @keyframes s3 { 0%, 30% { opacity: 0; } 33%, 92% { opacity: 1; } 100% { opacity: 0; } }
    @keyframes s4 { 0%, 45% { opacity: 0; } 48%, 92% { opacity: 1; } 100% { opacity: 0; } }
    @keyframes s5 { 0%, 60% { opacity: 0; } 63%, 92% { opacity: 1; } 100% { opacity: 0; } }
    @keyframes s6 { 0%, 75% { opacity: 0; } 78%, 92% { opacity: 1; } 100% { opacity: 0; } }
  </style>

  <rect width="1000" height="150" rx="6" fill="#111418"/>
  <line x1="90" y1="56" x2="910" y2="56" class="rail"/>
  <line x1="90" y1="56" x2="910" y2="56" class="run"/>

  <g>
    <circle cx="90"  cy="56" r="15" class="ring"/><circle cx="90"  cy="56" r="8" class="lit s1"/>
    <circle cx="254" cy="56" r="15" class="ring"/><circle cx="254" cy="56" r="8" class="lit s2"/>
  <g>
    <circle cx="90"  cy="56" r="15" class="ring"/><circle cx="90"  cy="56" r="8" class="lit s1"/>
    <circle cx="254" cy="56" r="15" class="ring"/><circle cx="254" cy="56" r="8" class="lit s2"/>
    <circle cx="418" cy="56" r="15" class="ring"/><circle cx="418" cy="56" r="8" class="lit s3"/>
    <circle cx="582" cy="56" r="15" class="ring"/><circle cx="582" cy="56" r="8" class="lit s4"/>
    <circle cx="746" cy="56" r="15" class="ring"/><circle cx="746" cy="56" r="8" class="lit s5"/>
    <circle cx="910" cy="56" r="15" class="ring"/><circle cx="910" cy="56" r="8" class="lit last s6"/>
  </g>

  <text x="90"  y="104" class="stage">PENDING</text>   <text x="90"  y="126" class="note">the brief</text>
  <text x="254" y="104" class="stage">DIGITIZING</text><text x="254" y="126" class="note">the plan</text>
  <text x="418" y="104" class="stage">PRODUCTION</text><text x="418" y="126" class="note">the build</text>
  <text x="582" y="104" class="stage">QC</text>        <text x="582" y="126" class="note">the tests</text>
  <text x="746" y="104" class="stage">READY</text>     <text x="746" y="126" class="note">the polish</text>
  <text x="910" y="104" class="stage">RELEASED</text>  <text x="910" y="126" class="note">shipped</text>
</svg>
