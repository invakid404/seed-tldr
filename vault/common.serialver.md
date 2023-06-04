---
id: common.serialver
title: Serialver
desc: ''
updated: 1685843802210
created: 1685843802210
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# serialver

> Returns the serialVersionUID of classes.
> It does not set a security manager by default.
> More information: <https://docs.oracle.com/en/java/javase/20/docs/specs/man/serialver.html>.

- Display the serialVersionUID of a class:

`serialver {{classnames}}`

- Display the serialVersionUID for a colon-separated list of classes and resources:

`serialver -classpath {{path/to/directory}} {{classname1:classname2:...}}`

- Use a specific option from reference page of Java application launcher to the Java Virtual Machine:

`serialver -Joption {{classnames}}`

