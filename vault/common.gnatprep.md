---
id: common.gnatprep
title: Gnatprep
desc: ''
updated: 1685473997231
created: 1685473997231
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gnatprep

> Preprocessor for Ada source code files (part of the GNAT toolchain).
> More information: <https://gcc.gnu.org/onlinedocs/gnat_ugn/Preprocessing-with-gnatprep.html>.

- Use symbol definitions from a file:

`gnatprep {{source_file}} {{target_file}} {{definitions_file}}`

- Specify symbol values in the command-line:

`gnatprep -D{{name}}={{value}} {{source_file}} {{target_file}}`

