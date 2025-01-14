---
id: common.datashader_cli
title: Datashader_cli
desc: ''
updated: 1687526782331
created: 1687526782331
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# datashader_cli

> Quick visualization of large datasets using CLI based on datashader.
> More information: <https://github.com/wybert/datashader-cli>.

- Create a shaded scatter plot of points and save it to a png file and set the background color:

`datashader_cli points {{path/to/input.parquet}} --x {{pickup_x}} --y {{pickup_y}} {{path/to/output.png}} --background {{black|white|#rrggbb}}`

- Visualize the geospatial data (supports Geoparquet, shapefile, geojson, geopackage, etc.):

`datashader_cli points {{path/to/input_data.geo.parquet}} {{path/to/output_data.png}} --geo true`

- Use matplotlib to render the image:

`datashader_cli points {{path/to/input_data.geo.parquet}} {{path/to/output_data.png}} --geo {{true}} --matplotlib true`

