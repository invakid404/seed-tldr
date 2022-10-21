---
id: common.aws-s3-rm
title: Aws S3 Rm
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
# aws s3 rm

> Delete S3 objects.
> More information: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/s3/rm.html>.

- Delete a specific S3 object:

`aws s3 rm s3://{{bucket_name}}/{{path/to/file}}`

- Preview the deletion of a specific S3 object without deleting it (dry-run):

`aws s3 rm s3://{{bucket_name}}/{{path/to/file}} --dryrun`

- Delete an object from a specific S3 access point:

`aws s3 rm s3://arn:aws:s3:{{region}}:{{account_id}}:{{access_point}}/{{access_point_name}}/{{object_key}}`

- Display help:

`aws s3 rm help`

