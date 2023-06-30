---
id: linux.archlinux-java
title: Archlinux Java
desc: ''
updated: 1688106199607
created: 1688106199607
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# archlinux-java

> Switch between installed Java environments.
> More information: <https://wiki.archlinux.org/title/Java#Switching_between_JVM>.

- List installed Java environments:

`archlinux-java status`

- Return the short name of the current default Java environment:

`archlinux-java get`

- Set the default Java environment:

`archlinux-java set {{java_environment}}`

- Unset the default Java environment:

`archlinux-java unset`

- Fix an invalid/broken default Java environment configuration:

`archlinux-java fix`

