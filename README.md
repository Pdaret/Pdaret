<p align="center">
  <img src="https://capsule-render.vercel.app/api?text=Hey Everyone!🕹️&animation=fadeIn&type=waving&color=gradient&height=100"/>
</p>



<a href="https://www.instagram.com/thepiyushmalhotra/">
  <img height="50" src="https://user-images.githubusercontent.com/46517096/166974368-9798f39f-1f46-499c-b14e-81f0a3f83a06.png"/>
</a>



<h2> 🚀 &nbsp;Some Tools I Have Used and Learned</h2>
<p align="left">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="vscode" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" alt="bash" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" alt="php" width="45" height="45"/>
</p>


- 👋 Hi, I’m @Sifouo
- 👀 I’m interested in Programmig,Security,Al,Network,I’m a Geek
- 🌱 I’m currently learning computer science
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me mr.srezaei@outlook.com -- TeleGram:  @Pdaret1


![Snake animation](https://github.com/thepiyushmalhotra/thepiyushmalhotra/blob/output/github-contribution-grid-snake.svg)




name: Generate Datas
on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:
jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
with:
          github_user_name: thepiyushmalhotra
          svg_out_path: dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

<!---
Sifouo/Sifouo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
