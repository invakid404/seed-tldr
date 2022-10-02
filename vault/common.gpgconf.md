---
id: common.gpgconf
title: Gpgconf
desc: ''
updated: 1664678009432
created: 1664678009432
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gpgconf

> Modify .gnupg home directories.
> More information: <https://www.gnupg.org/documentation/manuals/gnupg/gpgconf.html>.

- List all components:

`gpgconf --list-components`

- List the directories used by gpgconf:

`gpgconf --list-dirs`

- List all options of a component:

`gpgconf --list-options {{component}}`

- List programs and test whether they are runnable:

`gpgconf --check-programs`

- Reload a component:

`gpgconf --reload {{component}}`

