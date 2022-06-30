---
id: common.gdal2tiles-py
title: Gdal2tiles Py
desc: ''
updated: 1656591837468
created: 1656591837468
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gdal2tiles.py

> Generate TMS or XYZ tiles for a raster dataset.
> More information: <https://gdal.org/programs/gdal2tiles.html>.

- Generate TMS tiles for the zoom levels 2-5 of a raster dataset:

`gdal2tiles.py --zoom={{2-5}} {{path/to/input.tif}} {{path/to/output_directory}}`

- Generate XYZ tiles for the zoom levels 2-5 of a raster dataset:

`gdal2tiles.py --zoom={{2-5}} --xyz {{path/to/input.tif}} {{path/to/output_directory}}`

