---
id: common.gdal_contour
title: Gdal_contour
desc: ''
updated: 1658733644796
created: 1658733644796
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gdal_contour

> Create contour lines and polygons from a digital elevation model.
> More information: <https://gdal.org/programs/gdal_contour.html>.

- Create a vector dataset with contour lines spread over an 100-meter [i]nterval while [a]ttributing the elevation property as "ele":

`gdal_contour -a {{ele}} -i {{100.0}} {{path/to/input.tif}} {{path/to/output.gpkg}}`

- Create a vector dataset with [p]olygons spread over an 100-meter [i]nterval:

`gdal_contour -i {{100.0}} -p {{path/to/input.tif}} {{path/to/output.gpkg}}`

