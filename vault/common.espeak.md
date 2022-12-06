---
id: common.espeak
title: Espeak
desc: ''
updated: 1670310991769
created: 1670310991769
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# espeak

> Uses text-to-speech to speak through the default sound device.
> More information: <http://espeak.sourceforge.net>.

- Speak a phrase aloud:

`espeak "I like to ride my bike."`

- Speak a file aloud:

`espeak -f {{path/to/file}}`

- Save output to a WAV audio file, rather than speaking it directly:

`espeak -w {{filename.wav}} "It's GNU plus Linux"`

- Use a different voice:

`espeak -v {{voice}}`

