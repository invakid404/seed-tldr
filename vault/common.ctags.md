---
id: common.ctags
title: Ctags
desc: ''
updated: 1664196702928
created: 1664196702928
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ctags

> Generates an index (or tag) file of language objects found in source files for many popular programming languages.
> More information: <https://ctags.io/>.

- Generate tags for a single file, and output them to a file named "tags" in the current directory, overwriting the file if it exists:

`ctags {{path/to/file}}`

- Generate tags for all files in the current directory, and output them to a specific file, overwriting the file if it exists:

`ctags -f {{filename}} *`

- Generate tags for all files in the current directory and all subdirectories:

`ctags --recurse`

- Generate tags for a single file, and output them with start line number and end line number in JSON format:

`ctags --fields=+ne --output-format=json {{path/to/file}}`

