---
id: linux.rpm
title: Rpm
desc: ''
updated: 1670203646419
created: 1670203646419
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rpm

> RPM Package Manager.
> For equivalent commands in other package managers, see <https://wiki.archlinux.org/title/Pacman/Rosetta>.
> More information: <https://rpm.org/>.

- Show version of httpd package:

`rpm --query {{httpd}}`

- List versions of all matching packages:

`rpm --query --all '{{mariadb*}}'`

- Forcibly install a package regardless of currently installed versions:

`rpm --upgrade {{package_name.rpm}} --force`

- Identify owner of a file and show version of the package:

`rpm --query --file {{/etc/postfix/main.cf}}`

- List package-owned files:

`rpm --query --list {{kernel}}`

- Show scriptlets from an RPM file:

`rpm --query --package --scripts {{package_name.rpm}}`

- Show changed, missing and/or incorrectly installed files of matching packages:

`rpm --verify --all '{{php-*}}'`

- Display the changelog of a specific package:

`rpm --query --changelog {{package_name}}`

