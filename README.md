<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Shivam Mishra | Profile</title>
<style>
  :root {
    --bg: #0d1117;
    --panel: #161b22;
    --border: #30363d;
    --text: #e6edf3;
    --muted: #8b949e;
    --accent: #a78bfa;
    --link: #58a6ff;
  }
  * { box-sizing: border-box; }
  body {
    margin: 0;
    background: var(--bg);
    color: var(--text);
    font-family: -apple-system, "Segoe UI", Helvetica, Arial, sans-serif;
    line-height: 1.6;
  }
  a { color: var(--link); text-decoration: none; }
  a:hover { text-decoration: underline; }
  a:focus-visible { outline: 2px solid var(--accent); outline-offset: 2px; }
  .wrap { max-width: 900px; margin: 0 auto; padding: 24px 16px 48px; }
  .center { text-align: center; }
  img { max-width: 100%; }
  .badges { display: flex; flex-wrap: wrap; gap: 8px; justify-content: center; margin: 14px 0; }
  .banner { width: 100%; display: block; }
  blockquote {
    margin: 20px auto; padding: 0 16px; max-width: 560px;
    border-left: 3px solid var(--border); color: var(--muted); font-style: italic; text-align: left;
  }
  h2 {
    font-size: 1.5rem; margin: 40px 0 16px; padding-bottom: 8px;
    border-bottom: 1px solid var(--border);
  }
  hr { border: 0; border-top: 1px solid var(--border); margin: 8px 0; }
  .about { display: grid; grid-template-columns: 1.7fr 1fr; gap: 24px; align-items: center; }
  .about p { margin: 0 0 12px; }
  pre {
    background: var(--panel); border: 1px solid var(--border); border-radius: 8px;
    padding: 16px; font-family: "Fira Code", Consolas, monospace; font-size: 14px;
    color: #7ee787; overflow-x: auto; margin: 0;
  }
  .grid4 { display: grid; grid-template-columns: repeat(4, 1fr); border: 1px solid var(--border); border-radius: 8px; overflow: hidden; }
  .cell { padding: 16px 12px; text-align: center; border-right: 1px solid var(--border); }
  .cell:last-child { border-right: 0; }
  .cell .ico { font-size: 1.6rem; }
  .cell b { display: block; margin: 4px 0 2px; }
  .cell small { color: var(--muted); }
  .stack h4 { margin: 20px 0 8px; font-size: 0.95rem; color: var(--muted); font-weight: 600; }
  table.proj { width: 100%; border-collapse: collapse; }
  .proj th, .proj td { border: 1px solid var(--border); padding: 8px 12px; text-align: left; }
  .proj th { background: var(--panel); }
  .status {
    background: var(--panel); border: 1px solid var(--border); border-radius: 8px;
    padding: 16px; text-align: center; font-family: "Fira Code", Consolas, monospace; font-size: 14px;
  }
  ul.tasks { list-style: none; padding: 0; margin: 16px 0 0; }
  ul.tasks li { padding: 4px 0; }
  .stats { display: flex; flex-wrap: wrap; gap: 12px; justify-content: center; align-items: center; }
  .footer { margin-top: 48px; text-align: center; color: var(--muted); }
  @media (max-width: 720px) {
    .about { grid-template-columns: 1fr; }
    .grid4 { grid-template-columns: repeat(2, 1fr); }
    .cell:nth-child(2) { border-right: 0; }
    .cell:nth-child(-n+2) { border-bottom: 1px solid var(--border); }
  }
</style>
</head>
<body>
<main class="wrap">

  <!-- HEADER -->
  <div class="center">
    <img class="banner" alt="Shivam Mishra banner" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:2d2a5e&height=180&section=header&text=Shivam%20Mishra&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=CSE%20(AI)%20Student%20%E2%80%A2%20Code%20Learner%20%E2%80%A2%20Future%20Software%20Engineer&descSize=16&descAlignY=60" />
    <img alt="Typing animation" src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=A78BFA&center=true&vCenter=true&width=700&lines=1st+Year+B.Tech+%40+Swaminarayan+University;Learning+C%2FC%2B%2B+%7C+Python+%7C+Web+Dev+%7C+DSA;Building+in+public+%E2%80%94+one+commit+at+a+time+%F0%9F%9A%80" />
    <div class="badges">
      <img alt="Profile views" src="https://komarev.com/ghpvc/?username=mishrashivamcg-wq&label=PROFILE%20VIEWS&color=7c3aed&style=for-the-badge" />
      <img alt="Followers" src="https://img.shields.io/github/followers/mishrashivamcg-wq?label=FOLLOWERS&style=for-the-badge&logo=github&color=7c3aed" />
      <img alt="Open to collaborate" src="https://img.shields.io/badge/OPEN%20TO-COLLABORATE-10b981?style=for-the-badge" />
      <img alt="Batch 2026" src="https://img.shields.io/badge/BATCH-2026%20FRESHMAN-f59e0b?style=for-the-badge" />
    </div>
    <blockquote>Every expert was once a beginner who refused to quit.</blockquote>
  </div>

  <!-- ABOUT -->
  <h2>👨‍💻 About Me</h2>
  <div class="about">
    <div>
      <p>🎓 <b>1st Year B.Tech CSE (Artificial Intelligence)</b> @ Swaminarayan University, Kalol, Gujarat</p>
      <p>💻 <b>Student @ Coding Gita</b>, learning software development the practical way</p>
      <p>🧠 Currently learning <b>C/C++, Python, Git &amp; GitHub, HTML/CSS/JavaScript</b></p>
      <p>🎯 Passionate about <b>DSA • Full-Stack Web Development • AI • Software Engineering</b></p>
      <p>🧩 Solving problems on <a href="https://leetcode.com/u/BicooD9W5h/">LeetCode</a> (BicooD9W5h)</p>
      <p>🌱 Goal: <b>Master coding skills &amp; build high-impact tech projects</b></p>
      <p>📧 <a href="mailto:mishra.shivam.cg@gmail.com">mishra.shivam.cg@gmail.com</a></p>
    </div>
    <pre>┌──────────────────┐
