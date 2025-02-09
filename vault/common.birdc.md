---
id: common.birdc
title: Birdc
desc: ''
updated: 1689255122129
created: 1689255122129
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# birdc

> Bird remote control.
> Command tool to retrieve information like routes from bird and perform configurations during runtime.
> More information: <https://bird.network.cz/>.

- Open the remote control console:

`birdc`

- Reload the configuration without restarting Bird:

`birdc configure`

- Show the current status of Bird:

`birdc show status`

- Show all configured protocols:

`birdc show protocols`

- Show all details about a protocol:

`birdc show protocols {{upstream1}} all`

- Show all routes that contain a specific AS number:

`birdc "show route where bgp_path ~ [{{4242120045}}]"`

- Show all best routes:

`birdc show route primary`

- Show all details of all routes from a given prefix:

`birdc show route for {{fd00:/8}} all`

