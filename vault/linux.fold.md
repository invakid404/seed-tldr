---
id: linux.fold
title: Fold
desc: ''
updated: 1688890860461
created: 1688890860461
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fold

> Folds long lines for fixed-width output devices.
> More information: <https://gnu.org/software/coreutils/fold>.

- Fold lines in a fixed width:

`fold --width {{width}} {{path/to/file}}`

- Count width in bytes (the default is to count in columns):

`fold --bytes --width {{width_in_bytes}} {{path/to/file}}`

- Break the line after the rightmost blank within the width limit:

`fold --spaces --width {{width}} {{path/to/file}}`

