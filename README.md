# asdf-go-repos-sync
Plugin for [asdf](https://github.com/asdf-vm/asdf) Package Manager, install [go-repos-sync](https://github.com/nolte/go-repos-sync).

## Install

Look for the Latest Release of [go-repos-sync](https://github.com/nolte/go-repos-sync/releases).

```sh
asdf plugin-add go-repos-sync https://github.com/nolte/asdf-go-repos-sync.git
```

## Development

Using [nektos/act](https://github.com/nektos/act) for start the Github Workflow locally.

```
act \
  -P ubuntu-20.04=nektos/act-environments-ubuntu:18.04 \
  --job=asdf
```

Direct call, for local development.
```sh
ASDF_INSTALL_TYPE=test \
  ASDF_INSTALL_VERSION=0.0.1 \
  ASDF_INSTALL_PATH=/tmp/plugin \
  ./bin/install
```
