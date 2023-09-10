---
id: common.etcd
title: Etcd
desc: ''
updated: 1694355154968
created: 1694355154968
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# etcd

> A distributed, reliable key-value store for the most critical data of a distributed system.
> More information: <https://etcd.io>.

- Start a single-node etcd cluster:

`etcd`

- Start a single-node etcd cluster, listening for client requests on a custom URL:

`etcd --advertise-client-urls {{http://127.0.0.1:1234}} --listen-client-urls {{http://127.0.0.1:1234}}`

- Start a single-node etcd cluster with a custom name:

`etcd --name {{my_etcd_cluster}}`

- Start a single-node etcd cluster with extensive metrics available at <http://localhost:2379/debug/pprof/>:

`etcd --enable-pprof --metrics extensive`

