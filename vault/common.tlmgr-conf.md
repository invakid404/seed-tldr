---
id: common.tlmgr-conf
title: Tlmgr Conf
desc: ''
updated: 1659361609909
created: 1659361609909
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tlmgr conf

> Manage the TeX Live configuration.
> More information: <https://www.tug.org/texlive/tlmgr.html>.

- Show the current TeX Live configuration:

`tlmgr conf`

- Show the current `texmf`, `tlmgr`, or `updmap` configuration:

`tlmgr conf {{texmf|tlmgr|updmap}}`

- Show only a specific configuration option:

`tlmgr conf {{texmf|tlmgr|updmap}} {{configuration_key}}`

- Set a specific configuration option:

`tlmgr conf {{texmf|tlmgr|updmap}} {{configuration_key}} {{value}}`

- Delete a specific configuration option:

`tlmgr conf {{texmf|tlmgr|updmap}} --delete {{configuration_key}}`

- Disable the execution of system calls via `\write18`:

`tlmgr conf texmf {{shell_escape}} {{0}}`

- Show all additional `texmf` trees:

`tlmgr conf auxtrees show`

