---
id: common.git-remote
title: Git Remote
desc: ''
updated: 1664769727612
created: 1664769727612
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git remote

> Manage set of tracked repositories ("remotes").
> More information: <https://git-scm.com/docs/git-remote>.

- Show a list of existing remotes, their names and URL:

`git remote -v`

- Show information about a remote:

`git remote show {{remote_name}}`

- Add a remote:

`git remote add {{remote_name}} {{remote_url}}`

- Change the URL of a remote (use `--add` to keep the existing URL):

`git remote set-url {{remote_name}} {{new_url}}`

- Show the URL of a remote:

`git remote get-url {{remote_name}}`

- Remove a remote:

`git remote remove {{remote_name}}`

- Rename a remote:

`git remote rename {{old_name}} {{new_name}}`

