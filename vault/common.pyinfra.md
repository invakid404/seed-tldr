---
id: common.pyinfra
title: Pyinfra
desc: ''
updated: 1658488724524
created: 1658488724524
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pyinfra

> Automates infrastructure at a large scale.
> More information: <https://docs.pyinfra.com>.

- Execute a command over SSH:

`pyinfra {{target_ip_address}} exec -- {{command_name_and_arguments}}`

- Execute contents of a deploy file on a list of targets:

`pyinfra {{path/to/target_list.py}} {{path/to/deploy.py}}`

- Execute commands on locally:

`pyinfra @local {{path/to/deploy.py}}`

- Execute commands over Docker:

`pyinfra @docker/{{container}} {{path/to/deploy.py}}`

