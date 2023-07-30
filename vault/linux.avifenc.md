---
id: linux.avifenc
title: Avifenc
desc: ''
updated: 1690723056705
created: 1690723056705
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# avifenc

> AV1 Image File Format (AVIF) encoder.
> More information: <https://aomediacodec.github.io/av1-avif/>.

- Convert a specific PNG image to AVIF:

`avifenc {{path/to/input.png}} {{path/to/output.avif}}`

- Encode with a specific speed (6=default, 0=slowest and 10=fastest):

`avifenc --speed {{2}} {{path/to/input.png}} {{path/to/output.avif}}`

