---
id: common.tts
title: Tts
desc: ''
updated: 1674530367136
created: 1674530367136
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tts

> Synthesize speech on the command line.
> More information: <https://github.com/coqui-ai/TTS#command-line-tts>.

- Run text-to-speech with the default models, writing the output to "tts_output.wav":

`tts --text "{{text}}"`

- List provided models:

`tts --list_models`

- Query info for a model by idx:

`tts --model_info_by_idx {{model_type/model_query_idx}}`

- Query info for a model by name:

`tts --model_info_by_name {{model_type/language/dataset/model_name}}`

- Run a text-to-speech model with its default vocoder model:

`tts --text "{{text}}" --model_name {{model_type/language/dataset/model_name}}`

- Run your own text-to-speech model (using the Griffin-Lim vocoder):

`tts --text "{{text}}" --model_path {{path/to/model.pth}} --config_path {{path/to/config.json}} --out_path {{path/to/file.wav}}`

