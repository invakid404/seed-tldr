---
id: common.jdeps
title: Jdeps
desc: ''
updated: 1665419892001
created: 1665419892001
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jdeps

> Java class dependency analyzer.
> More information: <https://docs.oracle.com/en/java/javase/18/docs/specs/man/jdeps.html>.

- Analyze the dependencies of a `.jar` or `.class` file:

`jdeps {{path/to/filename.class}}`

- Print a summary of all dependencies of a specific `.jar` file:

`jdeps {{path/to/filename.jar}} -summary`

- Print all class-level dependencies of a `.jar` file:

`jdeps {{path/to/filename.jar}} -verbose`

- Output the results of the analysis in a DOT file into a specific directory:

`jdeps {{path/to/filename.jar}} -dotoutput {{path/to/directory}}`

- Display help:

`jdeps --help`

