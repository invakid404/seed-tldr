---
id: linux.telinit
title: Telinit
desc: ''
updated: 1666716359500
created: 1666716359500
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# telinit

> Change SysV runlevel.
> Since the concept SysV runlevels is obsolete the runlevel requests will be transparently translated into systemd unit activation requests.
> More information: <https://manned.org/telinit>.

- Power off the machine:

`telinit 0`

- Reboot the machine:

`telinit 6`

- Change SysV run level:

`telinit {{2|3|4|5}}`

- Change to rescue mode:

`telinit 1`

- Reload daemon configuration:

`telinit q`

- Do not send a wall message before reboot/power-off (6/0):

`telinit --no-wall {{value}}`

