---
id: common.wpscan
title: Wpscan
desc: ''
updated: 1694355155100
created: 1694355155100
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wpscan

> WordPress vulnerability scanner.
> More information: <https://github.com/wpscanteam/wpscan>.

- Update the vulnerability database:

`wpscan --update`

- Scan a WordPress website:

`wpscan --url {{url}}`

- Scan a WordPress website, using random user agents and passive detection:

`wpscan --url {{url}} --stealthy`

- Scan a WordPress website, checking for vulnerable plugins and specifying the path to the `wp-content` directory:

`wpscan --url {{url}} --enumerate {{vp}} --wp-content-dir {{remote/path/to/wp-content}}`

- Scan a WordPress website through a proxy:

`wpscan --url {{url}} --proxy {{protocol://ip:port}} --proxy-auth {{username:password}}`

- Perform user identifiers enumeration on a WordPress website:

`wpscan --url {{url}} --enumerate {{u}}`

- Execute a password guessing attack on a WordPress website:

`wpscan --url {{url}} --usernames {{username|path/to/usernames.txt}} --passwords {{path/to/passwords.txt}} threads {{20}}`

- Scan a WordPress website, collecting vulnerability data from the WPVulnDB (<https://wpvulndb.com/>):

`wpscan --url {{url}} --api-token {{token}}`

