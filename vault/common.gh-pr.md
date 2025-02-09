---
id: common.gh-pr
title: Gh Pr
desc: ''
updated: 1689531679578
created: 1689531679578
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gh pr

> Manage GitHub pull requests.
> Some subcommands such as `gh pr create` have their own usage documentation.
> More information: <https://cli.github.com/manual/gh_pr>.

- Create a pull request:

`gh pr create`

- Check out a specific pull request locally:

`gh pr checkout {{pr_number}}`

- View the changes made in the pull request for the current branch:

`gh pr diff`

- Approve the pull request for the current branch:

`gh pr review --approve`

- Merge the pull request associated with the current branch interactively:

`gh pr merge`

- Edit a pull request interactively:

`gh pr edit`

- Edit the base branch of a pull request:

`gh pr edit --base {{branch_name}}`

- Check the status of the current repository's pull requests:

`gh pr status`

