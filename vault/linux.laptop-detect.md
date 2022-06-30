---
id: linux.laptop-detect
title: Laptop Detect
desc: ''
updated: 1656591837630
created: 1656591837630
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# laptop-detect

> Attempt to determine if the script is running on a laptop or desktop.
> More information: <https://gitlab.com/debiants/laptop-detect>.

- Return an exit status of 0 if the current device is likely a laptop, else returns 1:

`laptop-detect`

- Print the type of device that the current system is detected as:

`laptop-detect --verbose`

- Display the version:

`laptop-detect --version`

