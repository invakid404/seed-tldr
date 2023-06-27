---
id: common.supervisord
title: Supervisord
desc: ''
updated: 1687904232913
created: 1687904232913
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# supervisord

> Supervisor is a client/server system for controlling some processes on UNIX-like operating systems.
> Supervisord is the server part of supervisor; it is primarily managed via a configuration file.
> More information: <http://supervisord.org>.

- Start `supervisord` with specified configuration file:

`supervisord -c {{path/to/file}}`

- Run supervisord in the foreground:

`supervisord -n`

