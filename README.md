<!-- 1. GitHub usernameを変更 -->
<div align="right">
  <img src="https://komarev.com/ghpvc/?username=s1f10220227" />
</div>

## <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28"> Hi there

- :technologist: I'm a student.
- :seedling: I'm currently learning AI!

<!-- 好きな技術スタックに変更 -->
## :seedling: Skills
<img alt="my skills" src="https://skillicons.dev/icons?theme=dark&perline=7&i=py,tensorflow,r,c,java,html,js,django,react,androidstudio,css,bootstrap,docker,kubernetes,postgres,sqlite,mongodb,ubuntu,linux,bash,anaconda,git,github,regex" />
<br>

<!-- GitHub usernameを変更, 2箇所 -->
## Activities
<div align="left">
  <img alt="Top Langs" height="170px" src="https://github-readme-stats.vercel.app/api?username=s1f10220227&theme=vue-dark&layout=compact" />
  <img alt="github stats" height="170px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=s1f10220227&theme=vue-dark&layout=compact" />
</div>

<!--START_SECTION:lapras-card-->
name: LAPRAS Card

on:
  workflow_dispatch:
  schedule:
    - cron: "0 0 * * *"

jobs:
  update-card:
    name: LAPRAS Card
    runs-on: ubuntu-latest
    steps:
      - uses: s1f10220227/s1f10220227@main
        with:
          SHARE_ID: "97RPYYS"
          # 以下オプション
          # https://lapras-card-generator.vercel.app でカスタマイズしたデザインを設定可能
          # ICON_FIRST: "#030E21"
          # ICON_SECOND: "#1688BF"
          # BACKGROUND_FIRST: "#020E27"
          # BACKGROUND_SECOND: "#0E5593"
          # zLANG: "ja"
          # CARD_WIDTH: "400"
          # UPDATE_TIME: "true"
          # README_FILE: "README.md"
          # IS_CENTER: "true"
          # ALTERNATIVE_TEXT: "Score of {SHARE_ID} on LAPRAS"
<!--END_SECTION:lapras-card-->
