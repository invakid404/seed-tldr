---
id: linux.pro
title: Pro
desc: ''
updated: 1683599668714
created: 1683599668714
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pro

> Manage Ubuntu Pro services.
> More information: <https://manpages.ubuntu.com/manpages/latest/en/man1/ubuntu-advantage.1.html>.

- Connect your system to the Ubuntu Pro support contract:

`sudo pro attach`

- Display the status of Ubuntu Pro services:

`pro status`

- Check if the system is affected by a specific vulnerability (and apply a fix if possible):

`pro fix {{CVE-number}}`

- Display the number of unsupported packages:

`pro security-status`

- List packages that are no longer available for download:

`pro security-status --unavailable`

- List third-party packages:

`pro security-status --thirdparty`

