---
id: linux.tac
title: Tac
desc: ''
updated: 1656591837655
created: 1656591837655
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tac

> Display and concatenate files with lines in reversed order.
> See also: `cat`.
> More information: <https://www.gnu.org/software/coreutils/tac>.

- Concatenate specific files in reversed order:

`tac {{path/to/file1 path/to/file2 ...}}`

- Display `stdin` in reversed order:

`{{cat path/to/file}} | tac`

- Use a specific separator:

`tac --separator {{,}} {{path/to/file1 path/to/file2 ...}}`

- Use a specific regex as a separator:

`tac --regex --separator {{[,;]}} {{path/to/file1 path/to/file2 ...}}`

- Use a separator before each file:

`tac --before {{path/to/file1 path/to/file2 ...}}`

