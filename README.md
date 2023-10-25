# COS tool

This is the snap for [`cos-tool`](https://github.com/canonical/cos-tool) a command-line tool to transforms `PromQL`/`LogQL` expressions on the fly, and validates that  Alert rules can be loaded successfully by either Prometheus or Loki.

Published for <img src="https://raw.githubusercontent.com/anythingcodes/slack-emoji-for-techies/gh-pages/emoji/tux.png" align="top" width="24" /> with 💝 by The [Canonical Observability Team](https://charmhub.io/topics/canonical-observability-stack)


## Install

```shell
sudo snap install cos-tool
```

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))


## How to pack de snap

```shell
snapcraft pack
```

```shell
Launching instance...
Executed: pull cos-tool
Executed: build cos-tool
Executed: stage cos-tool
Executed: prime cos-tool
Executed parts lifecycle
Generated snap metadata
Created snap package cos-tool_0.1_amd64.snap
```
