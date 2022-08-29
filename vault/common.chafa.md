---
id: common.chafa
title: Chafa
desc: ''
updated: 1661758019115
created: 1661758019115
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# chafa

> Image printing in the terminal.
> See also: `catimg`, `pixterm`.
> More information: <https://hpjansson.org/chafa>.

- Render an image directly in the terminal:

`chafa {{path/to/file}}`

- Render an image with 24-bit [c]olor:

`chafa -c full {{path/to/file}}`

- Improve image rendering with small color palettes using dithering:

`chafa -c 16 --dither ordered {{path/to/file}}`

- Render an image, making it appear pixelated:

`chafa --symbols vhalf {{path/to/file}}`

- Render a monochrome image with only braille characters:

`chafa -c none --symbols braille {{path/to/file}}`

