---
id: common.carbon-now
title: Carbon Now
desc: ''
updated: 1691562058930
created: 1691562058930
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# carbon-now

> Create beautiful images of code.
> More information: <https://github.com/mixn/carbon-now-cli>.

- Create an image from a file using default settings:

`carbon-now {{path/to/file}}`

- Create an image from a text in clipboard using default settings:

`carbon-now --from-clipboard`

- Create an image from `stdin` using default settings:

`{{input}} | carbon-now`

- Create images interactively for custom settings and optionally save a preset:

`carbon-now -i {{path/to/file}}`

- Create images from previously saved preset:

`carbon-now -p {{preset}} {{path/to/file}}`

- Start at a specified line of text:

`carbon-now -s {{line}} {{path/to/file}}`

- End at a specific line of text:

`carbon-now -e {{line}} {{path/to/file}}`

- Open image in a browser instead of saving:

`carbon-now --open {{path/to/file}}`

