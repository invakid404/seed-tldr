---
id: common.license
title: License
desc: ''
updated: 1670310991819
created: 1670310991819
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# license

> Create license files for open-source projects.
> More information: <https://nishanths.github.io/license>.

- Print a license to `stdout`, using the defaults (auto-detected author name, and current year):

`license {{license_name}}`

- Generate a license and save it to a file:

`license -o {{path/to/file}} {{license_name}}`

- List all available licenses:

`license ls`

- Generate a license with custom author name and year:

`license --name {{author}} --year {{release_year}} {{license_name}}`

