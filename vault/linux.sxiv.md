---
id: linux.sxiv
title: Sxiv
desc: ''
updated: 1691562059191
created: 1691562059191
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sxiv

> Simple X Image Viewer.
> More information: <https://github.com/muennich/sxiv>.

- Open an image:

`sxiv {{path/to/file}}`

- Open an image in fullscreen mode:

`sxiv -f {{path/to/file}}`

- Open a newline-separated list of images, reading filenames from `stdin`:

`echo {{path/to/file}} | sxiv -i`

- Open a space-separated list of images as a slideshow:

`sxiv -S {{seconds}} {{path/to/file}}`

- Open a space-separated list of images in thumbnail mode:

`sxiv -t {{path/to/file}}`

