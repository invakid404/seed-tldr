---
id: linux.sensible-editor
title: Sensible Editor
desc: ''
updated: 1684520364383
created: 1684520364383
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sensible-editor

> Open the default editor.
> More information: <https://manned.org/sensible-editor>.

- Open a file in the default editor:

`sensible-editor {{path/to/file}}`

- Open a file in the default editor, with the cursor at the end of the file:

`sensible-editor + {{path/to/file}}`

- Open a file in the default editor, with the cursor at the beginning of line 10:

`sensible-editor +10 {{path/to/file}}`

- Open 3 files in vertically split editor windows at the same time:

`sensible-editor -O3 {{path/to/file1 path/to/file2 path/to/file3}}`

