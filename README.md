<div align="center">

# asdf-lokalise [![Build](https://github.com/ahmdyasser/asdf-lokalise/actions/workflows/build.yml/badge.svg)](https://github.com/ahmdyasser/asdf-lokalise/actions/workflows/build.yml) [![Lint](https://github.com/ahmdyasser/asdf-lokalise/actions/workflows/lint.yml/badge.svg)](https://github.com/ahmdyasser/asdf-lokalise/actions/workflows/lint.yml)

[lokalise](https://github.com/ahmdyasser/asdf-lokalise) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add lokalise
# or
asdf plugin add lokalise https://github.com/ahmdyasser/asdf-lokalise.git
```

lokalise:

```shell
# Show all installable versions
asdf list-all lokalise

# Install specific version
asdf install lokalise latest

# Set a version globally (on your ~/.tool-versions file)
asdf global lokalise latest

# Now lokalise commands are available
lokalise
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ahmdyasser/asdf-lokalise/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [ahmdyasser](https://github.com/ahmdyasser/)
