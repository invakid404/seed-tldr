---
id: common.aws-s3-presign
title: Aws S3 Presign
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
# aws s3 presign

> Generate pre-signed URLs for Amazon S3 objects.
> More information: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/s3/presign.html>.

- Generate a pre-signed URL for a specific S3 object that is valid for one hour:

`aws s3 presign s3://{{bucket_name}}/{{path/to/file}}`

- Generate a pre-signed URL valid for a specific lifetime:

`aws s3 presign s3://{{bucket_name}}/{{path/to/file}} --expires-in {{duration_in_seconds}}`

- Display help:

`aws s3 presign help`

