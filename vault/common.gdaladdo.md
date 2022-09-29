---
id: common.gdaladdo
title: Gdaladdo
desc: ''
updated: 1664469464899
created: 1664469464899
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gdaladdo

> Build overview images of raster datasets.
> More information: <https://gdal.org/programs/gdaladdo>.

- Build overview images of a raster dataset using the "average" [r]esampling method:

`gdaladdo -r average {{path/to/input.tif}}`

