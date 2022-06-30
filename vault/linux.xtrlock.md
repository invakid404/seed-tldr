---
id: linux.xtrlock
title: Xtrlock
desc: ''
updated: 1656591837668
created: 1656591837668
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xtrlock

> Lock the X display until the user supplies their password.
> More information: <https://manned.org/xtrlock>.

- Lock the display and show a padlock instead of the cursor:

`xtrlock`

- Display a blank screen as well as the padlock cursor:

`xtrlock -b`

- Fork the xtrlock process and return immediately:

`xtrlock -f`

