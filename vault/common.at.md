---
id: common.at
title: At
desc: ''
updated: 1691562058908
created: 1691562058908
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# at

> Execute commands once at a later time.
> Service atd (or atrun) should be running for the actual executions.
> More information: <https://manned.org/at>.

- Execute commands from `stdin` in 5 minutes (press `Ctrl + D` when done):

`at now + 5 minutes`

- Execute a command from `stdin` at 10:00 AM today:

`echo "{{./make_db_backup.sh}}" | at 1000`

- Execute commands from a given file next Tuesday:

`at -f {{path/to/file}} 9:30 PM Tue`

