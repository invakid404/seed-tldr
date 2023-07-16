---
id: common.grpcurl
title: Grpcurl
desc: ''
updated: 1689531679609
created: 1689531679609
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# grpcurl

> Interact with gRPC servers.
> Like `curl`, but for gRPC.
> More information: <https://github.com/fullstorydev/grpcurl>.

- Send an empty request:

`grpcurl {{grpc.server.com:443}} {{my.custom.server.Service/Method}}`

- Send a request with a header and a body:

`grpcurl -H "{{Authorization: Bearer $token}}" -d {{'{"foo": "bar"}'}} {{grpc.server.com:443}} {{my.custom.server.Service/Method}}`

- List all services exposed by a server:

`grpcurl {{grpc.server.com:443}} list`

- List all methods in a particular service:

`grpcurl {{grpc.server.com:443}} list {{my.custom.server.Service}}`

