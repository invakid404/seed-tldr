---
id: common.aws-sts
title: Aws Sts
desc: ''
updated: 1665167653005
created: 1665167653005
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# aws sts

> Security Token Service (STS) allows to request temporary credentials for (IAM) users or federated users.
> More information: <https://docs.aws.amazon.com/cli/latest/reference/sts/>.

- Get temporary security credentials to access specific AWS resources:

`aws sts assume-role --role-arn {{aws_role_arn}}`

- Get an IAM user or role whose credentials are used to call the operation:

`aws sts get-caller-identity`

