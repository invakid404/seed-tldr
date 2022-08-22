---
id: common.flarectl
title: Flarectl
desc: ''
updated: 1661133980599
created: 1661133980599
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# flarectl

> Official CLI for Cloudflare.
> More information: <https://github.com/cloudflare/cloudflare-go/blob/master/cmd/flarectl/README.md>.

- Block a specific IP:

`flarectl firewall rules create --zone="{{example.com}}" --value="{{8.8.8.8}}" --mode="{{block}}" --notes="{{Block bad actor}}"`

- Add a DNS record:

`flarectl dns create --zone="{{example.com}}" --name="{{app}}" --type="{{CNAME}}" --content="{{myapp.herokuapp.com}}" --proxy`

- List all Cloudflare IPv4/IPv6 ranges:

`flarectl ips --ip-type {{ipv4|ipv6|all}}`

- Create many new Cloudflare zones automatically with names from `domains.txt`:

`for domain in $(cat {{domains.txt}}); do flarectl zone info --zone=$domain; done`

- List all firewall rules:

`flarectl firewall rules list`

