---
id: osx.java_home
title: Java_home
desc: ''
updated: 1672662882850
created: 1672662882850
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# java_home

> Return a value for $JAVA_HOME or execute command using this variable.
> More information: <https://www.unix.com/man-page/osx/1/java_home>.

- List JVMs based on a specific version:

`java_home --version {{1.5+}}`

- List JVMs based on a specific [arch]itecture:

`java_home --arch {{i386}}`

- List JVMs based on a specific tasks (defaults to `CommandLine`):

`java_home --datamodel {{Applets|WebStart|BundledApp|JNI|CommandLine}}`

- List JVMs in a XML format:

`java_home --xml`

- Display help:

`java_home --help`

