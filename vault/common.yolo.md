---
id: common.yolo
title: Yolo
desc: ''
updated: 1673893294193
created: 1673893294193
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# yolo

> The YOLO command line interface lets you simply train, validate or infer models on various tasks and versions.
> More information: <https://docs.ultralytics.com/cli/>.

- Create a copy of the default configuration in your current working directory:

`yolo task=init`

- Train the object detection, instance segment, or classification model with the specified configuration file:

`yolo task={{detect|segment|classify}} mode=train cfg={{path/to/config.yaml}}`

