---
id: linux.toolbox-init-container
title: Toolbox Init Container
desc: ''
updated: 1665115822554
created: 1665115822554
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# toolbox init-container

> Initialize a running `toolbox` container.
> This command should not be executed by the user, and cannot be run on the host.
> More information: <https://manned.org/toolbox-init-container.1>.

- Initialize a running toolbox:

`toolbox init-container --gid {{gid}} --home {{home}} --home-link --media-link --mnt-link --monitor-host --shell {{shell}} --uid {{uid}} --user {{user}}`

