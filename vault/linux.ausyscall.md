---
id: linux.ausyscall
title: Ausyscall
desc: ''
updated: 1665468173892
created: 1665468173892
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ausyscall

> Program that allows mapping syscall names and numbers.
> More information: <https://manned.org/ausyscall>.

- Display syscall number of a specific system call:

`ausyscall {{search_pattern}}`

- Display name of a specific system call number:

`ausyscall {{system_call_number}}`

- Display all system calls for a specific architecture:

`ausyscall {{architecture}} --dump`

