---
id: windows.sfc
title: Sfc
desc: ''
updated: 1676881477682
created: 1676881477682
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sfc

> Scans the integrity of Windows system files.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/sfc>.

- Display information about the usage of the command:

`sfc`

- Scan all system files and, if possible, repair any problems:

`sfc /scannow`

- Scan all system files without attempting to repair any:

`sfc /verifyonly`

- Scan a specific file and, if possible, repair any problems:

`sfc /scanfile={{path\to\file}}`

- Scan a specific file without attempting to repair it:

`sfc /verifyfile={{path\to\file}}`

- When repairing offline, specify the boot directory:

`sfc /offbootdir={{path\to\directory}}`

- When repairing offline, specify the Windows directory:

`sfc /offwindir={{path\to\directory}}`

