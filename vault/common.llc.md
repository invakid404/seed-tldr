---
id: common.llc
title: Llc
desc: ''
updated: 1657504906885
created: 1657504906885
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# llc

> Compiles LLVM Intermediate Representation or bitcode to target-specific assembly language.
> More information: <https://www.llvm.org/docs/CommandGuide/llc.html>.

- Compile a bitcode or IR file to an assembly file with the same base name:

`llc {{path/to/file.ll}}`

- Enable all optimizations:

`llc -O3 {{path/to/input.ll}}`

- Output assembly to a specific file:

`llc --output {{path/to/output.s}}`

- Emit fully relocatable, position independent code:

`llc -relocation-model=pic {{path/to/input.ll}}`

