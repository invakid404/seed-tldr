---
id: common.cf
title: Cf
desc: ''
updated: 1665484120276
created: 1665484120276
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cf

> Command-line tool to manage apps and services on Cloud Foundry.
> More information: <https://docs.cloudfoundry.org>.

- Log in to the Cloud Foundry API:

`cf login -a {{api_url}}`

- Push an app using the default settings:

`cf push {{app_name}}`

- View the services available from your organization:

`cf marketplace`

- Create a service instance:

`cf create-service {{service}} {{plan}} {{service_name}}`

- Connect an application to a service:

`cf bind-service {{app_name}} {{service_name}}`

- Run a script whose code is included in the app, but runs independently:

`cf run-task {{app_name}} "{{script_command}}" --name {{task_name}}`

- Start an interactive SSH session with a VM hosting an app:

`cf ssh {{app_name}}`

- View a dump of recent app logs:

`cf logs {{app_name}} --recent`

