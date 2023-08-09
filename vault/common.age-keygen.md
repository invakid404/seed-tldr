---
id: common.age-keygen
title: Age Keygen
desc: ''
updated: 1691590574725
created: 1691590574725
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# age-keygen

> Generate `age` key pairs.
> See `age` for how to encrypt/decrypt files.
> More information: <https://manned.org/age-keygen>.

- Generate a key pair, save it to an unencrypted file and print the public key to `stdout`:

`age-keygen --output {{path/to/file}}`

- Convert an identity to a recipient and print the public key to `stdout`:

`age-keygen -y {{path/to/file}}`

