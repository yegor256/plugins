# The Plugin Bazaar

[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/yegor256/plugins/blob/master/LICENSES/MIT.txt)

> A Claude Code marketplace of small, opinionated
> plugins maintained under `yegor256`.

This repository lists every plugin maintained
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
* [`bugscribe`](https://github.com/yegor256/bugscribe)
  — a single skill that reports an already-identified bug
    as a new GitHub issue, with a file/line pointer and a
    one-time ping to the repository owner.
* [`courier`](https://github.com/yegor256/courier)
  — a single skill that submits the commits on the current
    local branch as a new GitHub pull request, with a short
    prose explanation and a one-time ping to the repository
    owner.
* [`purist`](https://github.com/yegor256/purist)
  — a single skill that hardens the style checkers and
    static analyzers already wired into a project and adds
    a list of custom rules on top.

To use any plugin from this marketplace inside [Claude Code],
  add the marketplace once and then install plugins from it:

```text
/plugin marketplace add https://github.com/yegor256/plugins
/plugin install critic@yegor256
/plugin install witness@yegor256
/plugin install bugscribe@yegor256
/plugin install courier@yegor256
/plugin install purist@yegor256
```

The first command registers this repository as a plugin marketplace
  named `yegor256`;
  the remaining commands install plugins from it.
Repeat the install command for every other plugin you want.

To update later, run:

```text
/plugin marketplace update yegor256
```

To remove a plugin, run:

```text
/plugin uninstall <name>@yegor256
```

That's it.

[Claude Code]: https://code.claude.com/docs/en/plugins
