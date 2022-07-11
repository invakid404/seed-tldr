---
id: common.tlmgr-key
title: Tlmgr Key
desc: ''
updated: 1657538207552
created: 1657538207552
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tlmgr key

> Manage GPG keys used to verify TeX Live databases.
> More information: <https://www.tug.org/texlive/tlmgr.html>.

- List all keys for TeX Live:

`tlmgr key list`

- Add a key from a specific file:

`sudo tlmgr key add {{path/to/key.gpg}}`

- Add a key from stdin:

`cat {{path/to/key.gpg}} | sudo tlmgr key add -`

- Remove a specific key by its ID:

`sudo tlmgr key remove {{key_id}}`

