---
id: common.ogrinfo
title: Ogrinfo
desc: ''
updated: 1656591837535
created: 1656591837535
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ogrinfo

> List information about an OGR-supported data source.
> More information: <https://gdal.org/programs/ogrinfo.html>.

- List supported formats:

`ogrinfo --formats`

- List layers of a data source:

`ogrinfo {{path/to/input.gpkg}}`

- Get detailed information about a specific layer of a data source:

`ogrinfo {{path/to/input.gpkg}} {{layer_name}}`

- Show summary information about a specific layer of a data source:

`ogrinfo -so {{path/to/input.gpkg}} {{layer_name}}`

- Show summary of all layers of the data source:

`ogrinfo -so -al {{path/to/input.gpkg}}`

- Show detailed information of features matching a condition:

`ogrinfo -where '{{attribute_name > 42}}' {{path/to/input.gpkg}} {{layer_name}}`

- Update a layer in the data source with SQL:

`ogrinfo {{path/to/input.geojson}} -dialect SQLite -sql "{{UPDATE input SET attribute_name = 'foo'}}"`

