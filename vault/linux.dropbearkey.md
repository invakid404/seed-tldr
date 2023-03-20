---
id: linux.dropbearkey
title: Dropbearkey
desc: ''
updated: 1679289431326
created: 1679289431326
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dropbearkey

> Generate SSH keys in Dropbear format.
> More information: <https://manned.org/dropbearkey.1>.

- Generate an SSH key of [t]ype ed25519 and write it to key [f]ile:

`dropbearkey -t {{ed25519}} -f {{path/to/key_file}}`

- Generate an SSH key of [t]ype ecdsa and write it to key [f]ile:

`dropbearkey -t {{ecdsa}} -f {{path/to/key_file}}`

- Generate an SSH key of [t]ype RSA with 4096-bit key [s]ize and write it to key [f]ile:

`dropbearkey -t {{rsa}} -s {{4096}} -f {{path/to/key_file}}`

- Print the private key fingerprint and public key in key [f]ile:

`dropbearkey -y -f {{path/to/key_file}}`

