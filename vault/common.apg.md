---
id: common.apg
title: Apg
desc: ''
updated: 1684746997312
created: 1684746997312
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apg

> Creates arbitrarily complex random passwords.
> More information: <https://manned.org/apg>.

- Create random passwords (default password length is 8):

`apg`

- Create a password with at least 1 symbol (S), 1 number (N), 1 uppercase (C), 1 lowercase (L):

`apg -M SNCL`

- Create a password with 16 characters:

`apg -m {{16}}`

- Create a password with maximum length of 16:

`apg -x {{16}}`

- Create a password that doesn't appear in a dictionary (the dictionary file has to be provided):

`apg -r {{path/to/dictionary_file}}`

