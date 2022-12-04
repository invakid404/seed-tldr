---
id: common.autopep8
title: Autopep8
desc: ''
updated: 1670142130868
created: 1670142130868
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# autopep8

> Format Python code according to the PEP 8 style guide.
> More information: <https://github.com/hhatto/autopep8>.

- Format a file to `stdout`, with a custom maximum line length:

`autopep8 {{path/to/file.py}} --max-line-length {{length}}`

- Format a file, displaying a diff of the changes:

`autopep8 --diff {{path/to/file}}`

- Format a file in-place and save the changes:

`autopep8 --in-place {{path/to/file.py}}`

- Recursively format all files in a directory in-place and save changes:

`autopep8 --in-place --recursive {{path/to/directory}}`

