---
id: windows.wsl
title: Wsl
desc: ''
updated: 1676881477687
created: 1676881477687
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wsl

> Manage the Windows Subsystem for Linux from the command-line.
> More information: <https://learn.microsoft.com/windows/wsl/reference>.

- Start a Linux shell (in the default distribution):

`wsl {{shell_command}}`

- Run a Linux command without using a shell:

`wsl --exec {{command}} {{command_arguments}}`

- Specify a particular distribution:

`wsl --distribution {{distribution}} {{shell_command}}`

- List available distributions:

`wsl --list`

- Export a distribution to a `.tar` file:

`wsl --export {{distribution}} {{path\to\distro_file.tar}}`

- Import a distribution from a `.tar` file:

`wsl --import {{distribution}} {{path\to\install_location}} {{path/to/distro_file.tar}}`

- Change the version of wsl used for the specified distribution:

`wsl --set-version {{distribution}} {{version}}`

- Shut down Windows Subsystem for Linux:

`wsl --shutdown`

