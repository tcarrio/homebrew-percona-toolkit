# homebrew-percona-toolkit-mysql-8

This is a typical [Homebrew](https://brew.sh/) tap for [Percona Toolkit](https://www.percona.com/percona-toolkit). You can use it to install `percona-toolkit` on MacOS and Linux using Homebrew.

This is a fork of the Homebrew [percona-toolkit] targeted for MySQL 8 support. Newer versions of `percona-toolkit` explicitly target `mysql-client@9` which makes it incompatible with older MySQL servers.

## Install

To install `percona-toolkit` with Homebrew, aka. `brew`, run the following commands:

```bash
brew tap tcarrio/percona-toolkit-mysql-8
brew install percona-toolkit-mysql-8
```

## Upgrade

To upgrade, it is recommended that you run the `brew upgrade` command.

```bash
brew upgrade percona-toolkit-mysql-8
```

## Uninstall

If you want to uninstall `percona-toolkit`, run the following commands:

```bash
brew uninstall percona-toolkit-mysql-8
brew untap tcarrio/percona-toolkit-mysql-8
```

<!-- References -->

[percona-toolkit]: https://github.com/Homebrew/homebrew-core/blob/e0eb9cf8b84053091519e81e4ca7f2d26267286e/Formula/p/percona-toolkit.rb
[Percona Tookit]: https://www.percona.com/percona-toolkit