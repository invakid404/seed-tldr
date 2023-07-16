---
id: common.gitlab-runner
title: GitLab Runner
desc: ''
updated: 1689531679600
created: 1689531679600
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gitlab-runner

> Manage GitLab runners.
> More information: <https://docs.gitlab.com/runner/>.

- Register a runner:

`sudo gitlab-runner register --url {{https://gitlab.example.com}} --registration-token {{token}} --name {{name}}`

- Register a runner with a Docker executor:

`sudo gitlab-runner register --url {{https://gitlab.example.com}} --registration-token {{token}} --name {{name}} --executor {{docker}}`

- Unregister a runner:

`sudo gitlab-runner unregister --name {{name}}`

- Display the status of the runner service:

`sudo gitlab-runner status`

- Restart the runner service:

`sudo gitlab-runner restart`

- Check if the registered runners can connect to GitLab:

`sudo gitlab-runner verify`

