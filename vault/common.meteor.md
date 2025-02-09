---
id: common.meteor
title: Meteor
desc: ''
updated: 1693073888519
created: 1693073888519
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# meteor

> Full-stack JavaScript platform for building web applications.
> More information: <https://meteor.com>.

- Run a meteor project from its root directory in development mode:

`meteor`

- Create a project under the given directory:

`meteor create {{path/to/directory}}`

- Display the list of packages the project is currently using:

`meteor list`

- Add a package to the project:

`meteor add {{package}}`

- Remove a package from the project:

`meteor remove {{package}}`

- Create a production build of the project as a tarball under the given directory:

`meteor build {{path/to/directory}}`

