---
id: common.visudo
title: Visudo
desc: ''
updated: 1658926036848
created: 1658926036848
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# visudo

> Safely edit the sudoers file.
> More information: <https://www.sudo.ws/docs/man/visudo.man>.

- Edit the sudoers file:

`sudo visudo`

- Check the sudoers file for errors:

`sudo visudo -c`

- Edit the sudoers file using a specific editor:

`sudo EDITOR={{editor}} visudo`

- Display version information:

`visudo --version`

