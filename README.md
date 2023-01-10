![Header_Image](https://imgur.com/TMkhSXY.png)

### Hi there 👋

<!--Cancel changes
**FruitPassion/FruitPassion** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<!--START_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}
<!--END_SECTION:waka-->


[![My Skills](https://skillicons.dev/icons?i=html)](https://skillicons.dev) Test []

[![My Skills](https://skillicons.dev/icons?i=html,css,ae,bash,c,docker,django,git,linux,nginx,ps,py,qt,sqlite,bots)](https://skillicons.dev)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=FruitPassion&theme=onedark)](https://github.com/anuraghazra/github-readme-stats)

![Footer_Image](https://imgur.com/5f4uRW6.png)

