---
id: linux.mokutil
title: Mokutil
desc: ''
updated: 1684174823788
created: 1684174823788
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mokutil

> Configure Secure Boot Machine Owner Keys (MOK).
> Some operations, such as enabling and disabling Secure Boot or enrolling keys require a reboot.
> More information: <https://github.com/lcp/mokutil>.

- Show if Secure Boot is enabled:

`mokutil --sb-state`

- Enable Secure Boot:

`mokutil --enable-validation`

- Disable Secure Boot:

`mokutil --disable-validation`

- List enrolled keys:

`mokutil --list-enrolled`

- Enroll a new key:

`mokutil --import {{path/to/key.der}}`

- List the keys to be enrolled:

`mokutil --list-new`

- Set shim verbosity:

`mokutil --set-verbosity true`

