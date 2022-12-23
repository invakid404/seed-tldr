---
id: linux.nemo
title: Nemo
desc: ''
updated: 1671769278768
created: 1671769278768
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nemo

> Manages files and directories in Cinnamon desktop environment.
> More information: <https://manned.org/nemo>.

- Open the current user home directory:

`nemo`

- Open specific directories in separate windows:

`nemo {{path/to/directory1 path/to/directory2 ...}}`

- Open specific directories in tabs:

`nemo --tabs {{path/to/directory1 path/to/directory2 ...}}`

- Open a directory with a specific window size:

`nemo --geometry={{600}}x{{400}} {{path/to/directory}}`

- Close all windows:

`nemo --quit`

