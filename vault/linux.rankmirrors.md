---
id: linux.rankmirrors
title: Rankmirrors
desc: ''
updated: 1670142131085
created: 1670142131085
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rankmirrors

> Rank a list of Pacman mirrors by connection and opening speed.
> Writes the new mirrorlist to `stdout`.
> More information: <https://wiki.archlinux.org/index.php/mirrors>.

- Rank a mirror list:

`rankmirrors {{/etc/pacman.d/mirrorlist}}`

- Output only a given number of the top ranking servers:

`rankmirrors -n {{number}} {{/etc/pacman.d/mirrorlist}}`

- Be verbose when generating the mirrorlist:

`rankmirrors -v {{/etc/pacman.d/mirrorlist}}`

- Test only a specific URL:

`rankmirrors --url {{url}}`

- Output only the response times instead of a full mirrorlist:

`rankmirrors --times {{/etc/pacman.d/mirrorlist}}`

