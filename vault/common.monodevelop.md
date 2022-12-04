---
id: common.monodevelop
title: Monodevelop
desc: ''
updated: 1670142130964
created: 1670142130964
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# monodevelop

> Cross platform IDE for C#, F# and more.
> More information: <https://www.monodevelop.com/>.

- Start MonoDevelop:

`monodevelop`

- Open a specific file:

`monodevelop {{path/to/file}}`

- Open a specific file with the caret at a specific position:

`monodevelop {{path/to/file}};{{line_number}};{{column_number}}`

- Force opening a new window instead of switching to an existing one:

`monodevelop --new-window`

- Disable redirection of `stdout` and `stderr` to a log file:

`monodevelop --no-redirect`

- Enable performance monitoring:

`monodevelop --perf-log`

