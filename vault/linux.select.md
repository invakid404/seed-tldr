---
id: linux.select
title: Select
desc: ''
updated: 1691158488057
created: 1691158488057
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# select

> Bash builtin construct for creating menus.
> More information: <https://www.gnu.org/software/bash/manual/bash.html#index-select>.

- Create a menu out of individual words:

`select {{word}} in {{apple}} {{orange}} {{pear}} {{banana}}; do echo ${{word}}; done`

- Create a menu for picking a file or folder from the current directory:

`select {{file}} in *; do echo ${{file}}; done`

- Create a menu from a Bash array:

`{{fruits}}=({{apple}} {{orange}} {{pear}} {{banana}}); select {{word}} in ${{{fruits}}[@]}; do echo ${{word}}; done`

