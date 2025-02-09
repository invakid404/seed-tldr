---
id: linux.nmcli-general
title: Nmcli General
desc: ''
updated: 1659184494743
created: 1659184494743
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nmcli general

> Manage general settings of NetworkManager.
> This subcommand can also be called with `nmcli g`.
> More information: <https://networkmanager.dev/docs/api/latest/nmcli.html>.

- Show the general status of NetworkManager:

`nmcli general`

- Show the hostname of the current device:

`nmcli general hostname`

- Change the hostname of the current device:

`sudo nmcli general hostname {{new_hostname}}`

- Show the permissions of NetworkManager:

`nmcli general permissions`

- Show the current logging level and domains:

`nmcli general logging`

- Set the logging level and/or domains (see `man NetworkManager.conf` for all available domains):

`nmcli general logging level {{INFO|OFF|ERR|WARN|DEBUG|TRACE}} domain {{domain_1,domain_2,...}}`

