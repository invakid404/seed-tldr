---
id: linux.ctrlaltdel
title: Ctrlaltdel
desc: ''
updated: 1656591837612
created: 1656591837612
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ctrlaltdel

> Utility to control what happens when CTRL+ALT+DEL is pressed.
> More information: <https://manned.org/ctrlaltdel>.

- Get current setting:

`ctrlaltdel`

- Set CTRL+ALT+DEL to reboot immediately, without any preparation:

`sudo ctrlaltdel hard`

- Set CTRL+ALT+DEL to reboot "normally", giving processes a chance to exit first (send SIGINT to PID1):

`sudo ctrlaltdel soft`

