---
id: common.banner
title: Banner
desc: ''
updated: 1670142130873
created: 1670142130873
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# banner

> Print the given argument as a large ASCII art.
> More information: <https://manned.org/banner>.

- Print the text message as a large banner (quotes are optional):

`banner "{{Hello World}}"`

- Print the text message as a banner with a width of 50 characters:

`banner -w {{50}} "{{Hello World}}"`

- Read text from `stdin`:

`banner`