│  while (alive) { │
│    learn();      │
│    code();       │
│    repeat();     │
│  }               │
└──────────────────┘</pre>
  </div>

  <!-- CONNECT -->
  <h2>🤝 Let's Connect</h2>
  <div class="badges">
    <a href="https://www.linkedin.com/in/EDIT-YOUR-LINKEDIN"><img alt="LinkedIn" src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
    <a href="mailto:mishra.shivam.cg@gmail.com"><img alt="Gmail" src="https://img.shields.io/badge/GMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
    <a href="https://leetcode.com/u/BicooD9W5h/"><img alt="LeetCode" src="https://img.shields.io/badge/LEETCODE-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" /></a>
    <a href="https://github.com/mishrashivamcg-wq"><img alt="GitHub" src="https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  </div>

  <!-- MILESTONES -->
  <h2>🏆 Milestones</h2>
  <div class="grid4">
    <div class="cell"><div class="ico">🎓</div><b>Coding Gita</b><small>Enrolled • Semester 1</small></div>
    <div class="cell"><div class="ico">🧩</div><b>LeetCode</b><small>EDIT: XX problems solved</small></div>
    <div class="cell"><div class="ico">🔧</div><b>Git &amp; GitHub</b><small>Completed course workflow</small></div>
    <div class="cell"><div class="ico">🔜</div><b>Next Goal</b><small>First hackathon / first PR</small></div>
  </div>

  <!-- TECH STACK -->
  <h2>🛠️ Tech Stack</h2>
  <div class="stack center">
    <h4>💻 Languages</h4>
    <img alt="Languages" src="https://skillicons.dev/icons?i=c,cpp,python,js&perline=8" />
    <h4>🌐 Web Development</h4>
    <img alt="Web" src="https://skillicons.dev/icons?i=html,css&perline=8" />
    <h4>🧰 Tools</h4>
    <img alt="Tools" src="https://skillicons.dev/icons?i=git,github,vscode&perline=8" />
    <h4>🌱 Learning Next</h4>
    <img alt="Learning next" src="https://skillicons.dev/icons?i=react,nodejs,tailwind,mysql&perline=8" />
  </div>

  <!-- LEARNING -->
  <h2>⚡ What I'm Learning &amp; Building</h2>
  <div class="grid4">
    <div class="cell"><div class="ico">🧠</div><b>DSA</b><small>Arrays, strings, recursion, sorting</small></div>
    <div class="cell"><div class="ico">🌐</div><b>Web Dev</b><small>Responsive sites with HTML, CSS &amp; JS</small></div>
    <div class="cell"><div class="ico">🐍</div><b>Python &amp; AI</b><small>Foundations for machine learning</small></div>
    <div class="cell"><div class="ico">🔀</div><b>Git Workflow</b><small>Branches, PRs &amp; collaboration</small></div>
  </div>

  <!-- PROJECTS -->
  <h2>📚 Featured Projects</h2>
  <table class="proj">
    <thead><tr><th>Project</th><th>What it does</th><th>Tech</th></tr></thead>
    <tbody>
      <tr><td><a href="https://github.com/mishrashivamcg-wq">CGxSU Semester 1</a></td><td>Git &amp; GitHub course notes and assignments</td><td>Git, Markdown</td></tr>
      <tr><td>EDIT: Project 2</td><td>One line about it</td><td>C++</td></tr>
      <tr><td>EDIT: Project 3</td><td>One line about it</td><td>HTML, CSS, JS</td></tr>
    </tbody>
  </table>

  <!-- OPEN SOURCE -->
  <h2>🌍 Open Source Journey</h2>
  <div class="status">
    STATUS: JUST GETTING STARTED<br />
    Goal: first merged PR &nbsp;·&nbsp; Target: Hacktoberfest 2026
  </div>
  <ul class="tasks">
    <li>✅ Learned Git, branching and pull requests</li>
    <li>⬜ Find "good first issue" labels on beginner-friendly repos</li>
    <li>⬜ Open my first pull request</li>
    <li>⬜ Get my first PR merged 🎉</li>
  </ul>

  <!-- LEETCODE -->
  <h2>🧩 LeetCode</h2>
  <div class="center">
    <img alt="LeetCode stats" src="https://leetcard.jacoblin.cool/BicooD9W5h?theme=dark&font=Fira%20Code&ext=heatmap" />
  </div>

  <!-- GITHUB STATS -->
  <h2>📊 GitHub Stats</h2>
  <div class="stats">
    <img height="170" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=mishrashivamcg-wq&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" />
    <img height="170" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mishrashivamcg-wq&layout=compact&theme=tokyonight&hide_border=true" />
    <img alt="Streak" src="https://streak-stats.demolab.com/?user=mishrashivamcg-wq&theme=tokyonight&hide_border=true" />
  </div>

  <div class="footer">
    <p>⭐ If you like my work, drop a star on my repos! ⭐</p>
  </div>

</main>
</body>
</html>
