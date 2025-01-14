---
id: common.cradle-elastic
title: Cradle Elastic
desc: ''
updated: 1693073888430
created: 1693073888430
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cradle elastic

> Manage the Elasticsearch instances for a Cradle instance.
> More information: <https://cradlephp.github.io/docs/3.B.-Reference-Command-Line-Tools.html#elastic>.

- Truncate the Elasticsearch index:

`cradle elastic flush`

- Truncate the Elasticsearch index for a specific package:

`cradle elastic flush {{package}}`

- Submit the Elasticsearch schema:

`cradle elastic map`

- Submit the Elasticsearch schema for a specific package:

`cradle elastic map {{package}}`

- Populate the Elasticsearch indices for all packages:

`cradle elastic populate`

- Populate the Elasticsearch indices for a specific package:

`cradle elastic populate {{package}}`

