---
id: common.bazel
title: Bazel
desc: ''
updated: 1665377276095
created: 1665377276095
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bazel

> Open-source build and test tool similar to Make, Maven, and Gradle.
> More information: <https://bazel.build/reference/command-line-reference>.

- Build the specified target in the workspace:

`bazel build {{target}}`

- Remove output files and stop the server if running:

`bazel clean`

- Stop the bazel server:

`bazel shutdown`

- Display runtime info about the bazel server:

`bazel info`

- Display help:

`bazel help`

- Display version:

`bazel version`

