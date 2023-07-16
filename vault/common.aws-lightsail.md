---
id: common.aws-lightsail
title: Aws Lightsail
desc: ''
updated: 1689531679495
created: 1689531679495
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# aws lightsail

> Manage Amazon Lightsail resources.
> More information: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/lightsail/index.html>.

- List all virtual private servers, or instances:

`aws lightsail get-instances`

- List all bundles (instance plans):

`aws lightsail list-bundles`

- List all available instance images, or blueprints:

`aws lightsail list-blueprints`

- Create an instance:

`aws lightsail create-instances --instance-names {{name}} --availability-zone {{region}} --bundle-id {{nano_2_0}} --blueprint-id {{blueprint_id}}`

- Print the state of a specific instance:

`aws lightsail get-instance-state --instance-name {{name}}`

- Stop a specific instance:

`aws lightsail stop-instance --instance-name {{name}}`

- Delete a specific instance:

`aws lightsail delete-instance --instance-name {{name}}`

