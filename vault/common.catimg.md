---
id: common.catimg
title: Catimg
desc: ''
updated: 1661728864739
created: 1661728864739
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# catimg

> Image printing in the terminal.
> See also: `pixterm`, `chafa`.
> More information: <https://github.com/posva/catimg>.

- Print a JPEG, PNG, or GIF to the terminal:

`catimg {{path/to/file}}`

- Double the [r]esolution of an image:

`catimg -r 2 {{path/to/file}}`

- Disable 24-bit color for better [t]erminal support:

`catimg -t {{path/to/file}}`

- Specify a custom [w]idth or [H]eight:

`catimg {{-w|-H}} {{40}} {{path/to/file}}`

