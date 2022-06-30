---
id: linux.service
title: Service
desc: ''
updated: 1656591837652
created: 1656591837652
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# service

> Manage services by running init scripts.
> The full script path should be omitted (`/etc/init.d/` is assumed).
> More information: <https://manned.org/service>.

- List the name and status of all services:

`service --status-all`

- Start/Stop/Restart/Reload service (start/stop should always be available):

`service {{service_name}} {{start|stop|restart|reload}}`

- Do a full restart (runs script twice with start and stop):

`service {{service_name}} --full-restart`

- Show the current status of a service:

`service {{service_name}} status`

