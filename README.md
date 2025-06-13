<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=izabellyrubiac&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=radical&locale=en&hide_border=false&order=1" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=izabellyrubiac&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=radical&hide_border=false&order=2" height="150" alt="languages graph"  />
</div>

###

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/izabellyrubiac/izabellyrubiac/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/izabellyrubiac/izabellyrubiac/output/pacman-contribution-graph.svg">
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/izabellyrubiac/izabellyrubiac/output/pacman-contribution-graph.svg">
</picture>



      - name: push pacman-contribution-graph.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
