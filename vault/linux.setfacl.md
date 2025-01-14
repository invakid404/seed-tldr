---
id: linux.setfacl
title: Setfacl
desc: ''
updated: 1656591837652
created: 1656591837652
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# setfacl

> Set file access control lists (ACL).
> More information: <https://manned.org/setfacl>.

- Modify ACL of a file for user with read and write access:

`setfacl -m u:{{username}}:rw {{file}}`

- Modify default ACL of a file for all users:

`setfacl -d -m u::rw {{file}}`

- Remove ACL of a file for a user:

`setfacl -x u:{{username}} {{file}}`

- Remove all ACL entries of a file:

`setfacl -b {{file}}`

