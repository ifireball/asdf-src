<div align="center">

# asdf-src [![Build](https://github.com/ifireball/asdf-src/actions/workflows/build.yml/badge.svg)](https://github.com/ifireball/asdf-src/actions/workflows/build.yml) [![Lint](https://github.com/ifireball/asdf-src/actions/workflows/lint.yml/badge.svg)](https://github.com/ifireball/asdf-src/actions/workflows/lint.yml)

[src](https://github.com/ifireball/src) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- A Linux x86_64 machine ("src" is not built for any other OS/architecture - yet)
- `bash`, `curl`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add src
# or
asdf plugin add src https://github.com/ifireball/asdf-src.git
```

src:

```shell
# Show all installable versions
asdf list-all src

# Install specific version
asdf install src latest

# Set a version globally (on your ~/.tool-versions file)
asdf global src latest

# Now src commands are available
src --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ifireball/asdf-src/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Barak Korren](https://github.com/ifireball/)
