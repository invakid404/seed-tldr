---
id: linux.lsns
title: Lsns
desc: ''
updated: 1656591837633
created: 1656591837633
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lsns

> List information about all namespaces or about the specified namespace.
> More information: <https://man7.org/linux/man-pages/man8/lsns.8.html>.

- List all namespaces:

`lsns`

- List namespaces in JSON format:

`lsns --json`

- List namespaces associated with {{pid}}:

`lsns --task {{pid}}`

- List the specified type of namespaces only:

`lsns --type <mnt|net|ipc|user|pid|uts|cgroup|time>`

- List namespaces, only showing the namespace ID, type, PID, and command:

`lsns --output NS,TYPE,PID,COMMAND`

