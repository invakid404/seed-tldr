---
id: windows.ftp
title: Ftp
desc: ''
updated: 1676881477678
created: 1676881477678
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ftp

> Interactively transfer files between a local and remote FTP server.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/ftp>.

- Connect to a remote FTP server interactively:

`ftp {{host}}`

- Log in as an anonymous user:

`ftp -A {{host}}`

- Disable automatic login upon initial connection:

`ftp -n {{host}}`

- Run a file containing a list of FTP commands:

`ftp -s:{{path\to\file}} {{host}}`

- Download multiple files (glob expression):

`mget {{*.png}}`

- Upload multiple files (glob expression):

`mput {{*.zip}}`

- Delete multiple files on the remote server:

`mdelete {{*.txt}}`

- Display detailed help:

`ftp --help`

