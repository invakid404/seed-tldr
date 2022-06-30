---
id: common.mh_metric
title: Mh_metric
desc: ''
updated: 1656591837522
created: 1656591837522
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mh_metric

> Calculate and enforce code metrics for MATLAB or Octave code.
> More information: <https://misshit.org>.

- Print the code metrics for the specified files:

`mh_metric {{path/to/file1.m path/to/file2.m ...}}`

- Print the code metrics for the specified Octave files:

`mh_metric --octave {{path/to/file1.m path/to/file2.m ...}}`

- Print the code metrics for the specified directory recursively:

`mh_metric {{path/to/directory}}`

- Print the code metrics for the current directory:

`mh_metric`

- Print the code metrics report in HTML or JSON format:

`mh_metric --{{html|json}} {{path/to/output_file}}`

