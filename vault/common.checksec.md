---
id: common.checksec
title: Checksec
desc: ''
updated: 1693279019256
created: 1693279019256
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# checksec

> Check security properties of executables.
> More information: <https://github.com/slimm609/checksec.sh>.

- List security properties of an executable binary file:

`checksec --file={{path/to/binary}}`

- List security properties recursively of all executable files in a directory:

`checksec --dir={{path/to/directory}}`

- List security properties of a process:

`checksec --proc={{pid}}`

- List security properties of the running kernel:

`checksec --kernel`

