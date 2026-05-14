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
* [`witness`](https://github.com/yegor256/witness)
  — skills for an AI witness that reports the outcome of
    work done by other plugins, skills, and agents to a
    Telegram chat.

To use any plugin from this marketplace inside [Claude Code],
  add the marketplace once and then install plugins from it:

```text
/plugin marketplace add yegor256/plugins
/plugin install critic@yegor256
/plugin install witness@yegor256
```

The first command registers this repository as a plugin marketplace
  named `yegor256`;
  the remaining commands install plugins from it.
Repeat the install command for every other plugin you want.

To update later, run `/plugin marketplace update yegor256`;
  to remove a plugin, run `/plugin uninstall <name>@yegor256`.

[Claude Code]: https://code.claude.com/docs/en/plugins
