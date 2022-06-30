---
id: common.rich
title: Rich
desc: ''
updated: 1656591837559
created: 1656591837559
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rich

> Rich CLI is a toolbox for fancy output in the terminal.
> More information: <https://github.com/Textualize/rich-cli>.

- Display a file with syntax highlighting:

`rich {{path/to/file.py}}`

- Add line numbers, and indentation guides:

`rich {{path/to/file.py}} --line-number --guides`

- Apply a theme:

`rich {{path/to/file.py}} --theme {{monokai}}`

- Display a file in an interactive pager:

`rich {{path/to/file.py}} --pager`

- Display contents from a URL:

`rich {{https://raw.githubusercontent.com/Textualize/rich-cli/main/README.md}} --markdown --pager`

- Export a file as HTML:

`rich {{path/to/file.md}} --export-html {{path/to/file.html}}`

- Display text with formatting tags, custom alignment, and line width:

`rich --print {{"Hello [green on black]Stylized[/green on black] [bold]World[/bold]"}} --{{left|center|right}} --width {{10}}`

