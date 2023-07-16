---
id: common.gh-secret
title: Gh Secret
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
# gh secret

> Manage GitHub secrets.
> More information: <https://cli.github.com/manual/gh_secret>.

- List secret keys for the current repository:

`gh secret list`

- List secret keys for a specific organization:

`gh secret list --org {{organization}}`

- List secret keys for a specific repository:

`gh secret list --repo {{owner}}/{{repository}}`

- Set a secret for the current repository (user will be prompted for the value):

`gh secret set {{name}}`

- Set a secret from a file for the current repository:

`gh secret set {{name}} < {{path/to/file}}`

- Set an organization secret for specific repositories:

`gh secret set {{name}} --org {{organization}} --repos {{repository1,repository2}}`

- Remove a secret for the current repository:

`gh secret remove {{name}}`

- Remove a secret for a specific organization:

`gh secret remove {{name}} --org {{organization}}`

