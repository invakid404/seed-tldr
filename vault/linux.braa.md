---
id: linux.braa
title: Braa
desc: ''
updated: 1670310991907
created: 1670310991907
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# braa

> Ultra-fast mass SNMP scanner allowing multiple hosts simultaneously.
> More information: <https://github.com/mteg/braa>.

- Walk the SNMP tree of host with public string querying all OIDs under `.1.3.6`:

`braa public@{{ip}}:{{.1.3.6.*}}`

- Query the whole subnet `ip_range` for `system.sysLocation.0`:

`braa public@{{ip_range}}:{{.1.3.6.1.2.1.1.6.0}}`

- Attempt to set the value of `system.sysLocation.0` to a specific workgroup:

`braa private@{{ip}}:{{.1.3.6.1.2.1.1.6.0}}=s'{{workgroup}}'`

