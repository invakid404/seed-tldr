---
id: common.sshpass
title: Sshpass
desc: ''
updated: 1670145407066
created: 1670145407066
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sshpass

> An ssh password provider.
> It works by creating a TTY, feeding the password into it, and then redirecting `stdin` to the ssh session.
> More information: <https://manned.org/sshpass>.

- Connect to a remote server using a password supplied on a file descriptor (in this case, `stdin`):

`sshpass -d {{0}} ssh {{user}}@{{hostname}}`

- Connect to a remote server with the password supplied as an option, and automatically accept unknown ssh keys:

`sshpass -p {{password}} ssh -o StrictHostKeyChecking=no {{user}}@{{hostname}}`

- Connect to a remote server using the first line of a file as the password, automatically accept unknown ssh keys, and launch a command:

`sshpass -f {{path/to/file}} ssh -o StrictHostKeyChecking=no {{user}}@{{hostname}} "{{command}}"`

