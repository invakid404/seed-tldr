---
id: common.mh_lint
title: Mh_lint
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
# mh_lint

> Attempt to find bugs in MATLAB or Octave code.
> Please note that this tool is neither sound nor complete.
> More information: <https://misshit.org>.

- Check the current directory:

`mh_lint`

- Check a specific directory recursively:

`mh_lint {{path/to/directory}}`

- Check a MATLAB file:

`mh_lint {{path/to/file.m}}`

- Check an Octave file:

`mh_lint --octave {{path/to/file.m}}`

