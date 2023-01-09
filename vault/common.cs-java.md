---
id: common.cs-java
title: Cs Java
desc: ''
updated: 1673284741484
created: 1673284741484
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cs java

> The java and java-home commands fetch and install JVMs. The java command runs them too.
> More information: <https://get-coursier.io/docs/cli-java>.

- Call the java version by using coursier:

`cs java -version`

- Call a specific java version with custom properties using coursier:

`cs java --jvm {{jvm_name}}:{{jvm_version}} -Xmx32m -X{{another_jvm_opt}} -jar {{path/to/jar_name.jar}}`

- List all the available JVM in the coursier default index:

`cs java --available`

- List all the installed JVM in the system with his own location:

`cs java --installed`

- Set the a specific JVM as one-off "default" for the shell instance:

`cs java --jvm {{jvm_name}}:{{jvm_version}} --env`

- Revert the changes for the default JVM settings:

`eval "$(cs java --disable)"`

- Set a specific JVM as default for the whole system:

`cs java --jvm {{jvm_name}}:{{jvm_version}} --setup`

