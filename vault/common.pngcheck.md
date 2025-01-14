---
id: common.pngcheck
title: Pngcheck
desc: ''
updated: 1670142130989
created: 1670142130989
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pngcheck

> Print detailed information about and verify PNG, JNG, and MNG files.
> More information: <http://www.libpng.org/pub/png/apps/pngcheck.html>.

- Print a summary for an image (width, height, and color depth):

`pngcheck {{image.png}}`

- Print information for an image with [c]olorized output:

`pngcheck -c {{image.png}}`

- Print [v]erbose information for an image:

`pngcheck -cvt {{image.png}}`

- Receive an image from `stdin` and display detailed information:

`cat {{path/to/image.png}} | pngcheck -cvt`

- [s]earch for PNGs within a specific file and display information about them:

`pngcheck -s {{image.png}}`

- Search for PNGs within another file and e[x]tract them:

`pngcheck -x {{image.png}}`

