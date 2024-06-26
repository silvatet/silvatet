## Olá! Eu sou o Mateus João🖐️


[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/the_teuzz?igsh=ZG90b3hvN2JwbHNl)
[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mateus-jo%C3%A3o-08421b262?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)]( https://x.com/MateusTsugikuni?t=VtnIJ6aHUJM6rqmBfFA3yg&s=08)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/silvatet)

## Tecnologias que eu uso no meu dia

<div style="display: inline_block">
  <img align="center" alt="html5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img align="center" alt="css" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img align="center" alt="js" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img align="center" alt="ts" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
  <img align="center" alt="react" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
   <img align="center" alt="react" src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white"/>
  <img align="center" alt="react" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
    <img align="center" alt="react" src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
     <img align="center" alt="react" src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white" /> 
   <img align="center" alt="react" src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />


  
</div><br/>


![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=silvatet&layout=compact)


##Tecnologias que eu uso mais no dia a dia 

<div style="display inline_block">
  
<img align="center" alt="react" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
 <img align="center" alt="react" src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white"/>
<img align="center" alt="react" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
<img align="center" alt="react" src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
<img align="center" alt="react" src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white" /> 
<img align="center" alt="react" src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />


</div><br/>






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
        with:silvatet
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

##EMAIL DE CONTATO: teuzmachado5@gmail.com





