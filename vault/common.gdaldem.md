---
id: common.gdaldem
title: Gdaldem
desc: ''
updated: 1662290273050
created: 1662290273050
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gdaldem

> Tool to analyze and visualize digital elevation models (DEM).
> More information: <https://gdal.org/programs/gdaldem>.

- Compute the hillshade of a DEM:

`gdaldem hillshade {{path/to/input.tif}} {{path/to/output.tif}}`

- Compute the slope of a DEM:

`gdaldem slope {{path/to/input.tif}} {{path/to/output.tif}}`

- Compute the aspect of a DEM:

`gdaldem aspect {{path/to/input.tif}} {{path/to/output.tif}}`

