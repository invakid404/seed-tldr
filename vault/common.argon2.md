---
id: common.argon2
title: Argon2
desc: ''
updated: 1665895276196
created: 1665895276196
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# argon2

> Calculate Argon2 cryptographic hashes.
> More information: <https://github.com/P-H-C/phc-winner-argon2#command-line-utility>.

- Calculate a hash with a password and a salt with the default parameters:

`echo "{{password}}" | argon2 "{{salt_text}}"`

- Calculate a hash with the specified algorithm:

`echo "{{password}}" | argon2 "{{salt_text}}" -{{d|i|id}}`

- Display the output hash without additional information:

`echo "{{password}}" | argon2 "{{salt_text}}" -e`

- Calculate a hash with given iteration [t]imes, [m]emory usage, and [p]arallelism parameters:

`echo "{{password}}" | argon2 "{{salt_text}}" -t {{5}} -m {{20}} -p {{7}}`

