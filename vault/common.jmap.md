---
id: common.jmap
title: Jmap
desc: ''
updated: 1685843802153
created: 1685843802153
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jmap

> Java memory map tool.
> More information: <https://docs.oracle.com/en/java/javase/20/docs/specs/man/jmap.html>.

- Print shared object mappings for a Java process (output like pmap):

`jmap {{java_pid}}`

- Print heap summary information:

`jmap -heap {{filename.jar}} {{java_pid}}`

- Print histogram of heap usage by type:

`jmap -histo {{java_pid}}`

- Dump contents of the heap into a binary file for analysis with jhat:

`jmap -dump:format=b,file={{path/to/file}} {{java_pid}}`

- Dump live objects of the heap into a binary file for analysis with jhat:

`jmap -dump:live,format=b,file={{path/to/file}} {{java_pid}}`

