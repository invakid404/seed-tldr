---
id: common.pngquant
title: Pngquant
desc: ''
updated: 1668856570309
created: 1668856570309
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pngquant

> PNG converter and lossy image compressor.
> More information: <https://pngquant.org/>.

- Compress a specific PNG as much as possible and write result to a new file:

`pngquant {{path/to/file.png}}`

- Compress a specific PNG and override original:

`pngquant --ext .png --force {{path/to/file.png}}`

- Try to compress a specific PNG with custom quality (skip if below the min value):

`pngquant --quality {{0-100}} {{path/to/file.png}}`

- Compress a specific PNG with the number of colors reduced to 64:

`pngquant {{64}} {{path/to/file.png}}`

- Compress a specific PNG and skip if the file is larger than the original:

`pngquant --skip-if-larger {{path/to/file.png}}`

- Compress a specific PNG and remove metadata:

`pngquant --strip {{path/to/file.png}}`

- Compress a specific PNG and save it to the given path:

`pngquant {{path/to/file.png}} --output {{path/to/file.png}}`

- Compress a specific PNG and show progress:

`pngquant --verbose {{path/to/file.png}}`

