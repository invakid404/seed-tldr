---
id: common.twine
title: Twine
desc: ''
updated: 1665454803427
created: 1665454803427
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# twine

> Utility for publishing Python packages on PyPI.
> Subcommands such as `twine upload` have their own usage documentation.
> More information: <https://twine.readthedocs.io>.

- Upload to the Test PyPI [r]epository and verify things look right:

`twine upload -r testpypi dist/*`

- Upload to PyPI:

`twine upload dist/*`

- Upload to PyPI with a specified [u]sername and [p]assword:

`twine upload -u {{username}} -p {{password}} dist/*`

- Upload to an alternative repository URL:

`twine upload --repository-url {{repository_url}} dist/*`

