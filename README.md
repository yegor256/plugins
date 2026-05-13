# Plugins

[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/yegor256/plugins/blob/master/LICENSES/MIT.txt)

Claude Code marketplace listing every plugin maintained
  under the `yegor256` GitHub account.

Each plugin lives in its own repository;
  this repo is only the registry that ties them together
  under a single marketplace name.

Currently published plugins:

* [`critic`](https://github.com/yegor256/critic)
  — skills for an AI critic that helps writing and proofreading texts.

To use any plugin from this marketplace inside [Claude Code],
  add the marketplace once and then install plugins from it:

```text
/plugin marketplace add yegor256/plugins
/plugin install critic@yegor256
```

The first command registers this repository as a plugin marketplace
  named `yegor256`;
  the second installs the `critic` plugin from it.
Repeat the second command for every other plugin you want.

To update later, run `/plugin marketplace update yegor256`;
  to remove a plugin, run `/plugin uninstall <name>@yegor256`.

[Claude Code]: https://code.claude.com/docs/en/plugins
