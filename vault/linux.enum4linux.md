---
id: linux.enum4linux
title: Enum4linux
desc: ''
updated: 1666188108126
created: 1666188108126
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# enum4linux

> Tool for enumerating Windows and Samba information from remote systems.
> More information: <https://labs.portcullis.co.uk/tools/enum4linux/>.

- Try to enumerate using all methods:

`enum4linux -a {{remote_host}}`

- Enumerate using given login credentials:

`enum4linux -u {{user_name}} -p {{password}} {{remote_host}}`

- List usernames from a given host:

`enum4linux -U {{remote_host}}`

- List shares:

`enum4linux -S {{remote_host}}`

- Get OS information:

`enum4linux -o {{remote_host}}`

