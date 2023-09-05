---
id: common.stressapptest
title: Stressapptest
desc: ''
updated: 1693926996698
created: 1693926996698
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# stressapptest

> Userspace memory and IO test.
> More information: <https://github.com/stressapptest/stressapptest>.

- Test the given amount of memory (in Megabytes):

`stressapptest -M {{memory}}`

- Test memory as well as I/O for the given file:

`stressapptest -M {{memory}} -f {{path/to/file}}`

- Test specifying the verbosity level, where 0=lowest, 20=highest, 8=default:

`stressapptest -M {{memory}} -v {{level}}`

