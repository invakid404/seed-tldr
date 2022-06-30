---
id: common.visudo
title: Visudo
desc: ''
updated: 1656591837591
created: 1656591837591
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
> More information: <https://www.sudo.ws/man/1.8.13/visudo.man.html>.

- Edit the sudoers file:

`sudo visudo`

- Check the sudoers file for errors:

`sudo visudo -c`

- Edit the sudoers file using a specific editor:

`sudo EDITOR={{editor}} visudo`

- Display version information:

`visudo --version`

