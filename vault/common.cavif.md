---
id: common.cavif
title: Cavif
desc: ''
updated: 1688867742695
created: 1688867742695
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cavif

> PNG/JPEG to AVIF converter.
> More information: <https://github.com/kornelski/cavif-rs>.

- Convert a JPEG file to AVIF:

`cavif {{path/to/file.jpg}}`

- Adjust the image quality (1-100) and convert a PNG file to AVIF:

`cavif --quality {{60}} {{path/to/file.png}}`

- Set the output location explicitly:

`cavif {{path/to/file.jpg}} --output {{path/to/file.avif}}`

- Overwrite the destination file if it already exists:

`cavif --overwrite {{path/to/file.jpg}}`

