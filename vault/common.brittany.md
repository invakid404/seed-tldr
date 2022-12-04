---
id: common.brittany
title: Brittany
desc: ''
updated: 1670142130875
created: 1670142130875
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# brittany

> Pretty-print Haskell source files.
> More information: <https://github.com/lspitzner/brittany#readme>.

- Format a Haskell source file and print the result to `stdout`:

`brittany {{path/to/file.hs}}`

- Format all Haskell source files in the current directory in-place:

`brittany --write-mode=inplace {{*.hs}}`

- Check whether a Haskell source file needs changes and indicate the result through the programme's exit code:

`brittany --check-mode {{path/to/file.hs}}`

- Format a Haskell source file using the specified amount of spaces per indentation level and line length:

`brittany --indent {{4}} --columns {{100}} {{path/to/file.hs}}`

- Format a Haskell source file according to the style defined in the specified config file:

`brittany --config-file {{path/to/config.yaml}} {{path/to/file.hs}}`

