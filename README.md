<h1 align="center">Hi there, I'm Sudhanshu Sekhar Moharana 👋</h1>
<h3 align="center">Computer Science Engineering Student | AI & ML Enthusiast | Full Stack Developer</h3>

<p align="center">
  <a href="https://moharanasudhanshu.github.io/portfolio/">
    <img src="https://readme-typing-svg.demolab.com/?lines=B.Tech+CSE+Student+at+SUIIT;AI+%26+ML+Enthusiast;Full+Stack+Web+Developer;Currently+learning+Deep+Learning+%26+MERN&center=true&width=500&height=45&color=58A6FF&vCenter=true&size=22" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=MoharanaSudhanshu&color=blue&style=flat-square" alt="Profile views" />
  <a href="https://www.linkedin.com/in/sudhanshu-sekhar-moharana-518b85290/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/MoharanaSudhanshu">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
  </a>
  <a href="mailto:moharanasudhanshu1@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  <a href="https://moharanasudhanshu.github.io/portfolio/">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white" />
  </a>
</p>

---

## 🚀 About Me

- 🎓 B.Tech CSE student at **SUIIT**
- 🤖 Passionate about **Artificial Intelligence & Machine Learning**
- 💻 Full Stack Web Developer (MERN)
- 🌱 Currently learning **Deep Learning** & advanced MERN patterns
- 🔭 Currently building: **Heart Disease Prediction using ML**
- 📫 Reach me at: **moharanasudhanshu1@gmail.com**

---

## 🛠️ Tech Stack

**Languages**
<p>
  <img src="https://skillicons.dev/icons?i=c,cpp,java,python" />
</p>

**Frontend**
<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,react,tailwind" />
</p>

**Backend**
<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express" />
</p>

**Databases**
<p>
  <img src="https://skillicons.dev/icons?i=mongodb,postgresql" />
</p>

**Tools**
<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,postman,figma" />
</p>

---

## 🏆 Achievements

- 🥇 Code-o-Olympics Participant
- 🎖️ Hacktoberfest Contributor
- 🏆 AI/ML Project Developer

---

## 🚀 Featured Projects

### ❤️ [Heart Disease Prediction](https://github.com/MoharanaSudhanshu)
Machine learning model achieving 92% accuracy using Logistic Regression and Random Forest.

### 🧠 [Cervical Cancer Detection](https://github.com/MoharanaSudhanshu)
Deep learning based image classification system for early detection.

> 💡 Tip: link each project title directly to its GitHub repo once they're public — recruiters click straight through from here.

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MoharanaSudhanshu&show_icons=true&theme=tokyonight&count_private=true" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=MoharanaSudhanshu&theme=tokyonight" alt="GitHub Streak" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MoharanaSudhanshu&layout=compact&theme=tokyonight" alt="Top Languages" height="165"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=MoharanaSudhanshu&theme=tokyonight&no-frame=true&row=1&column=6" alt="Trophies" />
</p>

> ⚠️ If any widget above shows "Failed to retrieve" or a broken icon, it's usually a temporary rate-limit on the shared public API — see the setup notes at the bottom of this README for fixes.

---

## 📈 Contribution Activity Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=MoharanaSudhanshu&theme=tokyo-night&hide_border=true" alt="Activity Graph" />
</p>

---

## 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/MoharanaSudhanshu/MoharanaSudhanshu/output/github-contribution-grid-snake-dark.svg" alt="Contribution Snake" />
</p>

> Generated via a GitHub Action (`Platane/snk`) that regenerates daily — see setup steps at the bottom if the snake doesn't render yet.

---

## 💬 Random Dev Quote

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Random Dev Quote" />
</p>

---

## 🌱 Currently Learning

<p align="center">
  <img src="https://img.shields.io/badge/Deep%20Learning-in%20progress-yellow?style=flat-square" />
  <img src="https://img.shields.io/badge/MERN%20Stack-leveling%20up-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/DSA-practicing-orange?style=flat-square" />
</p>

---

<p align="center"><i>Thanks for stopping by — feel free to connect!</i> ⭐</p>

<details>
<summary>⚙️ Setup notes (for me, future reference)</summary>

**Contribution Snake workflow** — add `.github/workflows/snake.yml`:

\`\`\`yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  push:
    branches:
      - main
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: Platane/snk@v3
        id: snake
        with:
          github_user_name: MoharanaSudhanshu
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
\`\`\`

Run the workflow once manually (Actions tab → Run workflow) so the `output` branch exists before the image loads.

**If GitHub Stats / Trophies show a broken icon or "Failed to retrieve":**
1. Wait and refresh — usually a temporary rate limit on the shared public instance.
2. Try the mirror: `https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api?username=MoharanaSudhanshu...`
3. Self-host your own copy of github-readme-stats on Vercel with your own token for a permanent fix.

</details>
