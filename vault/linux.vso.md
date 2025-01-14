---
id: linux.vso
title: Vso
desc: ''
updated: 1694283497160
created: 1694283497160
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vso

> Package manager, system updater and a task automator for Vanilla OS.
> More information: <https://github.com/Vanilla-OS/vanilla-system-operator>.

- Check for system updates to the host system:

`vso sys-upgrade check`

- Upgrade the host system now:

`vso sys-upgrade upgrade --now`

- Initialize the Pico subsystem (used for package management):

`vso pico-init`

- Install applications inside the subsystem:

`vso install {{package1 package2 ...}}`

- Remove applications from the subsystem:

`vso remove {{package1 package2 ...}}`

- Enter the subsystem's shell:

`vso shell`

- Run an application from the subsystem:

`vso run {{package}}`

- Display VSO configuration:

`vso config show`

