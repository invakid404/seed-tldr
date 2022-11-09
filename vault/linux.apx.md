---
id: linux.apx
title: Apx
desc: ''
updated: 1667989445050
created: 1667989445050
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apx

> Package management utility for Vanilla OS.
> Install packages inside managed containers or directly inside the host.
> More information: <https://github.com/Vanilla-OS/apx>.

- Install a package in the system and initialize the container:

`sudo apx install --sys {{package}} && apx init`

- Install package(s) in the system or install AUR package(s) inside a container:

`sudo apx install --{{sys|aur}} {{package1 package2 ...}}`

- Run an installed package from AUR:

`apx --aur run {{package}}`

- Update the list of available packages in the system:

`sudo apx --sys update`

- Upgrade all installed packages in the system to their newest available version:

`sudo apx --sys upgrade`

- Remove package(s) in the system or from the AUR container:

`sudo apx --{{sys|aur}} remove {{package1 package2 ...}}`

- Enter the container to install packages using `apt` (Use `exit` inside the container to exit it):

`apx enter`

