---
id: linux.dropbearconvert
title: Dropbearconvert
desc: ''
updated: 1679368661846
created: 1679368661846
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dropbearconvert

> Convert between Dropbear and OpenSSH private key formats.
> More information: <https://manned.org/dropbearconvert.1>.

- Convert an OpenSSH private key to the Dropbear format:

`dropbearconvert openssh dropbear {{path/to/input_key}} {{path/to/output_key}}`

- Convert a Dropbear private key to the OpenSSH format:

`dropbearconvert dropbear openssh {{path/to/input_key}} {{path/to/output_key}}`

