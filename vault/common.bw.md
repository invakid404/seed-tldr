---
id: common.bw
title: Bw
desc: ''
updated: 1689531679517
created: 1689531679517
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bw

> Access and manage a Bitwarden vault.
> More information: <https://help.bitwarden.com/article/cli/>.

- Log in to a Bitwarden user account:

`bw login`

- Log out of a Bitwarden user account:

`bw logout`

- Search and display items from Bitwarden vault:

`bw list items --search {{github}}`

- Display a particular item from Bitwarden vault:

`bw get item {{github}}`

- Create a folder in Bitwarden vault:

`{{echo -n '{"name":"My Folder1"}' | base64}} | bw create folder`

