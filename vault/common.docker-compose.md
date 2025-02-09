---
id: common.docker-compose
title: Docker Compose
desc: ''
updated: 1692548305001
created: 1692548305001
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# docker compose

> Run and manage multi container docker applications.
> More information: <https://docs.docker.com/compose/reference/>.

- List all running containers:

`docker compose ps`

- Create and start all containers in the background using a `docker-compose.yml` file from the current directory:

`docker compose up --detach`

- Start all containers, rebuild if necessary:

`docker compose up --build`

- Start all containers by specifying a project name and using an alternate compose file:

`docker compose -p {{project_name}} --file {{path/to/file}} up`

- Stop all running containers:

`docker compose stop`

- Stop and remove all containers, networks, images, and volumes:

`docker compose down --rmi all --volumes`

- Follow logs for all containers:

`docker compose logs --follow`

- Follow logs for a specific container:

`docker compose logs --follow {{container_name}}`

