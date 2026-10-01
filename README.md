<!--
  ═══════════════════════════════════════════════════════════════════════════
  Marwan — GitHub Profile README
  ───────────────────────────────────────────────────────────────────────────
  Architecture:  Dynamic SVG endpoints + GitHub Actions for self-updating data
  Theme:         GitHub Dark (#0d1117) with neon-green accent (#00ff41)
  Renders:       Pixel-perfect SVGs for all visitors (no monospace dependency)

  SECTIONS:
  01 · Banner             — Animated gradient header
  02 · Identity           — Live terminal card with guestbook
  03 · Signal             — Neofetch-style stats card (dark/light aware)
  04 · Stack              — Curated tech icons
  05 · Metrics            — Extended GitHub stats (successor to github-readme-stats)
  06 · Streak & Activity  — Commit streak + contribution graph
  07 · Playable Grid      — Interactive contribution Snake game
  08 · Selected Work      — Pinned repository cards
  09 · Motto              — Animated quote
  10 · Reach Me           — Contact badges
  11 · Footer             — Closing wave

  MAINTENANCE:
  - Sections 02 and 03 are dynamic SVGs that fetch live GitHub data.
  - Section 07 requires a GitHub Action (instructions provided inline).
  - To customize themes, replace `00ff41` (neon green) with any hex code.
  ═══════════════════════════════════════════════════════════════════════════
-->

<!-- ══════════════════════════ 01 · BANNER ══════════════════════════════════ -->

<div align="center">

<a href="https://velixsoft.net">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:001a0d,100:00ff41&height=220&section=header&text=Marwan&fontSize=80&fontColor=00ff41&fontAlignY=35&animation=fadeIn&desc=Backend%20Developer%20%C2%B7%20Automation%20Engineer%20%C2%B7%20Reverse%20Engineer&descAlignY=58&descSize=18&descColor=ffffff"
    width="100%"
    alt="Marwan — Backend Developer, Automation Engineer, Reverse Engineer"
  />
</a>

<!-- ══════════════════════════ 02 · IDENTITY ═══════════════════════════════ -->

<!--
  DevQuest Interactive Terminal Card
  ───────────────────────────────────
  This is a live, interactive terminal card. Visitors can type commands
  and explore your GitHub identity. It includes a guestbook feature.

  Template:  terminal
  Theme:     matrix (neon green on black)
  API:       https://devquest-mu.vercel.app/api/card
-->

<a href="https://devquest-mu.vercel.app">
  <img
    src="https://devquest-mu.vercel.app/api/card?username=marwanvx&template=terminal&theme=matrix"
    alt="Interactive terminal card — type commands to explore my GitHub profile"
    width="720"
  />
</a>

<br/>
<br/>

<!-- ══════════════════════════ 03 · SIGNAL ═════════════════════════════════ -->

<!--
  Neofetch Profile Card
  ──────────────────────
  A retro `neofetch`-style stats card. Your GitHub avatar is converted
  to ASCII art, and stats are fetched live from the GitHub API.
  Supports dark/light mode via the <picture> element.
-->

<p align="center">
  <a href="https://github.com/jeantimex/neofetch-profile">
    <picture>
      <source
        media="(prefers-color-scheme: dark)"
        srcset="https://neofetch-profile.vercel.app/api?username=marwanvx&theme=github-dark"
      />
      <source
        media="(prefers-color-scheme: light)"
        srcset="https://neofetch-profile.vercel.app/api?username=marwanvx&theme=github-light"
      />
      <img
        src="https://neofetch-profile.vercel.app/api?username=marwanvx&theme=github-dark"
        alt="Neofetch-style GitHub stats card"
        width="720"
      />
    </picture>
  </a>
</p>

<br/>

### `marwan@velix:~$ cat mission.txt`

> I build automation tools, backend systems, and technical workflows with a
> focus on clean logic, performance, and reliability.

<img src="https://img.shields.io/badge/%F0%9F%94%AD%20BUILDING-automation%20%C2%B7%20backends%20%C2%B7%20RE-0d1117?style=flat-square&labelColor=0d1117&color=00ff41" />
<img src="https://img.shields.io/badge/%F0%9F%8C%B1%20LEARNING-system%20design%20%C2%B7%20protocols%20%C2%B7%20deobfuscation-0d1117?style=flat-square&labelColor=0d1117&color=00ff41" />
<img src="https://img.shields.io/badge/%F0%9F%A4%9D%20OPEN%20TO-collaboration%20%C2%B7%20scraping%20%C2%B7%20backend-0d1117?style=flat-square&labelColor=0d1117&color=00ff41" />

</div>

<br/>

---

<!-- ══════════════════════════ 04 · STACK ══════════════════════════════════ -->

## <samp>04 · &nbsp;Stack</samp>

<div align="center">

<p>
  <img src="https://skillicons.dev/icons?i=php,laravel,js,ts,python,nodejs,react,html,css,mysql,postgres,redis,nginx,linux,git,postman,firebase,aws&theme=dark&perline=9" alt="Languages and tools" />
</p>

<p>
  <img src="https://img.shields.io/badge/PHP-0d1117?style=for-the-badge&logo=php&logoColor=00ff41" />
  <img src="https://img.shields.io/badge/Laravel-0d1117?style=for-the-badge&logo=laravel&logoColor=00ff41" />
  <img src="https://img.shields.io/badge/JavaScript-0d1117?style=for-the-badge&logo=javascript&logoColor=00ff41" />
  <img src="https://img.shields.io/badge/TypeScript-0d1117?style=for-the-badge&logo=typescript&logoColor=00ff41" />
  <img src="https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=00ff41" />
  <img src="https://img.shields.io/badge/Node.js-0d1117?style=for-the-badge&logo=nodedotjs&logoColor=00ff41" />
  <img src="https://img.shields.io/badge/React-0d1117?style=for-the-badge&logo=react&logoColor=00ff41" />
  <img src="https://img.shields.io/badge/MySQL-0d1117?style=for-the-badge&logo=mysql&logoColor=00ff41" />
  <img src="https://img.shields.io/badge/PostgreSQL-0d1117?style=for-the-badge&logo=postgresql&logoColor=00ff41" />
  <img src="https://img.shields.io/badge/Redis-0d1117?style=for-the-badge&logo=redis&logoColor=00ff41" />
  <img src="https://img.shields.io/badge/Nginx-0d1117?style=for-the-badge&logo=nginx&logoColor=00ff41" />
  <img src="https://img.shields.io/badge/Linux-0d1117?style=for-the-badge&logo=linux&logoColor=00ff41" />
  <img src="https://img.shields.io/badge/Git-0d1117?style=for-the-badge&logo=git&logoColor=00ff41" />
  <img src="https://img.shields.io/badge/Firebase-0d1117?style=for-the-badge&logo=firebase&logoColor=00ff41" />
  <img src="https://img.shields.io/badge/AWS-0d1117?style=for-the-badge&logo=amazonaws&logoColor=00ff41" />
</p>

</div>

---

<!-- ══════════════════════════ 05 · METRICS ════════════════════════════════ -->

## <samp>05 · &nbsp;Metrics</samp>

<div align="center">

<!--
  GitHub Stats Extended
  ─────────────────────
  Actively maintained successor to github-readme-stats.
  Fully compatible parameter-wise — just a different domain.
-->

<p>
  <img
    height="170"
    src="https://github-stats-extended.vercel.app/api?username=marwanvx&show_icons=true&hide_border=true&bg_color=0d1117&title_color=00ff41&icon_color=00ff41&text_color=c9d1d9&rank_icon=github&include_all_commits=true&count_private=true"
    alt="GitHub stats"
  />
  <img
    height="170"
    src="https://github-stats-extended.vercel.app/api/top-langs/?username=marwanvx&layout=compact&hide_border=true&bg_color=0d1117&title_color=00ff41&text_color=c9d1d9&langs_count=8&count_private=true"
    alt="Top languages"
  />
</p>

<!-- ══════════════════════════ 06 · STREAK & ACTIVITY ══════════════════════ -->

<p>
  <img
    src="https://streak-stats.demolab.com?user=marwanvx&hide_border=true&background=0d1117&stroke=00ff41&ring=00ff41&fire=00ff41&currStreakLabel=00ff41&sideLabels=c9d1d9&currStreakNum=ffffff&sideNums=ffffff&dates=8b949e"
    alt="GitHub streak"
  />
</p>

<p>
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=marwanvx&bg_color=0d1117&color=00ff41&line=00ff41&point=ffffff&area=true&hide_border=true&custom_title=Contribution%20Activity"
    width="100%"
    alt="Activity graph"
  />
</p>

</div>

---

<!-- ══════════════════════════ 07 · PLAYABLE GRID ══════════════════════════ -->

## <samp>07 · &nbsp;Playable Grid</samp>

<div align="center">

<!--
  Interactive Snake Game
  ───────────────────────
  This turns your contribution graph into a playable Snake game.
  Visitors can use WASD or arrow keys to control the snake.

  SETUP REQUIRED:
  1. Create a GitHub Action file at `.github/workflows/snake.yml` in this repo.
  2. Copy the workflow below into that file.
  3. Commit — the action will generate the SVG on a schedule and on push.

  ─────────────────────────────────────────────────────────────
  name: Generate Snake

  on:
    schedule:
      - cron: "0 */12 * * *"
    workflow_dispatch:
    push:
      branches: [main]

  jobs:
    build:
      runs-on: ubuntu-latest
      permissions:
        contents: write
      steps:
        - uses: Platane/snk/svg-only@v3
          with:
            github_user_name: marwanvx
            outputs: |
              dist/github-snake.svg
              dist/github-snake-dark.svg?palette=github-dark
        - uses: crazy-max/ghaction-github-pages@v3
          with:
            target_branch: output
            build_dir: dist
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  ─────────────────────────────────────────────────────────────
-->

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/marwanvx/marwanvx/output/github-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/marwanvx/marwanvx/output/github-snake.svg"
  />
  <img
    src="https://raw.githubusercontent.com/marwanvx/marwanvx/output/github-snake.svg"
    alt="Playable contribution snake game"
    width="100%"
  />
</picture>

</div>

---

<!-- ══════════════════════════ 08 · SELECTED WORK ══════════════════════════ -->

## <samp>08 · &nbsp;Selected Work</samp>

<div align="center">

<a href="https://velixsoft.net">
  <img
    src="https://github-readme-stats.vercel.app/api/pin/?username=marwanvx&repo=velixsoft&hide_border=true&bg_color=0d1117&title_color=00ff41&icon_color=00ff41&text_color=c9d1d9"
    alt="VelixSoft"
  />
</a>

<!--
  Add pinned-repo cards here. Pattern:

  <a href="https://github.com/marwanvx/REPO_NAME">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=marwanvx&repo=REPO_NAME&hide_border=true&bg_color=0d1117&title_color=00ff41&icon_color=00ff41&text_color=c9d1d9" />
  </a>
-->

</div>

---

<!-- ══════════════════════════ 09 · MOTTO ══════════════════════════════════ -->

## <samp>09 · &nbsp;Motto</samp>

<div align="center">

<br/>

<img
  src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&pause=10000&color=00FF41&center=true&vCenter=true&width=900&height=80&lines=%22To+get+something+you+never+had%2C+you+have+to+do+something+you+never+did.%22"
  alt="Motto"
/>

<br/>

</div>

---

<!-- ══════════════════════════ 10 · REACH ME ═══════════════════════════════ -->

## <samp>10 · &nbsp;Reach Me</samp>

<div align="center">

<p>
  <a href="https://github.com/marwanvx">
    <img src="https://img.shields.io/badge/GitHub-marwanvx-0d1117?style=for-the-badge&logo=github&logoColor=00ff41" />
  </a>
  <a href="https://discord.gg/mrw.sys">
    <img src="https://img.shields.io/badge/Discord-mrw.sys-0d1117?style=for-the-badge&logo=discord&logoColor=00ff41" />
  </a>
  <a href="mailto:velixsoft@gmail.com">
    <img src="https://img.shields.io/badge/Email-velixsoft@gmail.com-0d1117?style=for-the-badge&logo=gmail&logoColor=00ff41" />
  </a>
  <a href="https://velixsoft.net">
    <img src="https://img.shields.io/badge/Website-velixsoft.net-0d1117?style=for-the-badge&logo=firefox&logoColor=00ff41" />
  </a>
</p>

</div>

---

<!-- ══════════════════════════ 11 · FOOTER ═════════════════════════════════ -->

<div align="center">

<img
  src="https://capsule-render.vercel.app/api?type=waving&color=0:00ff41,50:001a0d,100:0d1117&height=140&section=footer"
  width="100%"
  alt="Footer"
/>

<samp>
  <sub>Built with logic, not vibes.</sub>
</samp>

</div>
