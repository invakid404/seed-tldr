---
id: linux.mkhomedir_helper
title: Mkhomedir_helper
desc: ''
updated: 1691594336037
created: 1691594336037
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mkhomedir_helper

> Create the user's home directory after creating the user.
> More information: <https://manned.org/mkhomedir_helper>.

- Create a home directory for a user based on `/etc/skel` with umask 022:

`sudo mkhomedir_helper {{username}}`

- Create a home directory for a user based on `/etc/skel` with all permissions for owner (0) and read permission for group (3):

`sudo mkhomedir_helper {{username}} {{037}}`

- Create a home directory for a user based on a custom skeleton:

`sudo mkhomedir_helper {{username}} {{umask}} {{path/to/skeleton_directory}}`

