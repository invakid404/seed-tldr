---
id: linux.deluser
title: Deluser
desc: ''
updated: 1657538207583
created: 1657538207583
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# deluser

> Delete a user from the system.
> More information: <https://manpages.debian.org/latest/adduser/deluser.html>.

- Remove a user:

`sudo deluser {{username}}`

- Remove a user and their home directory:

`sudo deluser --remove-home {{username}}`

- Remove a user and their home, but backup their files into a `.tar.gz` file in the specified directory:

`sudo deluser --backup-to {{path/to/backup_directory}} --remove-home {{username}}`

- Remove a user, and all files owned by them:

`sudo deluser --remove-all-files {{username}}`

