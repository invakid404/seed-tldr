---
id: common.certutil
title: Certutil
desc: ''
updated: 1664901556943
created: 1664901556943
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# certutil

> Manage keys and certificates in both NSS databases and other NSS tokens.
> More information: <https://manned.org/certutil>.

- Create a new certificate database:

`certutil -N -d .`

- List all certificates in a database:

`certutil -L -d .`

- List all private keys in a database:

`certutil -K -d . -f {{path/to/pwdfile.txt}}`

- Import the signed certificate into the requesters database:

`certutil -A -n "{{Server-cert}}" -t ",," -i {{path/to/file.crt}} -d .`

- Add subject alternative names to a given certificate:

`certutil -S -f {{path/to/pwdfile.txt}} -d . -t ",," -c "{{Server-Cert}}" -n "{{server1}}" -g {{2048}} -s "CN={{testuser1}},O={{testrelm.test}}"`

