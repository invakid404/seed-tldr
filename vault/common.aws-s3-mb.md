---
id: common.aws-s3-mb
title: Aws S3 Mb
desc: ''
updated: 1666370345679
created: 1666370345679
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# aws s3 mb

> Create S3 buckets.
> More information: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/s3/mb.html>.

- Create an S3 bucket:

`aws s3 mb s3://{{bucket_name}}`

- Create an S3 bucket in a specific region:

`aws s3 mb s3://{{bucket_name}} --region {{region}}`

- Display help:

`aws s3 mb help`

