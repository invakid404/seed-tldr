---
id: osx.aiac
title: Aiac
desc: ''
updated: 1675437527713
created: 1675437527713
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# aiac

> Use OpenAI to generate IaC configurations, utilities, queries and more.
> More information: <https://github.com/gofireflyio/aiac>.

- Generate Terraform for Azure storage account:

`aiac get terraform {{for an azure storage account}}`

- Generate a Dockerfile for nginx:

`aiac get dockerfile {{for a secured nginx}}`

- Generate GitHub action that applies Terraform:

`aiac get github action {{that plans and applies terraform}}`

- Generate a port scanner in Python:

`aiac get python {{code that scans all open ports in my network}}`

- Generate a MongoDB query:

`aiac get mongo {{query that aggregates all documents by created date}}`

