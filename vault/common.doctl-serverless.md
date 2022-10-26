---
id: common.doctl-serverless
title: Doctl Serverless
desc: ''
updated: 1666750046306
created: 1666750046306
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# doctl serverless

> Manage serverless functions.
> More information: <https://docs.digitalocean.com/reference/doctl/reference/serverless/>.

- Connect local serverless support to a functions namespace:

`doctl serverless connect`

- Deploy a functions project to your functions namespace:

`doctl serverless deploy`

- Obtain metadata of a functions project:

`doctl serverless get-metadata`

- Provide information about serverless support:

`doctl serverless status`

