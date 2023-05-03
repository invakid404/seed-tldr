---
id: common.wfuzz
title: Wfuzz
desc: ''
updated: 1683081152634
created: 1683081152634
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wfuzz

> A web application bruteforcer.
> More information: <https://wfuzz.readthedocs.io/en/latest/user/basicusage.html>.

- Directory and file bruteforce using the specified wordlist and also proxying the traffic:

`wfuzz -w {{path/to/file}} -p {{127.0.0.1:8080}} {{http://example.com/FUZZ}}`

- Save the results to a file:

`wfuzz -w {{path/to/file}} -f {{filename}} {{http://example.com/FUZZ}}`

- Show colorized output while only showing the declared response codes in the output:

`wfuzz -c -w {{path/to/file}} --sc {{200,301,302}} {{http://example.com/FUZZ}}`

- Use a custom header to fuzz subdomains while hiding specific response codes and word counts. Increase the threads to 100 and include the target ip/domain:

`wfuzz -w {{path/to/file}} -H {{"Host: FUZZ.example.com"}} --hc {{301}} --hw {{222}} -t {{100}} {{example.com}}`

