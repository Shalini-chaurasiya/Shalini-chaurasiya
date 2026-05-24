# Hi, I'm Shalini Chaurasiya 👋

<p align="left">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=20&pause=1000&color=36BCF7&width=550&lines=B.Tech+(ECE)+Student;Aspiring+Software+Engineer;Full+Stack+and+GenAI+Enthusiast;Building+AI-powered+platforms" alt="Typing SVG" />
</p>

---

## 🚀 About Me
- 🔭 **Currently working on:** AI Interview Platform  
- 🌱 **Learning:** Full Stack Development (MERN), Agentic AI, **Three.js**, **Tailwind CSS**
- 💡 **Interested in:** Web Development, DSA, System Design, GenAI  
- ⚡ **Fun fact:** I love turning ideas into interactive digital reality.

---

## 🛠️ Tech Stack

### 💻 Languages & Frontend
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=cpp,js,html,css,react,tailwind,threejs" />
  </a>
</p>

### 🔧 Backend, Database & Tools
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,git,github,vscode,postman" />
  </a>
</p>

---

## 🚀 Projects

### 🔹 AI Interview Platform
- AI-based mock interview system with real-time feedback and performance analysis.
- **Tech Stack:** React.js, Node.js, MongoDB, GenAI APIs.

---

## 📊 GitHub Activity & Stats

### 🐍 Contribution Activity

name: Generate Snake

on:
  schedule: # Runs every 12 hours
    - cron: "0 */12 * * *"
  workflow_dispatch: # Allows manual trigger
  push:
    branches:
      - main

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 5
    
    steps:
      - name: Generate snake animation
        uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Shalini-chaurasiya/Shalini-chaurasiya/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Shalini-chaurasiya/Shalini-chaurasiya/output/github-contribution-grid-snake.svg">
  <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/Shalini-chaurasiya/Shalini-chaurasiya/output/github-contribution-grid-snake.svg">
</picture>

<br/>

<p align="left">
  <img src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api?username=Shalini-chaurasiya&show_icons=true&theme=tokyonight" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=Shalini-chaurasiya&layout=compact&theme=tokyonight" alt="Top Languages" width="48%" />
</p>

---

## 🔗 Connect With Me

<p align="left">
  <a href="https://www.linkedin.com/in/shalini-chaurasiya-03425931a/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:shalinichaurasiya2203@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/type=waving&color=36BCF7&height=100&section=footer" alt="Waving Footer" />
</p>
