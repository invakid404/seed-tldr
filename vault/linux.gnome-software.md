---
id: linux.gnome-software
title: Gnome Software
desc: ''
updated: 1656591837625
created: 1656591837625
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gnome-software

> Add and remove applications and update your system.
> More information: <https://apps.gnome.org/app/org.gnome.Software/>.

- Launch the GNOME Software GUI if it's not already running:

`gnome-software`

- Launch the GNOME Software GUI if it's not open, and navigate to the specified page:

`gnome-software --mode {{updates|updated|installed|overview}}`

- Launch the GNOME Software GUI if it's not open, and view the specified package:

`gnome-software --details {{package_name}}`

- Display the version:

`gnome-software --version`
