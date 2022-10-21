---
id: common.aws-s3-mv
title: Aws S3 Mv
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
# aws s3 mv

> Move local files or S3 objects to another location locally or in S3.
> More information: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/s3/mv.html>.

- Move a file from local to a specified bucket:

`aws s3 mv {{path/to/local_file}} s3://{{bucket_name}}/{{path/to/remote_file}}`

- Move a specific S3 object into another bucket:

`aws s3 mv s3://{{bucket_name1}}/{{path/to/file}} s3://{{bucket_name2}}/{{path/to/target}}`

- Move a specific S3 object into another bucket keeping the original name:

`aws s3 mv s3://{{bucket_name1}}/{{path/to/file}} s3://{{bucket_name2}}`

- Display help:

`aws s3 mv help`

