---
id: windows.repair-bde
title: Repair Bde
desc: ''
updated: 1664897374265
created: 1664897374266
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# repair-bde

> Attempt to repair or decrypt a damaged BitLocker-encrypted volume.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/repair-bde>.

- Attempt to repair a specified volume:

`repair-bde {{C:}}`

- Attempt to repair a specified volume and output to another volume:

`repair-bde {{C:}} {{D:}}`

- Attempt to repair a specified volume using the provided recovery key file:

`repair-bde {{C:}} -RecoveryKey {{path/to/file.bek}}`

- Attempt to repair a specified volume using the provided numerical recovery password:

`repair-bde {{C:}} -RecoveryPassword {{password}}`

- Attempt to repair a specified volume using the provided password:

`repair-bde {{C:}} -Password {{password}}`

- Attempt to repair a specified volume using the provided key package:

`repair-bde {{C:}} -KeyPackage {{path/to/directory}}`

- Log all output to a specific file:

`repair-bde {{C:}} -LogFile {{path/to/file}}`

- Display all available options:

`repair-bde /?`

