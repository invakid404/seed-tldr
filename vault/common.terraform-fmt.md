---
id: common.terraform-fmt
title: Terraform Fmt
desc: ''
updated: 1670142131015
created: 1670142131015
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# terraform fmt

> Format configuration according to Terraform language style conventions.
> More information: <https://www.terraform.io/docs/commands/fmt.html>.

- Format the configuration in the current directory:

`terraform fmt`

- Format the configuration in the current directory and subdirectories:

`terraform fmt -recursive`

- Display diffs of formatting changes:

`terraform fmt -diff`

- Do not list files that were formatted to `stdout`:

`terraform fmt -list=false`

