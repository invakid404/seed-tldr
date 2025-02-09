---
id: common.gh
title: Gh
desc: ''
updated: 1689531679579
created: 1689531679579
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gh

> Work seamlessly with GitHub.
> Some subcommands such as `gh config` have their own usage documentation.
> More information: <https://cli.github.com/>.

- Clone a GitHub repository locally:

`gh repo clone {{owner}}/{{repository}}`

- Create a new issue:

`gh issue create`

- View and filter the open issues of the current repository:

`gh issue list`

- View an issue in the default web browser:

`gh issue view --web {{issue_number}}`

- Create a pull request:

`gh pr create`

- View a pull request in the default web browser:

`gh pr view --web {{pr_number}}`

- Check out a specific pull request locally:

`gh pr checkout {{pr_number}}`

- Check the status of a repository's pull requests:

`gh pr status`

