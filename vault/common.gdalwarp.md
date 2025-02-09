---
id: common.gdalwarp
title: Gdalwarp
desc: ''
updated: 1659447754155
created: 1659447754155
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gdalwarp

> Image reprojection and warping utility.
> More information: <https://gdal.org/programs/gdalwarp>.

- Reproject a raster dataset:

`gdalwarp -t_srs {{EPSG:4326}} {{path/to/input.tif}} {{path/to/output.tif}}`

- Crop a raster dataset by using specific coordinates:

`gdalwarp -te {{min_x}} {{min_y}} {{max_x}} {{max_y}} -te_srs {{EPSG:4326}} {{path/to/input.tif}} {{path/to/output.tif}}`

- Crop a raster dataset using a vector layer:

`gdalwarp -cutline {{path/to/area_to_cut.geojson}} -crop_to_cutline {{path/to/input.tif}} {{path/to/output.tif}}`

