---
id: common.surge
title: Surge
desc: ''
updated: 1689531679731
created: 1689531679731
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# surge

> Simple web publishing.
> More information: <https://surge.sh>.

- Upload a new site to surge.sh:

`surge {{path/to/my_project}}`

- Deploy site to custom domain (note that the DNS records must point to the surge.sh subdomain):

`surge {{path/to/my_project}} {{my_custom_domain.com}}`

- List your surge projects:

`surge list`

- Remove a project:

`surge teardown {{my_custom_domain.com}}`

