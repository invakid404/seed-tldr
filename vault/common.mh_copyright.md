---
id: common.mh_copyright
title: Mh_copyright
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
# mh_copyright

> Adjust copyright headers for MATLAB or Octave code.
> More information: <https://misshit.org>.

- Update the year (range) to include the current year for the specified files:

`mh_copyright --primary-entity="{{entity}}" --update-year {{path/to/file_or_directory1.m path/to/file_or_director2.m ...}}`

- Update the year (range) to include the current year for all files:

`mh_copyright --primary-entity="{{entity}}" --update-year`

