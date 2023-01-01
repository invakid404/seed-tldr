---
id: common.afconvert
title: Afconvert
desc: ''
updated: 1672550129040
created: 1672550129040
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# afconvert

> Convert between AFF and raw file formats.
> More information: <https://manned.org/afconvert.1>.

- Use a specific extension (default: `aff`):

`afconvert -a {{extension}} {{path/to/input_file}} {{path/to/output_file1 path/to/output_file2 ...}}`

- Use a specific compression level (default: `7`):

`afconvert -X{{0..7}} {{path/to/input_file}} {{path/to/output_file1 path/to/output_file2 ...}}`

