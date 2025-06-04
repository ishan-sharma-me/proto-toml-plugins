# kubectl plugin

[kubectl](https://kubernetes.io/docs/reference/kubectl/) plugin for [proto](https://github.com/moonrepo/proto).

## Installation

This is a community plugin and is thus not built-in to proto. In order to use it, first either add it to your global or project-based `.prototools` by running:

### Global install

```shell
proto plugin add kubectl "source:https://raw.githubusercontent.com/ishan-sharma-me/proto-toml-plugins/main/kubectl/plugin.toml" --global
proto install kubectl
```

### Per-project install

```shell
proto plugin add kubectl "source:https://raw.githubusercontent.com/ishan-sharma-me/proto-toml-plugins/main/kubectl/plugin.toml"
proto pin kubectl latest --resolve
```
