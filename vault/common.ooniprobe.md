---
id: common.ooniprobe
title: Ooniprobe
desc: ''
updated: 1690564463620
created: 1690564463620
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ooniprobe

> Open Observatory of Network Interference (OONI).
> Test the blocking of websites and apps. Measure the speed and performance of your network.
> More information: <https://ooni.org/support/ooni-probe-cli/>.

- List all tests performed:

`ooniprobe list`

- Show information about a specific test:

`ooniprobe list {{7}}`

- Run all available tests:

`ooniprobe run all`

- Perform a specific test:

`ooniprobe run {{performance}}`

- Check the availability of a specific website:

`ooniprobe run websites --input {{https://ooni.org/}}`

- Check the availability of all websites listed in a file:

`ooniprobe run websites --input-file {{path/to/my-websites.txt}}`

- Display detailed information about a test in JSON format:

`ooniprobe show {{9}}`

