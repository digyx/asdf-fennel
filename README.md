<div align="center">

# asdf-fennel [![Build](https://github.com/digyx/asdf-fennel/actions/workflows/build.yml/badge.svg)](https://github.com/digyx/asdf-fennel/actions/workflows/build.yml) [![Lint](https://github.com/digyx/asdf-fennel/actions/workflows/lint.yml/badge.svg)](https://github.com/digyx/asdf-fennel/actions/workflows/lint.yml)

[fennel](https://fennel-lang.org/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add fennel
# or
asdf plugin add fennel https://github.com/digyx/asdf-fennel.git
```

fennel:

```shell
# Show all installable versions
asdf list-all fennel

# Install specific version
asdf install fennel latest

# Set a version globally (on your ~/.tool-versions file)
asdf global fennel latest

# Now fennel commands are available
fennel --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/digyx/asdf-fennel/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Roman Godmaire](https://github.com/digyx/)
