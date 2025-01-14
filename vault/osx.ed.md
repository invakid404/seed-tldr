---
id: osx.ed
title: Ed
desc: ''
updated: 1660529407138
created: 1660529407138
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ed

> The original Unix text editor.
> See also: `awk`, `sed`.
> More information: <https://www.gnu.org/software/ed/manual/ed_manual.html>.

- Start an interactive editor session with an empty document:

`ed`

- Start an interactive editor session with an empty document and a specific [p]rompt:

`ed -p '> '`

- Start an interactive editor session with an empty document and without diagnostics, byte counts and '!' prompt:

`ed -s`

- Edit a specific file (this shows the byte count of the loaded file):

`ed {{path/to/file}}`

- Replace a string with a specific replacement for all lines:

`,s/{{regular_expression}}/{{replacement}}/g`

