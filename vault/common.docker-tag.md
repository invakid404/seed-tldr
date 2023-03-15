---
id: common.docker-tag
title: Docker Tag
desc: ''
updated: 1678886697291
created: 1678886697291
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# docker tag

> Assign tags to existing Docker images.
> More information: <https://docs.docker.com/engine/reference/commandline/tag/>.

- Assign a name and tag to a specific image ID:

`docker tag {{id}} {{name}}:{{tag}}`

- Assign a tag to a specific image:

`docker tag {{image}}:{{current_tag}} {{image}}:{{new_tag}}`

- Display help:

`docker tag`

