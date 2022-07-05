---
id: common.man
title: Man
desc: ''
updated: 1657009575481
created: 1657009575481
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# man

> Format and display manual pages.
> More information: <https://www.man7.org/linux/man-pages/man1/man.1.html>.

- Display the man page for a command:

`man {{command}}`

- Display the man page for a command from section 7:

`man {{7}} {{command}}`

- List all available sections for a command:

`man -f {{command}}`

- Display the path searched for manpages:

`man --path`

- Display the location of a manpage rather than the manpage itself:

`man -w {{command}}`

- Display the man page using a specific locale:

`man {{command}} --locale={{locale}}`

- Search for manpages containing a search string:

`man -k "{{search_string}}"`

