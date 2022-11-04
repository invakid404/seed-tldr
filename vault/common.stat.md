---
id: common.stat
title: Stat
desc: ''
updated: 1667593494678
created: 1667593494678
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# stat

> Display file and filesystem information.
> More information: <https://www.gnu.org/software/coreutils/manual/html_node/stat-invocation.html>.

- Display properties about a specific file such as size, permissions, creation and access dates among others:

`stat {{path/to/file}}`

- Display properties about a specific file such as size, permissions, creation and access dates among others without labels:

`stat --terse {{path/to/file}}`

- Display information about the filesystem where a specific file is located:

`stat --file-system {{path/to/file}}`

- Show only octal file permissions:

`stat --format="%a %n" {{path/to/file}}`

- Show the owner and group of a specific file:

`stat --format="%U %G" {{path/to/file}}`

- Show the size of a specific file in bytes:

`stat --format="%s %n" {{path/to/file}}`

