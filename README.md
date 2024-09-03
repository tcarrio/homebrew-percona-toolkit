# homebrew-percona-toolkit

This is a typical [Homebrew](https://brew.sh/) tap for [Percona Toolkit](https://www.percona.com/percona-toolkit). You can use it to install `percona-toolkit` on MacOS and Linux using Homebrew.

This is a fork of the Homebrew [percona-toolkit] targeted for MySQL 8 support. Newer versions of `percona-toolkit` explicitly target `mysql-client@9` which makes it incompatible with older MySQL servers.

## Install

To install `percona-toolkit` with Homebrew, aka. `brew`, run the following commands:

```bash
brew tap tcarrio/percona-toolkit
brew install tcarrio/percona-toolkit/percona-toolkit
```

## Upgrade

To upgrade, it is recommended that you run the `brew upgrade` command.

```bash
brew upgrade tcarrio/percona-toolkit/percona-toolkit
```

## Uninstall

If you want to uninstall `percona-toolkit`, run the following commands:

```bash
brew uninstall tcarrio/percona-toolkit/percona-toolkit
brew untap tcarrio/percona-toolkit
```

<!-- References -->

[percona-toolkit]: https://github.com/Homebrew/homebrew-core/blob/e0eb9cf8b84053091519e81e4ca7f2d26267286e/Formula/p/percona-toolkit.rb
[Percona Tookit]: https://www.percona.com/percona-toolkit