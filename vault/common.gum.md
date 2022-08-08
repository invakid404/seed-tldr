---
id: common.gum
title: Gum
desc: ''
updated: 1659966407884
created: 1659966407884
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gum

> A tool for making glamorous shell scripts.
> More information: <https://github.com/charmbracelet/gum>.

- Interactively pick a specific option to print to `stdout`:

`gum choose "{{option_1}}" "{{option_2}}" "{{option_3}}"`

- Open an interactive prompt for the user to input a string with a specific placeholder:

`gum input --placeholder "{{value}}"`

- Open an interactive confirmation prompt and exit with either `0` or `1`:

`gum confirm "{{Continue?}}" --default=false --affirmative "{{Yes}}" --negative "{{No}}" {{&& echo "Yes selected" || echo "No selected"}}`

- Show a spinner while a command is taking place with text alongside:

`gum spin --spinner {{dot|line|minidot|jump|pulse|points|globe|moon|monkey|meter|hamburger}} --title "{{loading...}}" -- {{command}}`

- Format text to include emojis:

`gum format -t {{emoji}} "{{:smile: :heart: hello}}"`

- Interactively prompt for multi-line text (CTRL + D to save) and write to `data.txt`:

`gum write > {{data.txt}}`

