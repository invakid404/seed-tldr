---
id: linux.dnsmap
title: Dnsmap
desc: ''
updated: 1664875683964
created: 1664875683964
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dnsmap

> The dnsmap command scans a domain for common subdomains e.g. smtp.domain.org.
> More information: <https://github.com/resurrecting-open-source-projects/dnsmap>.

- Scan for subdomains using the internal wordlist:

`dnsmap {{example.com}}`

- Specify a list of subdomains to check for:

`dnsmap {{example.com}} -w {{path/to/wordlist.txt}}`

- Store results to a CSV file:

`dnsmap {{example.com}} -c {{path/to/file.csv}}`

- Ignore 2 IPs that are false positives (up to 5 possible):

`dnsmap {{example.com}} -i {{123.45.67.89,98.76.54.32}}`

