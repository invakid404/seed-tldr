---
id: linux.mate-screenshot
title: Mate Screenshot
desc: ''
updated: 1656591837635
created: 1656591837635
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mate-screenshot

> Make screenshots in MATE desktop environment.
> More information: <https://manned.org/mate-screenshot>.

- Create a fullscreen screenshot:

`mate-screenshot`

- Create an active window screenshot:

`mate-screenshot --window`

- Create a specific area screenshot:

`mate-screenshot --area`

- Create a screenshot interactively:

`mate-screenshot --interactive`

- Create a screenshot without borders:

`mate-screenshot --window --remove-border`

- Create a screenshot with a specific effect:

`mate-screenshot --effect={{shadow|border|none}}`

- Create a screenshot with a specific delay in seconds:

`mate-screenshot --delay={{5}}`

