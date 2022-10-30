---
id: linux.logrotate
title: Logrotate
desc: ''
updated: 1667133702836
created: 1667133702836
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# logrotate

> Rotates, compresses, and mails system logs.
> More information: <https://manned.org/logrotate>.

- Trigger a run manually:

`logrotate {{path/to/logrotate.conf}} --force`

- Run using a specific command to mail reports:

`logrotate {{path/to/logrotate.conf}} --mail {{/usr/bin/mail_command}}`

- Run without using a state (lock) file:

`logrotate {{path/to/logrotate.conf}} --state /dev/null`

- Run and skip the state (lock) file check:

`logrotate {{path/to/logrotate.conf}} --skip-state-lock`

- Tell `logrotate` to log verbose output into the log file:

`logrotate {{path/to/logrotate.conf}} --log {{path/to/log_file}}`

