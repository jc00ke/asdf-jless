<div align="center">

# asdf-jless [![Build](https://github.com/jc00ke/asdf-jless/actions/workflows/build.yml/badge.svg)](https://github.com/jc00ke/asdf-jless/actions/workflows/build.yml) [![Lint](https://github.com/jc00ke/asdf-jless/actions/workflows/lint.yml/badge.svg)](https://github.com/jc00ke/asdf-jless/actions/workflows/lint.yml)


[jless](https://pauljuliusmartinez.github.io/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add jless
# or
asdf plugin add jless https://github.com/jc00ke/asdf-jless.git
```

jless:

```shell
# Show all installable versions
asdf list-all jless

# Install specific version
asdf install jless latest

# Set a version globally (on your ~/.tool-versions file)
asdf global jless latest

# Now jless commands are available
jless --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jc00ke/asdf-jless/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jesse Cooke](https://github.com/jc00ke/)
