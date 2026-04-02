<h2 align="left">Hi, I am Jose 👋 A builder who enjoys creating meaningful projects and exploring new ideas.</h2>
name: Generate pacman animation

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"

  workflow_dispatch:

  push:
    branches:
    - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5

    steps:
      - name: generate pacman-contribution-graph.svg
        uses: abozanona/pacman-contribution-graph@main
        with:
          github_user_name: ${{ github.repository_owner }}


      - name: push pacman-contribution-graph.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="30" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="30" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="30" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="30" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="30" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.simpleicons.org/solidity/363636" height="30" alt="solidity logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=mongodb" height="30" alt="mongodb logo"  />
  <img width="12" />
  <img src="https://cdn.simpleicons.org/mysql/4479A1" height="30" alt="mysql logo"  />
  <img width="12" />
  <img src="https://cdn.simpleicons.org/blender/F5792A" height="30" alt="blender logo"  />
  <img width="12" />
  <img src="https://cdn.simpleicons.org/nodedotjs/339933" height="30" alt="nodejs logo"  />
</div>

###

<div align="left">
  <a href="https://discord.com/users/1232590985096331319" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Discord&logo=discord&label=&color=7289DA&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="discord logo"  />
  </a>
  <a href="https://www.instagram.com/itzz.jose_25/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="instagram logo"  />
  </a>
  <a href="joseregish25@gmail.com" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="gmail logo"  />
  </a>
  <a href="https://www.linkedin.com/in/jose-regish-9b7196350/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="linkedin logo"  />
  </a>
</div>

###

<div align="center">
  <img src="https://streak-stats.demolab.com?user=hackerjose25&locale=en&mode=daily&theme=highcontrast&hide_border=false&border_radius=5" height="150" alt="streak graph"  />
</div>

###

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hackerjose25/hackerjose25/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/hackerjose25/hackerjose25/output/pacman-contribution-graph.svg">
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/hackerjose25/hackerjose25/output/pacman-contribution-graph.svg">
</picture>

###

<div align="left">
  <a href="https://open.spotify.com/user/317hew6gxt3kuesq7rrng254viym">
    <img src="https://spotify-recently-played-readme.vercel.app/api?user=317hew6gxt3kuesq7rrng254viym&count=5&unique=false" alt="Spotify recently played"  />
  </a>
</div>

###
