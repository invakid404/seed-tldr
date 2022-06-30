---
id: common.glab
title: Glab
desc: ''
updated: 1656591837486
created: 1656591837486
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# glab

> Work seamlessly with GitLab from the command-line.
> Some subcommands such as `glab config` have their own usage documentation.
> More information: <https://github.com/profclems/glab>.

- Clone a GitLab repository locally:

`glab repo clone {{owner}}/{{repository}}`

- Create a new issue:

`glab issue create`

- View and filter the open issues of the current repository:

`glab issue list`

- View an issue in the default browser:

`glab issue view --web {{issue_number}}`

- Create a merge request:

`glab mr create`

- View a pull request in the default web browser:

`glab mr view --web {{pr_number}}`

- Check out a specific pull request locally:

`glab mr checkout {{pr_number}}`

