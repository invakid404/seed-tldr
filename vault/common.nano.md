---
id: common.nano
title: Nano
desc: ''
updated: 1673166091685
created: 1673166091685
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nano

> Command-line text editor. An enhanced `Pico` clone.
> More information: <https://nano-editor.org>.

- Start the editor:

`nano`

- Start the editor without using configuration files:

`nano --ignorercfiles`

- Open specific files, moving to the next file when closing the previous one:

`nano {{path/to/file1 path/to/file2 ...}}`

- Open a file and position the cursor at a specific line and column:

`nano +{{line}},{{column}} {{path/to/file}}`

- Open a file and enable soft wrapping:

`nano --softwrap {{path/to/file}}`

- Open a file and indent new lines to the previous line's indentation:

`nano --autoindent {{path/to/file}}`

- Open a file and create a backup file (`path/to/file~`) on save:

`nano --backup {{path/to/file}}`

