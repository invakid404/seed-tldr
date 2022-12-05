---
id: common.bat
title: Bat
desc: ''
updated: 1670210384626
created: 1670210384626
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bat

> Print and concatenate files.
> A `cat` clone with syntax highlighting and Git integration.
> More information: <https://github.com/sharkdp/bat>.

- Print the contents of a file to the standard output:

`bat {{path/to/file}}`

- Concatenate several files into the target file:

`bat {{file1}} {{file2}} > {{target_file}}`

- Append several files into the target file:

`bat {{file1}} {{file2}} >> {{target_file}}`

- Number all output lines:

`bat --number {{path/to/file}}`

- Syntax highlight a JSON file:

`bat --language json {{file.json}}`

- Display all supported languages:

`bat --list-languages`

