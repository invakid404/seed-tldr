---
id: osx.caffeinate
title: Caffeinate
desc: ''
updated: 1695485908939
created: 1695485908939
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# caffeinate

> Prevent macOS from sleeping.
> More information: <https://ss64.com/osx/caffeinate.html>.

- Prevent from sleeping for 1 hour (3600 seconds):

`caffeinate -u -t {{3600}}`

- Prevent from sleeping until a command completes:

`caffeinate -s "{{command}}"`

- Prevent from sleeping until a process with the specified PID completes:

`caffeinate -w {{pid}}`

- Prevent from sleeping (use `Ctrl + C` to exit):

`caffeinate -i`

- Prevent disk from sleeping (use `Ctrl + C` to exit):

`caffeinate -m`

