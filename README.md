<img align='right' src="https://github-readme-stats.vercel.app/api?username=LuMendes-bit&show_icons=true&title_color=783c00&text_color=af552e&icon_color=783c00&bg_color=f8efd4&cache_seconds=2300" alt="ilustração do status do github">

### Olá, meu nome é Lucas!

<img src="https://img.shields.io/static/v1?label=Overview&message=LuMendes-bits&color=f8efd4&style=for-the-badge&logo=GitHub" alt="Static GitHub">

[![LuMendes-bit](https://github-readme-stats.vercel.app/api/top-langs/?username=LuMendes-bit&hide=html&layout=compact&theme=show_icons=true&title_color=783c00&text_color=af552e&icon_color=783c00&bg_color=f8efd4&cache_seconds=2300)](https://github.com/anuraghazra/github-readme-stats)


- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
